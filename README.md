# Предсказание успешности хоккейных команд NHL

**Автор:** Арасланов Тимур  
**Дата выполнения:** 13 октября 2026 г.

## Описание проекта

Исследование исторических данных хоккейных команд NHL и построение модели классификации для прогнозирования того, окажется ли доля побед команды в следующем сезоне выше медианы по лиге.

## Состав проекта

- `hockey_team_notebook.ipynb` — полный анализ данных, исследовательский анализ, эксперименты с моделями, итоговая оценка и проверка воспроизводимости.
- `data/hockey_raw.csv` — исходная таблица данных.

## Источники данных

- [Scrape This Site — Hockey Teams](https://www.scrapethissite.com/pages/forms/)
- [The New York Times — материалы о правилах овертаймов NHL](https://www.nytimes.com/2008/02/17/sports/hockey/17score.html)

## Инструменты

- Python 3.13
- Google Colab
- pandas, NumPy, requests, Matplotlib, SciPy, scikit-learn

## Запуск

Откройте `hockey_team_notebook.ipynb` в Jupyter Notebook или Google Colab и выполняйте ячейки последовательно.

В начале ноутбука предусмотрен сбор исходных данных с сайта и сохранение CSV в `data/hockey_raw.csv`.