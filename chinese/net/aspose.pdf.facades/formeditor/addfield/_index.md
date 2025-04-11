---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。将指定类型的字段添加到表单
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

将指定类型的字段添加到表单。

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | FieldType | 必须添加的字段类型。 |
| fieldName | String | 必须添加的字段名称。 |
| pageNum | Int32 | 新字段必须放置的页码。 |
| llx | Single | 字段左下角的横坐标。 |
| lly | Single | 字段左下角的纵坐标。 |
| urx | Single | 字段右上角的横坐标。 |
| ury | Single | 字段右上角的纵坐标。 |

### 返回值

如果字段成功添加，则返回 true。

## 示例

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### 另请参阅

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

将指定类型的字段添加到表单。

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | FieldType | 必须添加的字段类型。 |
| fieldName | String | 必须添加的字段名称。 |
| initValue | String | 字段的初始值。 |
| pageNum | Int32 | 新字段必须放置的页码。 |
| llx | Single | 字段左下角的横坐标。 |
| lly | Single | 字段左下角的纵坐标。 |
| urx | Single | 字段右上角的横坐标。 |
| ury | Single | 字段右上角的纵坐标。 |

### 返回值

如果字段成功添加，则返回 true。

## 示例

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### 另请参阅

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)