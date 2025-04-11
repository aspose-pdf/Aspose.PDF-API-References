---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtenha o valor de campos de Rich Text, incluindo as informações de formatação de cada caractere
type: docs
weight: 260
url: /pt/net/aspose.pdf.facades/form/getrichtext/
---
## Método Form.GetRichText

Obtenha o valor de um campo de Rich Text, incluindo as informações de formatação de cada caractere.

```csharp
public string GetRichText(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo de Rich Text totalmente qualificado. |

### Valor de Retorno

Retorna uma string contendo informações de formatação do campo de Rich Text.

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)