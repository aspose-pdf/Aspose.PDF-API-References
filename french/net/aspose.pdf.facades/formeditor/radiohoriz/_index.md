---
title: "FormEditor.RadioHoriz"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété FormEditor. Indicateur indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est true"
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

Le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


