---
title: "Form.GetFieldFacade"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Returnerar FrofmFieldFacade-objekt som innehåller alla utseendeattribut"
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

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
| fieldName | String | Namn på fält att läsa. |

### Returvärde

FormFieldFacade object

### Se även

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


