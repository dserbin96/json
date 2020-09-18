# Фрагменты, экранная ориентация
Для данной лабороторной работы нужно занть Fragmet, FragmentManager разные ориентации экранов
В данной лабораторной работе необходимо создать два фрагмента и два активити. В первой активити при альбомной ориетации содержаться два 
фрагмента при взаимодействии с первым меняется значение второго. В портретной ориентации в первом активити содержиться один фрагмент при 
взаимодействии с элементами котрого открывается второй с определенными значениями.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1Pgeq6eI8hEckWU8lhrylEWOWN2KPDz-e"/>
 </p>

1) В первом варианте нужно создать два фрагмента. В первом список с изображениями, во втором само изображение.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1qw08nH7MDr4nlQc0xdcDboKO_2QpMGli"/>
 </p>

2) Во втором варианте нужно создать один фргмент с алфавитом, второй с выбранной буквой из первого

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1oQFEhTv9OLPOvT9Ys6OrLsV1yKWctBXU"/>
 </p>
 
 3) В третьем варианте нужно сделать один фрагмент с цифрами, второй с выбранной цифрой из первой
 
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1A4eUm8ee8Q2CMo-aop_6xH_KLenmMFpK"/>
 </p>
 
 4) В четвертом варианте нужно сделать один фрагмент с цифрами, второй с суммой из выбранных
 
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1qeJ8CAohI3g4Z7M_LazfkFlW_iPcgGpq"/>
 </p>

5) В пятом варианте нужно сделать один фрагмент с цифрами, второй фрагмент с рисоединенным элементом к слову

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1bg42-qyeu33TV6E8KUEKTUDU-IhIKQph"/>
 </p>

# SQL
В данной лабороторной работе происходит подключение к базе данных и вывод результата на экран.
Первый экран с вводом данных таблицы, второй с выведенными данными.
В некоторых лабораторных работах нужно использовать Spinner(для выподающего списка) и кнопки переключения RagioButton
http://developer.alexanderklimov.ru/android/views/spinner.php

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1AC7oDQyx2OJ_Bo6xoKVqOiem9I0EeSR0"/>
 </p>

1) База данных абитуриента

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1bkjE0S0gAxrMh5ppENpCJUVKZJkkMU0_"/>
 </p>

2) База данных преподавателей

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1Fm68TGzukoPN2IiqjxvGPkfFrvinwnQs"/>
 </p>
 
 3) База данных пациентов

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1thlW8YHuWIEnAaA4hQUzBmyEjbAzMIGR"/>
 </p>
 
 4) База данных презывников

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1n9gKxr3oxkSHR36aH9iiseD1qHB9ruuz"/>
 </p>
 
 5) База данных студентов

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=17z5Or_13s_fE2a1DD6QilkKntsIw8fmI"/>
 </p>
 
# Network, подключение зависимостей, JSON
В данной лабораторной работе происходят запросы в сеть и приходят данные в формате JSON. Необходимо рапарсить данные и показать на экране данные. Также для работы нужно добавить некотрые зависимости в Gradle для закачки сторонней библиотеки.
Для начало нужно подключить в зависимости библиотеки
https://developer.android.com/guide/topics/ui/layout/recyclerview (для работы со списком)
http://developer.alexanderklimov.ru/android/library/glide.php (для загрузки картинки)
https://developer.android.com/training/volley/ (для запросов в сеть)
так же нужно добавить в манифест разрешение на запрос в сеть
<uses-permission android:name="android.permission.INTERNET" />

 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1J8EykjvHd2mdOofT-AyzhygDaIp4J6Bh"/>
 </p>

К каждой лабораторной работе представлен свой url к которому нужно произвести запрос и распарсить.
Для отображения изображений можно работать с Glide, а для работы со списком нужно использовать RecyclerView

1) https://my-json-server.typicode.com/dserbin96/json/object распарсить university
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1O9b_2SjWO60T66qI95Jf-SdT2pgeqPvx"/>
 </p>

2) https://my-json-server.typicode.com/dserbin96/json/object распарсить arboretum
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1TuNrnVnWgs2LgOXWJmadxhktgQ9gjo-K"/>
 </p>

3) https://my-json-server.typicode.com/dserbin96/json/object распарсить department
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1zOF_76IrzCifYQDNsK0BN45XrwBUUyNT"/>
 </p>

4) https://my-json-server.typicode.com/dserbin96/json/corpus
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1CM76M1dYVz8KrXmyFJn9goESyKlJ1V2O"/>
 </p>

5) https://my-json-server.typicode.com/dserbin96/json/users
 <p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1x-IFKKLYrhpR2kFd_W2mj2LqKohNT6bQ"/>
 </p>
