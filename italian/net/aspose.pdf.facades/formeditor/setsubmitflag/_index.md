---
title: "FormEditor.SetSubmitFlag"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta il flag di invio del pulsante di submit"
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Imposta il flag di submit del pulsante submit.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del pulsante di submit. |
| submitFormFlag | SubmitFormFlag | Flag di submit. |

### Valore di ritorno

true se il campo è stato trovato e il flag di invio è stato impostato correttamente.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Vedi anche

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


