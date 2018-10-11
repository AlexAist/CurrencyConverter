# UML Диаграммы
1. [Диаграмма активности](#1)<br>
1.1 [Перевод из одной валюты в другую](#1.1)
2. [Диаграмма классов](#2)
3. [Диаграмма последовательности](#3)
4. [Диаграмма состояний](#4)
5. [Диаграмма развёртывания](#5)
6. [Диаграмма прецедентов](#6)<br>
6.1 [Актёры](#6.1)<br>
6.2 [Варианты использования](#6.2)<br>
6.2.1 [Варианты использования](#6.2.1)<br>
6.2.2 [Варианты использования](#6.2.2)<br>

### 1. Диаграмма активности<a name="1"></a>
#### 1.1 Перевод из одной валюты в другую<a name="1.1"></a>
![Active Diagram](https://github.com/Vanya112/CurrencyConverter/blob/master/Documentation/Diagrams/ActivityDiagram.png)


### 2. Диаграмма классов<a name="2"></a>
Диаграмма классов представляет собой следующую диаграмму: 
![Class Diagram](https://github.com/Vanya112/CurrencyConverter/blob/master/Documentation/Diagrams/ClassDiagram.png)

  
### 3. Диаграмма последовательности<a name="3"></a>
Диаграмма последовательности основного варианта использования представляет из себя следующую диаграмму:
![Sequence Diagram](https://github.com/Vanya112/CurrencyConverter/blob/master/Documentation/Diagrams/SequenceDiagram.png)

### 4. Диаграмма состояний<a name="4"></a>
Диаграмма состояний представляет из себя следующую диаграмму:
![States Diagram](https://github.com/Vanya112/CurrencyConverter/blob/master/Documentation/Diagrams/StatesDiagram.png)

### 5. Диаграмма развертывания<a name="5"></a>

### 6. Диаграмма прецедентов<a name="6"></a>
Диаграмма прецедентов представляет собой следующую диаграмму: 
![Use Case](https://github.com/Vanya112/CurrencyConverter/blob/master/Documentation/Diagrams/FunctionalRequirements.png)
#### 6.1 Актёры<a name="6.1"></a>

Актёр | Описание
--- | ---
Пользователь|Человек, использующий систему

#### 6.2 Варианты использования<a name="6.2"></a>

##### 6.2.1 Посмотреть текущий курс валют<a name="6.2.1">
1.Вариант использования начинается, когда пользователь запускает приложение на ПК.

2.Приложение запрашивает текущий курс валют у веб-сервера.

3.Приложение выводит текущий курс. Если нет, то вызывается альтернативный поток А1.

4.Вариант использования завершается
</a>
##### 6.2.2 Перевести из одной валюты в другую<a name="6.2.2">
1.Вариант использования начинается, когда пользователь запускает приложение на ПК.

2.Приложение запрашивает текущий курс валют у веб-сервера.
Приложение выводит текущий курс. Если нет, то вызывается альтернативный поток А1.

3.Пользователь вводит сумму и выбирает валюту.
 
4.Пользователь нажимает на кнопку перевода.

5.Приложение выводит итоговую сумму.

6.Вариант использования завершается.

Альтернативный поток А1: Приложение выводит сообщение о невозможности подключения к веб-серверу.
</a>