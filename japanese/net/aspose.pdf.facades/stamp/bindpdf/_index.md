---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: スタンプメソッド。スタンプとして使用されるPDFファイルとページ番号を設定します。
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

スタンプとして使用されるPDFファイルとページ番号を設定します。

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfFile | String | PDFファイルへのパス。 |
| pageNumber | Int32 | PDFファイル内のページ番号 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 参照

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

スタンプとして使用されるPDFファイルとページ番号を設定します。

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfStream | Stream | PDFドキュメントを含むストリーム。 |
| pageNumber | Int32 | スタンプとして使用されるドキュメントのページインデックス。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 参照

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)