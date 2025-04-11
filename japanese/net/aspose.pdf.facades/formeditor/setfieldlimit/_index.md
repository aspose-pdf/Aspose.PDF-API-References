---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。テキストフィールドの最大文字数を設定します
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit メソッド

テキストフィールドの最大文字数を設定します。

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | テキストフィールドの名前。 |
| fieldLimit | Int32 | フィールドの新しい制限値。 |

### 戻り値

フィールド制限が正常に設定された場合は true。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)