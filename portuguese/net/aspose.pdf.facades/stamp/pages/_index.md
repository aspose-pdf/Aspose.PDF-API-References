---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Propriedade Stamp. Obtém ou define um array com números de páginas que serão afetadas pelo carimbo. Se Pages = null, todas as páginas do documento são afetadas.
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/stamp/pages/
---
## Propriedade Stamp.Pages

Obtém ou define um array com números de páginas que serão afetadas pelo carimbo. Se Pages = null, todas as páginas do documento são afetadas.

```csharp
public int[] Pages { get; set; }
```

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)