---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. O documento XSLFO de origem pode conter erros de formatação. Este enum enumera as possíveis estratégias de tratamento desses erros de formatação.
type: docs
weight: 11540
url: /pt/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## Enumeração XslFoLoadOptions.ParsingErrorsHandlingTypes

O documento XSLFO de origem pode conter erros de formatação. Este enum enumera as possíveis estratégias de tratamento desses erros de formatação.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| TryIgnore | `0` | Neste caso, o conversor será instruído a tentar prosseguir com a conversão e ignorar os erros de formatação encontrados. Neste caso, o sucesso não é garantido, problemas sérios podem ocorrer mais tarde no conversor, e em tal caso será lançada uma exceção com a lista de erros de formatação encontrados. |
| ThrowExceptionImmediately | `1` | Neste caso, a conversão será interrompida imediatamente e uma exceção será lançada imediatamente após a detecção do primeiro erro de formatação. |
| InvokeCustomHandler | `2` | Este é o método mais ágil - o código personalizado deve fornecer (na propriedade WarningCallback) um manipulador especial que será chamado quando um erro de formatação for detectado. Esse manipulador pode, por exemplo, registrar ou contar erros etc. e fornecerá a decisão sobre se o processamento pode ser continuado para este ou aquele erro. |

### Veja Também

* classe [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)