---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten, die auch externe Dateien wie Bilder oder Schriftarten referenzieren können. Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung der erhaltenen HTML-Seite, die während der Konvertierung erstellt wurde, implementiert. In diesem Fall kann die Verarbeitung in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Markups der HTML-Seiten im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund im Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'htmlSavingInfo': es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Speichercode gäbe.
type: docs
weight: 5680
url: /de/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy-Delegat

Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten (die auch externe Dateien wie Bilder oder Schriftarten referenzieren können) enthalten. Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung der erhaltenen HTML-Seite (HTML selbst), die während der Konvertierung erstellt wurde, implementiert. In diesem Fall kann die Verarbeitung (wie das Speichern im Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Markups der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund im Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'htmlSavingInfo': es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Speichercode gäbe.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | repräsentiert Daten, die zum Speichern oder Verarbeiten der bereitgestellten HTML-Seite verwendet werden können |

### Siehe auch

* Klasse [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)