---
title: "PdfContentEditor.DeleteStampById"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。指定された Page 上のスタンプをスタンプ ID で削除します。"
type: docs
weight: 340
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

指定されたページ上でスタンプIDによりスタンプを削除します。

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | スタンプが削除される Page 番号です。 |
| stampId | Int32 | 削除すべきスタンプの識別子です。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

ドキュメントのすべてのページからIDでスタンプを削除します。

```csharp
public void DeleteStampById(int stampId)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stampId | Int32 | 削除すべきスタンプの識別子です。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


