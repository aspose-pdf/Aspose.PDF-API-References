---
title: SetSubmitFlag
second_title: Aspose.PDF for .NET API 参考
description: 设置提交按钮的提交标志
type: docs
weight: 370
url: /zh/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

设置提交按钮的提交标志。

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 提交按钮的名称。 |
| submitFormFlag | SubmitFormFlag | 提交标志。 |

### 返回值

如果找到字段并且成功设置了提交标志，则为 true。

### 例子

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### 也可以看看

* enum [SubmitFormFlag](../../submitformflag)
* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->