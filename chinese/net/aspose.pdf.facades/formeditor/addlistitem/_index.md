---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。向列表框添加新项
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

向列表框添加新项。

```csharp
public void AddListItem(string fieldName, string itemName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 要添加新项的字段名称。 |
| itemName | String | 新项的名称。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### 另请参阅

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

向现有列表框字段添加带有导出值的新项，仅适用于 AcroForm 组合框字段。

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 要添加项的字段名称。 |
| exportName | String[] | 表示带有导出值的新列表项的字符串数组，即（项标签，导出值）。 |

## 示例

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### 另请参阅

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)