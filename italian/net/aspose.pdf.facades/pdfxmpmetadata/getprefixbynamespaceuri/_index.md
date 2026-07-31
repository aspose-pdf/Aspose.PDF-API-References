---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfXmpMetadata. Ottiene il prefisso per l'URI dello spazio dei nomi"
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

Ottiene il prefisso per l'URI dello spazio dei nomi.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceURI | String | URI dello spazio dei nomi. |

### Valore di ritorno

Il valore del prefisso.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


