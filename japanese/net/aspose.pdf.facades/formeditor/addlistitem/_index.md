---
title: "FormEditor.AddListItem"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。リストボックスに新しい項目を追加します"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

リストボックスに新しい項目を追加します。

```csharp
public void AddListItem(string fieldName, string itemName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 新しい項目が追加されるフィールドの名前。 |
| itemName | String | 新しい項目の名前。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

既存のリストボックスフィールドにエクスポート値を持つ新しい項目を追加します（AcroForm コンボボックスフィールドにのみ適用）。

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 項目が追加されるフィールドの名前。 |
| exportName | String[] | エクスポート値を持つ新しいリスト項目を示す文字列配列、例: (項目ラベル, エクスポート値)。 |

## 例

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


