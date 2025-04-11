---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。フィールドの新しい位置を設定します
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField メソッド

フィールドの新しい位置を設定します。

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 移動する必要があるフィールドの名前。 |
| llx | Single | フィールドの左下隅の横座標。 |
| lly | Single | フィールドの左下隅の縦座標。 |
| urx | Single | フィールドの右上隅の横座標。 |
| ury | Single | フィールドの右上隅の縦座標。 |

### 戻り値

フィールドの位置が正常に変更された場合は true。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)