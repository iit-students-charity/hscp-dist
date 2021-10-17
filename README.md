# hscp-dist
Товарищи, если вдруг еще кто-то не писал курсач на SCP (ottorabago, привет), этот пост может вам помочь (а может и не помочь). 
Если вы уже читали методичку по SCP, то могли заметить определенную многословность языка (5 строк для того, чтобы запринтить строчку - это еще норм). 
Как следствие, большое количество кода - приводит к большой вероятности опечатки (про которые, как правило, OSTIS, заботливо не сообщает), да и дебажить такой код не просто.
Для выхода из такой ситуации, ваш скромный слуга, написал транслятор с значительно более высокоуровневого языка (HSCP) в SCP. 
Таким образом, вы можете писать код на приятном и относительно удобном языке, а затем транслировать его в SCP. 
В качестве, хоть какой-то гарантии надежности, могу сказать, что на этом языке я написал курсач.
На данный момент примерный уровень "расжатия" из HSCP в SCP составляет 1:8 (относительно моего курсача, цифры такие: 103 строки HSCP транслируются в 824 строки на SCP (кстати, на C++, курсач занял около 300 строк)). 
(Впрочем, рейт варьировался от 1:5 до 1:8)
Прикрепляю бинарник транслятора для Linux (если нужен для Windows, напишите - скомпилирую), пример (мой курсач - нахождение графа конденсации для орграфа) команду для запуска. 
Мануал тут же. 
Возможно он недостаточно подробный. Если что-то непонятно - пишите мне. Если есть какие-то проблемы - пишите мне. 
Если проблем нет - тоже пишите.
Дисклеймер: как и любое ПО, транслятор может содержать баги (Нашли? Пишите). 
Если что, я - не виноват. Также, если вы решили писать курсач на HSCP (спасибо за это), но нерасчитали время и не успели ничего сделать (ottorabago, привет), по причине проблем с HSCP или любых других проблем - я не виноват. (На самом деле, транслятор протестирован в разных условиях, и работает штатно (вроде бы), но всякое бывает)
