---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。リストフィールドからアイテムを削除します
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem メソッド

リストフィールドからアイテムを削除します。

```csharp
public void DelListItem(string fieldName, string itemName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの名前。 |
| itemName | String | 削除する必要があるアイテムの名前。 |

## 例

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)