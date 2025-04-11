---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter メソッド。デフォルトの画像形式で画像をファイルに保存します - jpeg
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

デフォルトの画像形式 - jpeg で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

指定されたページサイズとデフォルトの画像形式 - jpeg で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

指定された画像形式で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| format | ImageFormat | 画像の形式。 |

## 例

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

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

指定されたページサイズと画像形式で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| pageSize | PageSize | 画像のページサイズ。 |
| format | ImageFormat | 画像の形式。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

デフォルトの画像形式 - jpeg で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

指定されたページサイズで画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

指定された画像形式で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| format | ImageFormat | 画像の形式。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

指定されたページサイズで画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |
| format | ImageFormat | 画像の形式。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

指定された画像形式、寸法、および品質で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| format | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

## 例

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

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

指定された画像形式、寸法、および品質で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| format | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

指定された画像形式、画像サイズ、および品質で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| format | ImageFormat | 画像の形式。 |
| imageWidth | Double | 画像の幅、単位はピクセル。 |
| imageHeight | Double | 画像の高さ、単位はピクセル。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

## 例

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

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

指定された画像形式、サイズ、および品質で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| format | ImageFormat | 画像の形式。 |
| imageWidth | Double | 画像の幅、単位はピクセル。 |
| imageHeight | Double | 画像の高さ、単位はピクセル。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

指定された画像形式と寸法で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| format | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |

## 例

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

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

指定された画像形式、サイズ、および品質で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| format | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

指定された画像形式と品質で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| format | ImageFormat | 画像の形式。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

指定されたページサイズ、画像形式、および品質で画像をストリームに保存します。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |
| format | ImageFormat | 画像の形式。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

指定された画像形式と品質で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| format | ImageFormat | 画像の形式。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

指定されたページサイズ、画像形式、および品質で画像をファイルに保存します。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| pageSize | PageSize | 画像のページサイズ。 |
| format | ImageFormat | 画像の形式。 |
| quality | Int32 | Jpegファイルの品質 (0~100)、0が最低、100が最高 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)