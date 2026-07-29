---
title: "CheckboxField.Value"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية CheckboxField. تحصل أو تعيين قيمة حقل خانة الاختيار"
type: docs
weight: 70
url: /ar/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

يحصل أو يحدد قيمة حقل خانة الاختيار.

```csharp
public override string Value { get; set; }
```

## أمثلة

يوضح المثال كيفية الحصول على قيمة وتعيينها لخانة اختيار متعددة القيم.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// يمكن استرجاع القيم المسموح بها من مجموعة AllowedStates
// قم بتعيين قيمة خانة الاختيار باستخدام خاصية Value
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// يجب أن تكون القيمة أي عنصر من AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// إلغاء تحديد الصناديق إما بتعيين Value إلى "Off" أو تعيين Checked إلى false
checkbox.Value = "Off";
// أو، بدلاً من ذلك:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### انظر أيضًا

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


