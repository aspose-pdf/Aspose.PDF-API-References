---
title: LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF für .NET-API-Referenz
description: ACHTUNG Die Funktion wurde implementiert aber noch nicht in die öffentliche API gestellt da ein Blockerproblem in der OSHARED-Schicht für das Beispieldokument aufgedeckt wurde. Stellt den Verwendungsmodus der Seitengröße während der Konvertierung dar. Formate wie HTML EPUB usw. haben normalerweise ein Float-Design  so dass die erforderliche Seitengröße angepasst werden kann. Aber manchmal hat Inhalt horizontale Positionen oder Größen angegeben die es nicht zulassen Inhalt in die erforderliche Seitengröße zu bringen. In einem solchen Fall können wir definieren was in diesem Fall getan werden soll dh wenn die Größe des Inhalts nicht zu der erforderlichen anfänglichen Seitengröße passt. Ergebnis PDF-Dokument.
type: docs
weight: 3970
url: /de/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ACHTUNG! Die Funktion wurde implementiert, aber noch nicht in die öffentliche API gestellt, da ein Blockerproblem in der OSHARED-Schicht für das Beispieldokument aufgedeckt wurde. Stellt den Verwendungsmodus der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein Float-Design , so dass die erforderliche Seitengröße angepasst werden kann. Aber manchmal hat Inhalt horizontale Positionen oder Größen angegeben, die es nicht zulassen, Inhalt in die erforderliche Seitengröße zu bringen. In einem solchen Fall können wir definieren, was in diesem Fall getan werden soll (dh wenn die Größe des Inhalts nicht zu der erforderlichen anfänglichen Seitengröße passt). Ergebnis PDF-Dokument).

```csharp
public enum PageSizeAdjustmentModes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | In diesem Modus haben Ergebnisseiten die erforderliche Seitengröße, die in LoadOptions definiert ist, unabhängig davon, ob der Inhalt nach der Konvertierung die Seitengrenzen überschreitet oder nicht. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Dieser Modus definiert ein solches Verhalten: Nach dem Erhalt des Konvertierungsergebnisses , und der Feststellung, dass einige Inhalte abgeschnitten wurden, wird die Breite der Portansicht vergrößert, um sie an den Inhalt anzupassen, und die Konvertierung wird wiederholt. Dieser Modus ermöglicht es, weniger Seiten als Ergebnis zu erhalten Dieser Fall erfordert jedoch wiederholtes Rendering (und daher mehr Verarbeitungszeit). |

### Siehe auch

* class [LoadOptions](../loadoptions)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
