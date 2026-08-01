---
title: "FormEditor.DelListItem"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。リストフィールドから項目を削除します"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

リストフィールドから項目を削除します。

```csharp
public void DelListItem(string fieldName, string itemName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの名前。 |
| itemName | String | 削除すべき項目の名前。 |

## 例

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


