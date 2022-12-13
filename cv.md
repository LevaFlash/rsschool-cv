# CV - Лев Флейшман
![](https://github.com/LevaFlash/rsschool-cv/blob/gh-pages/GITAVA.jpg)
## Контакты:
Почта: levaflash@mail.ru \
Телеграм: @levaflash
## О себе:
### Моя цель: 
Быть одним из создателей современных, крутых и полезных проектов, одновременно зарабатывая этим себе на жизнь. В приоритете делать более интересные вещи и получать меньше денег, нежели делать более скучные, и получать больше денег.
### Сильные стороны: 
1. Умение искать и обрабатывать новую информацию
2. Общение с людьми не составляет проблемы
3. Усидчивость
4. Креативность
## Навыки и опыт работы в it:
На данный момент таковых не имею, я только начал учиться. Слегка освоил Git и научился решать задачи 8 kyu на CodeWars
## Примеры кода:
*Задача:* Square Every Digit.


*Условие задачи:*


Welcome. In this kata, you are asked to square every digit of a number and concatenate them.\
For example, if we run 9119 through the function, 811181 will come out, because 92 is 81 and 12 is 1.\
Note: The function accepts an integer and returns an integer.

```
function squareDigits(num){
  let res = num.toString().split('').map(a => Number(a) ** 2).join('')
  return Number(res)
}
```