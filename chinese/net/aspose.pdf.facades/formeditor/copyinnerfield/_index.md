---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。将现有字段复制到指定页码的相同位置。将生成一个新文档，该文档包含源文档的所有内容，除了新复制的字段。
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

将现有字段复制到指定页码的相同位置。将生成一个新文档，该文档包含源文档的所有内容，除了新复制的字段。

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 旧的完全限定字段名称。 |
| newFieldName | String | 新的完全限定字段名称。如果为 null，将设置为 fieldName + "~"。 |
| pageNum | Int32 | 用于容纳新字段的页码。如果为 -1，新字段将复制到与旧字段相同的页面。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### 另请参阅

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

将现有字段复制到由页码和坐标指定的新位置。将生成一个新文档，该文档包含源文档的所有内容，除了新复制的字段。

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 旧的完全限定字段名称。 |
| newFieldName | String | 新的完全限定字段名称。如果为 null，将设置为 fieldName + "~"。 |
| pageNum | Int32 | 用于容纳新字段的页码。如果为 -1，新字段将复制到与旧字段相同的页面。 |
| abscissa | Single | 新字段的横坐标。如果为 -1，横坐标将等于原始值。 |
| ordinate | Single | 新字段的纵坐标。如果为 -1，纵坐标将等于原始值。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### 另请参阅

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)