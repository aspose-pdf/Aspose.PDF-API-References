---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Extrai a coleção de instâncias de Link contidas no documento PDF
type: docs
weight: 370
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## Método PdfContentEditor.ExtractLink

Extrai a coleção de instâncias de Link contidas no documento PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Valor de Retorno

A coleção de objetos Link

## Exemplos

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

### Veja Também

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)