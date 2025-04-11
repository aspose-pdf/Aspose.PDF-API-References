---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-metod. Hämta XmpMetadata för den angivna pdf-filen i xml-format
type: docs
weight: 190
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Hämta XmpMetadata för den angivna pdf-filen i xml-format.

```csharp
public byte[] GetXmpMetadata()
```

### Return Value

Bytes av XmpMetadata.

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

Hämta en del av XmpMetadata för den angivna pdf-filen enligt ett meta-namn.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Metadata-namn. |

### Return Value

Bytes av metadata.

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