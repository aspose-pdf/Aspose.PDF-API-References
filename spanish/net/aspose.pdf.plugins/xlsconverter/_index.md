---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.XlsConverter. Representa el plugin XlsConverter
type: docs
weight: 9450
url: /es/net/aspose.pdf.plugins/xlsconverter/
---
## Clase XlsConverter

Representa el plugin `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XlsConverter](xlsconverter/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementación de IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Inicia el procesamiento de PdfToExcel con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo convertir un documento PDF a XLSX.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)