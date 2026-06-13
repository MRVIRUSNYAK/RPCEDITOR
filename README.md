# RPCEDITOR [![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/)

**RPCEDITOR** — программа, написанная на Python, которая позволяет настраивать и выводить кастомный игровой статус (Rich Presence) в профиле Discord.

## Возможности
- Настройка текстовых строк (State и Details).
- Поддержка большой и малой иконок с текстом при наведении.
- Отображение времени, прошедшего с момента запуска.
- Простой графический интерфейс для управления статусом.

## Зависимости

Для корректной работы программы необходимо установить пакеты в соответствии с вашей операционной системой.

### Для Linux Mint / Ubuntu:
```bash
sudo apt update && sudo apt install python3-pip python3-tk -y && pip install pypresence

Для Windows:

Для работы программы в ОС Windows требуются следующие компоненты:

    Python (версии 3.7 или выше). При установке обязательно отметьте галочку "Add Python to PATH".

    Компонент Tcl/Tk (интегрирован в стандартный установщик Python для Windows, отвечает за работу графического интерфейса).

    Библиотека pypresence для связи с Discord API.

Для установки библиотеки откройте командную строку (cmd) или PowerShell и выполните:
DOS

pip install pypresence
