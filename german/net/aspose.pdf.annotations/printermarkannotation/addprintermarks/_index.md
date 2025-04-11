---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: PrinterMarkAnnotation-Methode. Fügt Druckmarken zu allen Seiten im angegebenen Dokument hinzu
type: docs
weight: 10
url: /de/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Fügt Druckmarken zu allen Seiten im angegebenen Dokument hinzu.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Document | Das Dokument, dem die Druckmarken hinzugefügt werden. |
| marksKind | PrinterMarksKind | Die Art der hinzuzufügenden Druckmarken. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn das *document* null ist. |

## Bemerkungen

Diese Methode fügt verschiedene Arten von Druckmarken basierend auf den bereitgestellten [`PrinterMarksKind`](../../printermarkskind/) Flags hinzu. Wenn None bereitgestellt wird, werden keine Marken hinzugefügt.

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Klasse [PrinterMarkAnnotation](../)
* Namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Fügt Druckmarken zur angegebenen Seite hinzu.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Page | Die Seite, der die Druckmarken hinzugefügt werden. |
| marksKind | PrinterMarksKind | Die Art der hinzuzufügenden Druckmarken. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn die *page* null ist. |

## Bemerkungen

Diese Methode fügt verschiedene Arten von Druckmarken basierend auf den bereitgestellten [`PrinterMarksKind`](../../printermarkskind/) Flags hinzu. Wenn None bereitgestellt wird, werden keine Marken hinzugefügt.

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Klasse [PrinterMarkAnnotation](../)
* Namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../../)