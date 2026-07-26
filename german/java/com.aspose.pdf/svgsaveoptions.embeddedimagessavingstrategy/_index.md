---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Für eine Eigenschaft dieses Typs können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Verarbeitung des externen Speicherns eines Bildes implementiert, das aus einem aus PDF erstellten SVG extrahiert wurde."
type: docs
weight: 4730
url: /de/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Der Eigenschaft dieses Typs können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Verarbeitung des externen Speicherns eines Bildes implementiert, das aus einem aus PDF erstellten SVG extrahiert wurde und während der Konvertierung von PDF zu HTML als externe Ressource gespeichert werden muss. In einem solchen Fall kann die Verarbeitung (wie selbst erstelltes Speichern in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code durchgeführt werden, und dieser benutzerdefinierte Code muss einen Pfad (oder irgendeinen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das erzeugte SVG anstelle des ursprünglich vorgesehenen Pfads zu dieser Bildressource eingefügt wird. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht vom benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle erforderlichen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, als ob kein externer benutzerdefinierter Code vorhanden wäre.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
