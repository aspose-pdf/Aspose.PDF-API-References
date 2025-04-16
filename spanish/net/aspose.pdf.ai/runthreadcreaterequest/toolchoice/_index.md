---
title: RunThreadCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de RunThreadCreateRequest. Obtiene o establece qué herramienta, si la hay, es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto es el valor predeterminado y significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas antes de responder al usuario. Especificar una herramienta particular como "type": "file_search" o "type": "function", "function": "name": "my_function" obliga al modelo a llamar a esa herramienta.
type: docs
weight: 120
url: /es/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## Propiedad RunThreadCreateRequest.ToolChoice

Obtiene o establece qué (si la hay) herramienta es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto es el valor predeterminado y significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas antes de responder al usuario. Especificar una herramienta particular como {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta.

```csharp
public string ToolChoice { get; set; }
```

### Ver También

* clase [RunThreadCreateRequest](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../../)