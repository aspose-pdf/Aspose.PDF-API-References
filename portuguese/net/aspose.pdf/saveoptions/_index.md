---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SaveOptions. O tipo SaveOptions mantém um nível de abstração sobre opções de salvamento individuais
type: docs
weight: 9870
url: /pt/net/aspose.pdf/saveoptions/
---
## Classe SaveOptions

O tipo SaveOptions mantém um nível de abstração sobre opções de salvamento individuais

```csharp
public abstract class SaveOptions
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache enquanto prepara as páginas aps. Melhora o desempenho da conversão de pdf para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento dos dados. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)