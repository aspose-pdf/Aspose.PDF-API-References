---
title: "Stamp.BindPdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Stamp メソッド。スタンプとして使用する PDF ファイルとページ番号を設定します。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

スタンプとして使用される PDF ファイルとページ番号を設定します。

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pdfFile | String | PDF ファイルへのパスです。 |
| pageNumber | Int32 | PDF ファイル内のページ番号 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//最初のページがスタンプとして使用されます。
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 関連項目

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

スタンプとして使用される PDF ファイルとページ番号を設定します。

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pdfStream | Stream | PDF ドキュメントを含むストリームです。 |
| pageNumber | Int32 | スタンプとして使用されるドキュメントのページインデックス。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//最初のページがスタンプとして使用されます。
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 関連項目

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


