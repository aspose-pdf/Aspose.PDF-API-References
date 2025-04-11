---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Gibt den aktuellen Wert für Optionsfelder von Radio-Buttons zurück
type: docs
weight: 180
url: /de/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue-Methode

Gibt den aktuellen Wert für Optionsfelder von Radio-Buttons zurück.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Feldname |

### Rückgabewert

String-Wert für die aktuelle Radio-Gruppe-Option. Siehe auch [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)