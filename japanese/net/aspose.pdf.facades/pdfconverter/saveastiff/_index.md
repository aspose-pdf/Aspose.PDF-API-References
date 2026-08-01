---
title: "PdfConverter.SaveAsTIFF"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfConverter メソッド。PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。"
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル。 |

## 例

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

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 出力ファイル。 |
| compressionType | CompressionType | 圧縮の種類。 |

## 例

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

### 関連項目

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| pageSize | PageSize | 画像のページサイズ。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| compressionType | CompressionType | 圧縮の種類。 |

### 関連項目

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 出力ストリーム。 |
| compressionType | CompressionType | 圧縮の種類。 |

### 関連項目

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| compressionType | CompressionType | 圧縮の種類。 |

### 関連項目

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

PDF ドキュメントの各ページを画像に変換し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

PDF ドキュメントの各ページを画像に変換し、単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |
| settings | TiffSettings | TIFF パラメータを定義する Settings オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


