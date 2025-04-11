---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är okej
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField metod

Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är okej.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | det gamla fältnamnet |
| newFieldName | Sträng | det nya fältnamnet |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)