---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Security. Representa o plugin de Segurança
type: docs
weight: 9230
url: /pt/net/aspose.pdf.plugins/security/
---
## Classe Segurança

Representa o plugin `Security`.

```csharp
public sealed class Security : IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Security](security/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Inicia o processamento `Security` com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como criptografar um documento PDF.

```csharp
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

O exemplo demonstra como descriptografar um documento PDF.

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
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