README
--------------------
Шаблон для використання:
```
$ python2.7 edge-detection.py -m <sobel|kirsch|prewitt|blur> -i <image>
```
Приклад:

```
$ python2.7 edge-detection.py -m kirsch -i ~/Downloads/test.jpg
```

Завуження:

Перевіряв тільки на Python версії 2.7. Відкриваютсья тільки файли з розширенням .jpg. В результаті отримуємо картинку, що зберігається в каталозі tmp и відкривається вашим додатком для перегляду зображень. 

##### Original
![alt tag](http://imgur.com/IGedcAe.jpg)

##### Prewitt Mask
![alt tag](http://i.imgur.com/x0PexRu.jpg)

##### Sobel Mask
![alt tag](http://imgur.com/AeGiw40.jpg)

##### Kirsch
![alt tag](http://imgur.com/Pg106sC.jpg)



