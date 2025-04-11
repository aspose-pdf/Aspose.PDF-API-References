---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 메서드. 입력 pdf의 XmpMetadata를 xml 형식으로 가져옵니다.
type: docs
weight: 190
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

입력 pdf의 XmpMetadata를 xml 형식으로 가져옵니다.

```csharp
public byte[] GetXmpMetadata()
```

### Return Value

XmpMetadata의 바이트.

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

메타 이름에 따라 입력 pdf의 XmpMetadata의 일부를 가져옵니다.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | 메타데이터 이름. |

### Return Value

메타데이터의 바이트.

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