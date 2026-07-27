---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Para a propriedade desse tipo, você pode atribuir um delegate criado a partir de um método personalizado que implementa o processamento da gravação externa da imagem que foi extraída do SVG criado a partir do PDF."
type: docs
weight: 4730
url: /pt/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Para a propriedade desse tipo, você pode atribuir um delegate criado a partir de um método personalizado que implementa o processamento de salvamento externo de uma imagem que foi extraída de um SVG criado a partir de PDF e deve ser salva como recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvamento feito manualmente em um stream ou em disco) pode ser feito nesse código personalizado e esse código deve retornar o caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao SVG gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para salvar a imagem devem ser realizadas no código do método fornecido, pois o salvamento do resultado no código do conversor não será utilizado. Se o processamento deste ou daquele arquivo, por algum motivo, precisar ser feito pelo próprio código do conversor, e não no código personalizado, por favor defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas no próprio conversor como se não houvesse nenhum código personalizado externo.

## Métodos

| Método | Descrição |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
