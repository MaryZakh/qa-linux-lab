# qa-linux-lab

Учебный стенд для урока **Linux for QA** (курс Advanced Manual QA).

Все логи вымышленные: сервис booking-api, пользователи, IP-адреса и email придуманы для занятия.

| Файл | Для чего |
|---|---|
| `linux-qa-log-lab.tar.gz` | Стенд для терминала Killercoda (Ubuntu Playground) |
| `linux-qa-log-lab.zip` | Те же файлы для просмотра на своём компьютере (резервный режим урока) |

## Загрузка стенда в Killercoda Ubuntu Playground

Выполняйте команды по одной, когда видна строка ввода `root@ubuntu:~$`.

Скачать архив (при успехе ничего не выводит):

    curl -fsSL -O https://raw.githubusercontent.com/MaryZakh/qa-linux-lab/main/linux-qa-log-lab.tar.gz

Распаковать (при успехе ничего не выводит):

    tar -xzf linux-qa-log-lab.tar.gz

Перейти в папку стенда:

    cd linux-qa-log-lab

Проверить стенд:

    bash tools/check-lab.sh

Последняя строка проверки: `ИТОГ: стенд в порядке.`

Если при вставке в начале строки появилось `^[[200~` или в конце `~` — не нажимайте Enter, нажмите Ctrl+C и вставьте команду снова (или наберите вручную).
