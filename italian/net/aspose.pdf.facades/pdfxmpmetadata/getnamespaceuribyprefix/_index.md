---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfXmpMetadata. Ottiene l'URI del namespace tramite prefisso
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## Metodo PdfXmpMetadata.GetNamespaceURIByPrefix

Ottiene l'URI del namespace tramite prefisso.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | String | Il prefisso. |

### Valore di Ritorno

URI del namespace.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Vedi Anche

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)