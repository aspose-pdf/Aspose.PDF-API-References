---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Mendaftarkan URI namespace
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## Metode PdfXmpMetadata.RegisterNamespaceURI

Mendaftarkan URI namespace.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | String | Prefix. |
| namespaceURI | String | URI namespace. |

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Lihat Juga

* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)