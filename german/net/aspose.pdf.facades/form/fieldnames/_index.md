---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Formulareigenschaft. Gibt die Liste der Feldnamen im Formular zurück
type: docs
weight: 30
url: /de/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames-Eigenschaft

Gibt die Liste der Feldnamen im Formular zurück.

```csharp
public string[] FieldNames { get; }
```

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)