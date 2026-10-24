![Михаил Нагорный — DevOps-инженер. Python, Linux-инфраструктура и автоматизация.](assets/header.svg)

[English](README.md) · [Русский](README.ru.md) · [Публичные репозитории](https://github.com/xacx-dev?tab=repositories&type=public)

# Привет, я Михаил

**DevOps-инженер с опытом Python-разработки.** С февраля 2026 года занимаюсь Linux-инфраструктурой, автоматизацией развёртывания, CI/CD, мониторингом и эксплуатацией сервисов.

Опыт разработки помогает работать со всей системой: Python API, фоновыми задачами, базами данных, контейнерами, обратными прокси и Linux-службами, на которых работают приложения.

## Чем занимаюсь

- **Развёртывание и автоматизация:** окружения Docker и Compose, подготовка и обновление серверов через Ansible, GitHub Actions, скрипты релизов и процедуры отката.
- **Эксплуатация Linux:** Ubuntu, Debian и Astra Linux; службы и таймеры systemd, SSH, резервные копии, ротация логов, проверки работоспособности и перенос сервисов между VPS.
- **Мониторинг и диагностика:** агенты и прокси Zabbix, Grafana, мониторинг файловых систем и inode, journald, диагностика баз данных и сетевых соединений.
- **Сети и виртуализация:** Nginx, Caddy, HAProxy, HTTPS, DNS, IPv4/IPv6 и WireGuard; виртуальные машины Hyper-V и восстановление UEFI/GRUB.

## Технологии

| Область | Используемые инструменты |
| :--- | :--- |
| Инфраструктура и доставка | Linux · Docker · Docker Compose · Ansible · GitHub Actions · Git · Bash · PowerShell |
| Мониторинг и сети | Zabbix · Grafana · systemd · Nginx · Caddy · HAProxy · WireGuard · Hyper-V |
| Python backend | Django · Django REST Framework · aDRF · FastAPI · Pydantic · SQLAlchemy · Alembic · Tortoise ORM |
| Данные и фоновые задачи | PostgreSQL · MySQL · SQLite · Redis · RabbitMQ · Celery · APScheduler |
| Веб и интеграции | Vue 3 · TypeScript · JavaScript · Vite · HTML/CSS · aiogram · Telethon · Playwright |
| Качество и проверки | pytest · Ruff · Vitest · ESLint · проверка OpenAPI · Gitleaks |

<details>
<summary>Дополнительно: обработка данных, автоматизация и встраиваемый Linux</summary>

- **Обработка данных:** pandas, NumPy, DuckDB, PyArrow/Parquet, openpyxl и XlsxWriter.
- **Асинхронные сервисы и сбор данных:** asyncio, aiohttp, HTTPX, Requests, Selenium и Beautiful Soup.
- **ML-компоненты:** scikit-learn, обработка акустических данных и компоненты классификации в Python-проектах.
- **Встраиваемый Linux:** Raspberry Pi, GPIO, I²C, UART/serial, Weston/Wayland, DRM/KMS и kiosk-интерфейсы.
- **Запуск приложений:** Uvicorn, Gunicorn, WebSockets, REST API и интеграции со сторонними API.

</details>

## Опыт в проектах

Ниже — проекты с закрытым кодом. Описаны инженерные задачи без внутренних данных систем и заказчиков.

| Проект | Приложение и инженерные задачи | Основной стек |
| :--- | :--- | :--- |
| **Платформа сбора вакансий** | API сбора данных, браузерная автоматизация, загрузка из Telegram, отдельные workers и планировщик; контейнеризация, HTTPS и резервные копии. | FastAPI · SQLAlchemy · PostgreSQL · Redis · Playwright · Telethon · Docker |
| **Система операций маркетплейсов** | Backend и веб-приложение для операционных процессов и аналитики; развёртывание нескольких сервисов, миграции, фоновые workers, CI и скрипты релизов/отката. | Django/DRF · Vue 3 · TypeScript · PostgreSQL · Docker Compose · GitHub Actions |
| **Система обучения и аттестации** | Роли, учебные программы, аттестации и генерация документов; контейнеризация, очереди, HTTPS и резервное копирование БД по расписанию. | Django/DRF · Vue 3 · Celery · Redis · PostgreSQL · Docker Compose |
| **Telegram Mini App для программы лояльности** | Клиентское приложение, отдельный интерфейс администрирования и API; сборки frontend/backend, автоматические проверки и проверки здоровья контейнеров. | Django/aDRF · Vue 3 · TypeScript · PostgreSQL · Docker · GitHub Actions |
| **Платформа устройства на Raspberry Pi** | Дисплеи, датчики, аудио и Linux kiosk UI; службы systemd, обновления через Git, проверки работоспособности, резервные копии и откат. | Python · FastAPI · PostgreSQL · Raspberry Pi · systemd · Wayland |
| **Бизнес-боты и администрирование** | Telegram-боты с администрированием на Django, заданиями по расписанию, внешними API, обработкой таблиц и контейнеризированными сервисами. | aiogram · Django · APScheduler · PostgreSQL · Redis · Docker Compose |

## Открытый код

**[MaxBot_template](https://github.com/xacx-dev/MaxBot_template)** — каркас бота для MAX с отдельным API, миграциями БД и тремя сервисами в Compose. Есть Dockerfile, скрипт резервного копирования и ограничение объёма логов.  
`Python` · `FastAPI` · `SQLAlchemy` · `Alembic` · `PostgreSQL` · `Docker Compose`

<details>
<summary>Ранние проекты и эксперименты</summary>

| Репозиторий | Что внутри |
| :--- | :--- |
| [BotTelegramProject](https://github.com/xacx-dev/BotTelegramProject) | Бот сообщества: регистрация, профили, поиск участников и интеграция с API. Python, aiogram и Requests. |
| [BotAssistant](https://github.com/xacx-dev/BotAssistant) | Администрирование групп чатов и рассылки, включая импорт XLSX. Python, aiogram, Requests и openpyxl. |
| [HackathonKM](https://github.com/xacx-dev/HackathonKM) | Хакатонный бот с регистрацией, профилями, учебными вопросами и обратной связью через API. Python и aiogram. |
| [python-database-easy-and-fast](https://github.com/xacx-dev/python-database-easy-and-fast) | Экспериментальная файловая БД с TCP-сервером и Python-клиентом. |
| [vezdecode](https://github.com/xacx-dev/vezdecode) | Ранний проект на VK API для изучения связей между участниками беседы. |
| [minecraft-enrichment-uranium-cell](https://github.com/xacx-dev/minecraft-enrichment-uranium-cell) | Ранний эксперимент с автоматизацией в Minecraft / RedPower 2. |

Репозитории показывают ранние работы и эксперименты; зависимости и API соответствуют времени их создания.

</details>

## Профессиональный путь

- **ЭлРос · октябрь 2024 — настоящее время.** Пришёл ведущим инженером-программистом прикладного ПО: Django API, микросервисы и развёртывание. В **феврале 2026 перешёл в системное администрирование / DevOps**: инфраструктура, CI/CD, Ansible и мониторинг.
- **BOTTEC · май 2022 — июнь 2024.** Middle Python-разработчик: Telegram-боты для бизнеса, администрирование на Django, API-интеграции и развёртывание на Linux с Docker и Nginx.
- **CHATEX · октябрь — ноябрь 2021.** Стажировка во frontend-разработке: Vue.js, React, JavaScript, SDK и работа с API.
- **Haclever · октябрь 2019 — май 2020.** Junior Python-разработчик: боты на aiogram, сервисы FastAPI, асинхронное программирование и окружения Ubuntu/Docker.

## Образование и интересы

**Владимирский государственный университет** — бакалавриат «Инфокоммуникационные технологии и системы связи», **2025**. Магистратура по радиотехнике и радиосистемам — **ожидаемый выпуск в 2027 году**.

Вне разработки интересуюсь радиоинженерией, микроконтроллерами и автомобилями. Проекты на Raspberry Pi соединяют мой интерес к программированию и электронике.

---

**Связаться по работе:** [Telegram](https://t.me/the_xacx_work) · [GitHub](https://github.com/xacx-dev)
