<h1>Malinovka Miner Bot</h1>
<b>Malinovka Miner Bot</b> - простой бот, который позволит автоматизировать добычу руды в шахте на сервере Малиновка.
<br><br>Скачать бота без компиляции проекта: https://yadi.sk/d/IyKqFA4dX34DlA
<br>Лучше всего закинуть файл в папку с игрой.<br><br>

Требует реализации:
- Гибкость траектории движения (выбор определённого маршрута, добавление некоторых смещений движения)
- Обход персонажей находящийся в состоянии AFK (для дальнейшего во избежания бана)
- Добавление системы коллизии (на сервере уже присутствует частичная реализация, но этого недостаточно)
- Перехват сообщений из чата (сообщений от администрации)
- Отправление сообщений в чат
- Механизм прекращения работы бота в случае критической ситуации

Обновление: <b>10.11.2019</b>
- Добавлен механизм эмуляции движения персонажа в игре (с возможностью спринта)
- Подкорректирован момент с резким поворотом игрока после окончания работы с рудой (что могло резко выделить читера среди обычных игроков)
- Частично решён вопрос с ситуацией, когда персонаж отправлялся на точку сдачи руды без самой руды
- Введены некоторые корректировки в саму консоль
