# Домашнее задание к занятию "Что такое DevOps. СI/СD" - Абрамов Сергей


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Приведите ответ в свободной форме........`

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.

![install jenkins](https://github.com/smabramov/Jenc/blob/043135ac7e5c43a9a2b6f73d3fc6d9be4d3fed94/img/install%20jenkins.png)`

2. Установите на машину с jenkins golang.

![install go.png](https://github.com/smabramov/Jenc/blob/043135ac7e5c43a9a2b6f73d3fc6d9be4d3fed94/img/install%20go.png)`

3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.

![fork](https://github.com/smabramov/Jenc/blob/043135ac7e5c43a9a2b6f73d3fc6d9be4d3fed94/img/fork.png)`

4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

![go test](https://github.com/smabramov/Jenc/blob/043135ac7e5c43a9a2b6f73d3fc6d9be4d3fed94/img/go%20test.png)`

5. В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

![сборка](https://github.com/smabramov/Jenc/blob/043135ac7e5c43a9a2b6f73d3fc6d9be4d3fed94/img/%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B0.png)`

![nexus](https://github.com/smabramov/Jenc/blob/043135ac7e5c43a9a2b6f73d3fc6d9be4d3fed94/img/nexus.png)`
 


---

### Задание 2



1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.


![code](https://github.com/smabramov/Jenc/blob/4f9dec4a6186a01f41ef1b66e8ef26173834eda2/img/code.png)`

![pipeline](https://github.com/smabramov/Jenc/blob/4f9dec4a6186a01f41ef1b66e8ef26173834eda2/img/pipeline.png)`

![nexus1](https://github.com/smabramov/Jenc/blob/4f9dec4a6186a01f41ef1b66e8ef26173834eda2/img/nexus1.png)`

---

### Задание 3


1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.


![1](https://github.com/smabramov/Jenc/blob/41310cf30d378190f093f2b6b6c63f90fae8024d/img/1.png)`

![2](https://github.com/smabramov/Jenc/blob/41310cf30d378190f093f2b6b6c63f90fae8024d/img/2.png)`

![3](https://github.com/smabramov/Jenc/blob/41310cf30d378190f093f2b6b6c63f90fae8024d/img/3.png)`


