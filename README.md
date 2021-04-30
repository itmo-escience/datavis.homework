# Datavis homework

## Данные
В данных содержатся массив стран с базовой информацией о каждой стране и изменение во времени пяти параметров:
- population - население;
- gdp - ВВП;
- child-mortality - детская смертность;
- life-expectancy - продолжительность жизни;
- fertility-rate - коэффициент фертильности.

## Data
Data contains an array of countries with information about country and some parameters changing over time:
- population;
- gdp;
- child-mortality;
- life-expectancy;
- fertility-rate.

## Первый шаг
Построить пузырьковую диаграмму, на которой:
- Позиция элементов по осям x и y определяется заданными пользователем при помощи селекторов параметрами;
- Площадь элементов определяется заданным пользователем при помощи селектора параметром;
- Оси динамичиски меняются при изменении параметров;
- Цвет элементов задается на основе параметра region;
![](/gifs/step-1.gif)

## First step
Create a bubble chart on which:
- X and Y positions of elements is defined by selected parameters;
- An area of bubbles is defined by selected parameter;
- Axises changing dynamically with parameters changes;
- Bubbles is colored by region field;
![](/gifs/step-1.gif)

## Второй шаг 
Реализовать динамическое обновление пузырьковой диаграммы при изменении позиции временного ползунка.
![](/gifs/step-2.gif)

## Second step
Update bubble chart with time slider position changing.
![](/gifs/step-2.gif)

## Третий шаг
Построить столбчатую диаграмму, на которой:
- Отображается среднее значение по выбранному параметру для всех стран каждого из регионов:
- Позиция элементов по оси х соответствует порядку их следования в легенде;
- Цвета элементов определяются регионом и соответствуют цветовой кодировки в легенде и на пузырчатой диаграмме;
Столбчатая диаграмма должна динамически меняться при изменении параметра и позиции временного ползунка.
![](/gifs/step-3.gif)

## Third step
Create a bar chart on which:
- Mean value of chosen parameter for each country in region is shown;
- An order of bars matches the legend;
- Bars is colored by region field;
Bar chart should update on parameter or time slider change.
![](/gifs/step-3.gif)

## Четвертый шаг
При клике на элемент столбчатой диаграммы данный элемент выделяется среди других элементов при помощи прозрачности.
На пузырьковой диаграмме отображаются только страны, находящиеся в выбранном на столбчатой диаграмме регионе.
![](/gifs/step-4.gif)

## Fourth step
On click to the bar this bar should be highlighted using opacity. Bouble chart must display only disply only elements of the chosen region.
![](/gifs/step-4.gif)

## Пятый шаг
При клике на элемент пузырчатой диаграммы:
- Выбранный элемент выделяется среди прочих элементов пузырьковой диаграммы при помощи контура и отрисовывается поверх прочих элементов.
- На основе данных о выбранной стране строится линейная диаграмма, на которой:
  - По оси x оторажена временная шкала;
  - По оси y отложены значения выбранного параметра;
Линейная диаграмма должна динамически меняться при выборе другой страны и изменении выбранного параметра.
![](/gifs/step-5.gif)

## Fifth step
On the bubble:
- Chosen bubble must be drown over other elements in bubble chart and highlighted using stroke;
- Based on selected country data must be created a line chart on which:
  - X axes represents a time scale;
  - Y axes represents choosen parameter.
Line chart must update on parameter or time slider change.
![](/gifs/step-5.gif)

## Сдача
Для сдачи необходимо: 
- Сделать fork данного репозитория; 
- Внести нобходимые изменения;
- Настроить Github Pages в настройках своего репозитория;
- Прислать ссылку на страницу решения на Github Pages в тг(@PapaKKKarlo).

## Submission
To submit the homework:
- Make a fork of current repository;
- Make changes;
- Configure Github Pages in repository settings;
- Submit a link to the solution page in tg(@PapaKKKarlo).


Для отладки вы можете запустить [локальный сервер на python](https://developer.mozilla.org/ru/docs/Learn/Common_questions/set_up_a_local_testing_server).

For debugging, you can run a [local server in python](https://developer.mozilla.org/ru/docs/Learn/Common_questions/set_up_a_local_testing_server).
