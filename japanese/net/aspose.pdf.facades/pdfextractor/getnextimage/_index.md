---
title: "PdfExtractor.GetNextImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。PDF ドキュメントから次の画像を取得します。注意：このメソッドを使用する前に ExtractImage を呼び出す必要があります"
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

PDFドキュメントから次の画像を取得します。注: このメソッドを使用する前にExtractImageを呼び出す必要があります。

```csharp
public bool GetNextImage(string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像が保存されるファイル |

### 戻り値

画像が正常に抽出された場合は true が返されます

## 例

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

PDFドキュメントから次の画像を取得し、指定された画像形式で保存します。注: このメソッドを使用する前にExtractImageを呼び出す必要があります。

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | 画像が保存されるファイル |
| フォーマット | ImageFormat | 画像の形式。 |

### 戻り値

画像が正常に抽出された場合は true が返されます

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

PDFファイルから次の画像を取得し、指定された画像形式でストリームに保存します。

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像データが保存されるストリーム |
| フォーマット | ImageFormat | 画像の形式。 |

### 戻り値

画像が正常に抽出された場合は true が返されます

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

PDFファイルから次の画像を取得し、ストリームに保存します。

```csharp
public bool GetNextImage(Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像データが保存されるストリーム |

### 戻り値

画像が正常に抽出された場合は true が返されます

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


