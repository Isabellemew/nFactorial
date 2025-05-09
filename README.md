<<<<<<< HEAD
# nFactorial
=======
# nFactorial
Новостной агрегатор — это веб-приложение, которое позволяет пользователям просматривать свежие новости со всего мира. Пользователь может выбрать страну и категорию новостей, а также воспользоваться поиском по ключевым словам. Интерфейс выполнен в современном стиле с небесно-голубым фоном и логотипом в шапке сайта. Новости загружаются с помощью NewsAPI и отображаются в виде карточек с заголовком, источником, временем публикации и изображением. Проект реализован на React с использованием библиотеки BaseWeb для компонентов интерфейса.
Вот инструкция по установке и запуску вашего проекта:
### Установка и запуск
1. **Клонируйте репозиторий:**
   ```bash
   git clone <ссылка_на_ваш_репозиторий>
   cd nFactorial
   ```
2. **Установите зависимости:**
   ```bash
   npm install
   ```
   или, если используете yarn:
   ```bash
   yarn install
   ```
3. **Получите API-ключ для NewsAPI:**
   - Зарегистрируйтесь на [newsapi.org](https://newsapi.org/) и получите свой API-ключ.
4. **Создайте файл конфигурации:**
   - В корне проекта создайте файл `src/config.js` и добавьте в него:
     ```js
     export const apiKey = "ВАШ_API_КЛЮЧ";
     ```
5. **Запустите проект:**
   ```bash
   npm start
   ```
   или
   ```bash
   yarn start
   ```
Процесс проектирования и разработки новостного агрегатора включал определение ключевых функций (просмотр, фильтрация и поиск новостей), выбор стека технологий (React, NewsAPI), проектирование простого и удобного интерфейса с акцентом на пользовательский опыт, создание независимых компонентов для каждой части приложения, интеграцию с внешним API для получения новостей, стилизацию с использованием небесно-голубого фона и логотипа, а также тестирование всех функций для обеспечения корректной работы и адаптивности на разных устройствах.
В процессе работы над проектом был применён уникальный подход к управлению задачами и сроками с помощью системы Jira: все этапы разработки — от проектирования интерфейса до интеграции с NewsAPI — были разбиты на отдельные задачи, которым назначались ответственные и дедлайны. Такой подход позволил эффективно отслеживать прогресс, своевременно выявлять и устранять узкие места, а также обеспечил прозрачность и структурированность процесса разработки, что способствовало успешному и своевременному завершению проекта.
### Обсуждение компромиссов, принятых во время разработки:
В процессе разработки пришлось сделать выбор в пользу простоты и скорости реализации, поэтому для интерфейса использовалась готовая библиотека компонентов BaseWeb, а не полностью кастомная верстка. Это позволило быстрее собрать рабочий прототип, но ограничило гибкость в дизайне. Также, для получения новостей был выбран один внешний API (NewsAPI), что упростило интеграцию, но ограничило разнообразие источников.
### Описание известных ошибок или проблем в приложении:
Известные проблемы включают возможные ограничения по количеству запросов к NewsAPI (rate limit), из-за чего при частом обновлении новостей может временно перестать приходить информация. Также, иногда встречаются новости без изображений или с некорректными данными, что может влиять на внешний вид карточек. Адаптивность интерфейса протестирована на основных устройствах, но на некоторых экранах возможны незначительные визуальные проблемы
### бъяснение выбора технического стека:
React был выбран за его популярность, компонентный подход и большое сообщество, что облегчает поддержку и развитие проекта. BaseWeb позволил быстро реализовать современный и удобный интерфейс без необходимости разрабатывать все элементы с нуля. NewsAPI был выбран как простой и удобный источник новостей с понятной документацией и бесплатным тарифом для прототипирования.
>>>>>>> 7663770 (Upload project files)
