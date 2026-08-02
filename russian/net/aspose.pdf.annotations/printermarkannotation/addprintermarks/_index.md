---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PrinterMarkAnnotation. Добавляет отметки принтера на все страницы в указанном документе"
type: docs
weight: 10
url: /ru/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Добавляет отметки принтера ко всем страницам в указанном документе.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Document | Документ, к которому будут добавлены отметки принтера. |
| marksKind | PrinterMarksKind | Тип отметок принтера, которые нужно добавить. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *document* равен null. |

## Примечания

Этот метод добавляет различные типы отметок принтера в зависимости от предоставленных флагов [`PrinterMarksKind`](../../printermarkskind/). Если указано None, отметки не добавляются.

### См. также

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Добавляет отметки принтера к указанной странице.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Страница | Страница, к которой будут добавлены отметки принтера. |
| marksKind | PrinterMarksKind | Тип отметок принтера, которые нужно добавить. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *page* равен null. |

## Примечания

Этот метод добавляет различные типы отметок принтера в зависимости от предоставленных флагов [`PrinterMarksKind`](../../printermarkskind/). Если указано None, отметки не добавляются.

### См. также

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


