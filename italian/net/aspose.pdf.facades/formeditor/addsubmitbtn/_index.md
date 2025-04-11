---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Aggiungi pulsante di invio al modulo
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## Metodo FormEditor.AddSubmitBtn

Aggiungi pulsante di invio al modulo.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del nuovo pulsante. |
| page | Int32 | Pagina in cui verrà posizionato il pulsante. |
| label | String | Etichetta del pulsante. |
| url | String | URL del pulsante di invio. |
| llx | Single | Ascissa dell'angolo in basso a sinistra. |
| lly | Single | Ordinata dell'angolo in basso a sinistra. |
| urx | Single | Ascissa dell'angolo in alto a destra. |
| ury | Single | Ordinata dell'angolo in alto a destra. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)