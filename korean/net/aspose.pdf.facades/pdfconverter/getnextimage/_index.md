---
title: "PdfConverter.GetNextImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfConverter 메서드. 이미지를 기본 이미지 형식인 jpeg으로 파일에 저장합니다."
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

이미지를 파일에 기본 이미지 형식 - JPEG으로 저장합니다.

```csharp
public void GetNextImage(string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

이미지를 파일에 지정된 페이지 크기와 기본 이미지 형식 - JPEG으로 저장합니다.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| pageSize | PageSize | 이미지의 페이지 크기. |

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

이미지를 파일에 지정된 이미지 형식으로 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| 포맷 | ImageFormat | 이미지의 형식. |

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

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

이미지를 파일에 지정된 페이지 크기와 이미지 형식으로 저장합니다.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| pageSize | PageSize | 이미지의 페이지 크기. |
| 포맷 | ImageFormat | 이미지의 형식. |

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

이미지를 스트림에 기본 이미지 형식 - JPEG으로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

이미지를 스트림에 지정된 페이지 크기로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| pageSize | PageSize | 이미지의 페이지 크기. |

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

이미지를 스트림에 지정된 이미지 형식으로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| 포맷 | ImageFormat | 이미지의 형식. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

이미지를 스트림에 지정된 페이지 크기로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| pageSize | PageSize | 이미지의 페이지 크기. |
| 포맷 | ImageFormat | 이미지의 형식. |

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

이미지를 파일에 지정된 이미지 형식, 차원 및 품질로 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| 포맷 | ImageFormat | 이미지의 형식. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

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

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

이미지를 스트림에 지정된 이미지 형식, 차원 및 품질로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| 포맷 | ImageFormat | 이미지의 형식. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

이미지를 파일에 지정된 이미지 형식, 이미지 크기 및 품질로 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| 포맷 | ImageFormat | 이미지의 형식. |
| imageWidth | Double | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Double | 이미지 높이, 단위는 픽셀입니다.. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

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

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

이미지를 스트림에 지정된 이미지 형식, 크기 및 품질로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| 포맷 | ImageFormat | 이미지의 형식. |
| imageWidth | Double | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Double | 이미지 높이, 단위는 픽셀입니다. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

이미지를 파일에 지정된 이미지 형식과 차원으로 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| 포맷 | ImageFormat | 이미지의 형식. |
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

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

이미지를 스트림에 지정된 이미지 형식, 크기 및 품질로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| 포맷 | ImageFormat | 이미지의 형식. |
| imageWidth | Int32 | 이미지 너비, 단위는 픽셀입니다. |
| imageHeight | Int32 | 이미지 높이, 단위는 픽셀입니다. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

이미지를 스트림에 지정된 이미지 형식과 품질로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| 포맷 | ImageFormat | 이미지의 형식. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

이미지를 스트림에 지정된 페이지 크기, 이미지 형식 및 품질로 저장합니다.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지를 저장할 스트림. |
| pageSize | PageSize | 이미지의 페이지 크기. |
| 포맷 | ImageFormat | 이미지의 형식. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

이미지를 파일에 지정된 이미지 형식과 품질로 저장합니다.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| 포맷 | ImageFormat | 이미지의 형식. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

이미지를 파일에 지정된 페이지 크기, 이미지 형식 및 품질로 저장합니다.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지를 저장할 파일 경로와 이름. |
| pageSize | PageSize | 이미지의 페이지 크기. |
| 포맷 | ImageFormat | 이미지의 형식. |
| quality | Int32 | JPEG 파일의 품질 (0~100), 0은 가장 낮고 100은 가장 높습니다. |

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


