---
title: "Form.RenameField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form metod. Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är OK"
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är godkänt.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | det gamla fältnamnet |
| newFieldName | String | det nya fältnamnet |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


