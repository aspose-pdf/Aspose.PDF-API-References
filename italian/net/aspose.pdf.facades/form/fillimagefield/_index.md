---
title: "Form.FillImageField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Incolla un'immagine sul campo pulsante esistente come sua apparenza in base al nome completo del campo."
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Incolla un'immagine sul campo pulsante esistente come sua apparenza in base al suo nome campo completamente qualificato.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo pulsante immagine. |
| imageFileName | String | Il percorso del file immagine, sia relativo che assoluto, va bene. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Sovraccarica la funzione FillImageField. L'input è uno stream di immagine.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo. |
| imageStream | Stream | Il flusso dell'immagine. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


