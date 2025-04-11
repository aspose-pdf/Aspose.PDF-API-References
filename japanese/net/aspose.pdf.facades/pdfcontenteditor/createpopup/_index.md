---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントにポップアップ注釈を作成します。
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup メソッド

PDF ドキュメントにポップアップ注釈を作成します。

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| contents | String | 注釈の内容。 |
| open | Boolean | ポップアップ注釈が最初に表示されるべきかどうかを指定するフラグ。 |
| page | Int32 | 注釈が作成される元のページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)