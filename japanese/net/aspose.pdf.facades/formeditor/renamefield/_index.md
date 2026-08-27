---
title: "FormEditor.RenameField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。フィールドの名前を変更します"
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

フィールドの名前を変更します。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの古い名前。 |
| newFieldName | String | フィールドの新しい名前。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


