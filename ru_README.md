# Телеграм-бот с функциональностью ChatGPT

## Описание проекта
Для использования функциональности ChatGPT был создан этот бот с использованием API OpenAI.  
Для использования вам потребуется иметь собственный токен для телеграм-бота и для API OpenAI. Введите эти токены в файл template.env.  
Все требования находятся в файле requirements.txt.  

Функциональность бота позволяет вам выбирать между английским и русским языками.  
Вы можете отправлять текстовые и голосовые сообщения. Голосовые сообщения будут транскрибированы с использованием библиотеки Speech_recognition и вашего локального хранилища для импортированных голосовых файлов.  
Бот также имеет базовую функцию ведения журнала, а также функцию отправки сообщений об ошибках конкретному пользователю Telegram, который обеспечивает техническую поддержку бота.  

## Дополнительная информация
Инструменты: Telegram, OpenAI, Speech_recognition, Logger
