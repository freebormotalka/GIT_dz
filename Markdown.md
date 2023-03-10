# Инструкция по работе с GIT
Git - программа для контроля версий. 
В программировании проблемы совместной работы над проектами возникли ещё до появления облачных сервисов.

# Основные комманды GIT 
+ **git init** Инициализация: указываем папку, в которой git начнёт отслеживать изменения. В папке создаётся скрытая папка .git 
+ **git status** Показывает текущее состояние гита, есть ли изменения, которые нужно закоммитить (сохранить)
+ **git --version** Если Git установлен на компьютер, вы увидите его текущую версию.
+ **git add** добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита. Эта команда дается после добавления файлов. Писать название целиком не обязательно: терминал дозаполнит данные автоматически.
+ **git commit** зафиксировать или сохранить. По умолчанию git commit использует лишь этот индекс, так что вы можете использовать git add для сборки слепка вашего следующего коммита. Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.
+ **git diff** Показывает разницу между текущим файлом и сохранённым. Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений
+ **git log** Журнал изменений. Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений.
+ **git checkout** Переключение между версиями. Для работы нужно указать не только интересующий вас коммит, но и вернуться в тот, где работаем, при помощи команды **git checkout master**
+ **git help** Вызов справки по популярным командам
+ **git clone** Клонирование репрозитория в новую директорию    
+ **git merge** Сливает две ветки в одну
+ **git pull** Данная команда позволяет скачать все из текущего репозитория и автоматически сделать *merge* с нашей версией
+ **git push** Отправить нашу версию репозитория на внешний репозиторий. **Требует авторизации** на внешнем репозитории