---
title: "Класс TextRecognitionResult"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.TextRecognitionResult. Представляет агрегированные результаты OCR для одного исходного документа"
type: docs
weight: 1180
url: /ru/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Представляет агрегированные результаты OCR для одного исходного документа.

```csharp
public class TextRecognitionResult
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Список, содержащий подробные результаты OCR для каждой страницы документа. Для файлов с одним изображением этот список обычно содержит одну запись OcrDetail с PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Указывает, был ли OCR успешным для ВСЕХ страниц этого документа. False, если любой OcrDetail в OcrDetails имеет Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Идентификатор исходного файла (например, полный путь или уникальное имя). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Сводное сообщение об ошибке, если OverallSuccess = false, или резюме, если какая‑то страница не прошла. Null, если OverallSuccess = true. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Получает или задает общие статистические данные использования при обработке этого документа (все страницы). |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


