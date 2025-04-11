---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes Enum. Stellt den Modus der Nutzung des Randbereichs während der Konvertierung dar, wie HTML EPUB usw. definiert die Behandlung von Anweisungen des importierten Formats in Bezug auf die Nutzung von Rändern.
type: docs
weight: 6130
url: /de/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes Enumeration

Stellt den Modus der Nutzung des Randbereichs während der Konvertierung (wie HTML, EPUB usw.) dar, definiert die Behandlung von Anweisungen des importierten Formats in Bezug auf die Nutzung von Rändern.

```csharp
public enum MarginsAreaUsageModes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | In diesem Modus befolgt der Konverter das Format des importierten Dokuments (z. B. CSS des importierten HTML) bei der Nutzung des Randbereichs. Wenn das Format des importierten Dokuments die Nutzung des Randbereichs für das Rendering erfordert, wird der Konverter dies zulassen. |
| NeverPutContentOnMarginArea | `1` | Dieser Modus verbietet strikt die Nutzung des Randbereichs, sodass der Konverter den Randbereich niemals für das Rendering verwenden wird, selbst wenn CSS oder das Format des Quelldokuments dies zulässt oder erfordert. |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)