---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de FormEditor. Establece opciones para el cuadro combinado con valores de exportación
type: docs
weight: 30
url: /es/net/aspose.pdf.facades/formeditor/exportitems/
---
## Propiedad FormEditor.ExportItems

Establece opciones para el cuadro combinado con valores de exportación.

```csharp
public string[][] ExportItems { get; set; }
```

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)