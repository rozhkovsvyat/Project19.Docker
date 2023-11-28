# Project 19 : Docker
**#docker24.0.6**

<img align="right" width="100" height="100" src="https://github.com/rozhkovsvyat/Project19.Docker/assets/71471748/473223be-eaa6-48c0-bb8c-10485c608d80">
<img align="right" width="100" height="100" src="https://github.com/rozhkovsvyat/Project19.Docker/assets/71471748/184cf010-61c6-4488-baef-7f79979b2a59">

Развертывание проекта Phonebook в контейнерах на сервере Linux

> :eye_speech_bubble: https://hub.docker.com/repository/docker/rozhkovsvyat/project19

Используемые образы:
* **База данных идентификации** / [MongoDB](https://hub.docker.com/_/mongo) + [Mongo-Express](https://hub.docker.com/_/mongo-express)
* **База данных контактов** / [PostgreSQL](https://hub.docker.com/_/postgres) + [PgAdmin](https://hub.docker.com/r/dpage/pgadmin4)
* **Web-клиент телефонной книги** / [Phonebook.Web](rozhkovsvyat/project19:web)
* **API телефонной книги** / [Phonebook.API](rozhkovsvyat/project19:api)
* **Прокси** / [Nginx](https://hub.docker.com/_/nginx)

---

### SERVER

* **OS** Ubuntu 22.04
* **CPU** 1 / **RAM** 4Gb / **NVMe** 15Gb
* **IP** 185.154.194.115

---

### CONTAINERS




Телефонная книжка доступна по адресу [efcore.ru](https://efcore.ru)

Поддомены:
* [api.efcore.ru](https://api.efcore.ru/contacts)
* [mongo.efcore.ru](https://mongo.efcore.ru)
* [pg.efcore.ru](https://pg.efcore.ru)
