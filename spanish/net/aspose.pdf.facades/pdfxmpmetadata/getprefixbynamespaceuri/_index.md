---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Obtiene el prefijo por URI de espacio de nombres
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## Método PdfXmpMetadata.GetPrefixByNamespaceURI

Obtiene el prefijo por URI de espacio de nombres.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceURI | String | URI de espacio de nombres. |

### Valor de Retorno

El valor del prefijo.

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Ver También

* clase [PdfXmpMetadata](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)