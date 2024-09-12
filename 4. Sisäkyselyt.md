# Sisäkyselyt

### Tehtävä 1:
select country.name \
from country \
where country.iso_country in ( \
select iso_country \
from airport \
where name like "Satsuma%%");

![Screenshot_6](https://github.com/user-attachments/assets/40fd8c51-ef37-417f-a6e4-144e25891e68)

### Tehtävä 2:
select airport.name \
from airport \
where iso_country in ( \
select iso_country \
from country \
where name like "Monaco");

![Screenshot_1](https://github.com/user-attachments/assets/e24df29c-b203-4677-99fe-495b7b7b32e4)

### Tehtävä 3:
select screen_name \
from game where id in ( \
select game_id \
from goal_reached where goal_id in ( \
select id \
from goal where name = "CLOUDS") \
);

![Screenshot_2](https://github.com/user-attachments/assets/c1ed0583-5367-4867-9525-7c1e718f76ff)

### Tehtävä 4:
select country.name \
from country \
where iso_country not in ( \
select iso_country \
from airport);

![Screenshot_3](https://github.com/user-attachments/assets/06f30773-352e-4c0d-8739-ea9c3491fd60)

### Tehtävä 5:
select name \
from goal where id not in ( \
select goal_id \
from goal_reached where game_id in ( \
select id \
from game where screen_name = "Heini") \
);

![Screenshot_4](https://github.com/user-attachments/assets/c4601f62-1d8d-4160-b6d5-a33a48878ead)

