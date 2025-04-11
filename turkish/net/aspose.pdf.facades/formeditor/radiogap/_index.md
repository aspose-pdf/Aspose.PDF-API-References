---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: FormEditor özelliği. İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydetmek için üye, varsayılan 50'dir.
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap özelliği

İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydetmek için üye, varsayılan 50'dir.

```csharp
public float RadioGap { get; set; }
```

## Örnekler

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)