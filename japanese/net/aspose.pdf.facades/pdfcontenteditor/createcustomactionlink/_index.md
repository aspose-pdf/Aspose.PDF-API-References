---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメント内のカスタムアクションへのリンクを作成します。
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink メソッド

PDF ドキュメント内のカスタムアクションへのリンクを作成します。

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| originalPage | Int32 | リンクが作成される矩形がバウンドする元のページの番号。 |
| color | Color | アクティブクリック用の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行するのに対応するアクションの配列 (PredefinedAction 列挙型のメンバー)。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)