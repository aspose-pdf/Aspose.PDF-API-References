---
title: "FormEditor.CopyOuterField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Copia un campo esistente da un documento PDF a un altro documento mantenendo il numero di pagina originale e le coordinate. Nota: solo per i campi AcroForm, esclusi i radio button."
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate originali. Nota: Solo per campi AcroForm (escluso radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome completo originale del campo. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copia il campo di testo da source.pdf a PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali. Nota: Solo per campi AcroForm (escluso radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome completo originale del campo. |
| pageNum | Int32 | Il numero di pagina che conterrà il nuovo campo. Se -1, il nuovo campo verrà copiato nella stessa pagina in cui è ospitato quello vecchio. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati. Nota: Solo per campi AcroForm (escluso radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome completo originale del campo. |
| pageNum | Int32 | Il numero di pagina che conterrà il nuovo campo. Se -1, il nuovo campo verrà copiato nella stessa pagina in cui è ospitato quello vecchio. |
| ascissa | Single | L'ascissa del nuovo campo. Se -1, l'ascissa sarà uguale a quella originale. |
| ordinata | Single | L'ordinata del nuovo campo. Se -1, l'ordinata sarà uguale a quella originale. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


