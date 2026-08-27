---
title: "Form.RenameField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Rinomina un campo. È valido sia un campo AcroForm sia un campo XFA"
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

Rinomina un campo. È valido sia un campo AcroForm sia un campo XFA.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | il nome del campo vecchio |
| newFieldName | String | il nuovo nome del campo |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


