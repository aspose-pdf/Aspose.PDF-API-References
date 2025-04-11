---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes Enum. Das Quell-XSLFO-Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zur Handhabung solcher Formatierungsfehler.
type: docs
weight: 11540
url: /de/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes Aufzählung

Das Quell-XSLFO-Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zur Handhabung solcher Formatierungsfehler.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| TryIgnore | `0` | In diesem Fall wird der Konverter angewiesen, mit der Konvertierung fortzufahren und gefundene Formatierungsfehler zu ignorieren. In diesem Fall ist der Erfolg nicht garantiert, ernsthafte Probleme können später im Konverter auftreten, und in einem solchen Fall wird eine Ausnahme mit einer Liste der gefundenen Formatierungsfehler ausgelöst. |
| ThrowExceptionImmediately | `1` | In diesem Fall wird die Konvertierung sofort gestoppt und eine Ausnahme wird sofort nach der Erkennung des ersten Formatierungsfehlers ausgelöst. |
| InvokeCustomHandler | `2` | Dies ist die agilste Methode - benutzerdefinierter Code muss (in der WarningCallback-Eigenschaft) einen speziellen Handler bereitstellen, der aufgerufen wird, wenn ein Formatierungsfehler erkannt wird. Dieser Handler kann z.B. Fehler protokollieren oder zählen usw. und wird die Entscheidung liefern, ob die Verarbeitung für diesen oder jenen Fehler fortgesetzt werden kann. |

### Siehe auch

* Klasse [XslFoLoadOptions](../xslfoloadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)