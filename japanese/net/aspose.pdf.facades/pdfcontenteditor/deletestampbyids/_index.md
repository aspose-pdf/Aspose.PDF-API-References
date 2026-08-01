---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。指定された ID のスタンプをドキュメントのすべてのページから削除します"
type: docs
weight: 350
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

ドキュメントのすべてのページから指定されたIDのスタンプを削除します。

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stampIds | Int32[] | スタンプ ID の配列。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

指定されたページ上で複数のスタンプIDによりスタンプを削除します。

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | スタンプが削除されるページ番号。 |
| stampIds | Int32[] | スタンプ ID の配列。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


