# Кластеризация и прогнозирование оттока клиентов сети фитнес-центров

**Описание проекта**

Мы помогаем сети фитнес-центров создать стратегию взаимодействия с клиентами. Наша задача: провести анализ данных о клиентах и подготовить план действий по их удержанию.

**Задачи проекта**

1. Научиться прогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
2. Сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
3. Проанализировать основные признаки, наиболее сильно влияющие на отток;
4. Сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами:
    - выделить целевые группы клиентов;
    - предложить меры по снижению оттока;
    - определить другие особенности взаимодействия с клиентами.

## Стэк
Pandas, Scikit-learn, Seaborn, Matplotlib, SciPy

## Данные

В нашем распоряжении один csv-файл с данными о клиентах фитнес-центра на месяц до оттока и факт оттока на определённый месяц.
Таблица содержит следующие поля:

- 'Churn' — факт оттока в текущем месяце;
- 'gender' — пол;
- 'Near_Location' — проживание или работа в районе, где находится фитнес-центр;
- 'Partner' — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента);
- Promo_friends — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
- 'Phone' — наличие контактного телефона;
- 'Age' — возраст;
- 'Lifetime' — время с момента первого обращения в фитнес-центр (в месяцах).
- 'Contract_period' — длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год);
- 'Month_to_end_contract' — срок до окончания текущего действующего абонемента (в месяцах);
- 'Group_visits' — факт посещения групповых занятий;
- 'Avg_class_frequency_total' — средняя частота посещений в неделю за все время с начала действия абонемента;
- 'Avg_class_frequency_current_month' — средняя частота посещений в неделю за предыдущий месяц;
- 'Avg_additional_charges_total' — суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон.

## Результаты
По итогам проекта сфорулированы следующие рекомендации для фитнес-центров:
- Стимулировать продажу абонементов сроком больше, чем на месяц. Снизить продажу месячных абонементов. 
- Следить за параметрами: возраст, частота посещения, траты на доп.услуги. Они показательны для клиентов, которые могут перестать посещать фитнес-центр.   
- Расширить программу "Приведи друга"
