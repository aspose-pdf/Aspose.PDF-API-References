---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Ruft die Optionsfelder der Radio-Buttons und die zugehörigen Werte basierend auf dem Feldnamen ab. Diese Methode hat Bedeutung für Gruppen von Radio-Buttons.
type: docs
weight: 190
url: /de/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues-Methode

Ruft die Optionsfelder der Radio-Buttons und die zugehörigen Werte basierend auf dem Feldnamen ab. Diese Methode hat Bedeutung für Gruppen von Radio-Buttons.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Feldname |

### Rückgabewert

Hash-Tabelle der Optionswerte, die nach dem Namen des Formularelements indiziert sind

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)