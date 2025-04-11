---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 메서드. 기본 이미지 형식인 jpeg로 이미지를 파일에 저장합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

기본 이미지 형식인 jpeg로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

주어진 페이지 크기와 기본 이미지 형식인 jpeg로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

주어진 이미지 형식으로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| format | ImageFormat | 이미지의 형식입니다. |

## 예제

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

주어진 페이지 크기와 이미지 형식으로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |
| format | ImageFormat | 이미지의 형식입니다. |

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

기본 이미지 형식인 jpeg로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

주어진 페이지 크기로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

주어진 이미지 형식으로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| format | ImageFormat | 이미지의 형식입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

주어진 페이지 크기로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |
| format | ImageFormat | 이미지의 형식입니다. |

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

주어진 이미지 형식, 크기 및 품질로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

## 예제

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

주어진 이미지 형식, 크기 및 품질로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

주어진 이미지 형식, 이미지 크기 및 품질로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| imageWidth | Double | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Double | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

## 예제

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

주어진 이미지 형식, 크기 및 품질로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| imageWidth | Double | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Double | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

주어진 이미지 형식과 크기로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

## 예제

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

주어진 이미지 형식, 크기 및 품질로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

주어진 이미지 형식과 품질로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

주어진 페이지 크기, 이미지 형식 및 품질로 이미지를 스트림에 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

주어진 이미지 형식과 품질로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

### 참조

* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

주어진 페이지 크기, 이미지 형식 및 품질로 이미지를 파일에 저장합니다.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로 및 이름입니다. |
| pageSize | PageSize | 이미지의 페이지 크기입니다. |
| format | ImageFormat | 이미지의 형식입니다. |
| quality | Int32 | Jpeg 파일의 품질 (0~100), 0은 최저, 100은 최고입니다. |

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)