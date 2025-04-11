---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Benennt ein Feld um. Entweder AcroForm-Feld oder XFA-Feld ist in Ordnung
type: docs
weight: 330
url: /de/net/aspose.pdf.facades/form/renamefield/
---
## Form.FeldUmbenennen Methode

Benennt ein Feld um. Entweder AcroForm-Feld oder XFA-Feld ist in Ordnung.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | der alte Feldname |
| newFieldName | String | der neue Feldname |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)