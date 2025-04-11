---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Erhalten Sie die Einschränkung des Textfelds
type: docs
weight: 230
url: /de/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit-Methode

Erhalten Sie die Einschränkung des Textfelds.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der qualifizierte Feldname. |

### Rückgabewert

Gibt die Anzahl der Zeichen zurück, die in ein Textfeld eingegeben werden können. Wenn nicht festgelegt, wird 0 zurückgegeben.

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)