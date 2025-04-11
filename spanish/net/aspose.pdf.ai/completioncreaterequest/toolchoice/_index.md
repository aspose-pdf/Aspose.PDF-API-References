---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Propiedad CompletionCreateRequest. Obtiene o establece un objeto que controla qué herramienta, si es que hay alguna, es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas. Especificar una herramienta particular a través de {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta. none es el valor predeterminado cuando no hay herramientas presentes. auto es el valor predeterminado si hay herramientas presentes.
type: docs
weight: 150
url: /es/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## Propiedad CompletionCreateRequest.ToolChoice

Obtiene o establece un objeto que controla qué (si es que hay alguna) herramienta es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas. Especificar una herramienta particular a través de {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta. none es el valor predeterminado cuando no hay herramientas presentes. auto es el valor predeterminado si hay herramientas presentes.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Ver También

* clase [ToolChoice](../../toolchoice/)
* clase [CompletionCreateRequest](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)