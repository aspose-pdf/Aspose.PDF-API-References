---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Erhalten Sie den Wert eines Rich-Text-Feldes einschließlich der Formatierungsinformationen jedes Zeichens
type: docs
weight: 260
url: /de/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText-Methode

Erhalten Sie den Wert eines Rich-Text-Feldes, einschließlich der Formatierungsinformationen jedes Zeichens.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname des Rich-Text-Feldes. |

### Rückgabewert

Gibt eine Zeichenfolge zurück, die Formatierungsinformationen des Rich-Text-Feldes enthält.

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)