---
title: CopyOuterField
second_title: Aspose.PDF per .NET API Reference
description: Copia un campo esistente da un documento PDF a un altro documento con numero di pagina e ordinate originali. Avviso solo per i campi AcroForm escluso il box radio.
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copia un campo esistente da un documento PDF a un altro documento con numero di pagina e ordinate originali. Avviso: solo per i campi AcroForm (escluso il box radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome del campo completo originale. |

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//come cercare il campo in base al suo nome parziale:
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le ordinate originali. Avviso: solo per i campi AcroForm (escluso il box radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome del campo completo originale. |
| pageNum | Int32 | Il numero di pagine in cui contenere il nuovo campo. Se -1, il nuovo campo verrà copiato sulla stessa pagina di quello vecchio ospitato. |

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le ordinate specificati. Avviso: solo per i campi AcroForm (escluso il box radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del documento PDF che contiene il campo da copiare. |
| fieldName | String | Il nome del campo completo originale. |
| pageNum | Int32 | Il numero di pagine in cui contenere il nuovo campo. Se -1, il nuovo campo verrà copiato sulla stessa pagina di quello vecchio ospitato. |
| abscissa | Single | L'ascissa del nuovo campo. Se -1, l'ascissa sarà uguale a quella originale. |
| ordinate | Single | L'ordinata del nuovo campo. Se -1, l'ordinata sarà uguale a quella originale. |

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
