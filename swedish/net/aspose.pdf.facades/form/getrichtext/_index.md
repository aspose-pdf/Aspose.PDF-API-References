---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Hämta värdet av ett Rich Text-fält inklusive formateringsinformation för varje tecken
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText metod

Hämta värdet av ett Rich Text-fält, inklusive formateringsinformation för varje tecken.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det fullständigt kvalificerade fältnamnet för Rich Text-fältet. |

### Returvärde

Returnerar en sträng som innehåller formateringsinformation för Rich Text-fältet.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)