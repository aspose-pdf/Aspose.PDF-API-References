---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Assinatura. Representa o plugin de Assinatura
type: docs
weight: 9260
url: /pt/net/aspose.pdf.plugins/signature/
---
## Classe Assinatura

Representa o plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Signature](signature/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Inicia o processamento `Signature` com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como assinar um documento PDF.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)