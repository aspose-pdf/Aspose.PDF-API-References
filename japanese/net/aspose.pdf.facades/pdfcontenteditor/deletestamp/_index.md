---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。指定されたページのスタンプインデックスによって複数のスタンプを削除します。
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp メソッド

指定されたページのスタンプインデックスによって複数のスタンプを削除します。

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | スタンプが削除されるページ番号。 |
| index | Int32[] | スタンプインデックス。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)