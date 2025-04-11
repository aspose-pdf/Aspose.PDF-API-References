---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Remove a ação de envio do campo
type: docs
weight: 220
url: /pt/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## Método FormEditor.RemoveFieldAction

Remove a ação de envio do campo.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)