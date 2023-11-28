# Project 19 : Docker
**#docker24.0.6**

<img align="right" width="100" height="100" src="https://github.com/rozhkovsvyat/Project19.Docker/assets/71471748/473223be-eaa6-48c0-bb8c-10485c608d80">
<img align="right" width="100" height="100" src="https://github.com/rozhkovsvyat/Project19.Docker/assets/71471748/184cf010-61c6-4488-baef-7f79979b2a59">

Развертывание проекта Phonebook на сервере Linux

> :eye_speech_bubble: https://hub.docker.com/repository/docker/rozhkovsvyat/project19

Конфигурация: **OS** Ubuntu 22.04 / **CPU** 1 / **RAM** 4Gb / **NVMe** 15Gb

---

### CONTAINERS (7)

* **Книга контактов** / [Phonebook.Web](https://hub.docker.com/layers/rozhkovsvyat/project19/web/images/sha256-9d868c7bdd131866eb552de00f5c440b5d0a3b84270cb31090c6ac09afe44272?context=repo) + [Phonebook.API](https://hub.docker.com/layers/rozhkovsvyat/project19/api/images/sha256-95493f8e44b5972996270b9eb01b7b6087e95421f9dbfc7fce987c04e72238e5?context=repo)
* **База идентификации** / [MongoDB](https://hub.docker.com/_/mongo) + [Mongo-Express](https://hub.docker.com/_/mongo-express)
* **База контактов** / [PostgreSQL](https://hub.docker.com/_/postgres) + [PgAdmin](https://hub.docker.com/r/dpage/pgadmin4)
> 💡: Перенаправляет все запросы с HTTP на HTTPS используя сертификат Let's Encrypt
* **Реверс-прокси** / [Nginx](https://hub.docker.com/_/nginx)

---

### CRON

Каждое утро обновляет образы и пересобирает контейнеры, откатывая книгу в исходное состояние

---

Доступ к сервису: **[efcore.ru](https://efcore.ru)** / **[api.efcore.ru](https://api.efcore.ru/contacts)**

:busts_in_silhouette: **admin**<sub>default</sub> :key: **qaz123WSX!=**<sub>QWE123asd_</sub>
