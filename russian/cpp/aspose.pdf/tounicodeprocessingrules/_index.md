---
title: "Класс Aspose::Pdf::ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::ToUnicodeProcessingRules. Этот класс описывает правила, которые можно использовать для решения ошибки Adobe Preflight \"Text cannot be mapped to Unicode\" в C++."
type: docs
weight: 18700
url: /ru/cpp/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class


Этот класс описывает правила, которые можно использовать для решения ошибки Adobe Preflight «Текст нельзя сопоставить с Unicode».

```cpp
class ToUnicodeProcessingRules : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_MapNonLinkedSymbolsOnSpace](./get_mapnonlinkedsymbolsonspace/)() const | Некоторые шрифты не предоставляют информацию о юникодах для некоторых символов текста. Этот недостаток вызывает ошибку "Text cannot be mapped to Unicode". Используйте этот флаг, чтобы сопоставлять несвязанные символы с юникодом "space" (код 32). |
| [get_RemoveSpacesFromCMapNames](./get_removespacesfromcmapnames/)() const | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в названиях. Эти пробелы могут вызывать ошибки при сопоставлении юникода текста. Этот флаг указывает удалять пробелы из названий карт ToUnicode. По умолчанию false. |
| [set_MapNonLinkedSymbolsOnSpace](./set_mapnonlinkedsymbolsonspace/)(bool) | Некоторые шрифты не предоставляют информацию о юникодах для некоторых символов текста. Этот недостаток вызывает ошибку "Text cannot be mapped to Unicode". Используйте этот флаг, чтобы сопоставлять несвязанные символы с юникодом "space" (код 32). |
| [set_RemoveSpacesFromCMapNames](./set_removespacesfromcmapnames/)(bool) | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в названиях. Эти пробелы могут вызывать ошибки при сопоставлении юникода текста. Этот флаг указывает удалять пробелы из названий карт ToUnicode. По умолчанию false. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)() | Инициализирует новый экземпляр класса [ToUnicodeProcessingRules](./). |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool) | Инициализирует новый экземпляр класса [ToUnicodeProcessingRules](./) с указанным параметром для удаления пробелов из имен CMap. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool, bool) | Инициализирует новый экземпляр класса [ToUnicodeProcessingRules](./) с указанными параметрами. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
