---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Dieser Eigenschaft können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung von externen Ressourcen (Schriftart oder Bild), die aus PDF extrahiert wurden und während der Konvertierung von PDF zu HTML als externe Ressource gespeichert werden müssen, implementiert. In diesem Fall kann die Verarbeitung (wie das Speichern im Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen, und dieser benutzerdefinierte Code muss einen Pfad (oder einen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das generierte HTML anstelle des ursprünglich vorgesehenen Pfades zu dieser Bildressource integriert wird. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'resourceSavingInfo' Parameter. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe.
type: docs
weight: 5730
url: /de/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy Delegat

Dieser Eigenschaft können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung von externen Ressourcen (Schriftart oder Bild), die aus PDF extrahiert wurden und während der Konvertierung von PDF zu HTML als externe Ressource gespeichert werden müssen, implementiert. In diesem Fall kann die Verarbeitung (wie das Speichern im Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen, und dieser benutzerdefinierte Code muss einen Pfad (oder einen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das generierte HTML anstelle des ursprünglich vorgesehenen Pfades zu dieser Bildressource integriert wird. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'resourceSavingInfo' Parameter. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | stellt eine Menge von Daten zum Speichern der Ressource dar |

### Rückgabewert

muss die URL zur gespeicherten Ressource zurückgeben, die während der Generierung von HTML verwendet wird

### Siehe auch

* Klasse [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)