# 02. DATA STRUCTURE

Этот документ описывает будущую структуру данных `marketparser`.

Важно: на текущей задаче эти папки и CSV-файлы не создаются. Ниже описана только будущая структура.

## Будущая структура

```text
marketparser/
├── data/
│   ├── input/
│   │   └── product_ideas.csv
│   ├── manual/
│   │   └── manual_market_check.csv
│   ├── raw/
│   │   ├── ozon_raw.csv
│   │   └── wb_raw.csv
│   └── processed/
│       └── product_ideas_score.csv
├── reports/
│   └── demand_report.md
└── src/
    └── future parser code
```

## Назначение будущих папок

- `data/input` — исходные идеи и запросы.
- `data/manual` — данные ручной проверки.
- `data/raw` — сырые выгрузки будущего парсера.
- `data/processed` — обработанные оценки.
- `reports` — отчёты.
- `src` — будущий код, только после отдельной задачи.

## Правило текущего этапа

На текущем этапе не создавать:

- `marketparser/data`;
- `marketparser/reports`;
- `marketparser/src`;
- CSV-файлы;
- рабочий код.

Эти элементы можно будет создавать только по отдельной задаче.
