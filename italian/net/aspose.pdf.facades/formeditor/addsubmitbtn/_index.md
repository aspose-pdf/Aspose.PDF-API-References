---
title: "FormEditor.AddSubmitBtn"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Aggiungi pulsante di invio al modulo"
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Aggiungi un pulsante submit al modulo.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del nuovo pulsante. |
| pagina | Int32 | Pagina in cui verrà posizionato il pulsante. |
| etichetta | String | Didascalia del pulsante. |
| url | String | URL del pulsante di invio. |
| llx | Single | Ascissa dell'angolo inferiore sinistro. |
| lly | Single | Ordinata dell'angolo inferiore sinistro. |
| urx | Single | Ascissa dell'angolo superiore destro. |
| ury | Single | Ordinata dell'angolo superiore destro. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


