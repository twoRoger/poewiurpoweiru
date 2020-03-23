# Инструкция по добавлению карты распространения коронавируса

Чтобы добавить карту распространения коронавируса к себе на сайт необходимо в html код страницы добавить тег:

```html
<iframe src="https://yandex.ru/maps/covid19?embed=covid-map" width="800px" height="500px"></iframe>
```

Если хочется добавить карту вместе с панелью со сводными данными по России, параметр `embed=covid-map` нужно заменить на `embed=covid`:

```html
<iframe src="https://yandex.ru/maps/covid19?embed=covid" width="800px" height="500px"></iframe>
```
