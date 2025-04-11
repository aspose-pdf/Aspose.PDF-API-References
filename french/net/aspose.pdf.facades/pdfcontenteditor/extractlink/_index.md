---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Extrait la collection d'instances de Link contenues dans le document PDF
type: docs
weight: 370
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## Méthode PdfContentEditor.ExtractLink

Extrait la collection d'instances de Link contenues dans le document PDF.

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
    // work with Link instance
}
```

### Voir aussi

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)