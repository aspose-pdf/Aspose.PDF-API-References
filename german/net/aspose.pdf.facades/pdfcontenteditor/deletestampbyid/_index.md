---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Löscht den Stempel auf der angegebenen Seite nach Stempel-ID
type: docs
weight: 340
url: /de/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Löscht den Stempel auf der angegebenen Seite nach Stempel-ID.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Seitennummer, auf der der Stempel gelöscht wird. |
| stampId | Int32 | Identifikator des Stempels, der gelöscht werden soll. |

## Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Löscht den Stempel nach ID von allen Seiten des Dokuments.

```csharp
public void DeleteStampById(int stampId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stampId | Int32 | Identifikator des Stempels, der gelöscht werden soll. |

## Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)