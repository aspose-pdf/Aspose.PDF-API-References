---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置文本字段的对齐样式
type: docs
weight: 260
url: /zh/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment 方法

设置文本字段的对齐样式。

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 合格的字段名称。 |
| alignment | Int32 | 对齐样式定义，包括 FormFieldFacade.AlignLeft、FormFieldFacade.AlignCenter 和 FormFieldFacade.AlignRight。 |

### 返回值

如果找到字段并设置了对齐，则返回 true。

## 示例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)