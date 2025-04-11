---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Form-metod. Hämtar det fullständiga fältnamnet enligt dess korta fältnamn
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName metod

Hämtar det fullständiga fältnamnet enligt dess korta fältnamn.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullt kvalificerade fältnamnet. |

### Returvärde

Det fullständiga fältnamnet.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)