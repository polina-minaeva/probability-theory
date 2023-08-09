# probability-theory
Задание на тему: "Теория вероятностей". 

Номер 1. В магазин привезли устройства с 3-х разных предприятий. Соотношение устройств следующее: 20% - продукция первого предприятия, 30% - продукция второго предприятия, 50% - продукция третьего предприятия; далее, 10% продукции первого предприятия высшего сорта, на втором предприятии - 5% и на третьем - 20% продукции высшего сорта. Найти вероятность того, что случайно купленная новая продукция окажется высшего сорта.

Решение. 

1. Нашла вероятность покупки продукции высшего сорта на 1 предприятии, умножив долю продукции 1 предприятия на долю продукции высшего сорта на этом предприятии.

2. Аналогичные действия по 2 предприятию и 3 предприятию.
   
3. Нашла вероятность покупки продукции высшего сорта среди продукции всех предприятий, сложив вероятность покупки продукции высшего сорта на 1 предприятии, вероятность покупки продукции высшего сорта на 2 предприятии, вероятность покупки продукции высшего сорта на 3 предприятии

Номер 2. Пусть брошены 3 уравновешенные монеты. Рассмотреть 3 события:
A1 - монеты 1 и 2 упали одной и той же стороной;
A2 - монеты 2 и 3 упали одной и той же стороной;
A3 - монеты 1 и 3 упали одной и той же стороной.
Показать, почему эти 3 события (A1, A2, A3) являются попарно независимыми, но не являются независимыми в совокупности.

Решение. 

События А1, А2 и А3 не являются независимыми в совокупности, потому что исход одного события влияет на исход другого. Например, если монеты 1 и 2 упали одной и той же стороной (событие А1) и при этом они обе упали решкой вверх, то события А2 уже не произойдет, если, например, считать, что монета 3 упала орлом вверх (монета 2 при этом падает решкой вверх).
При этом сами по себе три события, если их рассматривать по отдельности, никак не зависят друг от друга. Может произойти и А1, и А2, и А3 с одинаковой вероятностью 1/2. Подробнее, на примере события А1: вероятность, что монета 1 упала решкой вверх или орлом вверх – 1/2 и 1/2 соотвественно. Монета 2 упала решкой вверх или орлом вверх – также 1/2 и 1/2. Монеты 1 и 2 упали одной и той же стороной – 2/4, или 1/2.
