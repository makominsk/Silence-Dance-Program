# Tech Context: Silence Dance Program

## Технологии и стек
- **Frontend**: Чистый HTML5, CSS3, JavaScript (ES6+)
- **Шрифты**: Google Fonts (Cormorant Garamond, Montserrat)
- **Инструменты разработки**: VSCode, Git
- **Браузерная поддержка**: Современные браузеры (Chrome, Firefox, Safari, Edge)

## Разработка и setup
- **Локальная разработка**: Открытие index.html в браузере
- **Редактирование**: Прямое изменение файлов в IDE
- **Тестирование**: Ручное тестирование в браузерах, проверка адаптивности
- **Деплой**: Статические файлы, можно хостить на GitHub Pages, Netlify, etc.

## Зависимости
- **Нет внешних зависимостей**: Проект не использует npm, yarn или другие менеджеры пакетов
- **Google Fonts**: Подключаются через CDN в head
- **Изображения**: Локальные файлы в папке images/

## Технические паттерны
- **CSS Organization**: Все стили в одном файле с разделением по секциям
- **JavaScript**: Vanilla JS без библиотек, модульный код
- **Performance**: Минимум HTTP-запросов, оптимизированные изображения
- **SEO**: Семантический HTML, meta-теги, alt-тексты

## Ограничения технологий
- **Без build-процесса**: Ручная оптимизация и минификация
- **Без backend**: Статический контент, обновления вручную
- **Без тестирования**: Ручное QA, нет automated tests
- **Без CMS**: Контент hardcoded в HTML

## Инструменты и workflow
- **Версионирование**: Git с удаленным репозиторием на GitHub
- **Кодинг стандарты**: Consistent indentation, meaningful class names
- **Отладка**: Browser DevTools для CSS/JS
- **Оптимизация**: Manual image compression, CSS minification if needed

## Будущие улучшения
- **Build tools**: Возможен переход на Parcel/Webpack для автоматизации
- **CMS integration**: Добавление headless CMS для управления контентом
- **PWA features**: Service workers для оффлайн-доступа
- **Analytics**: Google Analytics для отслеживания посетителей

## SEO инструменты
- **Мета-теги**: Description, keywords, viewport для мобильности
- **Структурированные данные**: JSON-LD Schema.org для образовательных организаций
- **Файлы для поисковиков**: robots.txt (запрет индексации технических файлов), sitemap.xml (карта сайта)
- **Аналитика**: Google Analytics с gtag для отслеживания трафика
- **Семантика**: Правильная иерархия заголовков H1-H3, alt-тексты для изображений
