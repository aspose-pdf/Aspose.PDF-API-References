---
title: ImportXfdf
second_title: Aspose.PDF per .NET API Reference
description: Importa il contenuto dei campi dal file xfdfxml e li inserisce nel nuovo pdf.
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Importa il contenuto dei campi dal file xfdf(xml) e li inserisce nel nuovo pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputXfdfStream | Stream | Il flusso di input xfdf(xml). |

### Esempi

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
