# hscp-dist
Товарищи, если вдруг еще кто-то не писал курсач на SCP (ottorabago, привет), этот пост может вам помочь (а может и не помочь). <br />
Если вы уже читали методичку по SCP, то могли заметить определенную многословность языка (5 строк для того, чтобы запринтить строчку - это еще норм). <br />
Как следствие, большое количество кода - приводит к большой вероятности опечатки (про которые, как правило, OSTIS, заботливо не сообщает), да и дебажить такой код не просто.<br />
Для выхода из такой ситуации, ваш скромный слуга, написал транслятор с значительно более высокоуровневого языка (HSCP) в SCP. <br />
Таким образом, вы можете писать код на приятном и относительно удобном языке, а затем транслировать его в SCP. <br />
В качестве, хоть какой-то гарантии надежности, могу сказать, что на этом языке я написал курсач.<br />
На данный момент примерный уровень "расжатия" из HSCP в SCP составляет 1:8 (относительно моего курсача, цифры такие: 103 строки HSCP транслируются в 824 строки на SCP (кстати, на C++, курсач занял около 300 строк). <br />
(Впрочем, рейт варьировался от 1:5 до 1:8)<br />
Прикрепляю бинарник транслятора для Linux (если нужен для Windows, напишите - скомпилирую), пример (мой курсач - нахождение графа конденсации для орграфа) команду для запуска. <br />
Мануал тут же. <br />
Возможно он недостаточно подробный. <br />
 **Дисклеймер**: Eсли вы решили писать курсач на HSCP (спасибо за это), но нерасчитали время и не успели ничего сделать (ottorabago, привет),
по причине проблем с HSCP или любых других проблем - я не виноват. 
<br />(На самом деле, транслятор протестирован в разных условиях, и работает штатно (вроде бы), но всякое бывает)<br />
**P.S.** Пример DFS'а можно посмотреть прямо в мануале (в конце). Мануал кстати небольшой: всего 5 страниц. <br />
**P.S.2.** ДИРЕКТОРИЯ СБОРКИ ОЧИЩАЕТСЯ ПЕРЕД СБОРКОЙ, ОСТОРОЖНО!<br />
**P.S.3.** Настоятельно рекомендую прочитать методичку по SCP (как минимум, основные концепции), прежде чем пытаться писать на HSCP.<br />
