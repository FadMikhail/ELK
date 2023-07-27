# Домашнее задание к занятию «ELK»

---

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

![image](https://github.com/FadMikhail/ELK/assets/132131230/601ce46a-d209-4bc5-a07a-a17ea15824a0)

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

![image](https://github.com/FadMikhail/ELK/assets/132131230/d06f8b1d-4d54-431d-ba81-42b30758acfe)

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

![image](https://github.com/FadMikhail/ELK/assets/132131230/f1f8ec20-f563-4483-9ab4-052ba1a44ab6)

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

![image](https://github.com/FadMikhail/ELK/assets/132131230/8951e53f-0fa5-4f79-afb8-1158a5acf76a)



