# AB тест


## Описание проекта
Вместе с отделом маркетинга  подготовлены списки гипотез для увеличения выручки.
Цель исследования: Необходимо с помощью приоритизации гипотез, запуска A/B-теста выявить гипотезы, для увеличения выручки компании.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **scipy**
- **matplotlib**

## 

## Общий вывод

На этапе анализа A/B теста были зафиксированы следующие результаты:
1.Есть статистически значимое различие по конверсии между группами как по сырым данным, так и после фильтрации аномалий. 
2.По сырым данным нет статистически значимого различия по среднему чеку между группами. Однако после удаления аномалий статистически значимое различие есть.
3.График различия конверсии между группами сообщает, что результаты группы B лучше группы A: имеют тенденцию к росту, либо зафиксировались около среднего значения.
4.График различия среднего чека колеблется: он-то и позволил нам найти аномалии.  
5.До очистки данных показатель конверсии был 14% а после очистки 15%. Данная разница говорит о том, что мы можем остановить наш A/B тест и зафиксировать победу группы B.
Итого выбираем вариант 1.
