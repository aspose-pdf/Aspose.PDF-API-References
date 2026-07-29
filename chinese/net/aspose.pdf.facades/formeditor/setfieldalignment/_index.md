---
title: "FormEditor.SetFieldAlignment"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置文本字段的对齐样式"
type: docs
weight: 260
url: /zh/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

设置文本字段的对齐样式。

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完整的字段名称。 |
| 对齐 | Int32 | 对齐样式的定义，包括 FormFieldFacade.AlignLeft、FormFieldFacade.AlignCenter 和 FormFieldFacade.AlignRight。 |

### 返回值

如果找到字段并且已设置对齐，则返回 true。

## 示例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


