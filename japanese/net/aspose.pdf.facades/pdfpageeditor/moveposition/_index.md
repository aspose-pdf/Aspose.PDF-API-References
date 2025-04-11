---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor メソッド。原点を (0, 0) から指定された点に移動します。原点は左下で、単位はポイント（1 インチ = 72 ポイント）です。
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition メソッド

原点を (0, 0) から指定された点に移動します。原点は左下で、単位はポイント（1 インチ = 72 ポイント）です。

```csharp
public void MovePosition(float moveX, float moveY)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| moveX | Single | X 座標。 |
| moveY | Single | Y 座標。 |

## 例

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### 関連項目

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)