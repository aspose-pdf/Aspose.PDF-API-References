---
title: SetFieldCombNumber
second_title: Aspose.PDF for .NET API 参考
description: 设置常规单行文本字段的梳数字段为 自动划分为等间距位置或梳子 作为 combNumber 参数的值
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

设置常规单行文本字段的梳数（字段为 自动划分为等间距位置或梳子， 作为 combNumber 参数的值）。

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 限定的字段名称。 |
| combNumber | Int32 | 要将字段划分为的梳数。 |

### 返回值

如果成功，则返回 true；否则返回 false。

### 例子

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->