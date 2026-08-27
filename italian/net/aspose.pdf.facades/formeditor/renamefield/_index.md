---
title: "FormEditor.RenameField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Cambia il nome del campo"
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

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

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


