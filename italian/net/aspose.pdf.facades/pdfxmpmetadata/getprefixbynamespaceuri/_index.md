---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfXmpMetadata. Ottiene il prefisso tramite URI del namespace
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## Metodo PdfXmpMetadata.GetPrefixByNamespaceURI

Ottiene il prefisso tramite URI del namespace.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceURI | String | URI del namespace. |

### Valore di Ritorno

Il valore del prefisso.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Vedi Anche

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)