# Техническое задание  
Дана строка text, и шаблон template. Длина строки text намного превосходит длину строки template. Найти все вхождение строки template в строку text при помощи алгоритма Бойера-Мура, пользуясь эвристикой "плохого символа" и эвристикой "хорошего суффикса".

# Вывод программы  
Поиск "князь": 75 ms  
Поиск "князь Андрей": 36 ms  
Поиск "князь Андрей Болконский": 7 ms 

# Осмысление    
получилось так, что чем длиннее строка тем быстрее она ищется. Это обуславливается тем, что при несовпадении символа строки и шаблона более длинную строку можно передвинуть на большую длинну, чем меньшую, а следовательно, дойти до конца текста быстрее.
