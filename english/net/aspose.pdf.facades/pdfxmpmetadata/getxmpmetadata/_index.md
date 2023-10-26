---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata method. Get the XmpMetadata of the input pdf in a xml format
type: docs
weight: 190
url: /net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Get the XmpMetadata of the input pdf in a xml format.

```csharp
public byte[] GetXmpMetadata()
```

### Return Value

The bytes of the XmpMetadata.

## Examples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Get a part of the XmpMetadata of the input pdf according to a meta name.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Metadata name. |

### Return Value

Bytes of metadata.

## Examples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


