---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Hämta begränsningen av textfält
type: docs
weight: 230
url: /sv/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit metod

Hämta begränsningen av textfält.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det kvalificerade fältnamnet. |

### Returvärde

Returnerar begränsningsnumret för tecken som ett textfält kan fyllas med. Om det inte är inställt, returnera 0.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)