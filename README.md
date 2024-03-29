# Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости
## Описание проекта <br>
В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. 
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

## Цель
Нужно научиться определять рыночную стоимость объектов недвижимости. Наша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.


## Инструменты
`предобработка данных`
`Python`
`Pandas`
`Matplotlib`
`numpy`
`исследовательский анализ данных`
` визуализация данных`


## Краткое описание проделанной работы
<i>На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость
объектов недвижимости разного типа, типичные параметры квартир, в зависимости от
удаленности от центра. Проведена предобработка данных. Добавлены новые данные.
Построены гистограммы, боксплоты, диаграммы рассеивания. </i>

## Вывод
<i> 
Типичный объект недвижимости будет выглядеть так:

- 1 или 2 комнаты
- дом 5-ти или 9-ти этажный
- объект преимущеннство распологается с 1 по 4 этаж
- общая площадь около 50 квадратных метров
- площадь кухни около 5 квадратных метров
- высота потолков от 2.5 до 2.8 метров
- стоимость около 3.5 миллионов
- расположение на расстоянии от центра в 13-15 км
- расположение от аэропорта на расстоянии в 15-25 километров
- расположение до парка около 200-600 метров

  
Также выяснили, что:

- быстрые продажи - до 45 дней
- нормальные продажи - от 45 до 248 дней
- долгие продажи - от 248 до 552 дней
- выбросы - все, что выше 552 дней
- чаще всего квартиры продаются где-то за 45 и 60 дней
- На общую (полную) стоимость объекта больше всего влияет общая площадь квартиры, жилая площадь и этаж расположения квартиры.
- Чем больше площадь, тем выше стоимость.
- Квартиры на первом этаже дешевле.
- Зависимоть между датой размещения объявления по дням, месяцам и стоимостью квартир практически отсутствует. А вот по годам можно сказать, что в 2014 году стоимость продажи была выше.
- Наибольшая средняя цена за 1 квадратный метр в Санкт-Петербурге, что довольно логично - ведь это административный центр. Следом по стоимости идет город Пушкин, что тоже оправдано - много исторических мест, многие объекты недвижимости имеют культурную ценность, много парков и расположение к городу довольно близкое. Наименьшая стоимость за квадратный метр в Всеволожске.
</i>


