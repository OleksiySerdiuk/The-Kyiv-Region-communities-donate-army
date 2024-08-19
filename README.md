# Яка громада Київської області найбільше допомагає ЗСУ

## Мета
Дослідити дані з 24.02.2022 по теперішній час та визначити, яка з громад Київської області витрачає найбільше бюджетних коштів на допомогу ЗСУ. 

## Вкладені файли:
- Kyiv_Region - Перелік та коди громад
- Kyiv_Region_Budget_2022-2024 - Річні бюджети громад 2022-2024 років
- Transaction_Report - Звіт про аналіз даних


## Аналіз даних
### Джерела відкритих даних:
https://spending.gov.ua/new/

### Показники
1. Загальні витрати
2. Витрати на оборону

### Підготовка та очищення даних
Зроблено профайлінг даних за допомогою бібліотеки Ydata-profiling. Результат аналізу у вкладених документах.

### Додаткові дані
1.Річний бюджет громади

### Джерела додаткових даних
Офіційні сайти територіальних громад

##
# :atm: Donate dashboard
Додаток Стрімліт показує суми коштів, які громади перерахували на підтримку Збройних сил України.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://the-kyiv-region-community-donates-army.streamlit.app/)

### Як запустити додаток на Вашому обладнанні

1. Встановити бібліотеки

   ```
   $ pip install -r requirements.txt
   ```

2. Запустити додаток

   ```
   $ streamlit run streamlit_app.py
   ```
##
### Jupyter Notebook
https://www.datacamp.com/datalab/w/3c676a97-2e93-4301-b0eb-0d3850d12c88/edit
