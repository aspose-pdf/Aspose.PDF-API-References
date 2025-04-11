---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. Define diferentes modos que podem ser usados ao converter um documento pdf em texto. Veja a classe TextDevice
type: docs
weight: 10900
url: /pt/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## Enumeração TextExtractionOptions.TextFormattingMode

Define diferentes modos que podem ser usados ao converter um documento pdf em texto. Veja a classe !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Pure | `0` | Representa o conteúdo pdf com um pouco de rotinas de formatação. |
| Raw | `1` | Representa o conteúdo pdf como está, ou seja, sem formatação. |
| Flatten | `2` | Representa o conteúdo pdf com fragmentos de texto posicionados por suas coordenadas. É basicamente semelhante ao modo "Raw". Mas enquanto "Raw" foca em preservar a estrutura dos fragmentos de texto (operadores) em um documento, "Flatten" foca em manter o texto na ordem em que é lido. |
| MemorySaving | `3` | Extração com economia de memória. É quase o mesmo que o modo 'Raw', mas funciona um pouco mais rápido e usa menos memória. |

### Veja Também

* classe [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)