---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Devuelve las banderas de envío de los botones de envío
type: docs
weight: 270
url: /es/net/aspose.pdf.facades/form/getsubmitflags/
---
## Método Form.GetSubmitFlags

Devuelve las banderas de envío del botón de envío

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo calificado. |

### Valor de Retorno

Banderas de envío del botón.

## Ejemplos

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Ver También

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)