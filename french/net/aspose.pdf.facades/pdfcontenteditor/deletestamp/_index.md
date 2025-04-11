---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Supprime plusieurs tampons sur la page spécifiée par les index de tampon
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## Méthode PdfContentEditor.DeleteStamp

Supprime plusieurs tampons sur la page spécifiée par les index de tampon.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de page où le tampon sera supprimé. |
| index | Int32[] | Index des tampons. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)