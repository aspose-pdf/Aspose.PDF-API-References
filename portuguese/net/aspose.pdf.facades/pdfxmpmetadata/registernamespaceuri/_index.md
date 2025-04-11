---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Registra o URI do namespace
type: docs
weight: 200
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## Método PdfXmpMetadata.RegisterNamespaceURI

Registra o URI do namespace.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | String | O prefixo. |
| namespaceURI | String | O URI do namespace. |

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Veja Também

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)