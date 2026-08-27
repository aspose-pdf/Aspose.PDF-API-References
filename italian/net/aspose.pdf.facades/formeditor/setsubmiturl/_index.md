---
title: "FormEditor.SetSubmitUrl"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta l'URL del pulsante"
type: docs
weight: 340
url: /it/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Imposta l'URL del pulsante.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del pulsante di invio. |
| url | String | URL completamente qualificato. |

### Valore di ritorno

true se l'URL per il pulsante è stato impostato correttamente.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


