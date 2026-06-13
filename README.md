<div style="font-family: 'Comic Sans MS', 'Comic Sans', cursive;">

# RPCEDITOR [![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/)

**RPCEDITOR** — программа, написанная на Python, которая позволяет настраивать и выводить кастомный игровой статус (Rich Presence) в профиле Discord.

## Возможности
- Настройка текстовых строк (State и Details).
- Поддержка большой и малой иконок с текстом при наведении.
- Отображение времени, прошедшего с момента запуска.
- Простой графический интерфейс для управления статусом.

## Зависимости

Для корректной работы программы необходимо установить пакеты в соответствии с вашей операционной системой.

### ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) Для Linux Mint / Ubuntu:
[КОМАНДА ДЛЯ ТЕРМИНАЛА]
sudo apt update && sudo apt install python3-pip python3-tk -y && pip install pypresence

### ![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows-11&logoColor=white) Для Windows:
Для работы программы в ОС Windows требуются следующие компоненты:
1. **Python** (версии 3.7 или выше). При установке обязательно отметьте галочку **"Add Python to PATH"**.
2. **Компонент Tcl/Tk** (интегрирован в стандартный установщик Python для Windows, отвечает за работу графического интерфейса).
3. **Библиотека pypresence** для связи с Discord API.

Для установки библиотеки откройте командную строку (cmd) или PowerShell и выполните:
[КОМАНДА ДЛЯ ТЕРМИНАЛА]
pip install pypresence

## Инструкция по использованию

1. Перейдите на [Discord Developer Portal](https://discord.com/developers/applications) и создайте новое приложение (**New Application**). Имя приложения будет отображаться как название вашей "игры".
2. Скопируйте **Application ID** созданного приложения.
3. (Опционально) В меню **Rich Presence -> Art Assets** загрузите изображения и сохраните их имена (ключи).
4. Запустите скрипт программы, введите скопированный ID и заполните нужные поля текста и картинок.
5. Нажмите кнопку запуска для обновления статуса в Discord.

</div>
