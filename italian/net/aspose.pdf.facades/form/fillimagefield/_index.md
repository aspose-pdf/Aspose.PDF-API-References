---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Metodo del modulo. Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Il nome di campo completamente qualificato del campo pulsante immagine. |
| imageFileName | String | Il percorso del file immagine, sia relativo che assoluto va bene. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Sovraccarica la funzione di FillImageField. L'input è uno stream di immagine.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Il nome di campo completamente qualificato. |
| imageStream | Stream | Lo stream dell'immagine. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)