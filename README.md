### INFTA GCP:
    - развернут кубер;
    - развернут терраформом;
    - процесс деплоя инфры описан через gitlab.com ci;
    - пайплайн тестирует код, деплоит инфру, дает возможность удалить инфру после завершения работы;
    - код находится в закрытом репозитории gitlab.com;
    - настроена интеграция (алерты) в личный слак канал infra;
    - репо https://gitlab.com/vldspinninrecords/otus-infra;

### UI APP:
    - приложение скопировано в свой приватный репозиторий gitlab https://gitlab.com/vldspinninrecords/otus-ui;
    - описан докерфайл для приложения;
    - настроен пайплайн с тестами и сборкой и пушем на хаб образа;
    - настроена интеграция (алерты) в личный слак канал ui;
    - ссылка на докерхаб: https://hub.docker.com/repository/docker/ovld/otus-ui;

### CRAWLER APP:
    - приложение скопировано в свой приватный репозиторий gitlab https://gitlab.com/vldspinninrecords/otus-crawler;
    - описан докерфайл для приложения;
    - настроен пайплайн с тестами и сборкой и пушем на хаб образа;
    - сслыка на докерхаб: https://hub.docker.com/repository/docker/ovld/otus-crawler'
    - настроена интеграция (алерты) в личный слак канал ui;
