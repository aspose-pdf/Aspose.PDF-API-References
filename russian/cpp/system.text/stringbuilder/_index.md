---
title: "System::Text::StringBuilder класс"
linktitle: "StringBuilder"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::StringBuilder class. Буфер для накопления строки по частям. Этот тип может быть выделен либо в стеке как тип значения, либо в куче с помощью функции System::MakeObject() function. После выделения объекта никогда не смешивайте эти два варианта использования: наличие указателей SmartPtr на объекты, выделенные в стеке, строго запрещено в C++."
type: docs
weight: 2400
url: /ru/cpp/system.text/stringbuilder/
---
## StringBuilder class


[Buffer](../../system/buffer/) to accumulate string part by part. This type can be allocated either in stack as value type or in heap using [System::MakeObject()](../../system/makeobject/) function. Once the object is allocated, never mix up these two usecases: having [SmartPtr](../../system/smartptr/) pointers onto stack-allocated objects is strictly prohibited.

```cpp
class StringBuilder : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Append](./append/)(char_t) | Добавляет символ в построитель. |
| [Append](./append/)(char_t, int) | Добавляет символы в построитель. |
| [Append](./append/)(const ArrayPtr\<char_t\>\&) | Добавляет массив символов в построитель. |
| [Append](./append/)(const ArrayPtr\<char_t\>\&, int, int) | Добавляет срез массива символов в построитель. |
| [Append](./append/)(const String\&) | Добавляет строку в построитель. |
| [Append](./append/)(const String\&, int, int) | Добавляет срез строки в построитель. |
| [Append](./append/)(const SharedPtr\<T\>\&) | Добавляет строковое представление объекта в построитель. |
| [Append](./append/)(const SharedPtr\<StringBuilder\>\&) | Добавляет содержимое построителя в построитель. |
| [Append](./append/)(float) | Добавляет значение с плавающей точкой в построитель. |
| [Append](./append/)(double) | Добавляет значение с плавающей точкой в построитель. |
| [Append](./append/)(int) | Добавляет целочисленное значение в построитель. |
| [Append](./append/)(T) | Добавляет арифметическое значение в построитель. |
| [Append](./append/)(E) | Добавляет строковое представление значения перечисления в построитель. |
| [AppendFormat](./appendformat/)(const String\&, const TArgs\&...) | Добавляет отформатированную строку в построитель. |
| [AppendFormat](./appendformat/)(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) | Добавляет отформатированную строку в построитель. |
| [AppendLine](./appendline/)() | Добавляет символ новой строки в построитель. |
| [AppendLine](./appendline/)(const String\&) | Добавляет строку, за которой следует символ новой строки, в построитель. |
| [Clear](./clear/)() | Удаляет все символы из построителя. |
| [CopyTo](./copyto/)(int, System::ArrayPtr\<char_t\> const\&, int, int) | Копирует данные построителя в существующие позиции массива. |
| [EnsureCapacity](./ensurecapacity/)(int32_t) | Обеспечивает, что ёмкость этого экземпляра [System.Text.StringBuilder](./) как минимум равна указанному значению. |
| [get_Capacity](./get_capacity/)() const | Получает текущую ёмкость строкового построителя. |
| [get_Length](./get_length/)() const | Получает длину строки, находящейся в построителе. |
| [idx_get](./idx_get/)(int) const | Получает символ в указанной позиции. |
| [idx_set](./idx_set/)(int, char_t) | Устанавливает символ в указанной позиции. |
| [Insert](./insert/)(int, const String\&) | Вставляет строку в фиксированную позицию построителя. |
| [Insert](./insert/)(int32_t, const String\&, int32_t) | Вставляет повторяющуюся строку в фиксированную позицию построителя. |
| [Insert](./insert/)(int, char_t) | Вставляет символ в фиксированную позицию построителя. |
| [Insert](./insert/)(int, const System::ArrayPtr\<char_t\>\&, int, int) | Вставляет символы в фиксированную позицию построителя. |
| [Insert](./insert/)(int, T) | Вставляет значение в фиксированную позицию построителя. |
| [operator[]](./operator[]/)(int) const | Получает символ в указанной позиции. |
| [Remove](./remove/)(int, int) | Удаляет фрагмент из построителя. |
| [Replace](./replace/)(const String\&, const String\&) | Заменяет подстроку через построитель. |
| [Replace](./replace/)(const String\&, const String\&, int, int) | Заменяет подстроку через диапазон построителя. |
| [Replace](./replace/)(char_t, char_t) | Заменяет символ через построитель. |
| [Replace](./replace/)(char_t, char_t, int, int) | Заменяет символ в диапазоне построителя. |
| [set_Capacity](./set_capacity/)(int) | Устанавливает текущую ёмкость строкового построителя. |
| [set_Length](./set_length/)(int) | Обрезает или расширяет строковый построитель до указанной длины. |
| [StringBuilder](./stringbuilder/)() | Конструктор. |
| [StringBuilder](./stringbuilder/)(int) | Конструктор. |
| [StringBuilder](./stringbuilder/)(const String\&) | Конструктор. |
| [StringBuilder](./stringbuilder/)(const String\&, int) | Конструктор. |
| [StringBuilder](./stringbuilder/)(const String\&, int, int, int) | Конструктор. |
| [ToString](./tostring/)() const override | Получает строку, текущо содержащуюся в построителе. |
| [ToString](./tostring/)(int, int) const | Получает подстроку, текущо содержащуюся в построителе. |
| [~StringBuilder](./~stringbuilder/)() | Деструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
