# SamobotHeart
Программа для Arduino и железо для робота

![Иллюстрация к проекту](https://github.com/vindozo/SamobotHeart/blob/master/samobot.jpg)


Сердце робота - силовой модуль управляемый Arduino Leonardo, собраный на макетной плате размерами 90x70 мм.

![схема](https://github.com/vindozo/SamobotHeart/blob/master/schema2_1.png)

ВЫВОДЫ:

1. Оказалось что мой старый смартфон не может работать с OTG USB. 
Пришлось использовать bluetooth модуль для связи, это дешевле чем покупать новый смартфон.
Схема и программа может работать в двух режимах связи.

2. Замеренная автономность с Б/У автомобильным аккамулятором составила более суток.
Аккумулятор разрядился до 9,5V за 26 часов при холостом ходе, робот просто стоял без движения. 
Добавил вольтметр в ардуино, чтобы следить за зарядом дистанционно.

3. При напряжении 7V на маршевом двигателе с автомобильной аккамуляторной батареей робот практически не едет, его вес становится около 20 кг.
С легкой литиевой перемещается уверенно, но ее хватает не на долго. Замена привода потребует пересмотра всей схемы.
