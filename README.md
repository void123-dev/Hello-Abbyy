# Hello-Abbyy
Тестовое консольное приложение

## Udates 2020-01-22
+ Функция DeleteEmptyRows() больше не используется;
+ Вместо DeleteEmptyRows() используется функция DeleteEmptyDescriptRow();
+ Тег <_FileName /> генерируется на уровне шаблона;
+ Тег <_Pages /> генерируется на уровне шаблона;
+ Добавлена функция InsertValueIntoField(), которая втсавляет значение в поле по имени;

## Udates 2020-01-21
+ Изменена функция DeleteEmptyRows():
  - Добавлен тег <_FileName/> в xml с названием оригинального файла;
  - Добавлен тег <_Pages/> в xml с номерами страниц документа из оригинального файла.
