---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置文本字段的垂直对齐样式
type: docs
weight: 270
url: /zh/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV 方法

设置文本字段的垂直对齐样式。

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 合格的字段名称。 |
| alignment | Int32 | 对齐样式定义，包括 FormFieldFacade.AlignTop、FormFieldFacade.AlignMiddle 和 FormFieldFacade.AlignRight。 |

### 返回值

如果找到字段并成功填充对齐，则返回 true。

## 示例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)