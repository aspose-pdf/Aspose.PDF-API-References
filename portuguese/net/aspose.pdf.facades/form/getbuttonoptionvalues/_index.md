---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Método do Form. Obtém os campos de opção do botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio
type: docs
weight: 190
url: /pt/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Método Form.GetButtonOptionValues

Obtém os campos de opção do botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do Campo |

### Valor de Retorno

Tabela hash de valores de opção indexados pelo nome do item do formulário

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)