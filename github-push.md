Git (произносится «гит») — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.

Среди проектов, использующих Git — ядро Linux, Swift, Android, Drupal, Cairo, GNU Core Utilities, Mesa, Wine, Chromium, Compiz Fusion, FlightGear, jQuery, PHP, NASM, MediaWiki, DokuWiki, Qt, ряд дистрибутивов Linux.

Программа является свободной и выпущена под лицензией GNU GPL версии 2. По умолчанию используется TCP порт 9418.

Распространенные опции

+ $ cd C:/Users/user/my_project - перемещение в директорию
+ git branch
Отображение списка веток в репозитории. Это синоним команды git branch --list.

+ git branch <branch>
Создание новой ветки с именем ＜ветка＞. Эта команда не выполняет переключение на эту новую ветку.

+ git branch -d <branch>
Удаление указанной ветки. Это «безопасная» операция, поскольку Git не позволит удалить ветку, если в ней есть неслитые изменения.

+ git branch -D <branch>
Принудительное удаление указанной ветки, даже если в ней есть неслитые изменения. Эта команда используется, если вы хотите навсегда удалить все коммиты, связанные с определенным направлением разработки.

+ git branch -m <branch>
Изменение имени текущей ветки на ＜ветка＞.

+ git branch -a
Вывод списка всех удаленных веток.

+ git push
используется для выгрузки содержимого локального репозитория в удаленный репозиторий. Она позволяет передать коммиты из локального репозитория в удаленный. Эта команда симметрична команде git fetch: при извлечении с помощью fetch коммиты импортируются в локальные ветки, а при публикации с помощью push коммиты экспортируются в удаленные ветки.

+ git pull
используется для извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым. Слияние удаленных вышестоящих изменений в локальный репозиторий — это обычная задача рабочего процесса, возникающая при совместной работе на основе системы Git. Команда git pull на самом деле представляет собой комбинацию двух других команд: git fetch и git merge. На первом этапе git pull выполняется команда git fetch, ограниченная локальной веткой, на которую указывает HEAD. Сразу после загрузки содержимого команда git pull выполняет слияние. Для слитого содержимого создается новый коммит, а указатель HEAD обновляется и начинает указывать на этот новый коммит.     