---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置提交按钮的提交标志
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag 方法

设置提交按钮的提交标志。

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 提交按钮的名称。 |
| submitFormFlag | SubmitFormFlag | 提交标志。 |

### 返回值

如果找到字段并成功设置提交标志，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### 另请参阅

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)