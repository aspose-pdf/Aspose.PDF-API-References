---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.Tool. Representa una herramienta que puede ser llamada por el modelo
type: docs
weight: 1190
url: /es/net/aspose.pdf.ai/tool/
---
## Clase Herramienta

Representa una herramienta que puede ser llamada por el modelo.

```csharp
public class Tool
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Tool](tool/#constructor)() | Inicializa una nueva instancia de la clase `Tool`. |
| [Tool](tool/#constructor_1)(Function) | Inicializa una nueva instancia de la clase `Tool` con la función especificada. |
| [Tool](tool/#constructor_2)(string) | Inicializa una nueva instancia de la clase `Tool` con el tipo de herramienta especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | Obtiene una instancia de herramienta que representa un intérprete de código. |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | Obtiene una instancia de herramienta que representa una herramienta de búsqueda de archivos. |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | Obtiene o establece la función que el modelo puede llamar. |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | Obtiene o establece el tipo de la herramienta. Actualmente, solo se admite función. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | Crea una nueva instancia de herramienta con la función especificada. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)