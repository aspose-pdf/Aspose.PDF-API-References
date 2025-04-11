---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 메서드. PDF 문서에서 다음 이미지를 검색합니다. 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

PDF 문서에서 다음 이미지를 검색합니다. 주의: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | 이미지가 저장될 파일 |

### Return Value

이미지가 성공적으로 추출되면 True입니다.

## Examples

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

주어진 이미지 형식으로 PDF 문서에서 다음 이미지를 검색합니다. 주의: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | 이미지가 저장될 파일 |
| format | ImageFormat | 이미지의 형식입니다. |

### Return Value

이미지가 성공적으로 추출되면 True입니다.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

PDF 파일에서 다음 이미지를 검색하고 주어진 이미지 형식으로 스트림에 저장합니다.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | 이미지 데이터가 저장될 스트림 |
| format | ImageFormat | 이미지의 형식입니다. |

### Return Value

이미지가 성공적으로 추출되면 True입니다.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

PDF 파일에서 다음 이미지를 검색하고 스트림에 저장합니다.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | 이미지 데이터가 저장될 스트림 |

### Return Value

이미지가 성공적으로 추출되면 True입니다.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)