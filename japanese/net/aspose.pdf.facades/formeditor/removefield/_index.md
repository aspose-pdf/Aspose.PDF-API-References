---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。フォームからフィールドを削除します
type: docs
weight: 210
url: /ja/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField メソッド

フォームからフィールドを削除します。

```csharp
public void RemoveField(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 削除する必要があるフィールドの名前。 |

## 例

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)