---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TableGenerator. Representa o plugin TableGenerator da Aspose.PDF
type: docs
weight: 9350
url: /pt/net/aspose.pdf.plugins/tablegenerator/
---
## Classe TableGenerator

Representa o plugin TableGenerator da Aspose.PDF.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TableGenerator](tablegenerator/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementação de IDisposable. Na verdade, não é necessário para TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Inicia o processamento do PdfGenerator com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como adicionar uma tabela a um arquivo PDF.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)