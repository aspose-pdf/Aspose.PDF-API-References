---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.XlsConverter. Representa o plugin XlsConverter
type: docs
weight: 9450
url: /pt/net/aspose.pdf.plugins/xlsconverter/
---
## Classe XlsConverter

Representa o plugin `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [XlsConverter](xlsconverter/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementação de IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Inicia o processamento de PdfToExcel com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como converter um documento PDF para XLSX.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)