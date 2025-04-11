---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Returnerar ett FrofmFieldFacade-objekt som innehåller alla utseendeattribut
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade metod

Returnerar ett FrofmFieldFacade-objekt som innehåller alla utseendeattribut.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fältet som ska läsas. |

### Returvärde

FormFieldFacade-objekt

### Se Även

* klass [FormFieldFacade](../../formfieldfacade/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)