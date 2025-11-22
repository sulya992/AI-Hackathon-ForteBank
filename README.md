## Как запустить проект локально

1. Клонировать репозиторий:

```bash
git clone https://github.com/sulya992/AI-Hackathon-ForteBank.git
cd AI-Hackathon-ForteBank

python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt

Структура проекта:
data/raw/ — сырые данные (не в git)
data/processed/ — подготовленные данные
notebooks/ — эксперименты и EDA
src/ — код фичей, моделей и API
docs/ — материалы для презентации

