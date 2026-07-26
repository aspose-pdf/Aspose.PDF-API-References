---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Für diese Eigenschaft können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Verarbeitung einer externen Ressource (Schriftart oder Bild), die aus dem PDF extrahiert wurde, implementiert und gespeichert werden muss."
type: docs
weight: 2150
url: /de/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Für diese Eigenschaft können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer externen Ressource (Schriftart oder Bild) implementiert, die aus dem PDF extrahiert wurde und während der Konvertierung von PDF zu HTML als externe Ressource gespeichert werden muss. In einem solchen Fall kann die Verarbeitung (wie das Speichern in einem Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen und dieser benutzerdefinierte Code muss einen Pfad (oder irgendeinen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das erzeugte HTML eingefügt wird anstelle des ursprünglich erwarteten Pfads zu dieser Bildressource. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung dieser oder jener Datei aus irgendeinem Grund vom Code des Konverters selbst durchgeführt werden muss, nicht im benutzerdefinierten Code, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'resourceSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, als ob kein externer benutzerdefinierter Code vorhanden wäre.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Aufgerufene Methode |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Aufgerufene Methode
