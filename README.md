# Яка громада Київської області найбільше допомагає ЗСУ

## Вкладені файли:
- Kyiv_Region - Перелік та коди громад
- Kyiv_Region_Budget_2022-2024 - Річні бюджети громад 2022-2024 років
- Transaction_Report - Звіт про аналіз даних

## Вступ

### Мета

Дослідити дані з 24.02.2022 по теперішній час та визначити, яка з громад Київської області витрачає найбільше бюджетних коштів на допомогу ЗСУ. 

## Огляд даних

### Джерела:
https://spending.gov.ua/new/

### Громади
Перелік громад у вкладеному файлі

### Показники
1. Загальні витрати
2. Витрати на оборону

## Аналіз даних

### Підготовка та очищення даних
Після очищення даних залишилися наступні колонки:
1. trans_date
2. amount
3. payer_edrpou
4. payer_name
5. recipt_edrpou
6. recipt_name
7. payment_details
8. kekv
9. kpk
   
Додатково зроблено профайлінг даних за допомогою бібліотеки Ydata-profiling. Результат аналізу у вкладених документах.

## Jupyter Notebook
https://www.datacamp.com/datalab/w/3c676a97-2e93-4301-b0eb-0d3850d12c88/edit

## Додаткові дані
1.Річний бюджет громади

### Джерела додаткових даних
Офіційні сайти територіальних громад

# :earth_americas: GDP dashboard template

A simple Streamlit app showing the GDP of different countries in the world.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
