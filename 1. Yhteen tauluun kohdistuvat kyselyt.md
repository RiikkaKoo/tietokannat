# Yhteen tauluun kohdistuvat kyselyt

### Tehtävä 1:
select * from goal; 

![Screenshot_4](https://github.com/user-attachments/assets/89ecfdea-d1fa-42bb-8904-7556ac4a99b6)

### Tehtävä 2:
select name, type from airport where iso_country = "FI";

![Screenshot_1](https://github.com/user-attachments/assets/29427198-ff69-496b-a962-79733a1b5181)

### Tehtävä 3:
select name from airport where iso_country = "FI" order by name asc;

![Screenshot_2](https://github.com/user-attachments/assets/467ac49e-2b44-4b92-8700-661e968e73ba)

### Tehtävä 4:
select name, type from airport where iso_country = "FI" order by type asc, name asc;

![Screenshot_3](https://github.com/user-attachments/assets/b322984b-346f-4278-8bb2-2f33136f2cf5)

### Tehtävä 5:
select name from country where name like "f%%";

![Screenshot_5](https://github.com/user-attachments/assets/fe017684-09ee-4dc8-adeb-ca7a0030e800)

### Tehtävä 6:
select name from country where name like "%f%";

![Screenshot_6](https://github.com/user-attachments/assets/5dd8fe63-b37c-4fa8-98d0-3a9cd31b039c)

### Tehtävä 7:
select location from game where screen_name like "Vesa";

![Screenshot_7](https://github.com/user-attachments/assets/51ae5a3c-fe45-40cc-a3d4-e319cc916e91)

### Tehtävä 8:
select co2_consumed from game where screen_name like "Ilkka";

![Screenshot_8](https://github.com/user-attachments/assets/3d4ab9b4-c172-4e5e-a758-c1fcdfe34d75)

### Tehtävä 9:
select distinct co2_budget from game;

![Screenshot_9](https://github.com/user-attachments/assets/6d4cf665-a68b-4004-8d78-f15ebfd6a4ae)
