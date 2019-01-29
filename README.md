# PISL2019-01-29.

### Начало работы:

<b>Посмотрите видео: <a href="https://youtu.be/mIs-X63CH78" target="_blank">Tutorial:QuickStart</a></b>

1. Инициализация. Нажмите Fork на странице https://github.com/Khmelov/PISL2019-01-29/
2. У вас в аккаунте fork появится тут  https://github.com/ваш_логин/PISL2019-01-29
3. Выберите в IDEA VCS -> Checkout version control -> GitHub и затем:
 * укажите ссылку на Ваш fork https://github.com/ваш_логин/PISL2019-01-29;
 * выберите путь к папке проекта (без русских букв и пробелов);
 * укажите имя папки проекта (например PISL2019-01-29_verXX - такой папки на диске быть не должно).
 * после создания проекта один раз выполните команду VCS -> Git -> Rebase my GitHub fork (для версий IDEA 2017 и ранее), для новых версий нужно прямо добавить VCS -> Git -> Remote источник для обновлений <b>upstream</b> с URL: https://github.com/Khmelov/PISL2019-01-29/

### Перед **каждым** сеансом работы:

1. Получите последние изменения основного репозитория VCS -> Git -> Pull (выберите upstream как источник)
2. **Скопируйте** папку с заданиями и тестами (by.it.\a.khmelev\lessonXX) в свою папку ((by.it.группа.фамилия.lessonXX))
3. Отправьте эти изменения в свой репозиторий VCS -> Git -> Push

### Работаем с кодом:

1. Добавьте файлы ВСЕ java-файлы вашего пакета под контроль версий (Ctrl+Shift+A или VCS -> Git -> Add)
2. Работайте с кодом. Добейтесь чтобы проект собирался и запускался без ошибок.
3. Делайте коммиты Ctrl+K. _возврат на пункт 2 нужное число раз ;)_
4. Отправьте накопленные изменения в свой репозиторий VCS -> Git -> Push
5. Если работу нужно сдать, проверьте что проект собирается и запускается, затем можно сделать VCS -> Git -> Pull Request
<br>_при Pull Request-е видно какие изменяются файлы. В идеале должны быть изменения только в вашей папке_

### ВНИМАНИЕ!

Если проект не запускается из-за ошибок в чужих папках **НЕ ИСПРАВЛЯЙТЕ ИХ!**.
<br>Кто-то их тоже исправит и будет конфликт слияния на github.
<br>А как тогда сделать правильно? Просто отключите проблемную папку:
* выделите её в дереве проекта
* нажмите на ней правой кнопкой мыши
* Выполните команду Mark Directory as -> Excluded
* эта команда затронет только Ваш компьютер

### Если все поломалось!

1. **Скопируйте** свою папку из src/by/it/ в отдельное место на диске.
 * найти свою папку на диске можно выделив ее в дереве папок в IDEA. Далее, правая кнопка -> Show in Explorer.
2. Удалите fork из своего аккаунта github (откройте форк на сайте, выберите Setting-Delete this repository)
3. Выполните всю последовательность из шапки (см. <b>Начало работы</b>).
4. Верните свою папку на место в свежем проекте.
5. Делайте коммит Ctrl+K.
6. Отправьте накопленные изменения в свой репозиторий VCS -> Git -> Push

_С уважением, Александр Хмелев._
