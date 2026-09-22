1. В домашней директории создать home_works создать директорию lesson_10
2. В директории lesson_10 создать директорию available, в ней файлы app.conf, readme.md, app.log с произвольным содержимым
3. В директории lesson_10 создать директорию enabled, в ней создать symlink на available/app.conf
4. В директории lesson_10 создать директории logs и debug; переместить файл available/app.log в директорию logs, а в debug сделать hardlink на logs/app.log
![Image Alt](https://github.com/Anitsupakl/-TMS_Lessons/blob/main/1-4.png?raw=true)

