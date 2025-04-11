---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: خاصية CheckboxField. تحصل أو تعين قيمة حقل مربع الاختيار
type: docs
weight: 70
url: /ar/net/aspose.pdf.forms/checkboxfield/value/
---
## خاصية CheckboxField.Value

تحصل أو تعين قيمة حقل مربع الاختيار.

```csharp
public override string Value { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على قيمة مربع اختيار متعدد القيم وتعيينها.

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

### انظر أيضًا

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)