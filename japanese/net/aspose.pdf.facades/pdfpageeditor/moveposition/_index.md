---
title: "PdfPageEditor.MovePosition"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor メソッド。原点を 0 0 から指定された点へ移動します。原点は左下で、単位はポイント（1 インチ = 72 ポイント）です。"
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

原点を (0, 0) から指定された点へ移動します。原点は左下で、単位はポイントです（1 インチ = 72 ポイント）。

```csharp
public void MovePosition(float moveX, float moveY)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| moveX | Single | X座標。 |
| moveY | Single | Y座標。 |

## 例

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


