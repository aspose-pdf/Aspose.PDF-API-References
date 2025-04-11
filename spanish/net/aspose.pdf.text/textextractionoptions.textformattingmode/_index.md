---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Enum de Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. Define diferentes modos que se pueden utilizar al convertir un documento pdf en texto. Ver clase TextDevice
type: docs
weight: 10900
url: /es/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## Enumeración TextExtractionOptions.TextFormattingMode

Define diferentes modos que se pueden utilizar al convertir un documento pdf en texto. Ver clase !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Pure | `0` | Representa el contenido pdf con un poco de rutinas de formato. |
| Raw | `1` | Representa el contenido pdf tal como está, es decir, sin formato. |
| Flatten | `2` | Representa el contenido pdf posicionando fragmentos de texto por sus coordenadas. Es básicamente similar al modo "Raw". Pero mientras "Raw" se centra en preservar la estructura de los fragmentos de texto (operadores) en un documento, "Flatten" se centra en mantener el texto en el orden en que se lee. |
| MemorySaving | `3` | Extracción con ahorro de memoria. Es casi igual al modo 'Raw' pero funciona un poco más rápido y utiliza menos memoria. |

### Véase también

* clase [TextExtractionOptions](../textextractionoptions/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../)