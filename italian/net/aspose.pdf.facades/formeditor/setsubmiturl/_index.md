---
title: SetSubmitUrl
second_title: Aspose.PDF per .NET API Reference
description: Imposta lURL del pulsante.
type: docs
weight: 380
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
| url | String | URL completo. |

### Valore di ritorno

true se l'URL per il pulsante è stato impostato correttamente.

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
