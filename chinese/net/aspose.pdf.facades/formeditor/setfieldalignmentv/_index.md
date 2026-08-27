---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置文本字段的垂直对齐样式"
type: docs
weight: 270
url: /zh/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

设置文本字段的垂直对齐样式。

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完整的字段名称。 |
| 对齐 | Int32 | 对齐样式的定义，包括 FormFieldFacade.AlignTop、FormFieldFacade.AlignMiddle 和 FormFieldFacade.AlignRight。 |

### 返回值

如果找到字段并且对齐成功填充，则为 true。

## 示例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


