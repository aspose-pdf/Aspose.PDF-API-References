---
title: "CheckboxField.Value"
second_title: "Aspose.PDF for .NET API 参考"
description: "CheckboxField 属性。获取或设置复选框字段的值。"
type: docs
weight: 70
url: /zh/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

获取或设置复选框字段的值。

```csharp
public override string Value { get; set; }
```

## 示例

此示例演示如何获取和设置多值复选框的值。

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// 允许的值可以从 AllowedStates 集合中检索。
// 使用 Value 属性设置复选框的值。
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// 该值应为 AllowedStates 的任意元素。
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// 通过将 Value 设置为 "Off" 或将 Checked 设置为 false 来取消选中复选框。
checkbox.Value = "Off";
// 或者，或者说：
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### 另请参见

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


