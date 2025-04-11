---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Defina a flag de envio do botão de envio
type: docs
weight: 330
url: /pt/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## Método FormEditor.SetSubmitFlag

Defina a flag de envio do botão de envio.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do botão de envio. |
| submitFormFlag | SubmitFormFlag | Flag de envio. |

### Valor de Retorno

true se o campo foi encontrado e a flag de envio foi definida com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Veja Também

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)