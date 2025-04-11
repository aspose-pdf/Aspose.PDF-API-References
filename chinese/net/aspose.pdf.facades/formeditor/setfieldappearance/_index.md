---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置字段标志
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance 方法

设置字段标志

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 需要更新标志的字段名称。 |
| flags | AnnotationFlags | 字段的标志。 |

### 返回值

如果标志成功更新，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### 另请参阅

* 枚举 [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)