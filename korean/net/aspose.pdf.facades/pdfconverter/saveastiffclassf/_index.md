---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 메서드. PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일로 저장합니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일로 저장합니다.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 스트림입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

## Examples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일로 저장합니다.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일로 저장합니다.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 스트림입니다. |

## Examples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)