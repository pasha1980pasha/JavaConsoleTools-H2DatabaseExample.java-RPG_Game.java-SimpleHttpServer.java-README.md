# ☕ Java Console Tools

Набор учебных Java-приложений для изучения баз данных, графического интерфейса и сетевого программирования.

## 📁 Содержание

| Файл | Описание |
|------|----------|
| `H2DatabaseExample.java` | Работа с H2 базой данных. Создание таблицы `notes`, вставка и чтение записей. База сохраняется на рабочем столе. |
| `RPG_Game.java` | Графическая RPG игра на Swing. Классы: Воин, Маг, Лучник. Битвы, магазин, отдых, прокачка, инвентарь. |
| `SimpleHttpServer.java` | Простой HTTP-сервер на встроенном Java-сервере. Отдает HTML-страницу с текущим временем на порту 8080. |

## 📋 Требования

- Java 11 или выше
- Для `H2DatabaseExample.java`: библиотека H2 Database (h2-*.jar)

## 🚀 Запуск

### H2DatabaseExample.java
```bash
javac -cp "h2-*.jar" H2DatabaseExample.java
java -cp ".;h2-*.jar" H2DatabaseExample
