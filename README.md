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
