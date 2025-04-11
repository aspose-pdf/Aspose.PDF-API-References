---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。リストボックスに新しいアイテムを追加します
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

リストボックスに新しいアイテムを追加します。

```csharp
public void AddListItem(string fieldName, string itemName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 新しいアイテムが追加されるフィールドの名前。 |
| itemName | String | 新しいアイテムの名前。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

既存のリストボックスフィールドにエクスポート値を持つ新しいアイテムを追加します。これはAcroFormコンボボックスフィールドのみです。

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | アイテムが追加されるフィールドの名前。 |
| exportName | String[] | エクスポート値を持つ新しいリストアイテムを示す文字列配列、すなわち（アイテムラベル、エクスポート値）。 |

## 例

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)