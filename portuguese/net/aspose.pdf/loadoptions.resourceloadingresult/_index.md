---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LoadOptionsResourceLoadingResult. Resultado do carregamento personalizado de recurso
type: docs
weight: 6150
url: /pt/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## Classe LoadOptions.ResourceLoadingResult

Resultado do carregamento personalizado de recurso

```csharp
public class ResourceLoadingResult
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Cria uma instância do resultado de carregamento |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Dados binários que foram carregados com o carregador personalizado - devem ser definidos após o carregamento |

## Campos

| Nome | Descrição |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Às vezes, a codificação do recurso é conhecida após ou durante o carregamento. Nesse caso, o código personalizado pode fornecer ao conversor esse conhecimento através deste parâmetro. Você pode deixar nulo neste parâmetro se a codificação for desconhecida ou não for relevante. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Às vezes, é impossível carregar o recurso solicitado por algum motivo. A indisponibilidade do recurso muitas vezes não leva a uma falha de conversão e o documento resultante pode ser criado de qualquer maneira (mas talvez em uma qualidade um pouco pior, sem imagens etc.). Se uma exceção ocorrer durante o carregamento, basta capturá-la e colocá-la neste parâmetro - às vezes essa informação é útil para o conversor na renderização do resultado. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Às vezes, por algum motivo, o carregamento não deve ocorrer no código personalizado. Nesse caso, defina este sinalizador como Verdadeiro. Nesse caso, o conversor tentará usar o carregador de recursos padrão interno para obter esse resultado (como se comporta na situação em que a estratégia personalizada não é fornecida). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Às vezes, o conhecimento sobre o tipo MIME do recurso carregado é útil para o conversor. Você pode fornecer o tipo MIME (se for conhecido após o carregamento) neste parâmetro. Por favor, deixe o parâmetro igual a nulo quando o tipo MIME for desconhecido ou não for necessário fornecê-lo. |

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)