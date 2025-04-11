---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 메서드. PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일입니다. |

## 예제

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### 참조

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 출력 파일입니다. |
| compressionType | CompressionType | 압축 유형입니다. |

## 예제

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### 참조

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

### 참조

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| compressionType | CompressionType | 압축 유형입니다. |

### 참조

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |
| converter | IIndexBitmapConverter | 외부 변환기입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |

### 참조

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 출력 스트림입니다. |
| compressionType | CompressionType | 압축 유형입니다. |

### 참조

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

### 참조

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| compressionType | CompressionType | 압축 유형입니다. |

### 참조

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

PDF 문서의 각 페이지를 지정된 크기의 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |
| converter | IIndexBitmapConverter | 외부 변환기입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일로 저장합니다.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | TIFF 이미지를 저장할 파일 이름입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |
| converter | IIndexBitmapConverter | 외부 변환기입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 스트림으로 저장합니다.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | TIFF 이미지를 저장할 스트림입니다. |
| settings | TiffSettings | TIFF 매개변수를 정의하는 설정 객체입니다. |
| converter | IIndexBitmapConverter | 외부 변환기입니다. |

### 참조

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)