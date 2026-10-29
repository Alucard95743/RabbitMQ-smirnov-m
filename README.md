# Домашнее задание к занятию "`Очереди RabbitMQ`" - `Смирнов Михаил`

### Задание 1. Установка RabbitMQ

![Установка RabbitMQ](img/TASK_1.png)

---

### Задание 2. Отправка и получение сообщений

![Результат работы producer.py](img/TASK_2,producer.png)

![Результат работы consumer](img/TASK_2,consumer.png)

---

### Задание 3. Подготовка HA кластера

![Доступные ноды кластера](img/TASK_3, node_follower.png)

![Аргументы](img/TASK_3,arguments.png)

![Cтатус кластера c ноды 1](img/TASK_3,node1_cluster_status.png)

![Cтатус кластера c ноды 2](img/TASK_3,node2_cluster_status.png)

![Cтатус кластера c ноды 3](img/TASK_3,node3_cluster_status.png)

![Демонстрация отправки\получения между двумя нодами](img/TASK3,d1-db2_prod_cons.png)

![Отправка очереди с ноды 1, отключение ноды один, забор очереди с ноды 3](img/TASK_3,node1_dead,node3_recieve_queue.png)



