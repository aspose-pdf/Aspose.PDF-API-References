---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta il flag di invio del pulsante di invio
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## Metodo FormEditor.SetSubmitFlag

Imposta il flag di invio del pulsante di invio.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del pulsante di invio. |
| submitFormFlag | SubmitFormFlag | Flag di invio. |

### Valore di ritorno

true se il campo è stato trovato e il flag di invio è stato impostato con successo.

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