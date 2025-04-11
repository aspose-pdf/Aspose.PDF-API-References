---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de FormEditor. El miembro para registrar el espacio entre dos botones de radio vecinos en píxeles, el valor predeterminado es 50
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/formeditor/radiogap/
---
## Propiedad FormEditor.RadioGap

El miembro para registrar el espacio entre dos botones de radio vecinos en píxeles, el valor predeterminado es 50.

```csharp
public float RadioGap { get; set; }
```

## Ejemplos

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)