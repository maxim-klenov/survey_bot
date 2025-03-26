# Telegram bot на GrammyJS

![image preview of the portfolio](main_photo.jpg)
**Описание бота**

Этот бот предназначен для проведения опроса среди пользователей Telegram. Он состоит из четырех вопросов, которые направлены на оценку использования ИИ-инструментов для учебы и их потенциала в будущем.

**Технологии**

- Бот написан на JavaScript с использованием библиотеки Grammy.
- Для взаимодействия с базой данных используется библиотека pg.
- Бот использует.env файл для хранения конфиденциальных данных.

**Функционал бота**

- Бот начинает диалог с пользователем, предлагая ему выбрать свой класс.
- После выбора класса бот предлагает начать опрос.
- В ходе опроса пользователь отвечает на четыре вопроса:
    - Использует ли он ИИ-инструменты для учебы?
    - Для каких предметов он чаще всего использует ИИ?
    - Как он оценивает влияние ИИ на качество его обучения?
    - Как он оценивает потенциал ИИ в будущем?
- После окончания опроса бот благодарит пользователя за участие и сохраняет его ответы в базе данных.

**Установка и запуск**

1. Клонировать репозиторий.
2. Установить зависимости с помощью команды `npm install`.
3. Создать файл `.env` и заполнить его необходимыми данными (BOT_API_KEY, DB_USER, DB_HOST, DB_NAME, DB_PASS, DB_PORT).
4. Запустить бота с помощью команды `node index.js`.
