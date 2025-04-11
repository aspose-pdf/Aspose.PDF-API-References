---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta l'URL del pulsante
type: docs
weight: 340
url: /it/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## Metodo FormEditor.SetSubmitUrl

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

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)