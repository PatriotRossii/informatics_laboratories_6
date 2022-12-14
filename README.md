# Лабораторная работа №7: Создание telegram-бота с расписанием

Лабораторная работа №7, выполненная в рамках дисциплины «Введение в информационные технологии».

Ссылка на задание: [pdf](appendix/task.pdf)

Ссылка на отчет о проделанной работе: [docx](appendix/report.docx)

## Домашнее задание

1. Реализовать обработку любых трех сообщений
2. Реализовать обработку любых трех команд
3. Реализовать обработку команды `/help`

## Инструкция по запуску

Перед запуском программы в корневой директории проекта необходимо создать файл `.env` с желаемыми credentials базы данных:

```
PG_DATABASE=...
PG_USER=...
PG_PASSWORD=...
PG_HOST=...
PG_PORT=...
```

Запуск с использованием пакетного менеджера `poetry`:

```bash
poetry install && poetry shell
python3 telegram_bot
```

Запуск стандартными средствами `python` (рекомендуется прежде создать отдельное [виртуальное окружение](https://docs.python.org/3/library/venv.html)):

```bash
pip3 install -r requirements.txt
python3 telegram_bot
```
