---
title: FillImageField
second_title: Aspose.PDF per .NET API Reference
description: Incolla unimmagine nel campo del pulsante esistente come aspetto in base a il nome del campo completo.
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Incolla un'immagine nel campo del pulsante esistente come aspetto in base a il nome del campo completo.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completo del campo del pulsante dell'immagine. |
| imageFileName | String | Il percorso del file immagine, relativo e assoluto, sono entrambi ok. |

### Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Funzione di sovraccarico di FillImageField. L'input è un flusso di immagini.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completo. |
| imageStream | Stream | Il flusso dell'immagine. |

### Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
