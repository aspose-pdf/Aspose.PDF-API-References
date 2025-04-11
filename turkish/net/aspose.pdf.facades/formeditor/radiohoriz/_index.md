---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor özelliği. Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini belirtmek için bir bayrak, varsayılan değeri doğrudur.
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz özelliği

Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini belirtmek için bir bayrak, varsayılan değeri doğrudur.

```csharp
public bool RadioHoriz { get; set; }
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