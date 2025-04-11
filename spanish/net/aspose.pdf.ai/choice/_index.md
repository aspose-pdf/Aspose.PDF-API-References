---
title: Class Choice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.Choice. Representa una elección en una respuesta de finalización de chat
type: docs
weight: 200
url: /es/net/aspose.pdf.ai/choice/
---
## Clase Choice

Representa una elección en una respuesta de finalización de chat.

```csharp
public class Choice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Choice](choice/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | Obtiene o establece la razón por la cual el modelo dejó de generar tokens. Esto se detendrá si el modelo alcanza un punto de parada natural o una secuencia de parada proporcionada, longitud si se alcanzó el número máximo de tokens especificado en la solicitud. |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | Obtiene o establece el índice de la elección en la lista de elecciones. |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | Obtiene o establece información de probabilidad logarítmica para la elección. |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | Obtiene o establece un mensaje de finalización de chat generado por el modelo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | Devuelve el contenido de la elección como una cadena. |

### Véase También

* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)