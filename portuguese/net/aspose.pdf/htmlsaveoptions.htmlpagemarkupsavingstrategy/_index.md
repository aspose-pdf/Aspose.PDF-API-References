---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: O resultado da conversão pode conter uma ou várias páginas HTML que também podem referenciar arquivos externos, como imagens ou fontes. Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implementa o processamento da página HTML obtida (HTML em si) que foi criada durante a conversão. Nesse caso, o processamento (como salvar em stream ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a marcação das páginas HTML devem ser realizadas no código do método fornecido, porque a salvaguarda do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele caso, por algum motivo, deve ser feito pelo próprio código do conversor, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor da mesma forma que se não houvesse nenhum código de salvamento personalizado externo.
type: docs
weight: 5680
url: /pt/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy

O resultado da conversão pode conter uma ou várias páginas HTML (que também podem referenciar arquivos externos, como imagens ou fontes). Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implementa o processamento da página HTML obtida (HTML em si) que foi criada durante a conversão. Nesse caso, o processamento (como salvar em stream ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a marcação da página HTML devem ser realizadas no código do método fornecido, porque a salvaguarda do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele caso, por algum motivo, deve ser feito pelo próprio código do conversor, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor da mesma forma que se não houvesse nenhum código de salvamento personalizado externo.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | representa dados que podem ser usados para salvar ou processar a página HTML fornecida |

### Veja Também

* classe [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)