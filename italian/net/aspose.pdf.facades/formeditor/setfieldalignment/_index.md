---
title: "FormEditor.SetFieldAlignment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta lo stile di allineamento di un campo di testo"
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Imposta lo stile di allineamento di un campo di testo.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome qualificato del campo. |
| alignment | Int32 | Definizione dello stile di allineamento, includendo FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter e FormFieldFacade.AlignRight. |

### Valore di ritorno

true se il campo è stato trovato e l'allineamento è stato impostato.

## Esempi

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


