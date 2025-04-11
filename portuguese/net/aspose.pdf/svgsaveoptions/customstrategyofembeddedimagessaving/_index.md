---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: Campo SvgSaveOptions. Este campo pode conter a estratégia de salvamento que deve ser usada se presente durante a conversão para o manuseio personalizado de arquivos de imagens externas referenciadas criadas, como BMP ou JPEG incorporados no SVG salvo. Essa estratégia deve processar recursos e retornar uma string que representa o URI desejável do recurso salvo no SVG gerado. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo código do conversor em si, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável de parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor, como se não houvesse nenhum código personalizado externo.
type: docs
weight: 30
url: /pt/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## Campo SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving

Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o manuseio personalizado de arquivos de imagens externas referenciadas criadas (como BMP ou JPEG incorporados) no SVG salvo. Essa estratégia deve processar recursos e retornar uma string que representa o URI desejável do recurso salvo no SVG gerado. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo código do conversor em si, e não no código personalizado, por favor, defina no código personalizado a flag 'CustomProcessingCancelled' da variável de parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor, como se não houvesse nenhum código personalizado externo.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Veja Também

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)