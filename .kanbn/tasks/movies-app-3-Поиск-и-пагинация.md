---
created: 2025-03-18T12:21:41.424Z
updated: 2025-03-18T12:21:41.423Z
assigned: ""
progress: 0
tags: []
---

# Movies App #3 - Поиск и пагинация

Требования к поиску:

Поиск должен происходить сразу после того, как пользователь ввел поисковый запрос (без нажатия на кнопку)
При вводе символов в поле ввода запросы не должны отправляться сразу в целях избежания лишних запросов на сервер. Дождитесь, пока пользователь допечатает. Используйте для этого функцию debounce из lodash
Если поиск не дал результатов, должно отображаться сообщение об этом
Пока фильмы загружаются, должен отображаться спиннер загрузки
Результаты поиска должны быть разделены постранично (используйте antd pagination). Постраничное деление данных (pagination) реализовывается на сервере, вам лишь нужно отобразить интерфейс для его использования. Найдите необходимое API для этого и воспользуйтесь им.

## Sub-tasks

- [ ] Добавить текстовое поле ввода, по изменению которого будет выполняться поиск
- [ ] Сделать серверную пагинацию (при переключении страниц должны отправляться новые запросы) с применением компонента Pagination.
