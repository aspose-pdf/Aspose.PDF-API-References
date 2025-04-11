---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Obtém o prefixo pelo URI do namespace
type: docs
weight: 180
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## Método PdfXmpMetadata.GetPrefixByNamespaceURI

Obtém o prefixo pelo URI do namespace.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| namespaceURI | String | URI do namespace. |

### Valor de Retorno

O valor do prefixo.

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Veja Também

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)