---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.Merger. Representa el plugin Merger
type: docs
weight: 8940
url: /es/net/aspose.pdf.plugins/merger/
---
## Clase Merger

Representa el plugin `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Merger](merger/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Inicia el procesamiento de `Merger` con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo fusionar dos documentos PDF.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)