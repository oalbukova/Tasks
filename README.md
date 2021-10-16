# Mercaux
## тестовое задание для Mercaux
 ## [Ссылка на готовый проект](https://oalbukova.github.io/Mercaux/)
> Все страницы являются адаптивными и кроссбраузерными
### Задание № 1
##### Дано:
> 6 логотипов.
##### Условия:
> использовать только CSS (less/sass)
##### Цели:
> * Сверстать блок, в котором 6 логотипов выстроены в ряд с равным расстоянием друг от друга (но крайние элементы приклеены к границам блока) и отцентрированы по горизонтали
> * При разрешении менее 700 пикселей логотипы выстраиваются в 2 строки по 3 элемента
> * При разрешении менее 600 пикселей – 3 строки по 2 элемента
> * При разрешении менее 400 пикселей – 6 строк по одному элементу



### Задание № 2
##### Дано:
> 4 блока, которые идут друг за другом по вертикали. В каждом из блоков содержится картинка и текст. В четных блоках картинка слева, текст справа. В нечетных блоках – наоборот, текст слева, а картинка справа. Картинка занимает всю высоту блока (400 пикселей). Текст отцентрирован по вертикали блока (не зависит от количества текста)
##### Условия:
> использовать CSS FLEX
##### Цели:
> При разрешении менее 600 пикселей верстка выстраивается в вертикальную последовательность картинка, затем текст (не зависимо от четности блока)


### Задание № 3
##### Цели
> Выполнить задание 2 без использования CSS FLEX

### Задание № 4
##### Дано:
> 4 блока (изображение + наложенный текст)
##### Условия:
> использовать CSS, Pure JS, адаптив
##### Цели:
> Сделать примитивное слайдшоу из заданных блоков. Автоматическое переключение раз в 2 секунды, по нажатию на блок – переключение на следующий слайд
##### Дополнительно реализовано:
> * поддержка перелистывания слайдов смахиванием (touch swipe) для устройств с сенсорным экраном и перетаскиванием мышью  – разрешает листать слайды свайпом и перемещением курсора мыши при зажатой левой кнопки мыши;
> * осуществлена остановка автоматической смены слайдов при поднесении к нему курсора

### Задание № 5
##### Дано:
> хэдер, в котором слева логотип (можно взять любой из файлов задания 1), а справа 2 главных элемента меню, в одном из них – 3 подэлемента
##### Условия:
> использовать CSS, Pure JS, для анимаций только CSS
##### Цели
> * Сделать приклеенный хэдер, в самом верхнем положении высота 50 пикселей, цвет фона белый, цвет текста черный. При скролле с самого верхнего положения страницы – высота хэдера становится 30 пикселей (с анимацией), логотип становится меньше, цвет фона черный, цвет текста белый
> * Сделать дропдаун меню в хэдере - верхний элемент составного пункта не кликабелен, элементы подменю кликабельны. Раскрытие по наведению, в мобильной верстке – по нажатию


### Задание № 6
##### Дано:
> футер
##### Условие:
> использовать CSS, адаптив
##### Цели:
> Приклеить футер к низу страницы


### Задание № 7
##### Дано:
> несколько блоков с якорями, верхнее меню
##### Условие:
> использовать CSS, Pure JS
##### Цели:
> По нажатию на ссылку в верхнем меню скроллить с анимацией страницу до соответствующего якоря


### Задание № 8
##### Дано:
> страница контактов компании
##### Условие:
> использовать CSS, Pure JS
##### Цели:
> вставить google карту, шириной во всю страницу, высотой 400 пикселей с пином на адрес компании: Москва, Столярный Переулок 3к13


### Задание № 9
##### Дано:
> блок, высотой 400 пикселей, шириной во весь экран. Картинка для фона.
##### Условие:
> использовать CSS
##### Цели:
> Внутри блока прописать картинку фоном, при адаптивной верстке чтобы изображение приклеивалось к левому краю (всегда виден монитор)


### Задание № 10
##### Дано:
> логотип, вставленный в блок через тег <img>
##### Условие:
> использовать CSS
##### Цели:
> Сделать логотип цвета #00b19d, не меняя исходное изображение, не добавляя background и новых изображений поверх него с помощью <img> или псевдоэлементов

### Задание № 11

##### Дано:
> скриншоты с экрана iPad, видео
##### Условие:
> использовать библиотеку anime.js
##### Цели:
> Запрограммировать анимацию, схожую с тем, что на видео (можно упростить элементы типа «тач по экрану»), используя библиотеку для анимаций и статические изображения



### Задание № 12
##### Дано:
> блок с формой, содержащей 3 элемента Input и кнопку
##### Условие:
> использовать CSS, Pure JS
##### Цели:
> * Сделать из блока диалоговое окно, которое открывается с произвольного элемента <a/> на странице и закрывается по крестику на попапе. Использовать перекрывающий оверлэй
> * Сделать проверку данных в форме при нажатии кнопки “отправить”: 1 поле проверяется на email формат, второе поле на текст с минимальной длиной 3 символа. Если проверка не пройдена – подсветить красным Input с ошибкой. Если ошибок нет – закрыть форму и написать на странице «успех»


