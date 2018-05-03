Докато слончетата са на плаж, им става много скучно. Особено когато родителите им не им разрешават да влизат във водата. За да убият скуката, те измислили следната игра: Слончето Лони си намисля едно цяло положително число. След това всяко едно от останалите слончета също си намисля число. Всяко слонче печели за числото си толкова точки колкото общи делители има неговото число с числото на Лони. В делителите не се брои единицата, но самото число може да донесе точка на слончето, ако е делител на числото на Лони и обратно: слончето ще получи точка, ако числото на Лони е делител на неготово число.
Играта била забавна, но слончетата не обичат да смятат, още по-малко да делят. Напишете програма game, която по дадено число, намислено от Лони и числата на останалите слончета, определя победителите в играта.

# Вход
На първия ред на стандартния вход се въвеждат две цели числа n – броя на слончетата и k – намисленото от Лони число, На втория ред се въвеждат n цели числа – числата, намислени от слончетата.

# Изход
На първия ред на стандартния изход се извежда едно цяло число – броя на точките на победителите в играта.
На втория ред се извеждат във възходящ ред, отделени с интервали, номерата на всички победители в играта. Ако нито едно слонче не е намислило число, което има общи делители с числото, намислено от Лони, програмата извежда текста: „No winners”.

# Ограничения
1 ≤ n ≤ 1000; 2 ≤ числата, намислени от слончетата ≤ 1000.

 
# Примерни тестове

## Вход 
```
4 18 
6 15 54 36
```

## Изход
```
5
3 4
```

## Вход
```
3 12 
2 3 24
```

## Изход
```
5
3
```

## Вход
```
4 28 
11 9 17 13
```

## Изход
```
No winners
```