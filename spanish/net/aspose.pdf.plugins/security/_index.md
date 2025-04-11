---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.Security. Representa el plugin de Seguridad
type: docs
weight: 9230
url: /es/net/aspose.pdf.plugins/security/
---
## Clase Seguridad

Representa el plugin `Security`.

```csharp
public sealed class Security : IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Security](security/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Inicia el procesamiento de `Security` con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo encriptar un documento PDF.

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

El ejemplo demuestra cómo desencriptar un documento PDF.

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

### Ver También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)