# Технологии индустриального программирования, лекция №1, описание проекта
## Сайт о компьютерных играх с оценками и отзывами 
Цель проекта - создать интернет сервис, на котором пользователи смогут ознакомиться с информацией о компьютерных играх, посмотреть среднюю оценку, а так же написать свой отзыв.

## Методология разработки
Для данного проекта была выбрана методология разработки Agile - гибкая методология разработки программного обеспечения, которая предполагает итеративный и инкрементный подход. Процесс разделяется на короткие циклы (итерации), что позволяет команде регулярно предоставлять работающий продукт, быстро адаптироваться к изменениям и получать обратную связь от пользователей.
Данная методология была выбрана ввиду следующих причин:
1. Agile позволяет легко вносить изменения на основе отзывов пользователей, что важно для проекта с множеством пользователей.
2. Постепенное добавление функциональности помогает лучше понять потребности пользователей на каждом этапе.
3. Обратная связь: Регулярное получение фидбэка от пользователей улучшает продукт, делая его более востребованным.

## Этапы разработки
В разработку проекта включены следующие этапы:

### 1. Сбор и анализ требований
Определить целевую аудиторию и ключевые функции, необходимые для проекта.
Необходимые действия:
1)Встречи с заказчиками, анализ конкурентов.
2)Формулирование списка функций и пользовательских историй (user stories).
3)Определение MVP (минимально жизнеспособного продукта).
Ожидаемый результат: Документ с функциональными и нефункциональными требованиями, приоритет функций.

### 2. Проектирование 
Спроектировать архитектуру системы и пользовательский интерфейс.
Необходимые действия:
1)Проектирование технической архитектуры (выбор технологий: бэкенд, фронтенд, база данных).
2)Создание прототипов интерфейса и UX-дизайн (схемы страниц, логика взаимодействий).
3)Определение API и базы данных
Ожидаемый результат: Техническая архитектура, дизайн макеты и прототипы.

### 3. Разработка 
Реализовать функции и интегрировать систему.
Необходимые действия:
1)Фронтенд разработка: создание интерфейса (например, на React/Vue.js).
2)Бэкенд разработка: создание API и бизнес-логики (например, с использованием Node.js/Python).
3)Настройка базы данных (например, PostgreSQL или MongoDB).
4)Интеграция фронтенда и бэкенда.
Ожидаемый результат: Работающий продукт с базовыми функциями для пользователей.

### 4. Тестирование 
Проверить качество продукта и исправить ошибки.
Необходимые действия:
1) Юнит-тестирование: проверка работы отдельных модулей.
2) Интеграционное тестирование: проверка взаимодействия компонентов.
3)Тестирование пользовательского интерфейса и UX.
4)Нагрузочное тестирование для проверки производительности под нагрузкой.
Ожидаемый результат:  Исправленный и протестированный продукт, готовый к релизу.

### 5. Обеспечение безопасности
Обеспечить защиту данных пользователей и системы.
Необходимые действия:
1) Реализация системы аутентификации и авторизации (например, с использованием OAuth).
2) Шифрование данных пользователей (например, хранение паролей с хешированием).
3) Защита от атак (SQL-инъекции, XSS, CSRF).
Ожидаемый результат: Защищенная система, готовая к использованию.

### 6. Запуск 
Развернуть систему и сделать её доступной пользователям.
Необходимые действия:
1) Подготовка серверной инфраструктуры (настройка облачного хостинга, например AWS или Heroku).
2) Разворачивание приложения в рабочей среде.
3) Настройка мониторинга и логирования для отслеживания ошибок и производительности.
Ожидаемый результат:  Живое приложение, доступное для пользователей.

### 7. Поддержка и развитие 
Поддерживать и улучшать сервис на основе обратной связи пользователей.
Необходимые действия:
1) Исправление ошибок, выявленных пользователями.
2) Регулярные обновления с добавлением новых функций.
3) Оптимизация производительности.
Ожидаемый результат: Постоянное улучшение и развитие продукта.

### 8. Сбор обратной связи и анализ (Feedback & Analysis)
Оценить успех продукта и внести улучшения.
Необходимые действия:
1) Сбор обратной связи от пользователей.
2) Анализ метрик использования (вовлеченность пользователей, оценка успешности функций).
3) Подготовка плана для следующих итераций.
Ожидаемый результат: План дальнейшего развития сервиса на основе аналитики.


