---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. O resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegado criado a partir de um método personalizado que implementa o processamento de uma página HTML que foi criado durante a conversão. Nesse caso, o processamento pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a página HTML devem ser realizadas no código do método fornecido, porque o salvamento do resultado no código do conversor não será utilizado. Se o processamento para este ou aquele caso, por algum motivo, deve ser feito pelo próprio código do conversor, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinalizará ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor, da mesma forma que se não houvesse nenhum código personalizado externo para processamento.
type: docs
weight: 270
url: /pt/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## Campo HtmlSaveOptions.CustomHtmlSavingStrategy

O resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegado criado a partir de um método personalizado que implementa o processamento de uma página HTML (para ser precisamente - markup-HTML, sem arquivos vinculados externos, se houver) que foi criado durante a conversão. Nesse caso, o processamento (como o salvamento do HTML da página em stream ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a página HTML devem ser realizadas no código do método fornecido, porque o salvamento do resultado no código do conversor não será utilizado. Se o processamento para este ou aquele caso, por algum motivo, deve ser feito pelo próprio código do conversor, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinalizará ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor, da mesma forma que se não houvesse nenhum código personalizado externo para processamento.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Veja Também

* delegado [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* classe [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)