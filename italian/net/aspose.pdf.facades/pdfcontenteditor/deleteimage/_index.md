---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Elimina le immagini specificate nella pagina specificata
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Elimina le immagini specificate nella pagina specificata.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Il numero della pagina da cui devono essere eliminate le immagini. |
| index | Int32[] | Un array che rappresenta gli indici delle immagini. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Elimina tutte le immagini dal documento PDF.

```csharp
public void DeleteImage()
```

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)