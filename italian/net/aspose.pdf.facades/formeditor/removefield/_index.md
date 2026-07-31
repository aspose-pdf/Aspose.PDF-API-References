---
title: "FormEditor.RemoveField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Rimuove il campo dal modulo"
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Rimuovi il campo dal modulo.

```csharp
public void RemoveField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo da rimuovere. |

## Esempi

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


