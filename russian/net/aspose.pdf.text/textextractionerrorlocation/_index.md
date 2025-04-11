---
title: Class TextExtractionErrorLocation
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextExtractionErrorLocation. Представляет местоположение в PDF-документе, где произошла ошибка извлечения текста
type: docs
weight: 10880
url: /ru/net/aspose.pdf.text/textextractionerrorlocation/
---
## Класс TextExtractionErrorLocation

Представляет местоположение в PDF-документе, где произошла ошибка извлечения текста.

```csharp
public sealed class TextExtractionErrorLocation
```

## Свойства

| Name | Description |
| --- | --- |
| [FontUsedKey](../../aspose.pdf.text/textextractionerrorlocation/fontusedkey/) { get; } | Ключ (имя) объекта шрифта PDF, который используется для отображения оператора, вызывающего ошибку извлечения текста. |
| [FormKey](../../aspose.pdf.text/textextractionerrorlocation/formkey/) { get; } | Ключ (имя) объекта XObject формы PDF, в котором находится ошибка извлечения текста потока содержимого. Не пусто, если ObjectType == 'xForm'. |
| [ObjectType](../../aspose.pdf.text/textextractionerrorlocation/objecttype/) { get; } | Тип объекта PDF (страница или xForm), в котором находится ошибка извлечения текста потока содержимого. |
| [OperatorIndex](../../aspose.pdf.text/textextractionerrorlocation/operatorindex/) { get; } | Индекс оператора отображения текста в потоке содержимого (коллекция операторов), который вызывает ошибку извлечения текста. |
| [OperatorString](../../aspose.pdf.text/textextractionerrorlocation/operatorstring/) { get; } | Текст оператора отображения, который вызывает ошибку извлечения текста. |
| [PageNumber](../../aspose.pdf.text/textextractionerrorlocation/pagenumber/) { get; } | Номер страницы документа, на которой находится ошибка извлечения текста. |
| [Path](../../aspose.pdf.text/textextractionerrorlocation/path/) { get; } | Местоположение PDF-документа, где произошла ошибка извлечения текста. |
| [TextStartPoint](../../aspose.pdf.text/textextractionerrorlocation/textstartpoint/) { get; } | Ключ (имя) объекта шрифта PDF, который используется для отображения оператора, вызывающего ошибку извлечения текста. |

## Методы

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.text/textextractionerrorlocation/tostring/)() | Возвращает строковое представление. |

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)