---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Nesta propriedade você pode atribuir um delegate criado a partir de um método personalizado que implementa o processamento de recurso externo (Fonte ou Imagem) que foi extraído do PDF e deve ser salvo."
type: docs
weight: 2150
url: /pt/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Para esta propriedade você pode atribuir um delegate criado a partir de um método personalizado que implementa o processamento de recurso externo (Fonte ou Imagem) que foi extraído do PDF e deve ser salvo como recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvar em stream ou disco) pode ser feito nesse código personalizado e esse código deve retornar o caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao HTML gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para salvar a imagem devem ser realizadas no código do método fornecido, pois a gravação do resultado no código do conversor não será utilizada. Se o processamento deste ou daquele arquivo, por algum motivo, precisar ser feito pelo código do conversor próprio, e não pelo código personalizado, defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'resourceSavingInfo'. Ela sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas no próprio conversor como se não houvesse nenhum código personalizado externo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Método invocado |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Método invocado
