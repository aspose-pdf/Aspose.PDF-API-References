---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtém o nome completo do campo de acordo com seu nome curto.
type: docs
weight: 250
url: /pt/net/aspose.pdf.facades/form/getfullfieldname/
---
## Método Form.GetFullFieldName

Obtém o nome completo do campo de acordo com seu nome curto.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo totalmente qualificado. |

### Valor de Retorno

O nome completo do campo.

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)