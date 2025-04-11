---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obter a limitação do campo de texto
type: docs
weight: 230
url: /pt/net/aspose.pdf.facades/form/getfieldlimit/
---
## Método Form.GetFieldLimit

Obter a limitação do campo de texto.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome qualificado do campo. |

### Valor de Retorno

Retorna o número de caracteres que um campo de texto pode ser preenchido. Se não estiver definido, retorna 0.

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)