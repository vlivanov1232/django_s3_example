# django_s3_example
Проект для демонстрации возможности хранения статики и медиа в S3 хранилище для Django

#Quick Start
1. Создайте бакет и пользователя для S3 совместимого хранилища
2. Заполните `.env`
3. `docker-compose pull`
4. `docker-compose run --build`
5. В `/admin` доступна загрузка файлов
6. В `/files` доступна api для получения файлов