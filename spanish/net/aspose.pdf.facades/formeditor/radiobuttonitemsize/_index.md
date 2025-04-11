---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de FormEditor. Obtiene o establece el tamaño del elemento de botón de radio cuando se agrega un nuevo campo de botón de radio
type: docs
weight: 60
url: /es/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## Propiedad FormEditor.RadioButtonItemSize

Obtiene o establece el tamaño del elemento de botón de radio (cuando se agrega un nuevo campo de botón de radio).

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

### Véase también

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)