---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter メソッド。PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |

## 例

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

### 参照

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 参照

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅、単位はピクセル。 |
| imageHeight | Int32 | 画像の高さ、単位はピクセル。 |

### 参照

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 参照

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF 画像を保存するストリーム。 |

## 例

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

### 参照

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF 画像を保存するストリーム。 |

### 参照

* クラス [PdfConverter](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)