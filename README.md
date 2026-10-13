## Олег - ML/MLOps-инженер

Делаю модели и всё, что вокруг них: пайплайны данных, сервисы, CI, мониторинг. Последнее время в основном RAG, LLM-сервисы и оценка их качества.

**В работе:** churn- и LTV-модели, гибридный поиск (FAISS + BM25 + RRF), LLM-генерация пуш-уведомлений на 13 языках, пайплайны на Dagster и ClickHouse.

**Учёба:** магистратура МИФИ по машинному обучению. ВКР - насколько можно доверять автоматическим метрикам и LLM-судьям при оценке русскоязычных RAG-систем и агентов. Проверяю через контролируемую инъекцию дефектов.

### Проекты

| | |
|---|---|
| [pd-model-mlops](https://github.com/junknewera/pd-model-mlops) | PD-модель дефолта по кредитным картам с полной MLOps-обвязкой: Great Expectations, DVC, MLflow, GitHub Actions, FastAPI в Docker, мониторинг дрифта через PSI |
| [ecology-helper](https://github.com/junknewera/ecology-helper) | RAG-чатбот по климату: E5-эмбеддинги, Qwen2.5-0.5B, ROUGE-1 0.57 против 0.24 без retrieval, Streamlit, Docker |
| [sber-avtopodpiska](https://github.com/junknewera/sber-avtopodpiska) | Прогноз конверсии по сессиям Google Analytics: CatBoost и LightGBM, хронологическая валидация, калибровка вероятностей |
| [ml-kursovaya](https://github.com/junknewera/ml-kursovaya) | Активность химических соединений против гриппа по дескрипторам RDKit: 3 регрессии и 4 классификации |
| [TodoList](https://github.com/junknewera/TodoList) | CLI-менеджер задач на C++: категории, приоритеты, undo, хранение в JSON, юнит-тесты |

### Open source

- [blanket](https://github.com/rafaelmardojai/blanket/pull/411) - перевёл микширование всех звуков в один GStreamer-пайплайн (merged)

### Стек

<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,postgres,redis,githubactions,linux,nix,cpp,git" />

ClickHouse, Dagster, Celery, FAISS, MLflow, DVC, CatBoost, LightGBM, Pydantic

Сижу на NixOS на ARM-ноутбуке (ThinkPad X13s), x86-софт гоняю через FEX.
