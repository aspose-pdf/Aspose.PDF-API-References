---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: Propriété FormEditor. Le drapeau pour indiquer si les radios sont disposées horizontalement ou verticalement, la valeur par défaut est vraie
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## Propriété FormEditor.RadioHoriz

Le drapeau pour indiquer si les radios sont disposées horizontalement ou verticalement, la valeur par défaut est vraie.

```csharp
public bool RadioHoriz { get; set; }
```

## Exemples

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)