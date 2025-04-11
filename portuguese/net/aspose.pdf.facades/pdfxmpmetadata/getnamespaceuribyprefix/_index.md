---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Obtém o URI do namespace pelo prefixo
type: docs
weight: 170
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## Método PdfXmpMetadata.GetNamespaceURIByPrefix

Obtém o URI do namespace pelo prefixo.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | String | O prefixo. |

### Valor de Retorno

URI do namespace.

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Veja Também

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)