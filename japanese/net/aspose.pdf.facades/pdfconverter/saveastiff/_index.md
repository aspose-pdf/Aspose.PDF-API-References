---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter メソッド。PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile)
```

| パラメータ | 型 | 説明 |
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

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| パラメータ | 型 | 説明 |
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

* 列挙 [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| pageSize | PageSize | 画像のページサイズ。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| compressionType | CompressionType | 圧縮の種類。 |

### 関連項目

* 列挙 [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* インターフェース [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 出力ストリーム。 |
| compressionType | CompressionType | 圧縮の種類。 |

### 関連項目

* 列挙 [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |

### 関連項目

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |

### 関連項目

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| compressionType | CompressionType | 圧縮の種類。 |

### 関連項目

* 列挙 [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

PDF ドキュメントの各ページを指定された寸法の画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* インターフェース [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するファイル名 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* インターフェース [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| settings | TiffSettings | TIFF パラメータを定義する設定オブジェクト。 |
| converter | IIndexBitmapConverter | 外部コンバータ |

### 関連項目

* クラス [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* インターフェース [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---