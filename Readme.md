# Лаба 4 по информатике
### Заполняем Докерфайлы
![image](https://github.com/cs-itmo-2023/lab-4-matveySav/assets/144665338/aa25da71-ab8b-4789-80da-72f140a17c01)
### Строим контейнеры и запускаем их
``` sudo docker -t build aafire1/2 . ```

``` sudo docker run -it aafire1/2 ```
### Проверяем работу aafire
![Pasted image 5](https://github.com/cs-itmo-2023/lab-4-matveySav/assets/144665338/73a2d7a0-cc52-4db4-b445-90a2ceeea0ff)
### Создаем сеть
``` sudo docker network create Network ```
### Смотрим имена запущенных контейнеров, подключаем их к созданной сети Network
![Pasted image 1](https://github.com/cs-itmo-2023/lab-4-matveySav/assets/144665338/e19ec50e-e40e-4ef6-84f9-70cf2e62c47c)
### Смотрим ip адреса присвоенные контейнерам в сети 
![Pasted image 2](https://github.com/cs-itmo-2023/lab-4-matveySav/assets/144665338/31830a04-a4bf-4a9b-a213-2aab4694fb95)

### Проверяем сетевой доступ с помощью устанановленной утилиты ping
![Pasted image 3](https://github.com/cs-itmo-2023/lab-4-matveySav/assets/144665338/a6defd77-0e84-4fcd-b937-9ecb678bd6d4)

![Pasted image 4](https://github.com/cs-itmo-2023/lab-4-matveySav/assets/144665338/8ee2435c-b2c2-4fd5-abb6-c44738a64243)