## Команда проекта

### 1. Проектный менеджер (Project Manager)
Задачи:
     - Управление проектом, планирование задач и координация команды.
     - Обеспечение соблюдения сроков и бюджета.
     - Коммуникация с заказчиками и заинтересованными сторонами.
     - Разрешение конфликтов и управление рисками.
Ключевые навыки: управление проектами (Scrum/Agile), коммуникационные навыки, тайм-менеджмент.
   
### 2. UX/UI дизайнер
Задачи:
     - Проектирование пользовательского интерфейса (UI) и взаимодействия (UX).
     - Создание макетов и прототипов для всех страниц сервиса.
     - Оптимизация пользовательского опыта (UX) на основе исследований и тестов.
     - Работа с фидбеком от пользователей для улучшения интерфейса.
Ключевые навыки: знание инструментов Figma/Adobe XD, дизайн интерфейсов, тестирование UX.

### 3. Фронтенд-разработчик
Задачи:
     - Разработка клиентской части приложения (интерфейса).
     - Реализация взаимодействия с бэкендом через API.
     - Оптимизация производительности интерфейса.
     - Адаптивная верстка для разных устройств (десктоп, планшеты, мобильные устройства).
 Ключевые навыки: HTML, CSS, JavaScript (React, Vue.js или Angular), адаптивная верстка, интеграция с API.

### 4. Бэкенд-разработчик
Задачи:
     - Разработка серверной части приложения (логика, обработка данных, API).
     - Управление базой данных (структурирование, оптимизация запросов).
     - Интеграция с внешними сервисами и API.
     - Реализация функциональности безопасности (аутентификация, авторизация).
Ключевые навыки: Node.js/Python/Ruby/Java, работа с базами данных (PostgreSQL, MongoDB), проектирование API, обеспечение безопасности данных.

### 5. DevOps инженер
   Задачи:
     - Настройка и поддержка серверной инфраструктуры.
     - Автоматизация развертывания приложения (CI/CD).
     - Мониторинг производительности системы и исправление сбоев.
     - Настройка резервного копирования и восстановление данных.
Ключевые навыки: управление облачными сервисами (AWS, Google Cloud, Azure), инструменты контейнеризации (Docker, Kubernetes), автоматизация процессов.

### 6. QA-инженер (Quality Assurance)
Задачи:
     - Разработка и выполнение тестовых сценариев для проверки функциональности приложения.
     - Тестирование на наличие багов, проблем с производительностью, уязвимостей безопасности.
     - Юнит-тесты, интеграционное и пользовательское тестирование.
     - Составление отчетов о тестировании и рекомендаций по улучшению.
Ключевые навыки: ручное и автоматизированное тестирование, знание инструментов для тестирования (Selenium, JUnit), внимание к деталям.

### 7. Аналитик данных
Задачи:
     - Сбор и анализ данных о пользователях и их взаимодействии с платформой.
     - Создание отчетов по поведению пользователей для дальнейшего улучшения UX/UI.
     - Работа с метриками для оценки эффективности функций и бизнес-целей.
     - Оптимизация системы рекомендаций на основе анализа данных.
Ключевые навыки: аналитика данных, работа с базами данных, статистический анализ, знание инструментов для визуализации (Tableau, Power BI).

### 8. Маркетолог
Задачи:
     - Разработка и реализация маркетинговой стратегии по продвижению платформы.
     - Работа с целевой аудиторией: привлечение и удержание пользователей.
     - Взаимодействие с медиа и блогерами для продвижения контента.
     - Анализ эффективности маркетинговых кампаний и корректировка стратегии.
Ключевые навыки: цифровой маркетинг, SMM, работа с контентом, аналитика маркетинговых метрик.

### 9. Техподдержка (опционально)
Задачи:
     - Поддержка пользователей и решение технических проблем.
     - Обратная связь по функциональности приложения, сбор предложений.
     - Управление запросами и тикетами от пользователей.
Ключевые навыки: знание продукта, коммуникация, работа с тикет-системами (Jira, Zendesk).




## Оценка сроков проекта

