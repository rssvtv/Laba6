### Лабораторная работа №6. Уведомления.
## Выполнила: Лепехина А.Д. ИСП-211о.
## Описание

Данное приложение позволяет пользователям создавать напоминания с заданным временем и текстом, сохранять их в базу данных, просматривать список напоминаний, удалять их, а также получать уведомления в указанный момент времени. Уведомления отображаются в Notification Center и переходят в детальный экран при нажатии. 
 
## Основные возможности

1. Создание напоминаний:
Пользователь задает заголовок, текст и дату/время напоминания через DatePickerDialog и TimePickerDialog.
Данные сохраняются в базу данных SQLite.

3. Просмотр напоминаний:
Список созданных напоминаний отображается в основном экране.

4. Удаление напоминаний:
Пользователь может удалить любое напоминание из списка.

5. Стилизованные уведомления:
Уведомления в статус-баре имеют кастомный логотип и содержат текст напоминания.

6. Обработка нажатия на уведомление:
При нажатии на уведомление открывается экран с полным текстом напоминания.


<p align="center">
    <img src="https://github.com/user-attachments/assets/cab7b99f-14ed-494e-8a9f-bc18a73ebece" width="250">
    <img src="https://github.com/user-attachments/assets/f51292b5-8c81-498f-9d3c-4e6981939f55" width="250">
    <img src="https://github.com/user-attachments/assets/d63663e8-ea2f-49c4-93d7-de3dfae7db69" width="250">
    <img src="https://github.com/user-attachments/assets/52b5caef-4edd-4310-9a31-5664e7e3ea48" width="250">
    <img src="https://github.com/user-attachments/assets/6049ced7-b78e-485d-96ac-5b2d6807bc38" width="250">
    <img src="https://github.com/user-attachments/assets/91f95b35-e557-4243-82be-b7b45630109b" width="250">
</p>

## Основной функционал
# 1. Создание напоминаний
Пользователь вводит заголовок и текст напоминания, выбирает дату и время. После нажатия кнопки Сохранить данные сохраняются в базу, а AlarmManager настраивает уведомление.

# 2. Уведомления
Уведомление настраивается с использованием:
- NotificationManager для управления уведомлениями.
- PendingIntent для обработки нажатий.
- AlarmManager для срабатывания уведомления в указанное время.

# 3. Список напоминаний
Отображение списка напоминаний происходит через RecyclerView, данные берутся из базы SQLite.

# 4. Удаление напоминаний
Долгое нажатие на элемент в списке позволяет удалить его.

---

## Установка и запуск
1. Скачать ZIP проекта.
2. Распаковать загруженный архив.
3. Склонируйте или загрузите проект в вашу интегрированную среду. В нашем случае это Android Studio.
4. Откройте проект:
 - Нажимаем на "Open" на начальном экране в верхней панели.
 - Выбрать распакованный архив.
 - Дождаться завершения всех процессов внутри проекта.
6. Подключите физическое устройство с помощью кабеля/Wi-Fi подключения или эмулятор для запуска приложения.
7. Нажмите Run, чтобы запустить приложение.

## Что было использовано:
- Язык программирования: Java
- Среда разработки: Android Studio
- Операционная система: Android
- База данных: SQLite
