<h1 align="center">
  Codifi.ly
</h1>

<p align="center">
  <strong>Современная интерактивная платформа для изучения Python</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-Backend-black.svg?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/SQLite-Database-003B57.svg?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Bootstrap_5-UI-7952B3.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
</p>

---

## О проекте

**Codifi.ly** — это образовательная веб-платформа, которая позволяет изучать программирование на Python прямо в браузере. Процесс обучения разбит на удобные шаги: от изучения теории и прохождения квизов до написания реального кода с мгновенной проверкой. 

Никаких скучных лекций. Только практика, современный дизайн и элементы геймификации!

## Главные особенности

- **Встроенная IDE (Skulpt)** — пишите и запускайте Python-код прямо в браузере без установки дополнительных программ.
- **Система прогресса** — зарабатывайте XP, повышайте свой ранг и отслеживайте успехи в личном кабинете.
- **Умный дизайн** — поддержка светлой и темной тем оформления (Glassmorphism), плавные анимации и кастомные элементы интерфейса.
- **Мультиязычность** — интерфейс полностью переведен на русский, английский и немецкий языки.
- **Интерактивный справочник** — быстрый и удобный поиск по теории с современной визуализацией.
- **Геймификация** — визуальный и звуковой отклик при правильном решении задач для повышения вовлеченности.

## Технологии

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (Bootstrap 5), JavaScript
- **База данных**: SQLite
- **Исполнение кода**: Skulpt (выполнение Python в браузере)

## Установка и запуск

1. Клонируйте репозиторий:
   ```bash
   git clone <url-репозитория>
   ```

2. Перейдите в директорию проекта:
   ```bash
   cd LearningApp
   ```

3. Создайте и активируйте виртуальное окружение:
   ```bash
   python -m venv .venv
   # Для Windows:
   .venv\Scripts\activate
   # Для Linux/macOS:
   source .venv/bin/activate
   ```

4. Установите зависимости (если есть requirements.txt):
   ```bash
   pip install -r requirements.txt
   ```

5. Инициализируйте или запустите приложение:
   ```bash
   python app.py
   ```

6. Откройте браузер и перейдите по адресу:
   ```text
   http://127.0.0.1:5000
   ```

## Структура проекта

- `app.py` — основной файл приложения Flask.
- `translate_course.py` — скрипт для генерации переводов курсов на другие языки.
- `static/` — статические файлы (такие как CSS, JavaScript, изображения и `courses.json`).
- `templates/` — HTML-шаблоны страниц.
- `instance/` — папка с файлом базы данных SQLite.
