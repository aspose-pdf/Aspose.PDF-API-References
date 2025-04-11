---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.TocGenerator. Representa el plugin TocGenerator de Aspose.PDF
type: docs
weight: 9430
url: /es/net/aspose.pdf.plugins/tocgenerator/
---
## Clase TocGenerator

Representa el plugin TocGenerator de Aspose.PDF.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TocGenerator](tocgenerator/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementación de IDisposable. De hecho, no es necesario para TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Inicia el procesamiento de PdfGenerator con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo agregar TOC a un archivo PDF.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)