---
title: "PdfContentEditor.ExtractLink"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Extrait la collection d'instances Link contenues dans le document PDF"
type: docs
weight: 370
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Extrait la collection d'instances Link contenues dans le document PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Valeur de retour

La collection d'objets Link

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // travailler avec l'instance Link
}
```

### Voir aussi

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


