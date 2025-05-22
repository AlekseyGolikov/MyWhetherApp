# <p align="center">MyWhetherApp  

  

### Описание
Простое приложение выводит актуальную температуру наружного воздуха
в любом городе по выбору пользователя. Значение температуры подгружается с сервиса 
api.openweathermap.org

[https://api.openweathermap.org/data/2.5/weather?q=__city__&APPID=__key__&units=metric&lang=ru](https://api.openweathermap.org/data/2.5/weather?q=__city__&APPID=__key__&units=metric&lang=ru)


### Описание алгоритма

В окне приложения размещены объект EditView для ввода названия города, объект TextView для вывода значения температуры, полученной с удалённого сервиса, и объект Button - кнопка.
Обмен данными происходит с применением класса AsyncTask.  

---

![Pic](/img/pic1.jpg "Стартовая")
-
![Pic](/img/pic2.jpg "После ввода \"Moscow\"")