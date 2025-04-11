---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.LoadOptionsMarginsAreaUsageModes. Representa o modo de uso da área de margens durante a conversão, como HTML, EPUB etc., define o tratamento das instruções do formato importado relacionadas ao uso de margens.
type: docs
weight: 6130
url: /pt/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## Enumeração LoadOptions.MarginsAreaUsageModes

Representa o modo de uso da área de margens durante a conversão (como HTML, EPUB etc.), define o tratamento das instruções do formato importado relacionadas ao uso de margens.

```csharp
public enum MarginsAreaUsageModes
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | Neste modo, o conversor obedece ao formato do documento importado (por exemplo, CSS do HTML importado) no uso da área de margens. Assim, se o formato do documento importado exigir o uso da área de margens para renderização, o conversor permitirá isso. |
| NeverPutContentOnMarginArea | `1` | Este modo proíbe estritamente o uso da área de margens, portanto, o conversor nunca usará a área de margens para renderização, mesmo que o CSS ou o formato do documento de origem permita ou exija isso. |

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)