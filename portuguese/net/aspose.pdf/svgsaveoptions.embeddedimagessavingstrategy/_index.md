---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Para propriedade de tal tipo, você pode atribuir um delegado criado a partir de um método personalizado que implementa o processamento de salvamento externo de uma imagem que foi extraída de um SVG criado a partir de PDF e deve ser salva como um recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvamento feito à mão em um stream ou no disco) pode ser feito nesse código personalizado e esse código personalizado deve retornar um caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao SVG gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para o salvamento da imagem devem ser realizadas no código do método fornecido, porque o salvamento do resultado no código do conversor não será utilizado. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo código do conversor em si, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todos os passos necessários para o processamento desse recurso devem ser feitos no próprio conversor, como se não houvesse nenhum código personalizado externo. Representa informações sobre a imagem salva que pode ser usada no código personalizado e deve retornar uma string que representa a URL da imagem que será colocada no SVG.
type: docs
weight: 10240
url: /pt/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy

Para propriedade de tal tipo, você pode atribuir um delegado criado a partir de um método personalizado que implementa o processamento de salvamento externo de uma imagem que foi extraída de um SVG criado a partir de PDF e deve ser salva como um recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvamento feito à mão em um stream ou no disco) pode ser feito nesse código personalizado e esse código personalizado deve retornar um caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao SVG gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para o salvamento da imagem devem ser realizadas no código do método fornecido, porque o salvamento do resultado no código do conversor não será utilizado. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo código do conversor em si, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todos os passos necessários para o processamento desse recurso devem ser feitos no próprio conversor, como se não houvesse nenhum código personalizado externo. Representa informações sobre a imagem salva que pode ser usada no código personalizado e deve retornar uma string que representa a URL da imagem que será colocada no SVG.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Veja Também

* classe [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* classe [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)