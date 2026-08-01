---
title: "PdfConverter.SaveAsTIFFClassF"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfConverter メソッド。PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。"
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF画像を保存するストリーム。 |
| imageWidth | Int32 | 画像の幅（単位はピクセル）。 |
| imageHeight | Int32 | 画像の高さ（単位はピクセル）。 |

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

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF画像を保存するストリーム。 |
| pageSize | PageSize | 画像のページサイズ。 |

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
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

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
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

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | TIFF画像を保存するストリーム。 |

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

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | TIFF画像を保存するストリーム。 |

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


