---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Obtenha os XmpMetadata do pdf de entrada em um formato xml
type: docs
weight: 190
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Obtenha os XmpMetadata do pdf de entrada em um formato xml.

```csharp
public byte[] GetXmpMetadata()
```

### Return Value

Os bytes dos XmpMetadata.

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

Obtenha uma parte dos XmpMetadata do pdf de entrada de acordo com um nome de meta.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Nome da metadata. |

### Return Value

Bytes da metadata.

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