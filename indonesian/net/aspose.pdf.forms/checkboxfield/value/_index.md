---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: Properti CheckboxField. Mendapatkan atau mengatur nilai dari bidang kotak centang
type: docs
weight: 70
url: /id/net/aspose.pdf.forms/checkboxfield/value/
---
## Properti CheckboxField.Value

Mendapatkan atau mengatur nilai dari bidang kotak centang.

```csharp
public override string Value { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mendapatkan dan mengatur nilai dari kotak centang multi-nilai.

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

### Lihat Juga

* kelas [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)