---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF Document 内のカスタムアクションへのリンクを作成します。"
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

PDF ドキュメント内のカスタムアクションへのリンクを作成します。

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| originalPage | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| color | Color | クリック可能な領域の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行することに対応するアクションの配列（PredefinedAction enum のメンバー）。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


