---
title: GetFieldLimit
second_title: Aspose.PDF för .NET API Referens
description: Få textfältets begränsning.
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Få textfältets begränsning.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |

### Returvärde

Returnera begränsningen av antalet tecken ett textfält kan fyllas i. Den är inte inställd, returnera 0.

### Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->