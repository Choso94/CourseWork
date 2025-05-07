# Анализатор транзакций из Excel

## Описание

Проект реализует:
- 📊 JSON-ответ для главной страницы (`views.py`)
- 🏦 Инвесткопилка — сколько можно отложить при округлении трат (`services.py`)
- 📁 Отчет по тратам в категории за 3 месяца (`reports.py`)

## Запуск

1. Установите зависимости:
   ```bash
   pip install -r requirements.txt
Запустите:

bash
Копировать
Редактировать
python src/main.py
Тестирование
bash
Копировать
Редактировать
pytest tests/
Структура
src/ — основной код

tests/ — юнит-тесты

data/operations.xlsx — входной Excel-файл

user_settings.json — настройки валют и акций

yaml
Копировать
Редактировать

---

## 📄 `user_settings.json` (пример)

```json
{
  "user_currencies": ["USD", "EUR"],
  "user_stocks": ["AAPL", "AMZN", "GOOGL", "MSFT", "TSLA"]
}