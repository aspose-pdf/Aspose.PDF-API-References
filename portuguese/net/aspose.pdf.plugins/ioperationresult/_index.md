---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.Plugins.IOperationResult. Interface geral de resultado de operação que define métodos comuns que o resultado da operação do plugin concreto deve implementar
type: docs
weight: 8850
url: /pt/net/aspose.pdf.plugins/ioperationresult/
---
## Interface IOperationResult

Interface geral de resultado de operação que define métodos comuns que o resultado da operação do plugin concreto deve implementar.

```csharp
public interface IOperationResult
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Obtém dados brutos. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Indica se o resultado é um caminho para um arquivo de saída. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Indica se o resultado é um fluxo de saída. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Indica se o resultado é uma string de texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Tenta converter o resultado para o arquivo. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Tenta converter o resultado para o objeto de fluxo. |

### Veja Também

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)