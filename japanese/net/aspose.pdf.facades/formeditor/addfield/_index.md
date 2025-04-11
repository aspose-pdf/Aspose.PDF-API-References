---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。指定されたタイプのフィールドをフォームに追加します
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

指定されたタイプのフィールドをフォームに追加します。

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fieldType | FieldType | 追加する必要があるフィールドのタイプ。 |
| fieldName | String | 追加する必要があるフィールドの名前。 |
| pageNum | Int32 | 新しいフィールドを配置するページ番号。 |
| llx | Single | フィールドの左下隅の横座標。 |
| lly | Single | フィールドの左下隅の縦座標。 |
| urx | Single | フィールドの右上隅の横座標。 |
| ury | Single | フィールドの右上隅の縦座標。 |

### 戻り値

フィールドが正常に追加された場合は true。

## 例

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### 関連項目

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

指定されたタイプのフィールドをフォームに追加します。

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fieldType | FieldType | 追加する必要があるフィールドのタイプ。 |
| fieldName | String | 追加する必要があるフィールドの名前。 |
| initValue | String | フィールドの初期値。 |
| pageNum | Int32 | 新しいフィールドを配置するページ番号。 |
| llx | Single | フィールドの左下隅の横座標。 |
| lly | Single | フィールドの左下隅の縦座標。 |
| urx | Single | フィールドの右上隅の横座標。 |
| ury | Single | フィールドの右上隅の縦座標。 |

### 戻り値

フィールドが正常に追加された場合は true。

## 例

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### 関連項目

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)