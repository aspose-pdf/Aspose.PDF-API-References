---
title: "Класс TextExtractionErrorLocation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextExtractionErrorLocation. Представляет место в PDF‑документе, где возникла ошибка извлечения текста"
type: docs
weight: 11060
url: /ru/net/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class

Представляет место в документе PDF, где возникла ошибка извлечения текста.

```csharp
public sealed class TextExtractionErrorLocation
```

## Свойства

| Имя | Описание |
| --- | --- |
| [FontUsedKey](../../aspose.pdf.text/textextractionerrorlocation/fontusedkey/) { get; } | Ключ (имя) объекта PDF Font, используемый для отображения оператора, вызывающего ошибку извлечения текста. |
| [FormKey](../../aspose.pdf.text/textextractionerrorlocation/formkey/) { get; } | Ключ (имя) PDF Form XObject, в котором обнаружена ошибка извлечения текста из потока содержимого. Не пустой, если ObjectType == 'xForm'. |
| [ObjectType](../../aspose.pdf.text/textextractionerrorlocation/objecttype/) { get; } | Тип PDF‑объекта (Page или xForm), в котором обнаружена ошибка извлечения текста из потока содержимого. |
| [OperatorIndex](../../aspose.pdf.text/textextractionerrorlocation/operatorindex/) { get; } | Индекс оператора отображения текста в потоке содержимого (коллекция операторов), вызывающего ошибку извлечения текста. |
| [OperatorString](../../aspose.pdf.text/textextractionerrorlocation/operatorstring/) { get; } | Оператор отображения текста, вызывающий ошибку извлечения текста. |
| [PageNumber](../../aspose.pdf.text/textextractionerrorlocation/pagenumber/) { get; } | Номер страницы документа, где обнаружена ошибка извлечения текста. |
| [Path](../../aspose.pdf.text/textextractionerrorlocation/path/) { get; } | Местоположение PDF‑документа, где возникла ошибка извлечения текста. |
| [TextStartPoint](../../aspose.pdf.text/textextractionerrorlocation/textstartpoint/) { get; } | Ключ (имя) объекта PDF Font, используемый для отображения оператора, вызывающего ошибку извлечения текста. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.text/textextractionerrorlocation/tostring/)() | Возвращает строковое представление. |

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


