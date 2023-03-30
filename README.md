# Стриминговая платформа БД

Имеется база данных для музыкальной стриминговой платформы, предоставляющая информацию об исполнителях, их альбомах и песнях, а так же пользователях и их плейлистах.

В данной базе данных можно выделить следующие сущности: user, user's playlist, song, albom, artist, subscription.

База будет в 2НФ.
![image](https://user-images.githubusercontent.com/103955957/228663879-898db2e9-7da2-49dd-a673-f72c6bad0b19.png)
![image](https://user-images.githubusercontent.com/103955957/228664059-09756bca-a3cf-4463-b829-413991a0f6fa.png)
После нормализации появились сущности: playlist collection, song from playlist, song from albom, user's subscription.
Таблица user's subscription версионная с типом SCD2.
ссылка на физическу модель:
https://docs.google.com/spreadsheets/d/1Cl-uk99KDPX_19_CsYYtf6vCMjXbbKZlXXBPP63R_60/edit?usp=sharing
