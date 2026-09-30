Python и C/C++. Telegram-боты, backend, автоматизация, ML и компьютерное зрение.

### Проекты

- [VrZoneBot](https://github.com/TihonSotnikov/VrHeaven-VrZoneBot) - production-бот учёта VR-сеансов в компьютерных клубах: расчёт цены, распределение выручки, выплаты одной транзакцией, аудит-журнал, outbox-очередь, миграции, деплой по тегам с откатом. Python, aiogram 3, SQLite, systemd. 617 тестов.
- [PromoBot](https://github.com/TihonSotnikov/VrHeaven-PromoBot) - бот партнёрской программы: промокоды, расчёт комиссий, индивидуальные ставки, мягкая отмена, интерфейс в одном сообщении. Python, aiogram 3, SQLite, APScheduler. 60 тестов.
- [Digital-Legacy](https://github.com/TihonSotnikov/Digital-Legacy) - сервис цифрового наследия: AES-256-GCM, Argon2id, локальный OCR, машина состояний с атомарными переходами, отдельный worker. FastAPI, PostgreSQL, Docker Compose, Caddy. 31 приёмочный сценарий, 272 теста.
- [Worker-Selection-App](https://github.com/TihonSotnikov/Worker-Selection-App) - подбор рабочих по интервью: faster-whisper, LLM с JSON Schema, навык засчитывается только по цитате кандидата, CatBoost + SHAP для прогноза удержания. FastAPI, JS.
- [Semantic-Search-System](https://github.com/TihonSotnikov/Semantic-Search-System) - семантический поиск по базе знаний: sentence-transformers, top-k через min-heap, REST API, Docker-образ в GHCR. Командный проект.
- [TypingTrainer](https://github.com/TihonSotnikov/TypingTrainer) - тренажёр слепой печати: ядро на C++20 отдельно от Qt в своём потоке, команды и события на std::variant, интерфейс на QML, CI на трёх ОС. 90 тестов ядра.

### Стек

Python (aiogram, FastAPI, SQLAlchemy, pytest) · C/C++ (C++20, Qt/QML, CMake, GoogleTest) · PostgreSQL, SQLite · Linux, Docker · PyTorch, ONNX, sentence-transformers
