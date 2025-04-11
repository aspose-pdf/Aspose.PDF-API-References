---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Security sınıfı. Güvenlik eklentisini temsil eder
type: docs
weight: 9230
url: /tr/net/aspose.pdf.plugins/security/
---
## Güvenlik sınıfı

`Security` eklentisini temsil eder.

```csharp
public sealed class Security : IPlugin
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Security](security/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Belirtilen parametrelerle `Security` işlemini başlatır. |

## Örnekler

Örnek, PDF belgesini nasıl şifreleyeceğini gösterir.

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

Örnek, PDF belgesini nasıl şifre çözme yapacağını gösterir.

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

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)