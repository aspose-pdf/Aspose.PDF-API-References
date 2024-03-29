---
title: SetFieldAlignmentV
second_title: Aspose.PDF for .NET API 参考
description: 设置文本字段的垂直对齐方式
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

设置文本字段的垂直对齐方式。

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 限定的字段名称。 |
| alignment | Int32 | 对齐方式定义，包括 FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle 和 FormFieldFacade.AlignRight。 |

### 返回值

如果找到字段并且对齐已成功填充，则为 true。

### 例子

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
