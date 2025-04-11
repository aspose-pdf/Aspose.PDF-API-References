---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Retorna as flags de submissão dos botões de envio
type: docs
weight: 270
url: /pt/net/aspose.pdf.facades/form/getsubmitflags/
---
## Método Form.GetSubmitFlags

Retorna as flags de submissão do botão de envio

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo qualificado. |

### Valor de Retorno

Flags de submissão do botão.

## Exemplos

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Veja Também

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)