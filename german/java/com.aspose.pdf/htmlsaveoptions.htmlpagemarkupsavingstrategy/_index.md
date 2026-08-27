---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Das Ergebnis der Konvertierung kann eine oder mehrere HTML‑Seiten enthalten (die ebenfalls externe Dateien wie Bilder oder Schriftarten referenzieren können). Sie können dieser Eigenschaft einen erstellten Delegaten zuweisen."
type: docs
weight: 2110
url: /de/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten (die ebenfalls externe Dateien wie Bilder oder Schriftarten referenzieren können). Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Verarbeitung der erzeugten HTML-Seite (HTML selbst) implementiert, die während der Konvertierung erstellt wurde. In einem solchen Fall kann die Verarbeitung (wie das Speichern in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Markups der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'htmlSavingInfo': Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, so wie es wäre, wenn kein externes benutzerdefiniertes Speichercode vorhanden wäre.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Interne beginInvoke‑Methode. |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Interne endInvoke‑Methode. |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Aufgerufene Methode |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Interne beginInvoke‑Methode.

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Interne endInvoke‑Methode.

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Aufgerufene Methode
