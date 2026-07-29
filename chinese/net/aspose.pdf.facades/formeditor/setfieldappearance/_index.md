---
title: "FormEditor.SetFieldAppearance"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置字段标志。"
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

设置字段标志

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 应更新标志的字段名称。 |
| flags | AnnotationFlags | 字段的标志。 |

### 返回值

如果标志成功更新则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### 另请参见

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


