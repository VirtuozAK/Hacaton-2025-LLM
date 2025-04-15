# 🧠 AI Summary & QA Tool

Скрипт автоматически загружает HTML-страницы из заданного массива, получает текст, делает его краткое содержание OpenAI API и отвечает на заранее заданные вопросы.


## 📦 Требования

- Python 3.9 или выше
- API-ключ и URL для доступа к OpenAI-совместимому API


## 🛠 Установка

1. Установи Python:  
   [Скачать Python](https://www.python.org/downloads/)

2. Клонируй репозиторий и перейди в директорию проекта:

3. Установи зависимости:

```bash
pip install -r requirements.txt
```


## 🔐 Конфигурация

В скопированном файле `secret.py` в корне проекта замени API_KEY = "your-api-key" на свой ключ


## 🚀 Запуск

Перейди в `secret.py` и задай список сайтов и вопросов

Запусти основной скрипт:

```bash
python main.py
```


## 💡 Как это работает

1. Получает HTML-код с каждого URL по отдельности
2. Очищает код от ненужных конструкций
3. Формирует краткое содержание текста
4. Отвечает на список вопросов по тексту
5. Выводит результаты в консоль
