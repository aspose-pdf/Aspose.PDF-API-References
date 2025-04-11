---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: PrinterMarkAnnotation-metod. Lägger till tryckmärken på alla sidor i det angivna dokumentet
type: docs
weight: 10
url: /sv/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Lägger till tryckmärken på alla sidor i det angivna dokumentet.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som tryckmärkena kommer att läggas till i. |
| marksKind | PrinterMarksKind | Typen av tryckmärken som ska läggas till. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Utlöses när *document* är null. |

## Kommentarer

Denna metod lägger till olika typer av tryckmärken baserat på de angivna [`PrinterMarksKind`](../../printermarkskind/) flaggorna. Om None anges, läggs inga märken till.

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* klass [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Lägger till tryckmärken på den angivna sidan.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Sidan som tryckmärkena kommer att läggas till i. |
| marksKind | PrinterMarksKind | Typen av tryckmärken som ska läggas till. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Utlöses när *page* är null. |

## Kommentarer

Denna metod lägger till olika typer av tryckmärken baserat på de angivna [`PrinterMarksKind`](../../printermarkskind/) flaggorna. Om None anges, läggs inga märken till.

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* klass [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)