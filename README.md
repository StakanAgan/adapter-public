# R-Keeper-adapter

Адаптер для RKeeper, который можно использовать в качестве примера при написании нового адаптера к POS системе.

### Покрытие тестами

Для запуска тестов поднимите контейнер с Redis используйте команду:

```sh
docker compose up -d redis
pytest

```

### Запуск сервиса
Сервис запускается командой 
```shell
docker compose up -d
```