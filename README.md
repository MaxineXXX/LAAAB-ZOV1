## Лабораторная работа 1

*С чего начинается Linux? С Терминала!!!*

Итак, вы установили дистрибутив Linux Ubuntu (желательно его, но если у вас уже есть другой Linux или вообще MacOS то можно их использовать) и запустили его. Перед вами рабочий стол, панель задач, иконки и прочие вещи - все как и в других ~~менее удобных~~ операционных системах. Предвижу, что вы уже вдоволь наигрались с новым (или нет?) для вас графическим интерфейсом (GUI - graphical user interface) и готовы к самому интересному - знакомству с Терминалом (CLI - command line interface) и выполнению Лабораторной работы №1.

1. Создайте новый файл с именем `script.bash`

```bash
touch script.bash
```

2. Откройте созданный файл `script.bash` для редактирования. Стандартный текстовый редактор в Linux Ubuntu это `gedit`. Выполните в терминале

```bash
gedit script.bash
```

3. Впишите следующий скрипт

```bash
#!/bin/bash

echo "Welcome to ITMO University"
```

4. Сохраните файл. Закройте текстовый редактор `gedit`. Запустите bash-скрипт, выполнив в терминале

```bash
bash script.bash
```

5. Если вы все сделали верно, то в терминале должна отобразиться строка `Welcome to ITMO University`.


А теперь, используя знания полученные из лекций, дополнительных источников и, добавив к этому немного смекалки, решите следующую задачу.

### Задача

Модифицируйте файл `script.bash` так, чтобы при его запуске в терминале в виде

```bash
bash script.bash Vasya Pupkin
```

Вывод был

`Welcome, Vasya Pupkin`

*Hint:* Скрипт должен работать для любых имен, даже если это Benedict Timothy Carlton Cumberbatch.

### Как успешно сдать работу?

Создать свой репозиторий из шаблона этого. Как это делается - "Use this template" -> "Create a new repository" и сделайте его public. 

Находясь уже в своем репозитории - создайте новый файл формата .md и там оформляйте отчет. В отчете опишите все шаги которые вы делали, чтобы получить финальный результат работы. Скриншотов не жалейте, они бесплатные)

Чтобы успешно защитить эту работу у вас должен быть понятный отчет, вы должны понимать базу и основу работы в терминале, какие вообще команды бывают, и знать материал из лекции. Если я вижу что вы понимаете материал, я помогу вам прийти к правильному ответу и это будет плюс вам, если увижу что вы в теме плаваете - нужно было лучше готовиться)))
![image](https://github.com/user-attachments/assets/7fa99c40-727f-4437-922c-d596e87a44b3)

![image](https://github.com/user-attachments/assets/c75a9563-9e7f-40c5-a244-e6c94a4c9d70)
![image](https://github.com/user-attachments/assets/3abbdd18-22e7-495b-a850-1968a7871435)
![image](https://github.com/user-attachments/assets/f5376ae3-74b7-4be8-83ad-c0b0bbe95c6f)
![image](https://github.com/user-attachments/assets/3d308369-5d34-49fb-ace4-36a3621c6439)
![image](https://github.com/user-attachments/assets/cfbe2aa6-6737-4c2d-b5df-12a7626b43de)
![image](https://github.com/user-attachments/assets/fd3b24e5-d221-4c85-9b8e-8992a2de1932)
![image](https://github.com/user-attachments/assets/c700dcd1-5e37-4ac8-85a4-af8c9c8638bd)
![image](https://github.com/user-attachments/assets/df349acb-9571-4f3c-9647-60907e45b329)
![image](https://github.com/user-attachments/assets/9bca1414-415d-4e61-9a10-f88fd61d638c)


### Дополнительные источники

* О системе котроля версий `git`, рекомендуем прочесть разделы 1, 2.1 и 2.2 из [https://git-scm.com/book/ru/v2](https://git-scm.com/book/ru/v2).

* Специальные типы переменных [https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#OTHERTYPESV](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#OTHERTYPESV)

* Ресурс, где можно найти ответы на (почти) любые вопросы - https://stackoverflow.com/ и не поверите где еще - https://www.google.ru/

* Хорошая книга по Shell/bash в Linux - "Learn Linux Shell Scripting – Fundamentals of Bash 4.4"  Sebastiaan Tammer
