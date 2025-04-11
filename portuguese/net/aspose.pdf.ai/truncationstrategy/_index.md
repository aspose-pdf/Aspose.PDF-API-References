---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.TruncationStrategy. Representa a estratégia de truncamento que controla como um thread será truncado antes da execução
type: docs
weight: 1240
url: /pt/net/aspose.pdf.ai/truncationstrategy/
---
## Classe TruncationStrategy

Representa a estratégia de truncamento que controla como um thread será truncado antes da execução.

```csharp
public class TruncationStrategy
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Obtém ou define o número de mensagens mais recentes do thread ao construir o contexto para a execução. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Obtém ou define a estratégia de truncamento a ser usada para o thread. O padrão é auto. Se definido como last_messages, o thread será truncado para as n mensagens mais recentes no thread. Quando definido como auto, mensagens no meio do thread serão descartadas para se ajustar ao comprimento do contexto do modelo, max_prompt_tokens. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)