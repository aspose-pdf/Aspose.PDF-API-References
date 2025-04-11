---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Você pode atribuir a esta propriedade uma estratégia personalizada que implementa o processamento e/ou salvamento de uma parte do CSS que foi criada durante a conversão de PDF para HTML. Nesse caso, o processamento, como salvar em stream ou disco, deve ser feito nesse código personalizado.
type: docs
weight: 5590
url: /pt/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## Delegate HtmlSaveOptions.CssSavingStrategy

Você pode atribuir a esta propriedade uma estratégia personalizada que implementa o processamento e/ou salvamento de uma parte do CSS que foi criada durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvar em stream ou disco) deve ser feito nesse código personalizado.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | representa um conjunto de dados que pode ser usado para salvar a parte do CSS fornecida |

### Veja Também

* classe [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)