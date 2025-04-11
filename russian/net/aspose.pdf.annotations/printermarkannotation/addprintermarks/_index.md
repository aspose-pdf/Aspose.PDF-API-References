---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: Метод PrinterMarkAnnotation. Добавляет печатные метки ко всем страницам в указанном документе
type: docs
weight: 10
url: /ru/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Добавляет печатные метки ко всем страницам в указанном документе.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Document | Документ, к которому будут добавлены печатные метки. |
| marksKind | PrinterMarksKind | Вид печатных меток для добавления. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *document* равно null. |

## Примечания

Этот метод добавляет различные типы печатных меток на основе предоставленных флагов [`PrinterMarksKind`](../../printermarkskind/). Если предоставлено None, метки не добавляются.

### См. также

* класс [Document](../../../aspose.pdf/document/)
* перечисление [PrinterMarksKind](../../printermarkskind/)
* класс [PrinterMarkAnnotation](../)
* пространство имен [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Добавляет печатные метки на указанной странице.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Страница, к которой будут добавлены печатные метки. |
| marksKind | PrinterMarksKind | Вид печатных меток для добавления. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *page* равно null. |

## Примечания

Этот метод добавляет различные типы печатных меток на основе предоставленных флагов [`PrinterMarksKind`](../../printermarkskind/). Если предоставлено None, метки не добавляются.

### См. также

* класс [Page](../../../aspose.pdf/page/)
* перечисление [PrinterMarksKind](../../printermarkskind/)
* класс [PrinterMarkAnnotation](../)
* пространство имен [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../../)