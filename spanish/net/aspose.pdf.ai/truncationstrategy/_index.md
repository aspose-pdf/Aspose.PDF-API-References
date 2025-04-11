---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.TruncationStrategy. Representa la estrategia de truncamiento que controla cómo se truncará un hilo antes de la ejecución
type: docs
weight: 1240
url: /es/net/aspose.pdf.ai/truncationstrategy/
---
## Clase TruncationStrategy

Representa la estrategia de truncamiento que controla cómo se truncará un hilo antes de la ejecución.

```csharp
public class TruncationStrategy
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Obtiene o establece el número de mensajes más recientes del hilo al construir el contexto para la ejecución. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Obtiene o establece la estrategia de truncamiento a utilizar para el hilo. El valor por defecto es auto. Si se establece en last_messages, el hilo se truncará a los n mensajes más recientes en el hilo. Cuando se establece en auto, se eliminarán mensajes en el medio del hilo para ajustarse a la longitud del contexto del modelo, max_prompt_tokens. |

### Ver También

* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)