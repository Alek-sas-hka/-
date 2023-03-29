# Стриминговая платформа БД

Имеется база данных для музыкальной стриминговой платформы, предоставляющая информацию об исполнителях, их альбомах и песнях, а так же пользователях и их плейлистах.

В данной базе данных можно выделить следующие сущности: user, user's playlist, song, albom, artist, subscription.

База будет в 2НФ.

После нормализации появились сущности: playlist collection, song from playlist, song from albom, user's subscription.

ссылки на логическую, концептуальную и физическуб модели:
[my data base.drawio (4).pdf](https://github.com/Alek-sas-hka/BD-streaming-platform/files/11105391/my.data.base.drawio.4.pdf)
https://docs.google.com/spreadsheets/d/1Cl-uk99KDPX_19_CsYYtf6vCMjXbbKZlXXBPP63R_60/edit?usp=sharing
