---
title: GetField
second_title: Aspose.PDF für .NET-API-Referenz
description: Ruft den Wert des Felds gemäß seinem Feldnamen ab.
type: docs
weight: 230
url: /de/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Ruft den Wert des Felds gemäß seinem Feldnamen ab.

```csharp
public string GetField(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollständig qualifizierte Feldname. |

### Rückgabewert

Der Wert des Felds.

### Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Siehe auch

* class [Form](../../form)
* namensraum [Aspose.Pdf.Facades](../../form)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->