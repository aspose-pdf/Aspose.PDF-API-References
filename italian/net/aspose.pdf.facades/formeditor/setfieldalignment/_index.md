---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta lo stile di allineamento di un campo di testo
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## Metodo FormEditor.SetFieldAlignment

Imposta lo stile di allineamento di un campo di testo.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |
| alignment | Int32 | La definizione dello stile di allineamento, inclusi FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter e FormFieldFacade.AlignRight. |

### Valore di Ritorno

true se il campo è stato trovato e l'allineamento è stato impostato.

## Esempi

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)