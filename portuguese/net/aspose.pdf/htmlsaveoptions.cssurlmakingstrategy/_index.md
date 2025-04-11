---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Você pode atribuir a esta propriedade um delegado criado a partir de um método personalizado que implementa a criação da URL do CSS referenciado no documento HTML gerado. Por exemplo, se você quiser fazer o CSS referenciado no HTML, por exemplo, como otherPage.ASPXCssIDzjjkklj, então tal estratégia personalizada deve retornar otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /pt/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## Delegado HtmlSaveOptions.CssUrlMakingStrategy

Você pode atribuir a esta propriedade um delegado criado a partir de um método personalizado que implementa a criação da URL do CSS referenciado no documento HTML gerado. Por exemplo, se você quiser fazer o CSS referenciado no HTML, por exemplo, como "otherPage.ASPX?CssID=zjjkklj", então tal estratégia personalizada deve retornar "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | representa um conjunto de dados que pode ser usado para a geração da URL do CSS |

### Valor de Retorno

deve retornar uma string que representa a URL do CSS ou o modelo da URL

### Veja Também

* classe [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)