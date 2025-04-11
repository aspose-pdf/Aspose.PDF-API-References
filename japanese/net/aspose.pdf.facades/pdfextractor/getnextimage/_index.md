---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor メソッド。PDF ドキュメントから次の画像を取得します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

PDF ドキュメントから次の画像を取得します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。

```csharp
public bool GetNextImage(string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像が保存されるファイル |

### 戻り値

画像が正常に抽出された場合は True

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

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

指定された画像形式で PDF ドキュメントから次の画像を取得します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | 画像が保存されるファイル |
| format | ImageFormat | 画像の形式。 |

### 戻り値

画像が正常に抽出された場合は True

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

PDF ファイルから次の画像を取得し、指定された画像形式でストリームに保存します。

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像データが保存されるストリーム |
| format | ImageFormat | 画像の形式。 |

### 戻り値

画像が正常に抽出された場合は True。

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

PDF ファイルから次の画像を取得し、ストリームに保存します。

```csharp
public bool GetNextImage(Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 画像データが保存されるストリーム |

### 戻り値

画像が正常に抽出された場合は True。

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)