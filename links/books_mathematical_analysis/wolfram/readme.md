## [Назад в поиск по предмету](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/mathematical-analysis.md)

### Подчсчет в математическом пакете Wolfram Alpha
#### [Wolfram Alpha](https://www.wolframalpha.com/) ![](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/wolfram.png)

[Документация языка Wolfram Language](https://reference.wolfram.com/language/)

[Книга про Wolfram Alpha (На английском)](https://www.wolfram.com/language/elementary-introduction/2nd-ed/)

* [Пределы](#пределы)
* [Суммирование](#суммирование)
* [Биномиальный коэффициент](#биномиальный-коэффициент)
* [Неопределенный интеграл](#неопределенный-интеграл)
* [Определенный интеграл](#определенный-интеграл)

## Пределы 
  Синтаксис:
 
    limit 'function(x)' ,x-> к чему стремиться
#
#### Пример 1 :
    
    limit sin(x)/x, x->0
Результат :    
![Альтернативный текст](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/image.png)

#### Пример 2 :
    
    limit 3(x)^2/x, x->inf
Результат :  

![Альтернативный текст](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/Screenshot_20201006_195710.png)
##  Суммирование
Синтаксис :
    
    sum (function(k)) , k = начало суммирования to конец суммирования
#### Пример 1 :   
    sum x^k/k!, k=0 to +oo
Результат :

![Альтернативный текст](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/Screenshot_20201006_203634.png)    
#### Пример 2 :
Также можно суммировать вот так :

    sum (3/4)^j, j=0..infinity
Результат:

![Альтернативный текст](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/Screenshot_20201006_204616.png "Сумма" )

##  Биномиальный коэффициент
Число сочетаний из n по k 

    binomial(n,k)
#
    binomial(10,2)
Результат :

![](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/binomial.png)
    
##  Неопределенный интеграл

Синтаксис :

    integrate (Function(x))
#### Пример 1 :   
    integrate x^2-2x+3
Результат :

![](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/integrate.png)

## Определенный интеграл

Синтаксис :

    integrate (Function(x)) x= от чего .. до чего
#### Пример 1 :   
    integrate -3x^2+2x+9, x=-1..2
Результат :

![](https://github.com/ifanzilka/Mathematics_KPFU/blob/master/links/books_mathematical_analysis/wolfram/img/integrate3.png)

