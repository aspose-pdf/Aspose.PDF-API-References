---
title: "FormEditor.SetFieldLimit"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。テキストフィールドの最大文字数を設定します。"
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

テキストフィールドの最大文字数を設定します。

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | テキストフィールドの名前です。 |
| fieldLimit | Int32 | フィールドの制限の新しい値です。 |

### 戻り値

フィールドの制限が正常に設定された場合は true です。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


