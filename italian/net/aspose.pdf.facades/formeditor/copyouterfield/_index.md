---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina originale e le ordinate. Nota: Solo per i campi AcroForm esclusi i radio box
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina originale e le ordinate. Nota: Solo per i campi AcroForm (esclusi i radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome del campo originale completamente qualificato. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le ordinate originali. Nota: Solo per i campi AcroForm (esclusi i radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome del campo originale completamente qualificato. |
| pageNum | Int32 | Il numero di pagina che ospiterà il nuovo campo. Se -1, il nuovo campo sarà copiato nella stessa pagina in cui si trovava quello vecchio. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le ordinate. Nota: Solo per i campi AcroForm (esclusi i radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome del campo originale completamente qualificato. |
| pageNum | Int32 | Il numero di pagina che ospiterà il nuovo campo. Se -1, il nuovo campo sarà copiato nella stessa pagina in cui si trovava quello vecchio. |
| abscissa | Single | L'ascissa del nuovo campo. Se -1, l'ascissa sarà uguale a quella originale. |
| ordinate | Single | L'ordinata del nuovo campo. Se -1, l'ordinata sarà uguale a quella originale. |

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)