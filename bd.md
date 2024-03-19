| | | |
|-|-|-|
|employee| | |
|Поле|Тип данных|Описание|
|employee_id|serial|Primary key|
|last_ name|varchar(70)| |
|first_name|varchar(70)| |
|middle_name|varchar(70)| |
| | | |
| | | |
|address | | |
|Поле|Тип данных|Описание|
|address_id|serial|Primary key|
|area_id|integer|Foreign key|
|city_id|integer|Foreign key|
|street|varchar(150)| |
|house|varchar(50)| |
| | | |
|division| | |
|Поле|Тип данных|Описание|
|Type_division_id|serial|Primary key|
|Type_division|varchar(50)| |
| | | |
|department| | |
|Поле|Тип данных|Описание|
|department_id|serial|Primary key|
|department_name|varchar(50)| |
| | | |
|Project| | |
|Поле|Тип данных|Описание|
|Project_id|serial|Primary key|
|Project_name|varchar(100)| |
| | | |
|Post| | |
|Поле|Тип данных|Описание|
|Post_id|Primary key|serial|
|Post_name|varchar(100)| |
| | | |
|area| | |
|Поле|Тип данных|Описание|
|area_id|serial|Primary key|
|area_name|varchar(100)| |
| | | |
|employee information| | |
|Поле|Тип данных|Описание|
|employee_information_id|integer|Primary key|
|employee_id|integer|Foreign key|
|address_id|integer|Foreign key|
|Date_hiring|date| |
|salary |float| |
|department_id|integer|Foreign key|
|division_id|integer|Foreign key|
|Project_id|integer|Foreign key|
|Post_id|integer|Foreign key|
| | | |
|city| | |
|Поле|Тип данных|Описание|
|city_id| serial|Primary key|
|city_name|varchar(100)| |
