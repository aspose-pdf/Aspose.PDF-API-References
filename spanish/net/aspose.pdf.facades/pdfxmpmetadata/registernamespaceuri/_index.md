---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Registra el URI del espacio de nombres
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## Método PdfXmpMetadata.RegisterNamespaceURI

Registra el URI del espacio de nombres.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | String | El prefijo. |
| namespaceURI | String | El URI del espacio de nombres. |

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Ver También

* clase [PdfXmpMetadata](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)