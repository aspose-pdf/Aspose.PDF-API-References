---
title: "PdfContentEditor.CreateMarkup"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF Document にマークアップ注釈を作成します。"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

PDF ドキュメントにマークアップ注釈を作成します。

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する Rectangle です。 |
| contents | String | アノテーションの内容です。 |
| タイプ | Int32 | マークアップ注釈のタイプです。0 (ハイライト)、1 (下線)、2 (打ち消し線)、3 (波線) のいずれかにできます。 |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| clr | Color | マークアップの Color です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


