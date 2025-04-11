---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Löscht die angegebenen Bilder auf der angegebenen Seite
type: docs
weight: 320
url: /de/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Löscht die angegebenen Bilder auf der angegebenen Seite.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Nummer der Seite, auf der die Bilder gelöscht werden müssen. |
| index | Int32[] | Ein Array, das die Indizes der Bilder darstellt. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Löscht alle Bilder aus dem PDF-Dokument.

```csharp
public void DeleteImage()
```

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)