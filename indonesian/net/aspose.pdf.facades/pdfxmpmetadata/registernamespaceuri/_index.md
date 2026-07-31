---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfXmpMetadata. Mendaftarkan URI namespace"
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

Mendaftarkan URI namespace.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | String | Awalan. |
| namespaceURI | String | URI namespace. |

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


