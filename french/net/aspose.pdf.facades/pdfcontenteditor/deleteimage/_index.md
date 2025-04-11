---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Supprime les images spécifiées sur la page spécifiée
type: docs
weight: 320
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Supprime les images spécifiées sur la page spécifiée.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de la page sur laquelle les images doivent être supprimées. |
| index | Int32[] | Un tableau représentant les index des images. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Supprime toutes les images du document PDF.

```csharp
public void DeleteImage()
```

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)