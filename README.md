# to-do-testing-project

Небольшое приложение со списком задач. Служит подопытным для курсов по тестированию: на нём пишут автотесты, а не изучают его код.

## Зачем это нужно

Тестировщику нужен стенд, который ведёт себя как настоящее приложение: ходит в сеть, показывает состояние загрузки, падает и восстанавливается. Здесь всё это есть на маленьком объёме.

Что можно проверять:

- **загрузку данных** из внешнего API (`rest-api-example.hexlet.app/tasks`);
- **поведение при отказе сети**: если API недоступен, приложение показывает ошибку и подставляет запасной список задач, то есть продолжает работать;
- **добавление задачи** и **переключение статуса** в интерфейсе.

Приложение развёрнуто на GitHub Pages, так что для написания тестов его не обязательно поднимать локально.

## Запуск

```bash
make install
make build      # сборка
pnpm run dev    # дев-сервер на http://localhost:5173
pnpm run preview # отдать собранное
```

Деплой на Pages происходит сам при пуше в `main`.

---

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/assets/master/images/hexlet_logo128.png)](https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=to-do-testing-project)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet](https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=to-do-testing-project).

See most active contributors on [hexlet-friends](https://friends.hexlet.io/).