Проект состоит из нескольких фаз, каждая из которых требует различного времени на выполнение. С учетом методологии Agile, проект будет разбит на итерации (спринты), что позволит более гибко управлять процессом. Оценка сроков выполнения каждого этапа выглядит следующим образом:

### Этапы проекта:

1. Сбор и анализ требований: 2-3 недели
   - Встречи с клиентами, анализ конкурентов, определение пользовательских историй.

2. Проектирование (Design): 3-4 недели
   - Создание макетов интерфейса, разработка архитектуры системы, проработка UX-дизайна.

3. Разработка (Development):
   - Фронтенд разработка: 6-8 недель
     - Реализация клиентской части (страницы, рецензии, рейтинги и т.д.).
   - Бэкенд разработка: 8-10 недель
     - Разработка API, базы данных, функционала рекомендаций и авторизации.
   
4. Тестирование (Testing): 3-4 недели
   - Юнит-тесты, интеграционное тестирование, нагрузочное тестирование.

5. Обеспечение безопасности (Security): 2-3 недели
   - Реализация аутентификации, шифрование данных, защита от атак.

6. Запуск (Deployment): 1-2 недели
   - Развертывание сервиса на сервере, настройка инфраструктуры и CI/CD.

7. Поддержка и улучшение (после релиза): Постоянно
   - Исправление багов, добавление новых функций и обновление системы на основе пользовательских отзывов.

### Общий срок проекта:
4–6 месяцев, включая все этапы разработки и тестирования, с учетом, что команда будет работать над параллельными задачами и итерациями. Время может корректироваться в зависимости от сложности отдельных функций, количества изменений и объема обратной связи от пользователей.


## Оценка сроков проекта:

1. Сбор требований и проектирование: 1-1,5 месяца
   - Сбор пользовательских требований, проектирование архитектуры и UX/UI.
   
2. Разработка: 4-5 месяцев
   - Фронтенд и бэкенд разработка, интеграция с базой данных.
   - Реализация основных функций, таких как регистрация пользователей, система оценок, рецензии, система рекомендаций.

3. Тестирование: 1-1,5 месяца
   - Полное тестирование на ошибки, проверка безопасности, нагрузочное тестирование.

4. Запуск и маркетинг: 1-2 месяца
   - Запуск на серверах, продвижение платформы, поддержка первых пользователей.

Итого: 6-9 месяцев для разработки MVP с основными функциями и последующим запуском.

## Оценка бюджета проекта:

1. Затраты на персонал:
   - Проектный менеджер (1 чел.) — 120,000–150,000 руб./мес.
   - UX/UI дизайнер (1 чел.) — 100,000–140,000 руб./мес.
   - Фронтенд-разработчик (1 чел.) — 130,000–180,000 руб./мес.
   - Бэкенд-разработчик (1 чел.) — 130,000–180,000 руб./мес.
   - QA-инженер (1 чел.) — 100,000–140,000 руб./мес.
   - DevOps-инженер (опционально) — 130,000–160,000 руб./мес.
   - Маркетолог (1 чел.) — 100,000–130,000 руб./мес.

Среднемесячный фонд зарплаты: около 750,000–980,000 руб.

Для 6-9 месяцев:
- Минимальная оценка (6 месяцев): 4.5 – 5.9 млн руб.
- Максимальная оценка (9 месяцев): 6.75 – 8.8 млн руб.

2. Инфраструктура и инструменты:
   - Облачные сервисы (AWS, Google Cloud) — 20,000–50,000 руб./мес.
   - Инструменты для разработки и дизайна (Figma, Jira, GitHub) — 10,000–30,000 руб./мес.

Итого на инфраструктуру за 6-9 месяцев: 180,000–720,000 руб.

3. Маркетинг:
   - Рекламные кампании (таргетинг, контекстная реклама) — 200,000–500,000 руб.
   - Взаимодействие с блогерами, геймерами и СМИ — 100,000–300,000 руб.

Итого на маркетинг: 300,000–800,000 руб.

4. Прочие расходы:
   - Юридические и бухгалтерские услуги — 50,000–100,000 руб.
   - Непредвиденные расходы — 100,000–200,000 руб.


## Общий бюджет:

1. Минимальный бюджет (6 месяцев): около 5.5–6.8 млн руб.
2. Максимальный бюджет (9 месяцев): около 7.5–10.5 млн руб.

