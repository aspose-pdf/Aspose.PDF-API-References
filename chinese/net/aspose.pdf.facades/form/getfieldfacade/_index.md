---
title: "Form.GetFieldFacade"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。返回包含所有外观属性的 FrohmFieldFacade 对象"
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

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
| fieldName | String | 要读取的字段名称。 |

### 返回值

FormFieldFacade 对象

### 另请参见

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


