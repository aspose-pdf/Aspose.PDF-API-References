---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.Signature. Representa el plugin de Firma
type: docs
weight: 9260
url: /es/net/aspose.pdf.plugins/signature/
---
## Clase Signature

Representa el plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Signature](signature/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Inicia el procesamiento de `Signature` con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo firmar un documento PDF.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)