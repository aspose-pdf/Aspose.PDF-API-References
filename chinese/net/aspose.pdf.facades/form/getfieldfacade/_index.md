---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。返回包含所有外观属性的 FrofmFieldFacade 对象
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade 方法

返回包含所有外观属性的 FrofmFieldFacade 对象。

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 要读取的字段名称。 |

### 返回值

FormFieldFacade 对象

### 另请参阅

* 类 [FormFieldFacade](../../formfieldfacade/)
* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)