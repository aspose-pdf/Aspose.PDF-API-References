---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントにマークアップ注釈を作成します
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup メソッド

PDF ドキュメントにマークアップ注釈を作成します。

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する矩形。 |
| contents | String | 注釈の内容。 |
| type | Int32 | マークアップ注釈の種類。0 (ハイライト)、1 (下線)、2 (取り消し線)、3 (波線) のいずれか。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| clr | Color | マークアップの色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)