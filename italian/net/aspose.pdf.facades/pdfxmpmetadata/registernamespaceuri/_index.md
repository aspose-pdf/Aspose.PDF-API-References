---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfXmpMetadata. Registra l'URI del namespace
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## Metodo PdfXmpMetadata.RegisterNamespaceURI

Registra l'URI del namespace.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | String | Il prefisso. |
| namespaceURI | String | L'URI del namespace. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Vedi Anche

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)