---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Obtiene el URI del espacio de nombres por prefijo
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## Método PdfXmpMetadata.GetNamespaceURIByPrefix

Obtiene el URI del espacio de nombres por prefijo.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | String | El prefijo. |

### Valor de Retorno

URI del espacio de nombres.

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Ver También

* clase [PdfXmpMetadata](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)