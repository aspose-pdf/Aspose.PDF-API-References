---
title: "FormEditor.MoveField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。フィールドの新しい位置を設定します。"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

フィールドの新しい位置を設定します。

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 移動する必要があるフィールドの名前です。 |
| llx | Single | フィールドの左下隅の横座標です。 |
| lly | Single | フィールドの左下隅の縦座標です。 |
| urx | Single | フィールドの右上隅の横座標です。 |
| ury | Single | フィールドの右上隅の縦座標です。 |

### 戻り値

フィールドの位置が正常に変更された場合は true です。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


