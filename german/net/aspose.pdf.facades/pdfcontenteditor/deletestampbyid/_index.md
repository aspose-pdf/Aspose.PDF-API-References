---
title: DeleteStampById
second_title: Aspose.PDF für .NET-API-Referenz
description: Löscht Stempel auf der angegebenen Seite nach Stempel-ID.
type: docs
weight: 340
url: /de/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Löscht Stempel auf der angegebenen Seite nach Stempel-ID.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Seitenzahl, wo der Stempel gelöscht wird. |
| stampId | Int32 | Bezeichner des zu löschenden Stanps. |

### Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Stempel nach ID von allen Seiten des Dokuments löschen.

```csharp
public void DeleteStampById(int stampId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stampId | Int32 | Kennzeichen des Stempels, der gelöscht werden soll. |

### Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->