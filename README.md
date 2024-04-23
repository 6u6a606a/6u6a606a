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
![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/f8606799-ad26-42e8-8e0c-a9cd4b525dc9)

7. Создаю ещё один файл:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/78bea58b-b73c-48ab-90f4-faf649811eb4)

8. Делаю коммит:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/9fd25647-f377-435a-8b33-b2a74c92803f)

9. Просматриваю логи:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/b6c18528-79f9-4b72-8967-4663cece38c2)

10. Посмотрел изменения в файле по сравнению с последним коммитом:
```
git checkout -- test.txt
```

12. Убрал изменения относительно последнего коммита из файла:
```
git restore test.txt
```

13. Просмотр существующих веток:

![image](https://github.com/6u6a606a/6u6a606a/assets/127476352/34806b62-5cfd-42d9-9836-01258d72ff29)

14. Создание новой ветки и переключение на нее:

