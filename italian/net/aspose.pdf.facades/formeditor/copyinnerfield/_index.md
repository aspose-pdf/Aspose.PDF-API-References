---
title: "FormEditor.CopyInnerField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Copia un campo esistente nella stessa posizione del numero di pagina specificato. Verrà prodotto un nuovo documento che contiene tutto ciò che il documento di origine ha, eccetto il campo appena copiato."
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copia un campo esistente nella stessa posizione del numero di pagina specificato. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento di origine possiede, eccetto il campo appena copiato.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il vecchio nome completo del campo. |
| newFieldName | String | Il nuovo nome completo del campo. Se nullo, verrà impostato come fieldName + "~". |
| pageNum | Int32 | Il numero di pagina che conterrà il nuovo campo. Se -1, il nuovo campo verrà copiato nella stessa pagina in cui è ospitato quello vecchio. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Crea una copia del campo di testo nella seconda pagina.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina sia dalle coordinate. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento di origine possiede, eccetto il campo appena copiato.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il vecchio nome completo del campo. |
| newFieldName | String | Il nuovo nome completo del campo. Se nullo, verrà impostato come fieldName + "~". |
| pageNum | Int32 | Il numero di pagina che conterrà il nuovo campo. Se -1, il nuovo campo verrà copiato nella stessa pagina in cui è ospitato quello vecchio. |
| ascissa | Single | L'ascissa del nuovo campo. Se -1, l'ascissa sarà uguale a quella originale. |
| ordinata | Single | L'ordinata del nuovo campo. Se -1, l'ordinata sarà uguale a quella originale. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Crea una copia del campo di testo nella seconda pagina.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


