| name                    | type        | attributes                        | key     | note             |
| ----------------------- | ----------- | --------------------------------- | ------- | ---------------- |
| id                      | BIGINT(20)  | NOT NULL- AUTOINCREMENT -UNSIGNED | PRIMARY |
| model_name              | VARCHAR(20) | NOT NULL                          |         |
| car_brand               | VARCHAR(20) | NOT NULL                          |
| color                   | VARCHAR(10) | NOT NULL                          |
| car_chassis             | CHAR(17)    | NOT NULL                          |
| conditions              | CHAR(1)     | NOT NULL                          |         | "rating 1 to 10" |
| car_license_plate       | CHAR(7)     | NOT NULL                          |
| sold_on                 | DATETIME    | NULL                              |
| year_of_car_manufacture | YEAR        | NOT NULL                          |
| car_power_supply        | VARCHAR(15) | NOT NULL                          |
| car_change              | VARCHAR(15) | NOT NULL                          |
