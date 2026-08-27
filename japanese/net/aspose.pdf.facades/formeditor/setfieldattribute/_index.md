---
title: "FormEditor.SetFieldAttribute"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。フィールドの属性を設定します。"
type: docs
weight: 290
url: /ja/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

フィールドの属性を設定します。

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 属性を設定すべきフィールドの名前。 |
| フラグ | PropertyFlag | フラグ (NoExport/ReadOnly/Required) |

### 戻り値

属性が正常に設定された場合は true です。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### 関連項目

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


