---
title: SetFieldAttribute
second_title: Aspose.PDF for .NET API 参考
description: 设置字段属性
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

设置字段属性。

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 应设置属性的字段名称。 |
| flag | PropertyFlag | 标志（NoExport/ReadOnly/必需） |

### 返回值

如果属性设置成功，则为 true。

### 例子

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### 也可以看看

* enum [PropertyFlag](../../propertyflag)
* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
