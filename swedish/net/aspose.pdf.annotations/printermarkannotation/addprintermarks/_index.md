---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PrinterMarkAnnotation‑metod. Lägger till skrivarmärken på alla sidor i det angivna dokumentet"
type: docs
weight: 10
url: /sv/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Lägger till skrivarens markeringar på alla sidor i det angivna dokumentet.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Dokument | Dokumentet som skrivarmärkena ska läggas till i. |
| marksKind | PrinterMarksKind | Typ av skrivarmärken att lägga till. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *document* är null. |

## Anmärkningar

Denna metod lägger till olika typer av skrivarmärken baserat på de angivna [`PrinterMarksKind`](../../printermarkskind/) flaggorna. Om None anges, läggs inga märken till.

### Se även

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Lägger till skrivarens markeringar på den angivna sidan.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Sidan som skrivarmärkena kommer att läggas till. |
| marksKind | PrinterMarksKind | Typ av skrivarmärken att lägga till. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *page* är null. |

## Anmärkningar

Denna metod lägger till olika typer av skrivarmärken baserat på de angivna [`PrinterMarksKind`](../../printermarkskind/) flaggorna. Om None anges, läggs inga märken till.

### Se även

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


