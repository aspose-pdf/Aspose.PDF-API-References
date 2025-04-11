---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Preenche os campos da caixa de texto com valores de texto e salva o documento. Relevante para documentos assinados. Aviso: Somente pode ser aplicado a Caixa de Texto. Tanto os nomes dos campos quanto os valores são sensíveis a maiúsculas e minúsculas.
type: docs
weight: 140
url: /pt/net/aspose.pdf.facades/form/fillfields/
---
## Método Form.FillFields

Preenche os campos da caixa de texto com valores de texto e salva o documento. Relevante para documentos assinados. Aviso: Somente pode ser aplicado a Caixa de Texto. Tanto os nomes dos campos quanto os valores são sensíveis a maiúsculas e minúsculas.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldNames | String[] | Nomes dos campos. |
| fieldValues | String[] | Novos valores dos campos. |
| output | Stream& | Stream onde o documento será salvo. |

### Valor de Retorno

true se os campos foram encontrados e preenchidos com sucesso.

## Exemplos

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)