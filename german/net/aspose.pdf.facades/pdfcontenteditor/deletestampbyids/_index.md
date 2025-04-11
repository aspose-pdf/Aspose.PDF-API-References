---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments
type: docs
weight: 350
url: /de/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stampIds | Int32[] | Array von Stempel-IDs. |

## Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Löscht Stempel auf der angegebenen Seite anhand mehrerer Stempel-IDs.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Seitennummer, auf der Stempel gelöscht werden. |
| stampIds | Int32[] | Array von Stempel-IDs. |

## Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)