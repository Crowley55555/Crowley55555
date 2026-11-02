# Привет, я Артём Лавров

**Python-разработчик — AI-боты и автоматизация для бизнеса.** Москва, работаю удалённо.

Делаю Telegram-ботов и сервисы с нейросетями, которые снимают с бизнеса ручную работу: AI-консультант отвечает клиентам по прайсу и частым вопросам, собирает заявку и передаёт менеджеру. Подключаю GigaChat, YandexGPT, OpenAI и другие внешние API и довожу интеграцию до рабочего состояния; в последних проектах пишу автотесты (pytest).

## Чем могу помочь

- **AI-консультант в Telegram** — бот отвечает клиентам по вашему сценарию и ведёт к покупке или заявке.
- **Обработка документов и фото** — текст из PDF и картинок, распознавание изображений нейросетью.
- **Бэкенд и API** — FastAPI или Django, подключение внешних сервисов и AI.

## Опыт

Год стажировки в **ООО «СМАЙПЛ» (SMAIPL)** на функциях платформы AI-агентов (09.2025 — 09.2026): извлечение текста из PDF, анализ PDF с распознаванием изображений, распознавание изображений через GPT-4o, омниканальный запрос (текст + фото), генератор SVG через OpenRouter, функции генерации видео (Sora 2, Kling, Veo 3), интеграции с Яндекс.Диском, переводом Яндекс и OpenAI, геокодером на OpenStreetMap. Техлид группы стажёров: ревью кода на соответствие документации, рекомендации по логике, публикация решений на сервер.

Рекомендательное письмо от генерального директора — пришлю по запросу.

## Проекты (закреплены ниже)

- **[tvsalebot](https://github.com/Crowley55555/tvsalebot)** — AI-консультант по продаже телевизоров: пошаговый сценарий продаж, 55 pytest-тестов. aiogram · FastAPI · GigaChat · Docker.
- **[brand-activities-bot](https://github.com/Crowley55555/brand-activities-bot)** — бот активностей для 5 брендов: регистрация с ПДн-согласием, опросы, запись к специалисту, колесо призов, модерация UGC, промокоды, веб-админка с ролями; **835 pytest-items**. Обезличенная демо-копия MVP, развёрнутого на 2 серверах. FastAPI · aiogram · PostgreSQL · SQLAlchemy · Alembic · Docker.
- **[pricefaq-bot](https://github.com/Crowley55555/pricefaq-bot)** — AI-консультант по прайсу и FAQ с передачей заявки менеджеру в Telegram: отвечает по базе знаний (RAG на ChromaDB), собирает заявку (имя → телефон → услуга → время), failover между 4 LLM (GigaChat → YandexGPT → OpenRouter → OpenAI). Демо на автосервисе. aiogram · FastAPI · LangChain · ChromaDB.
- **[GhostCopyWriter](https://github.com/Crowley55555/GhostCopyWriter)** — SaaS-генератор постов для соцсетей: веб-кабинет и Telegram-бот, посты с картинками для VK/Telegram/Дзен за один запрос; доступ по токенам, тарифы. Django · Flask · python-telegram-bot · GigaChat · OpenAI · PostgreSQL · Redis · Docker · nginx.
- **[Ai-API-Assistant-playground](https://github.com/Crowley55555/Ai-API-Assistant-playground)** — Django-песочница для AI-ассистентов: GigaChat и YandexGPT, сравнение моделей, Function Calling, история чатов. Django · DRF · GigaChat · YandexGPT.
- **[VKimgPoster](https://github.com/Crowley55555/VKimgPoster)** — автопостер картинок во ВКонтакте как AI-tool: публикация в сообщество через официальный VK API; поставляется с OpenAI/Anthropic-совместимой JSON-схемой функции (tool-call из LLM). Python · requests · VK API.

## Стек

**Backend:** Python, FastAPI, Django, Flask, Pydantic, SQLAlchemy, Alembic, PostgreSQL, Redis.
**Боты и AI:** aiogram, python-telegram-bot, GigaChat, YandexGPT, OpenAI API, OpenRouter, LangChain, RAG (ChromaDB), промпт-инжиниринг.
**Инфра:** Docker, docker compose, nginx, Linux, Git.
**Качество:** pytest, ревью кода.
**Парсинг:** requests, httpx, BeautifulSoup, Playwright.

## Связаться

- **Telegram:** [@rain511](https://t.me/rain511)
- **GitHub:** здесь, `Crowley55555`
