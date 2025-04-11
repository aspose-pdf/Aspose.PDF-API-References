---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。返回字段的标志
type: docs
weight: 220
url: /zh/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag 方法

返回字段的标志。

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段名称 |

### 返回值

属性标志（只读/必需/不导出）

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### 另请参阅

* 枚举 [PropertyFlag](../../propertyflag/)
* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)