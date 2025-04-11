---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.TableGenerator. Representa el plugin TableGenerator de Aspose.PDF
type: docs
weight: 9350
url: /es/net/aspose.pdf.plugins/tablegenerator/
---
## Clase TableGenerator

Representa el plugin TableGenerator de Aspose.PDF.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TableGenerator](tablegenerator/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementación de IDisposable. De hecho, no es necesario para TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Inicia el procesamiento de PdfGenerator con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo agregar una tabla a un archivo PDF.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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