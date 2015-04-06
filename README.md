# Android-Snippets
Snippets for Android

## DateFormatter.class ##
Класс для форматирования Unix Timestamp в понятный для человека русскоязычный текст. Поддерживается как длинный, так и короткий формат.

## SharedPreferencesHelper.class ##
Класс для удобного доступа к SharedPreferences. Перед использованием нужно инициализировать:

**Добавить** `SharedPreferencesHelper.initialize(this);` в кастомный **Application**. Список настроек добавлять нужно в константу **PREFS**

## PluralFormatter.class ##
Класс для склонения количества чего угодно.  Использовать:

`PluralFormatter.make(100, new String[]{"день", "дня", "дней"});`

Получится: `100 дней`
