# Eleks.Internship.Nazar_Melnyk 
Eleks.Internship.Iazyk_Nazarii_Slavik_Pankovych_Nazar_Melnyk_Dmytro_Yakovyna

Practical task of Nazar Melnyk for Eleks Internship (November 2017)

## Student Info
* Name:  Nazar Melnyk
* University: KEP
* Course: 4

## Task Info
### System Analizer
### Estimate - 60h
Розробити систему для відстежування та аналізу поточного стану системи. Програма повинна бути виконана у вигляді Windows Service для можливості моніторингу не залежно від поточного користувача.
#### Аналізатор повинен слідкувати за наступними парметрами:
*	  Обєм вільного місця на диску С. При зміні обєму вільного місця більш ніж на 100 МБ в файл повинен записуватись лог наступного формату - “{дата і час}, обєм вільного місця змінився з {попереднє значення} МБ до {поточне значення} МБ”.
*	  Наявність Інтернет зєднання. При зміні стану Інтернет зєднання в файл повинен записуватись лог наступного формату - “{дата і час} зміна стану Інтернет зєднання - {Підключено/Відключено}”.
*	  Також дані про обєм вільного місця та наявність інтернет зєднання повинні записуватись в файли при старті та запунці Windows Service.

