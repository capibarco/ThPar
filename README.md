﻿Отчет о проделанной работе
Федоров Дмитрий 21931

|Имя|<p>double.c</p><p>d</p>|<p>float.c</p><p></p><p>f</p>|<p>coredouble.c</p><p></p><p>cord</p>|<p>corefloat.c</p><p></p><p>corf</p>|<p>coredouble.c</p><p></p><p>mcord</p>|<p>corefloat.c</p><p></p><p>mcorf</p>|
| :- | :- | :- | :- | :- | :- | :- |
|компилятор|pgcc|pgcc|pgcc|pgcc|pgcc|Pgcc|
|Суммарное время выполнения циклов|<p>210us</p><p>108.42us – суммирование</p><p>102.08us – вычисление массива</p>|<p>154us</p><p>84.896us –</p><p>суммирование</p><p>68.447us – вычисление массива</p>|0.08s|0.08s|0.08s|0.08s|
|Общее время работы программ|3.081767s|3.067938s|0.262008s|0.229349s|0.222153s|0.216680s|
|<p>Точность расчетов</p><p>- разлчие от верной суммы</p>|0|-0.000129|0|-0.213894|0|-0.213894|

Вычисления на видеокарте происходят быстрее, но долго происходит трансфер информации межу памятью, возможно можно ускорить. Я бы хотел доработать, но зашел в тупик и не знаю как

Code gpu: 



Code cpu:
