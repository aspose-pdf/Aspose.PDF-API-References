---
title: "PdfContentEditor.DeleteStamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。指定されたページ上のスタンプインデックスにより複数のスタンプを削除します。"
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

指定されたページ上でスタンプインデックスで複数のスタンプを削除します。

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | スタンプが削除される Page 番号です。 |
| インデックス | Int32[] | スタンプインデックス。 |

## 例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


