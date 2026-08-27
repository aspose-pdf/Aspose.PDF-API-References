---
title: "FormEditor.SetFieldCombNumber"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置常规单行文本字段的梳子数量，字段会自动按照 combNumber 参数的值划分为等间距的若干位置或梳子。"
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

为常规单行文本字段设置梳子数量（字段会自动划分为与 combNumber 参数值等量的等间距位置，即梳子）。

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完整的字段名称。 |
| combNumber | Int32 | 用于将字段划分的梳子数量。 |

### 返回值

如果成功，返回 true；否则返回 false。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


