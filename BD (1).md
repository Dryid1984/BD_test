| | | | | | | | | | | | | | | | | | | | | |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|сотрудник |employee| | | | | | | | | | | |employee|salary |Post|division|department|Date_hiring|address |Project|
| |Поле|Тип данных|Описание| | | | | | | | | |ФИО сотрудника|Оклад|Должность|Тип подразделения|Структурное подразделение|Дата найма|Адрес филиала|Проект на который назначен|
| |employee_id|serial|Primary key| | | | | | | | | |Суханова Арина Руслановна|103333.00|ведущий QA инженер|Отдел|Центр компетенций QA Москва|01/20/2013|Приморский край, г. Владивосток, ул Нижнепортовая, д. 1|{Итэлма Инженерный корпус}|
|Фамилия|last_ name|varchar(70)| | | | | | | | | | | | | | | | | | |
|Имя |first_name|varchar(70)| | | | | | | | | | | | | | | | | | |
|Отчество|middle_name|varchar(70)| | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
|Адрес|address | | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |address_id|serial|Primary key| | | | | | | | | | | | | | | | | |
|Область|area_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
|город|city_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
|улица|street|varchar(150)| | | | | | | | | | | | | | | | | | |
|дом|house|varchar(50)| | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
|Структурное подразделение|department| | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |department_id|serial|Primary key| | | | | | | | | | | | | | | | | |
|Структурное подразделение|department_name|varchar(50)| | | | | | | | | | | | | | | | | | |
|тип подразделения|Type_division|varchar(50)| | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
|Проект на который назначен|Project| | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |Project_id|serial|Primary key| | | | | | | | | | | | | | | | | |
| |Project_name|varchar(100)| | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
|Должность|Post| | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |Post_id|Primary key|serial| | | | | | | | | | | | | | | | | |
| |Post_name|varchar(100)| | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
|Область|area| | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |area_id|serial|Primary key| | | | | | | | | | | | | | | | | |
| |area_name|varchar(100)| | | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
| |employee information| | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |employee_information_id|integer|Primary key| | | | | | | | | | | | | | | | | |
|сотрудник |employee_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
|Адрес|address_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
|дата приема|Date_hiring|date| | | | | | | | | | | | | | | | | | |
|деньги|salary |numeric| | | | | | | | | | | | | | | | | | |
|Структурное подразделение|department_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
|Проект на который назначен|Project_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
|Должность|Post_id|integer|Foreign key| | | | | | | | | | | | | | | | | |
| | | | | | | | | | | | | | | | | | | | | |
|город|city| | | | | | | | | | | | | | | | | | | |
| |Поле|Тип данных|Описание| | | | | | | | | | | | | | | | | |
| |city_id| serial|Primary key| | | | | | | | | | | | | | | | | |
| |city_name|varchar(100)| | | | | | | | | | | | | | | | | | |
