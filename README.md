# Цели
В этом проекте разбираются доверительные интервалы, А/Б-тест и корреляционный анализ. В проекте поставлена задача - улучшить работу пиццерии. Нам известны [данные о заказах пиццы](datasets/pizza.csv)

## Доверительные интервалы и A/B- тестирование

### Выполнен начальный анализ данных:

* Построена гистограмма зависимости количества проданной пиццы от дня 
недели.
* Высчитано время приготовления каждой пиццы.
* Построен 95% доверительный интервал для среднего времени приготовления пиццы.
* Найдена пицца, у которой верхняя граница доверительного интервала её изготовления самая высокая(среди пицц, у которых за все время заказывали более 100 штук)
* Найдена пицца с самым широким доверительным интервалом(среди пицц, у которых за все время заказывали более 100 штук)

### Проведено АВ тестирование

Предстояло выяснить, какая реклама больше всего нравится покупателю. Была собрана [статистика](datasets/click.csv), (баннер a - старый баннер, баннер b - новый) для которой предстоит сделать анализ. 

В качестве нулевой гипотезы (H0) выбрано суждение о том, что старый баннер лучше нового.  
В качестве альтернативной гипотезы (H1) выбрано суждение о том, что новый баннер лучше старого. 

* Построен 95% доверительный интервал для доли каждого из баннеров.
* Построен 95% доверительный интервал для разности двух долей.
* Проведен АБ-тест.

## Корреляционный анализ

### В данной части разбираются корреляции Пирсона и Спирмена, их значение и исследование устойчивости к выбросам 

* По сгенерированным выборкам посчитаны коррелиции Пирсона и Спирмена для заданных функций. Дано объяснение полученных результатов.
* Построено облако из точек, выведены значения коэффициентов корреляции и созданы выбросы для проверки устойчивости корреляций к выбросам.
* Перемещения точек выведены на графике.
* Сделан вывод о том, какая корреляция больше устойчива к выбросам.

