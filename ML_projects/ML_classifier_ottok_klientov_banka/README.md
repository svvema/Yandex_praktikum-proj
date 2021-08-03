# Отток клиентов из банка

## Ссылка
nbviewer.jupyter.org: [Отток клиентов из банка](https://nbviewer.jupyter.org/github/svvema/Yandex_praktikum-proj/blob/main/ML_projects/ML_classifier_ottok_klientov_banka/ML_classifier_ottok_klientov_banka.ipynb)

## Задача

Предсказать закрытие счета в банке, на основе поведения клиента.

## Используемые библиотеки
*pandas, plotly, matplotlib, numpy, sklearn*


## Данные

В наличии были следующие исторические данные от банка:

### Признаки
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — количество недвижимости у клиента
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата

### Целевой признак
- Exited — факт ухода клиента    