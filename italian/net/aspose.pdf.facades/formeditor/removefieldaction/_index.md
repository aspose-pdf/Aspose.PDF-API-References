---
title: "FormEditor.RemoveFieldAction"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Rimuove l'azione di submit del campo"
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

Rimuovi l'azione di invio del campo.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


