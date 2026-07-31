---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfXmpMetadata. Registra l'URI dello spazio dei nomi."
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

Registra l'URI dello spazio dei nomi.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | String | Il prefisso. |
| namespaceURI | String | L'URI dello spazio dei nomi. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


