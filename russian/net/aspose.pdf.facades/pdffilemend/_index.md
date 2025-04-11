---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileMend. Представляет класс для добавления текстов и изображений на страницы существующего PDF документа
type: docs
weight: 4530
url: /ru/net/aspose.pdf.facades/pdffilemend/
---
## Класс PdfFileMend

Представляет класс для добавления текстов и изображений на страницы существующего PDF документа.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Конструктор. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Инициализирует новый объект `PdfFileMend` на основе *документа*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Устанавливает логическое значение, которое указывает на перенос слов в методах AddText. Если значение истинно, текст в FormattedText будет переноситься. По умолчанию значение ложно. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Устанавливает или получает стратегию позиционирования текста. [`PositioningMode`](../positioningmode/) Режим по умолчанию - Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Устанавливает или получает алгоритм переноса слов. См. WordWrapMode и IsWordWrap. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Добавляет изображение на указанную страницу PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Добавляет изображение на указанные страницы PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Добавляет изображение на указанную страницу PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Добавляет изображение на указанные страницы PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Добавляет изображение на указанную страницу PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Добавляет изображение на указанные страницы PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Добавляет изображение на указанную страницу PDF документа по указанным координатам. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Добавляет изображение на указанные страницы PDF документа по указанным координатам. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Не реализовано. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Не реализовано. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Не реализовано. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Закрывает объект PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Сохраняет PDF документ в указанный поток. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Сохраняет PDF документ в указанный файл. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)