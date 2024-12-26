# UmDom

**RU**
«УмДом+» — клиентское приложение на SwiftUI для техподдержки «умного дома». Хранит историю и FAQ в SQLite, подключается к OpenAI API (через прокси) для генерации ответов и изображений. Пользователи узнают о компании, читают FAQ, задают вопросы боту, получают ответы и могут при желании сгенерировать тематическую иллюстрацию.


Приложение «УмДом+» реализует клиентскую часть для решения задач технической поддержки по «умному дому». В основе — SwiftUI для интерфейса, локальная база данных SQLite для хранения истории запросов и заранее известных подсказок (FAQ), а также обращение к OpenAI API (через прокси) для генерации ответов и изображений.

Основные сценарии использования:

Пользователи знакомятся с компанией, которая устанавливает и обслуживает «умные дома».
Читают ответы на часто задаваемые вопросы (FAQ).
Задают собственные вопросы боту, получают ответы и рекомендации в реальном времени.
При желании могут сгенерировать тематическое изображение (например, “дом с солнечными панелями”).


Основные функции:
  Главный экран:
    1) Краткое описание приложения.
    2) Кнопка «Начать», ведущая к разделу “О нас”.
     
  О нас:
    1) Дополнительная информация о компании, предлагаемом оборудовании и услугах.
     
  Часто задаваемые вопросы (FAQ):
    1) Список тематических категорий.
    2) Раскрывающиеся блоки с вопросами и ответами.
     
  Чат-бот (Тех. поддержка 24/7):
    1) Полноценный чат, где пользователь вводит вопрос, а бот (модель OpenAI) отвечает.
    2) Автоподсказки из локальной БД, если вопрос уже известен или схож.
    3) Генерация изображений по “prompt” (например, эскиз или концепт умного дома).
    4) Сохранение истории переписки в SQLite (при перезапуске приложения история восстанавливается).

**EN**

“UmDom+” is a SwiftUI-based client application designed for smart home technical support. It stores user history and FAQs in a local SQLite database and connects to the OpenAI API (via a proxy) to generate responses and images. Users can learn about the company, read the FAQ, ask questions to the bot, receive answers, and optionally generate themed illustrations.

Overview
The “UmDom+” application serves as the client-side solution for providing technical support to smart home users. It is built on SwiftUI for the user interface, uses a local SQLite database to store query history and frequently asked questions (FAQ), and integrates with the OpenAI API (through a proxy) to generate answers and images.

Main Usage Scenarios:
  Learn about the Company:
  Users discover information about the company that installs and maintains smart homes.
  Frequently Asked Questions (FAQ)
  Users read answers to common questions and find guidance on various issues.
  Ask Questions via Chatbot
  Users submit their own questions to the bot and receive real-time answers and recommendations.
  Generate Themed Images
  If desired, users can generate topic-related images (e.g., “a house with solar panels”).
  Key Features
  Home Screen
  Brief description of the application.
  “Get Started” button leading to the About Us section.
  About Us
  Additional information about the company, the equipment offered, and available services.
  Frequently Asked Questions (FAQ)
  A list of themed categories.
  Expandable blocks with questions and answers.
  Chatbot (24/7 Technical Support)
  A full-featured chat where the user types a question and the bot (OpenAI model) responds.
  Auto-suggestions from the local database if the question is already known or similar.
  Image generation based on custom prompts (e.g., a sketch or concept of a smart home).
  Conversation history saved in SQLite (restored on app restart).
