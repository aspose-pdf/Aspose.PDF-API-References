---
title: "Form.GetFieldFlag"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。返回字段的标志"
type: docs
weight: 220
url: /zh/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

返回字段的标志。

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段名称 |

### 返回值

属性标志（ReadOnly / Required / NoExport

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### 另请参见

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


