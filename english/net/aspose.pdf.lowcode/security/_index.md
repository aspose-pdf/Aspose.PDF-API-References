---
title: "Security Class"
linktitle: "Security"
articleTitle: "Security"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Security class. Represents Security plugin."
type: docs
weight: 820
url: "/net/aspose.pdf.lowcode/security/"
keywords: "Security, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## Security class

Represents [`Security`](../security/) plugin.

```csharp
public sealed class Security : IPlugin
```

## Examples

The example demonstrates how to encrypt PDF document.

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

The example demonstrates how to decrypt PDF document.

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

## Constructors

| Name | Description |
| --- | --- |
| [Security](security/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/security/process/)(IPluginOptions) | Starts the `Security` processing with the specified parameters. |

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

