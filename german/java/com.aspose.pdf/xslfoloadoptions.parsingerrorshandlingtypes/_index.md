---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit solchen Formatierungsfehlern."
type: docs
weight: 5790
url: /de/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit solchen Formatierungsfehlern.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Dies ist die flexibelste Methode – benutzerdefinierter Code muss (in der Eigenschaft WarningCallback) einen speziellen Handler bereitstellen, der aufgerufen wird, wenn ein Formatierungsfehler erkannt wird. Dieser Handler kann z.B. Fehler protokollieren oder zählen usw. und liefert die Entscheidung, ob die Verarbeitung für diesen oder jenen Fehler fortgesetzt werden kann. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | In diesem Fall wird die Konvertierung sofort gestoppt und es wird sofort nach dem Erkennen des ersten Formatierungsfehlers eine Ausnahme ausgelöst. |
| [TryIgnore](#TryIgnore) | In diesem Fall wird der Konverter angewiesen, mit der Konvertierung fortzufahren und gefundene Formatierungsfehler zu ignorieren. In diesem Fall ist der Erfolg nicht garantiert, ernsthafte Probleme können später im Konverter auftreten, und in einem solchen Fall wird eine Ausnahme mit einer Liste der gefundenen Formatierungsfehler ausgelöst. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Dies ist die flexibelste Methode – benutzerdefinierter Code muss (in der Eigenschaft WarningCallback) einen speziellen Handler bereitstellen, der aufgerufen wird, wenn ein Formatierungsfehler erkannt wird. Dieser Handler kann z.B. Fehler protokollieren oder zählen usw. und liefert die Entscheidung, ob die Verarbeitung für diesen oder jenen Fehler fortgesetzt werden kann.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

In diesem Fall wird die Konvertierung sofort gestoppt und es wird sofort nach dem Erkennen des ersten Formatierungsfehlers eine Ausnahme ausgelöst.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

In diesem Fall wird der Konverter angewiesen, mit der Konvertierung fortzufahren und gefundene Formatierungsfehler zu ignorieren. In diesem Fall ist der Erfolg nicht garantiert, ernsthafte Probleme können später im Konverter auftreten, und in einem solchen Fall wird eine Ausnahme mit einer Liste der gefundenen Formatierungsfehler ausgelöst.
