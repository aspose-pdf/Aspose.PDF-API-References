---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.Optimizer. Representa el plugin Optimizador
type: docs
weight: 8970
url: /es/net/aspose.pdf.plugins/optimizer/
---
## Clase Optimizador

Representa el plugin `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Optimizer](optimizer/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Inicia el procesamiento del `Optimizer` con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo optimizar un documento PDF.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)