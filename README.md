Лабораторная работа: Создание Android приложения с несколькими экранами
Задание 1. Создание проекта приложения
Запустите среду программирования в IDE IntelliJ IDEA.

Задание 2. Создание приложений с одним экраном (Activity)
Необходимо создать два Activity и организовать переход между ними.

Содержимое Activity 1:

Кнопка с именем btn1.
Содержимое Activity 2:

TextView с текстом «Переданный параметр: значение_параметра».
значение_параметра – принятый параметр из Activity 1.
При запуске приложения пользователь должен попадать на экран с Activity 1. После нажатия на кнопку btn1 необходимо осуществить переход к Activity 2 и передавать параметр из Activity 1. В качестве значения передаваемого параметра использовать свою фамилию.

Ключевые классы: Activity, Intent, Button, TextView

Описание лаборатной работы №1
Этот проект демонстрирует основы создания Android приложений с несколькими экранами (Activity) и передачу данных между ними с использованием Intent.

Используемые технологии
Java
Android Jetpack Compose
Структура проекта
MainActivity: Первая активность, содержащая кнопку для перехода на вторую активность.
SecondActivity: Вторая активность, отображающая текст, полученный из первой активности.