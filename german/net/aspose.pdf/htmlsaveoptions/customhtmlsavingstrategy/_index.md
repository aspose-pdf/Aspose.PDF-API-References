---
title: CustomHtmlSavingStrategy
second_title: Aspose.PDF für .NET-API-Referenz
description: Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten Sie können dieser Eigenschaft einen Delegaten zuweisen der aus einer benutzerdefinierten Methode erstellt wurde die die Verarbeitung einer HTML-Seite genauer gesagt - Markup-HTML ohne externe verknüpfte Dateien falls vorhanden implementiert wurde während der Konvertierung erstellt. In diesem Fall kann die Verarbeitung wie das Speichern des HTML-Codes der Seite im Stream oder auf der Festplatte in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden  da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund vom Konvertercode selbst durchgeführt werden muss nicht im benutzerdefinierten Code setzen Sie bitte im benutzerdefinierten Code das Flag CustomProcessingCancelled der Variable des htmlSavingInfo-Parameters Es wird dem Konverter signalisieren dass dies alles der Fall ist notwendige Schritte zur Verarbeitung dieser Ressource müssen im Konverter selbst auf dieselbe Weise ausgeführt werden als gäbe es keinen externen benutzerdefinierten Code zur Verarbeitung .
type: docs
weight: 220
url: /de/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer HTML-Seite (genauer gesagt - Markup-HTML, ohne externe verknüpfte Dateien, falls vorhanden) implementiert wurde während der Konvertierung erstellt. In diesem Fall kann die Verarbeitung (wie das Speichern des HTML-Codes der Seite im Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden , da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund vom Konvertercode selbst durchgeführt werden muss, nicht im benutzerdefinierten Code, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variable des 'htmlSavingInfo'-Parameters: Es wird dem Konverter signalisieren, dass dies alles der Fall ist notwendige Schritte zur Verarbeitung dieser Ressource müssen im Konverter selbst auf dieselbe Weise ausgeführt werden, als gäbe es keinen externen benutzerdefinierten Code zur Verarbeitung .

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Siehe auch

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namensraum [Aspose.Pdf](../../htmlsaveoptions)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->