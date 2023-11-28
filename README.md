# Project 19 : Docker
**#docker24.0.6-linux**

<img align="right" width="100" height="100" src="https://github.com/rozhkovsvyat/Project19.Docker/assets/71471748/473223be-eaa6-48c0-bb8c-10485c608d80">
<img align="right" width="100" height="100" src="https://github.com/rozhkovsvyat/Project19.Docker/assets/71471748/184cf010-61c6-4488-baef-7f79979b2a59">

Развертывание проекта Phonebook в контейнерах

> :eye_speech_bubble: https://hub.docker.com/repository/docker/rozhkovsvyat/project19

Конфигурация: **OS** Ubuntu 22.04 / **CPU** 1 / **RAM** 4Gb / **NVMe** 15Gb

---

### CONTAINERS

* **База идентификации с оболочкой** / [MongoDB](https://hub.docker.com/_/mongo) + [Mongo-Express](https://hub.docker.com/_/mongo-express)
* **База контактов с оболочкой** / [PostgreSQL](https://hub.docker.com/_/postgres) + [PgAdmin](https://hub.docker.com/r/dpage/pgadmin4)
* **Web-клиент книги** / [Phonebook.Web](rozhkovsvyat/project19:web)
* **API книги** / [Phonebook.API](rozhkovsvyat/project19:api)
* **Реверс-прокси** / [Nginx](https://hub.docker.com/_/nginx)

---

### RELEASE




Web-клиент доступен по адресу [efcore.ru](https://efcore.ru) 

API доступно по адресу [api.efcore.ru](https://api.efcore.ru/contacts)
* **admin** / qaz123WSX!=
* **default** / QWE123asd_

Поддомены:
* [api.efcore.ru](https://api.efcore.ru/contacts)
* [mongo.efcore.ru](https://mongo.efcore.ru)
* [pg.efcore.ru](https://pg.efcore.ru)
