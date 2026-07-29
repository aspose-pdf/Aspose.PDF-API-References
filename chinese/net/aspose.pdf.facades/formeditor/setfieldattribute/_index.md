---
title: "FormEditor.SetFieldAttribute"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置字段的属性"
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

设置字段的属性。

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 应设置属性的字段名称。 |
| 标志 | PropertyFlag | 标志（NoExport/ReadOnly/Required） |

### 返回值

如果属性成功设置，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### 另请参见

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


