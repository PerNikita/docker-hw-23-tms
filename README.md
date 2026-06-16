# docker-hw-23-tms
● Найдите на Docker Hub образ, который вы хотите запустить на вашей
машине.
● Используя команду docker run, запустите контейнер на основе этого
образа. Добавьте флаги, чтобы установить имя контейнера,
перенаправить порты, установить переменные окружения и т.д.
Используйте команду docker ps, чтобы убедиться, что контейнер
запущен.

<img width="1720" height="1051" alt="изображение" src="https://github.com/user-attachments/assets/7df1c62e-c8cf-48de-a4b8-6a4df8a8bea4" />

● Создайте Docker volume с помощью команды docker volume create.
● Запустите контейнер, используя команду docker run, и подключите
созданный Docker volume к контейнеру.
● Используйте команду docker network create для создания новой Docker
network.

<img width="2104" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/f397712e-7aad-449c-ae46-2e683067841f" />


Опционально:
● Создайте второй контейнер из того же образа, используя команду docker run,
и подключите его к созданной Docker network.
● Внутри первого контейнера, используя утилиту nano, создайте текстовый
файл в подключенном Docker volume.

<img width="1831" height="563" alt="изображение" src="https://github.com/user-attachments/assets/06dd9daf-caf6-4161-979d-505f36e48a01" />

● Внутри первого контейнера, используя утилиту logger, запишите несколько
сообщений в созданный текстовый файл.
● Используйте команду docker logs для просмотра логов первого контейнера и
убедитесь, что сообщения были успешно записаны в лог-файл.
● Используйте команду docker exec для выполнения команды во втором
контейнере и проверьте, что созданный текстовый файл доступен из второго
контейнера.

<img width="1101" height="1238" alt="изображение" src="https://github.com/user-attachments/assets/085c2051-e35d-41ba-87aa-9e77791da1d9" />


● Используйте команду docker stop для остановки обоих контейнеров.
● Используйте команду docker rm для удаления контейнеров и команду docker
rmi для удаления образа.
● Используйте команду docker volume rm для удаления Docker volume и
команду docker network rm для удаления Docker network.


<img width="1043" height="464" alt="изображение" src="https://github.com/user-attachments/assets/65eb3d44-d1d0-4425-bb5a-41fa8b4dc533" />

