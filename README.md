# Домашнее задание к занятию " `Что такое DevOps. CI/CD`" - `Акаев Тимур`

---

### Задание 1

`Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.` 

`Установите на машину с jenkins golang. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.`

`Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build.`

![Установка jenkins 1](https://github.com/timurgithub/netology-git-hw/blob/main/img/jenkins_install.png)

![Установка go 1](https://github.com/timurgithub/netology-git-hw/blob/main/img/go_install.png)

![Jenkins_firstpipe](https://github.com/timurgithub/netology-git-hw/blob/main/img/jenkins_build_firstpipe.png)


---

### Задание 2

`Создайте новый проект pipeline.`
`Перепишите сборку из задания 1 на declarative в виде кода.`

![Pipline](https://github.com/timurgithub/netology-git-hw/blob/main/img/Pipline.png)

![Pipline done](https://github.com/timurgithub/netology-git-hw/blob/main/img/Pipline_done.png)