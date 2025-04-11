---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: CheckboxField 属性。获取或设置复选框字段的值
type: docs
weight: 70
url: /zh/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value 属性

获取或设置复选框字段的值。

```csharp
public override string Value { get; set; }
```

## 示例

该示例演示如何获取和设置多值复选框的值。

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Allowed values may be retrieved from the AllowedStates collection
// Set the checkbox value using Value property
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// The value should be any element of AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Uncheck boxes by either setting Value to "Off" or setting Checked to false
checkbox.Value = "Off";
// or, alternately:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### 另请参阅

* 类 [CheckboxField](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)