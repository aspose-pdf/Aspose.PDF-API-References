---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di FormEditor. Ottiene o imposta la dimensione dell'elemento del pulsante di opzione quando viene aggiunto un nuovo campo pulsante di opzione
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## Proprietà FormEditor.RadioButtonItemSize

Ottiene o imposta la dimensione dell'elemento del pulsante di opzione (quando viene aggiunto un nuovo campo pulsante di opzione).

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

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)