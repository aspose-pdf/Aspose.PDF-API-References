---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de FormEditor. La bandera para indicar si los radios están dispuestos horizontal o verticalmente, el valor predeterminado es verdadero
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## Propiedad FormEditor.RadioHoriz

La bandera para indicar si los radios están dispuestos horizontal o verticalmente, el valor predeterminado es verdadero.

```csharp
public bool RadioHoriz { get; set; }
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