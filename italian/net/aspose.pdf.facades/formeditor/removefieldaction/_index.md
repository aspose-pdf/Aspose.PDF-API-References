---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Rimuovi l'azione di invio del campo
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## Metodo FormEditor.RemoveFieldAction

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

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)