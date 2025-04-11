---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ConversionMode do Aspose.Pdf.Plugins. Define o modo de conversão do documento de saída
type: docs
weight: 8500
url: /pt/net/aspose.pdf.plugins/conversionmode/
---
## Enumeração ConversionMode

Define o modo de conversão do documento de saída.

```csharp
public enum ConversionMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| TextBox | `0` | Este modo é rápido e bom para preservar ao máximo a aparência original do arquivo PDF, mas a editabilidade do documento resultante pode ser limitada. |
| Flow | `1` | Modo de reconhecimento completo, o mecanismo realiza agrupamento e análise em múltiplos níveis para restaurar a intenção original do autor do documento e produzir um documento maximamente editável. A desvantagem é que o documento de saída pode parecer diferente do arquivo PDF original. |
| EnhancedFlow | `2` | Um modo Flow alternativo que suporta o reconhecimento de tabelas. |

### Veja Também

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)