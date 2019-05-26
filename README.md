# Клавиатурный тренжёр на Windows - программа для тренировки быстрого набора текста на компьютерной клавиатуре
# Требования к проекту

### Содержание
1. [Введение](#1) <br>
1.1. [Назначение](#1.1) <br>
1.2. [Бизнес-требования](#1.2) <br>
1.2.1. [Исходные данные](#1.2.1) <br>
1.2.2. [Границы проекта](#1.2.2) <br>
1.3. [Аналоги](#1.3) <br>
2. [Требования пользователя](#2) <br>
2.1. [Программные интерфейсы](#2.1) <br>
2.2. [Интерфейсы пользователя](#2.2) <br>
2.3. [Характеристики пользователей](#2.3)<br>
3. [Системные требования](#3)<br>
3.1. [Функциональные требования](#3.1)<br> 
3.2. [Нефункциональные требования](#3.2)<br>
3.2.1. [Атрибуты качества](#3.2.1)<br>
3.2.1.1. [Требования к удобству использования](#3.2.1.1)<br>
3.2.1.2. [Требования важные дла разработчика](#3.2.1.2)<br>
3.2.2. [Ограничения](#3.2.2)<br>

## 1. Введение <a name="1"></a>

### 1.1. Назначение <a name="1.1"></a>

В данном документе будут описаны функциональные и нефункциональные требования к приложению "Клавиатурный тренажер на Windows". "Клавиатурный тренажер на Windows" - это приложение, помогающее развить скорость печати и обучающее десятипальцевому методу печати.

### 1.2. Бизнес-требования <a name="1.2"></a>

#### 1.2.1. Исходные данные <a name="1.2.1"></a>

В мире современных технологий работа с компьютером, а соответственно, и с набором текста становится необходимой и обыденной задачей. В 
результате возрастает важность умения быстро набирать текст. Для данной цели существует метод слепой печати - методика набора текста 
«вслепую», то есть не глядя на клавиши печатной машинки или клавиши клавиатуры, используя все (или большинство) пальцы рук. Для обучения 
данному методу можно придумать несколько способов. Один из вариантов - клавиатурный тренажер, который поможет структурировать обучение 
и превратить его в игру.

#### 1.2.2. Границы проекта <a name="1.2.2"></a>

Данное приложение поможет организовать и разнообразить процесс обучения десятипальцевому методу печати, позволит отслеживать прогресс или отточить уже приобретенные навыки.

### 1.3. Аналоги <a name="1.3"></a>

#### [СОЛО на клавиатуре](https://solo.nabiraem.ru/) <br/> 
Возможность настроить сетевой доступ к программе для "соревновательного режима". Наличие звукового сопровождения. Большое количество модов и уроков. Настройка уровней и видимость прогресса.

#### [RapidTyping](http://www.rapidtyping.com/ru/) <br/>
Возможность задать себе цель, настроить интерфейс приложения на свой вкус, выбрать тип клавиатуры, вид и продолжительность урока. Большой выбор языков печати. Присутствует возможность добавления собственного текста и уроков. Статистика, позволяющая увидеть прогресс по скорости и правильности печати.

## 2. Требования пользователя <a name="2"></a>

### 2.1. Программные интерфейсы <a name="2.1"></a>

Приложение разрабатывается на языке Java под Windows с использованием библиотеки для создания графического интерфейса Fx.

### 2.2. Интерфейсы пользователя <a name="2.2"></a>

Графический интерфейс представлен в виде [мокапов]. <br/>
При запуске приложения пользователь попадает в меню:

![Меню] (https://github.com/eduardrogov/keyboard-teacher/blob/master/images/Меню.png) <br/>

Далее при нажатие на кнопку "Настройки" появляется окно настроек:

![Настройки] (https://github.com/eduardrogov/keyboard-teacher/blob/master/images/Настройки.png) <br/>

При нажатии на кнопку "Начать" в зависимости от выбранного вида тренировки пользователь перейдет к окнам игры:

![Игра1] (https://github.com/eduardrogov/keyboard-teacher/blob/master/images/Начать_тренировка_на_обучение.png) <br/>

![Игра2] (https://github.com/eduardrogov/keyboard-teacher/blob/master/images/Начать_тренировка_на_скорость.png) <br/>


### 2.3. Характеристики пользователя <a name="2.3"></a>

Для данного приложения нет определенной возрастной категории, оно доступно для любого пользователя, способного набирать текст на клавиатуре. Целевой аудиторией приложения являются пользователи компьютеров или люди, работающие с набором текстов. Приложение может быть полезно при желании пользователя улучшить качество и скорость печати.

## 3. Системные требования <a name="3"></a>

### 3.1. Функциональные требования <a name="3.1"></a>

Пользователю предоставлены возможности:

1. Возможность выбрать вид тренировки;
2. Возможность выбрать различные уровни и моды для тренировки на обучение;
3. Возможность узнать скорость печати при тренировке на скорость;
4. Возможность правильность печати при тренировке на скорость
5. Выбор английской раскладки клавиатуры;
6. Выбор русской раскладки клавиатуры
7. Добавление своего текста для тренировки;
8. Изменение интерфейса приложения.

### 3.2. Нефункциональные требования <a name="3.2"></a>

#### 3.2.1. Атрибуты качества<a name="3.2.1"></a>

##### 3.2.1.1. Требования к удобству использования <a name="3.2.1.1"></a>

  1. Наличие меню для удобной навигации по приложению;
  2. Возможность настроить интерфейс под свои предпочтения;
  3. Ошибки при вводе текста подсвечиваются красным, а правильно введенный текст - зеленым.
  
##### 3.2.1.2. Требования важные дла разработчика <a name="3.2.1.2"></a>

  1. Обработка нажатия клавиши должна происходить не более чем за 3 секунды. 
  2. Приложение должно продолжить работу при возникновении ошибок.

#### 3.2.2. Ограничения<a name="3.2.2"></a>

  1. Операционная система Windows 10  и младше;
  2. Наличие Java 8.

