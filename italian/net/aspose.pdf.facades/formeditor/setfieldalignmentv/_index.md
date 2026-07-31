---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta lo stile di allineamento verticale di un campo di testo."
type: docs
weight: 270
url: /it/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Imposta lo stile di allineamento verticale di un campo di testo.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome qualificato del campo. |
| alignment | Int32 | La definizione dello stile di allineamento, includendo FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle e FormFieldFacade.AlignRight. |

### Valore di ritorno

true se il campo è stato trovato e l'allineamento è stato impostato correttamente.

## Esempi

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


