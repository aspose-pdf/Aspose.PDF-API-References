---
title: "PdfContentEditor.ExtractLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントに含まれる Link インスタンスのコレクションを抽出します。"
type: docs
weight: 370
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

PDFドキュメントに含まれるLinkインスタンスのコレクションを抽出します。

```csharp
public IList<Annotation> ExtractLink()
```

### 戻り値

Link オブジェクトのコレクション。

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // Link インスタンスを操作する。
}
```

### 関連項目

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


