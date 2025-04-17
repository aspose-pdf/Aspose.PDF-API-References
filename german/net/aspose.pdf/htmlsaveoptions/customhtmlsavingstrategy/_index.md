---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions-Feld. Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten. Sie können dieser Eigenschaft ein Delegat zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer HTML-Seite implementiert, die während der Konvertierung erstellt wurde. In diesem Fall kann die Verarbeitung in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund im Code des Konverters selbst und nicht im benutzerdefinierten Code erfolgen muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'htmlSavingInfo' Es wird dem Konverter signalisieren, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code zur Verarbeitung gäbe.
type: docs
weight: 270
url: /de/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy-Feld

Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten. Sie können dieser Eigenschaft ein Delegat zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer HTML-Seite implementiert (um genau zu sein - Markup-HTML, ohne externe verlinkte Dateien, falls vorhanden), die während der Konvertierung erstellt wurde. In diesem Fall kann die Verarbeitung (wie das Speichern der HTML-Seite im Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund im Code des Konverters selbst und nicht im benutzerdefinierten Code erfolgen muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'htmlSavingInfo': Es wird dem Konverter signalisieren, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code zur Verarbeitung gäbe.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Siehe auch

* Delegat [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* Klasse [HtmlSaveOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)