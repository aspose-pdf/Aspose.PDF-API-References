---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: Propriété FormEditor. Obtient ou définit la taille de l'élément bouton radio lorsque un nouveau champ bouton radio est ajouté
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## Propriété FormEditor.RadioButtonItemSize

Obtient ou définit la taille de l'élément bouton radio (lorsqu'un nouveau champ bouton radio est ajouté).

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)