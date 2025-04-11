---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置常规单行文本字段的组合数量，该字段会自动分为与 combNumber 参数值相等的多个均匀间隔的位置或组合。
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber 方法

设置常规单行文本字段的组合数量（该字段会自动分为与 combNumber 参数值相等的多个均匀间隔的位置或组合）。

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 合格的字段名称。 |
| combNumber | Int32 | 将字段划分为的组合数量。 |

### 返回值

如果成功，返回 true；否则返回 false。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)