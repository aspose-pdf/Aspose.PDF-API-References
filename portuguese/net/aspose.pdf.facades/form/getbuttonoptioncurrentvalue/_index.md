---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Método do Form. Retorna o valor atual para campos de opção de botão de rádio
type: docs
weight: 180
url: /pt/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Método Form.GetButtonOptionCurrentValue

Retorna o valor atual para campos de opção de botão de rádio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do Campo |

### Valor de Retorno

Valor String para a opção atual do grupo de rádio. Veja também [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)