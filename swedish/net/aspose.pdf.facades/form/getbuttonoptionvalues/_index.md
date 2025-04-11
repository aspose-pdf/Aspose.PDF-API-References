---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Hämtar alternativfälten för radioknappar och relaterade värden baserat på fältnamnet. Denna metod har betydelse för grupper av radioknappar
type: docs
weight: 190
url: /sv/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues metod

Hämtar alternativfälten för radioknappar och relaterade värden baserat på fältnamnet. Denna metod har betydelse för grupper av radioknappar.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Fältnamn |

### Returvärde

Hash-tabell av alternativvärden indexerade efter formulärobjektnamn

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)