---
title: "Класс ToUnicodeProcessingRules"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.ToUnicodeProcessingRules. Этот класс описывает правила, которые можно использовать для решения ошибки Adobe Preflight «Текст не может быть сопоставлен с Unicode»"
type: docs
weight: 11300
url: /ru/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

Этот класс описывает правила, которые можно использовать для решения ошибки Adobe Preflight «Текст не может быть сопоставлен с Unicode».

```csharp
public class ToUnicodeProcessingRules
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Инициализирует новый экземпляр класса `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Инициализирует новый экземпляр класса `ToUnicodeProcessingRules` с указанным параметром для удаления пробелов из имён CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Инициализирует новый экземпляр класса `ToUnicodeProcessingRules` с указанными параметрами. |

## Свойства

| Имя | Описание |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Некоторые шрифты не предоставляют информацию о юникодах для некоторых символов текста. Этот недостаток информации вызывает ошибку \"Text cannot be mapped to Unicode\". Используйте этот флаг, чтобы сопоставлять несвязанные символы с юникодом \"пробел\"(code 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в именах. Эти пробелы могут вызывать ошибки при сопоставлении текста с юникодом. Этот флаг указывает удалять пробелы из имён карт кодов символов ToUnicode. По умолчанию false. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


