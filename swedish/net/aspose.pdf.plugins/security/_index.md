---
title: "Klassen Security"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.Security-klass. Representerar Security‑plugin"
type: docs
weight: 9380
url: /sv/net/aspose.pdf.plugins/security/
---
## Security class

Representerar `Security`‑plugin.

```csharp
public sealed class Security : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Security](security/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Startar `Security`‑bearbetningen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man krypterar PDF-dokumentet.

```csharp
// skapa Security 
var plugin = new Security();
// skapa EncryptionOptions-objekt för att ange instruktioner
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// lägg till indatafilens sökväg
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
// utför processen
plugin.Process(opt);
```

Exemplet visar hur man dekrypterar PDF-dokumentet.

```csharp
// skapa Security 
var plugin = new Security();
// skapa DecryptionOptions-objekt för att ange instruktioner
var opt = new DecryptionOptions("123456"));
// lägg till indatafilens sökväg
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
// utför processen
plugin.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


