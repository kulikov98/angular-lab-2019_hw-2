# angular-lab-2019_hw-2

Продолжим тему быстрого питания. Вы хозяин небольшого кафе/магазина/чего угодно (кроме магазина покемонов, прошу), и у этого заведения есть возможность сделать заказ через интернет. В вашем приложении планируется две страницы: страница со списком всех товаров и страница с корзиной, в которой пользователь может ввести свои данные и отправить заказ. В течении нескольких домашних заданий мы постепенно соберем это приложение.

### Задание к лекции "Angular Intro", 19/11
##### Основная часть
1) Определитесь с тематикой вашего заведения, названием. Cоздайте приложение с этим названием (`ng new`)
2) Создайте компонент карточки товара. Он должен выводить название вашего товара и стоимость.
3) Создайте компонент списка товаров. Он должен просто выводить все товары.
4) Вставьте компонент со списком товаров в app компонент. Данные, которые использует этот список, должны браться из app компонента.
Для реализации посмотрите, как работает `@Input()`(propety binding) и `*ngFor`.

##### Часть под звездочкой *(можно делать не полностью или не делать вообще)*
5) Карточка товара должна отображать количество выбранного товара с кнопкой `+`. Изначальное количество - 0, каждое нажатие на `+` должно добавлять 1 товар. Для того, чтобы это сделать, посмотрите, как работает `@Output()`(event binding).
6) Помимо кнопки `+`, добавьте кнопку `-`. Она вычитает 1 товар. Если товаров 0, то она disabled.
7) Поместите все данные о товарах в сервис.

### Дополнительные требования
1) Все сущности, которые вы добавляете, должны быть сгенерированы при помощи `ng cli`
2) Выберете с самого начала css препроцессор, который вы используете/хотите попробовать, и добавьте его в опции при выполнении команды `ng new`(можно добавить и после создания проекта, если не разберетесь, как это сделать, пишите). Если вы никогда не имели дело с препроцессорами, то можно пропустить это требование
3) *(не обязательно к выполнению, в первую очередь для тех, кто уже пишет на ангуляре)* Используйте библиотеку Angular Material
