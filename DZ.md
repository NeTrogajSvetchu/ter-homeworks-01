Чек-лист готовности к домашнему заданию

1. TER
   
![Alt text](png/1.png)

2. 01/src
   
![Alt text](png/2.png)

3. docker
   
![Alt text](png/3.png)

4. docker login
   
![Alt text](png/4.png)

Задание 1.

1. +
2. personal.auto.tfvars
3. "result": "sPkaF0CN3vFApjv8"
4. 
   1. Missing name for resource - отсутствовал указывающий labels "nginx".
   2. Invalid resource - name ошибка в указывающем labels "1nginx" - "nginx"
   3. Reference to undeclared resource - ошибка в сылке на объект.
   
        name  = "example_${random_password.random_string_FAKE.resulT}"

        name  = "example_${random_password.random_string.result}"
5. docker ps

![Alt text](png/5.png)

6. "terraform apply -auto-approve" данная команда пименяет изменения в .tf и применяет их без просмотра плана и подтверждения пользователя.
   
![Alt text](png/6.png)

7. +

![Alt text](png/7.png)

8. keep_locally = true для удоления необхлдимо тзменить значение на false  
   
![Alt text](png/8.png)

Задание 2. +

![Alt text](png/9.png)
![Alt text](png/10.png)
