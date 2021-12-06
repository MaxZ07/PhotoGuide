```
sequenceDiagram
    Пользователь ->> Приложение: Запуск приложения
    Приложение ->> БД: Запрос на места, находящиеся в определенном радиусе от пользователя
    БД ->> Приложение: Возвращает данные о местах
    Приложение ->> Приложение: Отображение мест на карте
    Пользователь ->> Приложение: Выбор одной из множества отметок на карте
    Приложение ->> БД: Запрос на фотографии, связанные с этим местом
    БД ->> Приложение: Возвращает данные о фотографиях
    Приложение ->> Приложение: Отображение фотографий в выбранном месте
    Пользователь ->> Приложение: Выбор одной из множества фотографий
    Приложение ->> БД: Запрос на комментарии, связанные с этой фотографией
    БД ->> Приложение: Возвращает данные о комментариях
    Приложение ->> Приложение: Отображение фотографии и соответствующих комментарий
```

[![](https://mermaid.ink/img/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAg0J_QvtC70YzQt9C-0LLQsNGC0LXQu9GMIC0-PiDQn9GA0LjQu9C-0LbQtdC90LjQtTog0JfQsNC_0YPRgdC6INC_0YDQuNC70L7QttC10L3QuNGPXG4gICAg0J_RgNC40LvQvtC20LXQvdC40LUgLT4-INCR0JQ6INCX0LDQv9GA0L7RgSDQvdCwINC80LXRgdGC0LAsINC90LDRhdC-0LTRj9GJ0LjQtdGB0Y8g0LIg0L7Qv9GA0LXQtNC10LvQtdC90L3QvtC8INGA0LDQtNC40YPRgdC1INC-0YIg0L_QvtC70YzQt9C-0LLQsNGC0LXQu9GPXG4gICAg0JHQlCAtPj4g0J_RgNC40LvQvtC20LXQvdC40LU6INCS0L7Qt9Cy0YDQsNGJ0LDQtdGCINC00LDQvdC90YvQtSDQviDQvNC10YHRgtCw0YVcbiAgICDQn9GA0LjQu9C-0LbQtdC90LjQtSAtPj4g0J_RgNC40LvQvtC20LXQvdC40LU6INCe0YLQvtCx0YDQsNC20LXQvdC40LUg0LzQtdGB0YIg0L3QsCDQutCw0YDRgtC1XG4gICAg0J_QvtC70YzQt9C-0LLQsNGC0LXQu9GMIC0-PiDQn9GA0LjQu9C-0LbQtdC90LjQtTog0JLRi9Cx0L7RgCDQvtC00L3QvtC5INC40Lcg0LzQvdC-0LbQtdGB0YLQstCwINC-0YLQvNC10YLQvtC6INC90LAg0LrQsNGA0YLQtVxuICAgINCf0YDQuNC70L7QttC10L3QuNC1IC0-PiDQkdCUOiDQl9Cw0L_RgNC-0YEg0L3QsCDRhNC-0YLQvtCz0YDQsNGE0LjQuCwg0YHQstGP0LfQsNC90L3Ri9C1INGBINGN0YLQuNC8INC80LXRgdGC0L7QvFxuICAgINCR0JQgLT4-INCf0YDQuNC70L7QttC10L3QuNC1OiDQktC-0LfQstGA0LDRidCw0LXRgiDQtNCw0L3QvdGL0LUg0L4g0YTQvtGC0L7Qs9GA0LDRhNC40Y_RhVxuICAgINCf0YDQuNC70L7QttC10L3QuNC1IC0-PiDQn9GA0LjQu9C-0LbQtdC90LjQtTog0J7RgtC-0LHRgNCw0LbQtdC90LjQtSDRhNC-0YLQvtCz0YDQsNGE0LjQuSDQsiDQstGL0LHRgNCw0L3QvdC-0Lwg0LzQtdGB0YLQtVxuICAgINCf0L7Qu9GM0LfQvtCy0LDRgtC10LvRjCAtPj4g0J_RgNC40LvQvtC20LXQvdC40LU6INCS0YvQsdC-0YAg0L7QtNC90L7QuSDQuNC3INC80L3QvtC20LXRgdGC0LLQsCDRhNC-0YLQvtCz0YDQsNGE0LjQuVxuICAgINCf0YDQuNC70L7QttC10L3QuNC1IC0-PiDQkdCUOiDQl9Cw0L_RgNC-0YEg0L3QsCDQutC-0LzQvNC10L3RgtCw0YDQuNC4LCDRgdCy0Y_Qt9Cw0L3QvdGL0LUg0YEg0Y3RgtC-0Lkg0YTQvtGC0L7Qs9GA0LDRhNC40LXQuVxuICAgINCR0JQgLT4-INCf0YDQuNC70L7QttC10L3QuNC1OiDQktC-0LfQstGA0LDRidCw0LXRgiDQtNCw0L3QvdGL0LUg0L4g0LrQvtC80LzQtdC90YLQsNGA0LjRj9GFXG4gICAg0J_RgNC40LvQvtC20LXQvdC40LUgLT4-INCf0YDQuNC70L7QttC10L3QuNC1OiDQntGC0L7QsdGA0LDQttC10L3QuNC1INGE0L7RgtC-0LPRgNCw0YTQuNC4INC4INGB0L7QvtGC0LLQtdGC0YHRgtCy0YPRjtGJ0LjRhSDQutC-0LzQvNC10L3RgtCw0YDQuNC5IiwibWVybWFpZCI6eyJ0aGVtZSI6ImRhcmsifSwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/edit#eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAg0J_QvtC70YzQt9C-0LLQsNGC0LXQu9GMIC0-PiDQn9GA0LjQu9C-0LbQtdC90LjQtTog0JfQsNC_0YPRgdC6INC_0YDQuNC70L7QttC10L3QuNGPXG4gICAg0J_RgNC40LvQvtC20LXQvdC40LUgLT4-INCR0JQ6INCX0LDQv9GA0L7RgSDQvdCwINC80LXRgdGC0LAsINC90LDRhdC-0LTRj9GJ0LjQtdGB0Y8g0LIg0L7Qv9GA0LXQtNC10LvQtdC90L3QvtC8INGA0LDQtNC40YPRgdC1INC-0YIg0L_QvtC70YzQt9C-0LLQsNGC0LXQu9GPXG4gICAg0JHQlCAtPj4g0J_RgNC40LvQvtC20LXQvdC40LU6INCS0L7Qt9Cy0YDQsNGJ0LDQtdGCINC00LDQvdC90YvQtSDQviDQvNC10YHRgtCw0YVcbiAgICDQn9GA0LjQu9C-0LbQtdC90LjQtSAtPj4g0J_RgNC40LvQvtC20LXQvdC40LU6INCe0YLQvtCx0YDQsNC20LXQvdC40LUg0LzQtdGB0YIg0L3QsCDQutCw0YDRgtC1XG4gICAg0J_QvtC70YzQt9C-0LLQsNGC0LXQu9GMIC0-PiDQn9GA0LjQu9C-0LbQtdC90LjQtTog0JLRi9Cx0L7RgCDQvtC00L3QvtC5INC40Lcg0LzQvdC-0LbQtdGB0YLQstCwINC-0YLQvNC10YLQvtC6INC90LAg0LrQsNGA0YLQtVxuICAgINCf0YDQuNC70L7QttC10L3QuNC1IC0-PiDQkdCUOiDQl9Cw0L_RgNC-0YEg0L3QsCDRhNC-0YLQvtCz0YDQsNGE0LjQuCwg0YHQstGP0LfQsNC90L3Ri9C1INGBINGN0YLQuNC8INC80LXRgdGC0L7QvFxuICAgINCR0JQgLT4-INCf0YDQuNC70L7QttC10L3QuNC1OiDQktC-0LfQstGA0LDRidCw0LXRgiDQtNCw0L3QvdGL0LUg0L4g0YTQvtGC0L7Qs9GA0LDRhNC40Y_RhVxuICAgINCf0YDQuNC70L7QttC10L3QuNC1IC0-PiDQn9GA0LjQu9C-0LbQtdC90LjQtTog0J7RgtC-0LHRgNCw0LbQtdC90LjQtSDRhNC-0YLQvtCz0YDQsNGE0LjQuSDQsiDQstGL0LHRgNCw0L3QvdC-0Lwg0LzQtdGB0YLQtVxuICAgINCf0L7Qu9GM0LfQvtCy0LDRgtC10LvRjCAtPj4g0J_RgNC40LvQvtC20LXQvdC40LU6INCS0YvQsdC-0YAg0L7QtNC90L7QuSDQuNC3INC80L3QvtC20LXRgdGC0LLQsCDRhNC-0YLQvtCz0YDQsNGE0LjQuVxuICAgINCf0YDQuNC70L7QttC10L3QuNC1IC0-PiDQkdCUOiDQl9Cw0L_RgNC-0YEg0L3QsCDQutC-0LzQvNC10L3RgtCw0YDQuNC4LCDRgdCy0Y_Qt9Cw0L3QvdGL0LUg0YEg0Y3RgtC-0Lkg0YTQvtGC0L7Qs9GA0LDRhNC40LXQuVxuICAgINCR0JQgLT4-INCf0YDQuNC70L7QttC10L3QuNC1OiDQktC-0LfQstGA0LDRidCw0LXRgiDQtNCw0L3QvdGL0LUg0L4g0LrQvtC80LzQtdC90YLQsNGA0LjRj9GFXG4gICAg0J_RgNC40LvQvtC20LXQvdC40LUgLT4-INCf0YDQuNC70L7QttC10L3QuNC1OiDQntGC0L7QsdGA0LDQttC10L3QuNC1INGE0L7RgtC-0LPRgNCw0YTQuNC4INC4INGB0L7QvtGC0LLQtdGC0YHRgtCy0YPRjtGJ0LjRhSDQutC-0LzQvNC10L3RgtCw0YDQuNC5IiwibWVybWFpZCI6IntcbiAgXCJ0aGVtZVwiOiBcImRhcmtcIlxufSIsInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)

# Предусловия
* Пользователь должен быть зарегистрирован и авторизован

# Постусловия
* Фотографии, их координаты и комментарии к ним отображены
* Фотографии, их координаты и комментарии к ним сохранены

# Сценарий
* Пользователь запускает приложение
* Приложение отправляет запрос к БД о местах, находящихся в определенном радиусе от пользователя
* БД возвращает данные о местах
* Приложение отображает места на карте
* Пользователь выбирает одну из множества отметок на карте
* Приложение отправялет запрос к БД о фотографиях, связанных с этим местом
* БД возвращает данные о фотографиях
* Приложение отображает фотографии в выбранном месте
* Пользователь выбирает одну из множества фотографий
* Приложение отправляет запрос к БД о комментариях, связанных с этой фотографией
* БД возвращает данные о комментариях
* Приложение отображает фотографию и соответствующие комментарии