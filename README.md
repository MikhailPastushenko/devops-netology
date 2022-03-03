# devops-netology Михаил Пастушенко
Задание №1 – Создать и настроить репозиторий для дальнейшей работы на курсе

git config --global
![img.png](img.png)

git diff
![img_1.png](img_1.png)

git diff --staged
![img_2.png](img_2.png)

git add readme.md
![img_3.png](img_3.png)

git diff
![img_4.png](img_4.png)

git diff --staged
![img_5.png](img_5.png)

git commit -m "First commit"
![img_6.png](img_6.png)

git diff --staged
![img_7.png](img_7.png)

в каталоге Terraform, благодаря файлу .gitignore, будут проигнорированы
1) все файлы из подкаталогов ./terraform/ на любом уровне вложенности
2) файлы, включающие .tfstate
3) файлы с раширениями .log, .tfvars, .tfvars.json, _override.tf, _override.tf.json
4) файлы override.tf , override.tf.json, .terraformrc, terraform.rc


Ветка fix из задания "2.2. Основы Git"