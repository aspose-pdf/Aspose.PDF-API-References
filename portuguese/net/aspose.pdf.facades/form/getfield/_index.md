---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtém o valor dos campos de acordo com seu nome de campo
type: docs
weight: 200
url: /pt/net/aspose.pdf.facades/form/getfield/
---
## Método Form.GetField

Obtém o valor do campo de acordo com seu nome de campo.

```csharp
public string GetField(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo totalmente qualificado. |

### Valor de Retorno

O valor do campo.

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)