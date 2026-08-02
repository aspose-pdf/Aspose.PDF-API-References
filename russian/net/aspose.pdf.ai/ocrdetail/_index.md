---
title: "Класс OcrDetail"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.OcrDetail class. Представляет результат OCR для одной страницы document или одного файла изображения"
type: docs
weight: 860
url: /ru/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Представляет результат OCR для одной страницы документа или одного файла изображения.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OcrDetail](ocrdetail/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Сообщение об ошибке, описывающее, почему OCR не удалось для этой страницы, если Success равно false. Null в противном случае. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | Извлечённое текстовое содержимое со page. Null, если Success равно false или текст не найден. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | Номер page, начинающийся с 1, в исходном document. Для одностраничных изображений это всегда будет 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Указывает, был ли OCR‑извлечение для этой конкретной page успешным. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Получает или задаёт статистику использования. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Сравнивает текущий экземпляр OcrDetail с другим объектом OcrDetail на основе их свойства PageNumber. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


