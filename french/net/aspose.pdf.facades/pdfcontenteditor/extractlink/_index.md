---
title: ExtractLink
second_title: Référence de l'API Aspose.PDF pour .NET
description: Extrait la collection dinstances Link contenues dans le document PDF.
type: docs
weight: 370
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Extrait la collection d'instances Link contenues dans le document PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Return_Value

La collection d'objets Link

### Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // fonctionne avec l'instance Link
}
```

### Voir également

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->