---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Rimuovi campo dal modulo
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/formeditor/removefield/
---
## Metodo FormEditor.RemoveField

Rimuovi campo dal modulo.

```csharp
public void RemoveField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo che deve essere rimosso. |

## Esempi

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)