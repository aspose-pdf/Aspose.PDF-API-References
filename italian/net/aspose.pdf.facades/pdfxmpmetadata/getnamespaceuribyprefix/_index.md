---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfXmpMetadata metodo. Ottiene l'URI dello spazio dei nomi per prefisso"
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

Ottiene l'URI dello spazio dei nomi per prefisso.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | String | Il prefisso. |

### Valore di ritorno

URI dello spazio dei nomi.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


