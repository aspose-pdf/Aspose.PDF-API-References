---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.ToUnicodeProcessingRules. Этот класс описывает правила, которые могут быть использованы для решения ошибки Adobe Preflight "Текст не может быть сопоставлен с Unicode"
type: docs
weight: 11110
url: /ru/net/aspose.pdf/tounicodeprocessingrules/
---
## Класс ToUnicodeProcessingRules

Этот класс описывает правила, которые могут быть использованы для решения ошибки Adobe Preflight "Текст не может быть сопоставлен с Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Инициализирует новый экземпляр класса `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Инициализирует новый экземпляр класса `ToUnicodeProcessingRules` с указанным параметром для удаления пробелов из имен CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Инициализирует новый экземпляр класса `ToUnicodeProcessingRules` с указанными параметрами. |

## Свойства

| Имя | Описание |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Некоторые шрифты не предоставляют информацию о юникодах для некоторых текстовых символов. Этот недостаток информации вызывает ошибку "Текст не может быть сопоставлен с Unicode". Используйте этот флаг для сопоставления несвязанных символов с юникодом "пробел" (код 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в именах. Эти пробелы могут вызывать ошибки при сопоставлении текста с юникодом. Этот флаг указывает на необходимость удаления пробелов из имен карт кодов символов ToUnicode. По умолчанию false. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)