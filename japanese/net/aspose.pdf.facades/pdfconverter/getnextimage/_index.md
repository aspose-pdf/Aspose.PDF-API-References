---
title: "PdfConverter.GetNextImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfConverter メソッド。画像をデフォルトの画像形式 jpeg でファイルに保存します。"
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

画像をファイルに保存します（デフォルトの画像形式 - jpeg）。

```csharp
public void GetNextImage(string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

画像をファイルに保存します（指定されたページサイズとデフォルトの画像形式 - jpeg）。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

画像をファイルに保存します（指定された画像形式）。

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| フォーマット | ImageFormat | 画像の形式。 |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

画像をファイルに保存します（指定されたページサイズと画像形式）。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| pageSize | PageSize | 画像のページサイズ。 |
| フォーマット | ImageFormat | 画像の形式。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

画像をストリームに保存します（デフォルトの画像形式 - jpeg）。

```csharp
public void GetNextImage(Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

画像をストリームに保存します（指定されたページサイズ）。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

画像をストリームに保存します（指定された画像形式）。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| フォーマット | ImageFormat | 画像の形式。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

画像をストリームに保存します（指定されたページサイズ）。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |
| フォーマット | ImageFormat | 画像の形式。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

画像をファイルに保存します（指定された画像形式、寸法、品質）。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| フォーマット | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

画像をストリームに保存します（指定された画像形式、寸法、品質）。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| フォーマット | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

画像をファイルに保存します（指定された画像形式、画像サイズ、品質）。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| フォーマット | ImageFormat | 画像の形式。 |
| imageWidth | Double | 画像の幅（単位はピクセル）。 |
| imageHeight | Double | 画像の高さ（単位はピクセル）。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

画像をストリームに保存します（指定された画像形式、サイズ、品質）。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| フォーマット | ImageFormat | 画像の形式。 |
| imageWidth | Double | 画像の幅（単位はピクセル）。 |
| imageHeight | Double | 画像の高さ（単位はピクセル）。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

画像をファイルに保存します（指定された画像形式と寸法）。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| フォーマット | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

画像をストリームに保存します（指定された画像形式、サイズ、品質）。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| フォーマット | ImageFormat | 画像の形式。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

画像をストリームに保存します（指定された画像形式と品質）。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| フォーマット | ImageFormat | 画像の形式。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

画像をストリームに保存します（指定されたページサイズ、画像形式、品質）。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |
| フォーマット | ImageFormat | 画像の形式。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

画像をファイルに保存します（指定された画像形式と品質）。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| フォーマット | ImageFormat | 画像の形式。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

画像をファイルに保存します（指定されたページサイズ、画像形式、品質）。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像を保存するファイルのパスと名前。 |
| pageSize | PageSize | 画像のページサイズ。 |
| フォーマット | ImageFormat | 画像の形式。 |
| quality | Int32 | JPEG ファイルの品質 (0~100)、0 が最低で 100 が最高です。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


