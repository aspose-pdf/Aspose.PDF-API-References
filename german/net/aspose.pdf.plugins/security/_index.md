---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Security-Klasse. Stellt das Sicherheits-Plugin dar
type: docs
weight: 9230
url: /de/net/aspose.pdf.plugins/security/
---
## Sicherheitsklasse

Stellt das `Security`-Plugin dar.

```csharp
public sealed class Security : IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Security](security/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Startet die `Security`-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein PDF-Dokument verschlüsselt.

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

Das Beispiel zeigt, wie man ein PDF-Dokument entschlüsselt.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)