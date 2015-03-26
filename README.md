# Android-Snippets
Snippets for Android

## DateFormatter.class ##
Класс для форматирования Unix Timestamp в понятный для человека русскоязычный текст. Поддерживается как длинный, так и короткий формат.

## SharedPreferencesHelper ##
Класс для удобного доступа к SharedPreferences. Перед использованием нужно инициализировать:

**Добавить** `SharedPreferencesHelper.initialize(this);` в кастомный **Application**
