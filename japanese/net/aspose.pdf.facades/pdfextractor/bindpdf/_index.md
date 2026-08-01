---
title: "PdfExtractor.BindPdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。入力 PDF ファイルをバインドします"
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

入力PDFファイルをバインドします。

```csharp
public override void BindPdf(string inputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | バインドする PDF ファイル |

## 例

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

ストリームからPDFドキュメントをバインドします。

```csharp
public override void BindPdf(Stream inputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | PDF ドキュメントデータを含むストリーム |

## 例

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


