---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。指定されたページのスタンプをスタンプ ID によって削除します
type: docs
weight: 340
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

指定されたページのスタンプをスタンプ ID によって削除します。

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | スタンプが削除されるページ番号。 |
| stampId | Int32 | 削除されるスタンプの識別子。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

ドキュメントのすべてのページから ID によってスタンプを削除します。

```csharp
public void DeleteStampById(int stampId)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stampId | Int32 | 削除されるスタンプの識別子。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)