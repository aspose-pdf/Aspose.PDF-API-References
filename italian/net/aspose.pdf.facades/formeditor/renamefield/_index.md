---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Cambia il nome del campo
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/formeditor/renamefield/
---
## Metodo FormEditor.RenameField

Cambia il nome del campo.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Vecchio nome del campo. |
| newFieldName | String | Nuovo nome del campo. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)