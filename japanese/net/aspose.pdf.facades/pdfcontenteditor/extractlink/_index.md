---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントに含まれる Link インスタンスのコレクションを抽出します
type: docs
weight: 370
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink メソッド

PDF ドキュメントに含まれる Link インスタンスのコレクションを抽出します。

```csharp
public IList<Annotation> ExtractLink()
```

### 戻り値

Link オブジェクトのコレクション

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### 参照

* クラス [Annotation](../../../aspose.pdf.annotations/annotation/)
* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)