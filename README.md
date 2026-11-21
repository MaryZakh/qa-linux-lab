# qa-linux-lab

Учебный стенд для урока **Lesson 7. Linux for QA** (курс Advanced Manual QA).

Все логи вымышленные: сервис booking-api, пользователи, IP-адреса и email придуманы для занятия.

| Файл | Для чего |
|---|---|
| `linux-qa-log-lab.tar.gz` | Стенд для терминала Killercoda (Ubuntu Playground) |
| `linux-qa-log-lab.zip` | Те же файлы для просмотра на своём компьютере (резервный режим урока) |

## Загрузка стенда в Killercoda Ubuntu Playground

Три команды (выполнять по очереди):

    cd ~ && curl -fsSL -o linux-qa-log-lab.tar.gz https://raw.githubusercontent.com/GITHUB_LOGIN/qa-linux-lab/main/linux-qa-log-lab.tar.gz
    tar -xzf linux-qa-log-lab.tar.gz && cd linux-qa-log-lab
    bash tools/check-lab.sh

Последняя строка проверки: `ИТОГ: стенд в порядке.`
