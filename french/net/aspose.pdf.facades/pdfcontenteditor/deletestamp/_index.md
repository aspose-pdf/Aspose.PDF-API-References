---
title: DeleteStamp
second_title: Référence de l'API Aspose.PDF pour .NET
description: Supprime plusieurs tampons sur la page spécifiée par des index de tampon.
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

Supprime plusieurs tampons sur la page spécifiée par des index de tampon.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de page où le tampon sera supprimé. |
| index | Int32[] | Index des timbres. |

### Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->