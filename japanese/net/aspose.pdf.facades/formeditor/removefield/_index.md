---
title: "FormEditor.RemoveField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。フォームからフィールドを削除します"
type: docs
weight: 210
url: /ja/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

フォームからフィールドを削除します。

```csharp
public void RemoveField(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 削除する必要があるフィールドの名前。 |

## 例

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


