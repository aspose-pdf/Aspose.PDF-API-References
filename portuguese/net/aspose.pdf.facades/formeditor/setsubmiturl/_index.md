---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Define a URL do botão
type: docs
weight: 340
url: /pt/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## Método FormEditor.SetSubmitUrl

Define a URL do botão.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do botão de envio. |
| url | String | URL totalmente qualificada. |

### Valor de Retorno

true se a URL do botão foi definida com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)