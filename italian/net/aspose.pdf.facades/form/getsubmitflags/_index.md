---
title: GetSubmitFlags
second_title: Aspose.PDF per .NET API Reference
description: Restituisce i flag di invio del pulsante di invio
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

Restituisce i flag di invio del pulsante di invio

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |

### Valore di ritorno

Flag di presentazione del pulsante.

### Esempi

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Guarda anche

* enum [SubmitFormFlag](../../submitformflag)
* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->