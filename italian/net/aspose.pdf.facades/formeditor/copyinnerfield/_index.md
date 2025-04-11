---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Copia un campo esistente nella stessa posizione nel numero di pagina specificato. Verrà prodotto un nuovo documento che contiene tutto ciò che ha il documento sorgente tranne il campo copiato di recente
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copia un campo esistente nella stessa posizione nel numero di pagina specificato. Verrà prodotto un nuovo documento, che contiene tutto ciò che ha il documento sorgente tranne il campo copiato di recente.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il vecchio nome del campo completamente qualificato. |
| newFieldName | String | Il nuovo nome del campo completamente qualificato. Se nullo, verrà impostato come fieldName + "~". |
| pageNum | Int32 | Il numero di pagina che conterrà il nuovo campo. Se -1, il nuovo campo sarà copiato nella stessa pagina in cui si trovava il vecchio. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina che dalle ordinate. Verrà prodotto un nuovo documento, che contiene tutto ciò che ha il documento sorgente tranne il campo copiato di recente.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il vecchio nome del campo completamente qualificato. |
| newFieldName | String | Il nuovo nome del campo completamente qualificato. Se nullo, verrà impostato come fieldName + "~". |
| pageNum | Int32 | Il numero di pagina che conterrà il nuovo campo. Se -1, il nuovo campo sarà copiato nella stessa pagina in cui si trovava il vecchio. |
| abscissa | Single | L'ascissa del nuovo campo. Se -1, l'ascissa sarà uguale a quella originale. |
| ordinate | Single | L'ordinata del nuovo campo. Se -1, l'ordinata sarà uguale a quella originale. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)