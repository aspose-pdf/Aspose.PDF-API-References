---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: CheckboxField özelliği. Onay kutusu alanının değerini alır veya ayarlar
type: docs
weight: 70
url: /tr/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value özelliği

Onay kutusu alanının değerini alır veya ayarlar.

```csharp
public override string Value { get; set; }
```

## Örnekler

Örnek, çok değerli bir onay kutusunun değerini nasıl alıp ayarlayacağınızı gösterir.

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

### Ayrıca Bakınız

* sınıf [CheckboxField](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)