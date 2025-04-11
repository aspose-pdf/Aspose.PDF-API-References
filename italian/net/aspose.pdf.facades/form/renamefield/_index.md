---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Rinomina un campo. Sia il campo AcroForm che il campo XFA vanno bene
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/form/renamefield/
---
## Metodo Form.RenameField

Rinomina un campo. Sia il campo AcroForm che il campo XFA vanno bene.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | il vecchio nome del campo |
| newFieldName | String | il nuovo nome del campo |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)