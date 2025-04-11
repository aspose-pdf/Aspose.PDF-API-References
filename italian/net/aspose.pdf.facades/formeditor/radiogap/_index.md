---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: Proprietà FormEditor. Il membro per registrare il gap tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/formeditor/radiogap/
---
## Proprietà FormEditor.RadioGap

Il membro per registrare il gap tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50.

```csharp
public float RadioGap { get; set; }
```

## Esempi

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)