---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Gibt ein FrofmFieldFacade-Objekt zurück, das alle Erscheinungsattribute enthält
type: docs
weight: 210
url: /de/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade-Methode

Gibt ein FrofmFieldFacade-Objekt zurück, das alle Erscheinungsattribute enthält.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des zu lesenden Feldes. |

### Rückgabewert

FormFieldFacade-Objekt

### Siehe auch

* Klasse [FormFieldFacade](../../formfieldfacade/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)