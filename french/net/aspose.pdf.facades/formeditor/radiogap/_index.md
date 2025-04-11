---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: Propriété FormEditor. Le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, par défaut 50
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/formeditor/radiogap/
---
## Propriété FormEditor.RadioGap

Le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, par défaut 50.

```csharp
public float RadioGap { get; set; }
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