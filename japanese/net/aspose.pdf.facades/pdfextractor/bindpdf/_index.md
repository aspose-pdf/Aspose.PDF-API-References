---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor メソッド。入力 PDF ファイルをバインドします
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

入力 PDF ファイルをバインドします。

```csharp
public override void BindPdf(string inputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | バインドする PDF ファイル |

## 例

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### 参照

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

ストリームから PDF ドキュメントをバインドします。

```csharp
public override void BindPdf(Stream inputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | PDF ドキュメントデータを含むストリーム |

## 例

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### 参照

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)