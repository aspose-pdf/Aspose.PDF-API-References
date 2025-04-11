---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Restituisce i flag di invio dei pulsanti di invio
type: docs
weight: 270
url: /it/net/aspose.pdf.facades/form/getsubmitflags/
---
## Metodo Form.GetSubmitFlags

Restituisce i flag di invio del pulsante di invio

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |

### Valore di ritorno

Flag di invio del pulsante.

## Esempi

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Vedi Anche

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)