Ссылка на просмотр проекта через nbviewer: [Событийная аналитика - анализ поведения пользователей](https://nbviewer.org/github/mariasaveleva/study-projects/blob/d9f1673fc01718e255703c2ca3d8e7fa23063a27/project%20event%20analytics/Событийная%20аналитика%20%28анализ%20AAB-эксперимента%29.ipynb)

##
### Описание
В компании-стартапе, которая продаёт продукты питания, нужно разобраться, как ведут себя пользователи мобильного приложения. Для этого нужно было изучить воронку продаж. Узнать, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах и на каких именно. После этого исследовать результаты A/A/B-эксперимента.

### Данные
Каждая запись в логе — это действие пользователя, или событие. 
- EventName — название события
- DeviceIDHash — уникальный идентификатор пользователя
- EventTimestamp — время события
- ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная

### Инструменты и основные навыки
*Python (Pandas, Matplotlib, Seaborn, Plotly, NumPy, SciPy, Math), продуктовые метрики, событийная аналитика, A/B-тестирование, проверка статистических гипотез*
