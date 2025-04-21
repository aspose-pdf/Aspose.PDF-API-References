---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Para esta propriedade, você pode atribuir um delegado criado a partir de um método personalizado que implementa o processamento de recurso externo que foi extraído do PDF e deve ser salvo como recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento pode ser feito nesse código personalizado e esse código personalizado deve retornar um caminho que será posteriormente incorporado ao HTML gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para salvar a imagem devem ser realizadas no código do método fornecido, porque a salvaguarda do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo próprio código do conversor, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'resourceSavingInfo'. Isso sinaliza ao conversor que todos os passos necessários para o processamento desse recurso devem ser feitos no próprio conversor, como se não houvesse nenhum código personalizado externo.
type: docs
weight: 5730
url: /pt/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## Delegate HtmlSaveOptions.ResourceSavingStrategy

Para esta propriedade, você pode atribuir um delegado criado a partir de um método personalizado que implementa o processamento de recurso externo (Fonte ou Imagem) que foi extraído do PDF e deve ser salvo como recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvar em stream ou disco) pode ser feito nesse código personalizado e esse código personalizado deve retornar um caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao HTML gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para salvar a imagem devem ser realizadas no código do método fornecido, porque a salvaguarda do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo próprio código do conversor, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'resourceSavingInfo'. Isso sinaliza ao conversor que todos os passos necessários para o processamento desse recurso devem ser feitos no próprio conversor, como se não houvesse nenhum código personalizado externo.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | representa um conjunto de dados para salvaguarda de recurso |

### Valor de Retorno

deve retornar a URL para o recurso salvo que será usado durante a geração do HTML

### Veja Também

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)