# Работа с Git

1. Задаю имя и Email:

```
git config --global user.name "<Dmitry_Efremov>"
git config --global user.email "<dimitrijefremov80@mail.ru>"
```

2. Создаю локальный репозиторий:

```
git init
```

3. Создаю .txt:
   
![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/7efdf6fa-17a6-422f-af69-9343957741c1)

4. Добавляю строки в txt-файл:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/80b24a8c-5cae-4762-a615-aa93e771f83f)

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/45da1b7e-35c1-49fa-91c6-216c21d6e714)

5. Делаю коммит:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/c20bf123-08e8-42f6-b8d2-ac38a2bbecdd)

6. Проверяю статус:

```
git status
```

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/fecb0d81-1e58-4d6b-9b33-88db034bab54)

7. Создаю ещё один файл:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/78bea58b-b73c-48ab-90f4-faf649811eb4)

8. Делаю коммит:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/9fd25647-f377-435a-8b33-b2a74c92803f)

9. Просматриваю протокол коммитов:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/b6c18528-79f9-4b72-8967-4663cece38c2)

10. Посмотрел изменения в файле по сравнению с последним коммитом:

```
git checkout -- test.txt
```

11. Убрал изменения относительно последнего коммита из файла:

```
git restore test.txt
```

12. Просмотр существующих веток:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/34806b62-5cfd-42d9-9836-01258d72ff29)

13. Создание новой ветки:
```
git branch test_br
```
14. Переключение на неё:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/6f8f9f0a-fcf3-491a-a2a9-cc9921d7f85a)

15. Создание новой ветки и переключение на неё

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/cb08dd27-3ad0-46bd-a6bd-4543fcad7dec)

16. Удаление свежесозданной ветки:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/7e72e3fc-7646-4e1d-90ea-ef982dc2526b)

17. Добавление merge изменений из указанной ветки в текущую:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/75e0c6dd-a1b8-412f-a021-099ff2b1ec66)

18. Создал конфликт и посмотрел статус:

```
git status
```

19. Конфликт устранён:

```
git add test.txt
git commit -m "Конфликт устранён"
```

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/e969edf5-6624-483f-b369-a119f21ddf6c)

20. Переключение на указанный коммит:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/3ce9b45c-d3e3-4a28-9707-208072dd09a2)

21. Ребазирование текущей ветки:

```
git rebase master
```

22. Удаление ветки:

```
git branch -d test_br
```
![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/8e5e6f09-1963-46df-80e4-1be0234ff5f8)


23. Пропуск текущего конфликтного коммита и переход к следующему:

```
git rebase --skip
```

24. Отправка изменений из локального репозитория для указанной ветки в удаленный (дистанционный):

```
git remote add origin https://github.com/6u6a606a/6u6a606a
git push origin master
```

25. Забрал изменения из репозитория, для которого были созданы удаленные ветки по умолчанию:

```
git pull origin master
```

26. Забрал изменения удаленной ветки из репозитория основной ветки по умолчанию:

```
git checkout -b brtest
echo. > test2.txt
git add test2.txt
git commit -m "хотите расскажу анекдот?"
git push origin brtest
git pull origin brtest:master
```

27. Клонировал репозиторий:

```
git clone https://github.com/6u6a606a/6u6a606a
```
