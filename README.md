# Elena's Network — Digital Business Card & Mentorship Hub

Официальный сайт-визитка и информационный хаб бизнес-команды **Елены Мелиховой** (независимого партнера **Greenway Global**, г. Павлодар, Казахстан).

**Live URL:** [https://dmitry-lab-git.github.io/elenas_network/](https://dmitry-lab-git.github.io/elenas_network/)

## Описание проекта
Одностраничный презентационный сайт с разделом частых вопросов (FAQ), спроектированный для конвертации теплого трафика из социальных сетей и личных встреч в мессенджеры (WhatsApp, Telegram), а также для локальной (GEO) и AI-оптимизации (LLM SEO).

## Структура проекта
```text
elenas_network/
├── index.html          # Главная страница-визитка (двуязычная, динамический перевод RU/EN)
├── faq.html            # Страница частых вопросов (RU) + JSON-LD FAQPage
├── faq-en.html         # Страница частых вопросов (EN) + JSON-LD FAQPage
├── llms.txt            # Структурированная база знаний для AI-поисковиков (ChatGPT, Perplexity, Gemini)
├── README.md           # Документация репозитория
├── assets/
│   └── img/            # Графические материалы (портрет наставника и др.)
├── css/
│   └── style.css       # Адаптивные стили, сетки и переменные
├── src/
│   └── main.js         # Логика навигации, мобильного меню, скролла и словаря i18n
└── registry/
    └── elenas-network.md # Паспорт проекта и история эволюции