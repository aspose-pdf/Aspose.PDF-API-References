---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Holt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen
type: docs
weight: 250
url: /de/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName-Methode

Holt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname. |

### Rückgabewert

Der vollständige Feldname.

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)