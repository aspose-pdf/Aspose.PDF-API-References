---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.Splitter. Representa el plugin Splitter
type: docs
weight: 9280
url: /es/net/aspose.pdf.plugins/splitter/
---
## Clase Splitter

Representa el plugin `Splitter`.

```csharp
public class Splitter : IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Splitter](splitter/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Inicia el procesamiento del `Splitter` con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo dividir un documento PDF.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)