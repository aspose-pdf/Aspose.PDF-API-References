---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF für Java API-Referenz"
description: "ACHTUNG! Das Feature wurde implementiert, aber noch nicht in die öffentliche API aufgenommen, da ein Blocker-Problem in der OSHARED-Schicht für das Beispieldokument aufgedeckt wurde. Stellt den Verwendungsmodus der Seitengröße dar."
type: docs
weight: 2810
url: /de/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

ACHTUNG! Das Feature ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blocker-Problem in der OSHARED-Schicht für das Beispieldokument aufgetreten ist. Stellt den Verwendungsmodus der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass die erforderliche Seitengröße angepasst werden kann. Manchmal gibt der Inhalt jedoch horizontale Positionen oder Größen an, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen. In einem solchen Fall können wir festlegen, was zu tun ist (z. B. wenn die Größe des Inhalts nicht in die erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt).

## Felder

| Feld | Beschreibung |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Dieser Modus definiert folgendes Verhalten: Nach Erhalt des Konvertierungsergebnisses und Feststellung, dass ein Teil des Inhalts abgeschnitten wurde, wird die Breite des Portview vergrößert, um den Inhalt aufzunehmen, und die Konvertierung wird wiederholt. Dieser Modus ermöglicht es, in einem solchen Fall weniger Seiten im Ergebnis zu erhalten, erfordert jedoch wiederholtes Rendern (und damit mehr Verarbeitungszeit). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | In diesem Modus haben die Ergebnisseiten die in LoadOptions definierte erforderliche Seitengröße, unabhängig davon, ob der Inhalt nach der Konvertierung über die Seitenränder hinausgeht oder nicht. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Dieser Modus definiert folgendes Verhalten: Nach Erhalt des Konvertierungsergebnisses und Feststellung, dass ein Teil des Inhalts abgeschnitten wurde, wird die Breite des Portview vergrößert, um den Inhalt aufzunehmen, und die Konvertierung wird wiederholt. Dieser Modus ermöglicht es, in einem solchen Fall weniger Seiten im Ergebnis zu erhalten, erfordert jedoch wiederholtes Rendern (und damit mehr Verarbeitungszeit).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

In diesem Modus haben die Ergebnisseiten die in LoadOptions definierte erforderliche Seitengröße, unabhängig davon, ob der Inhalt nach der Konvertierung über die Seitenränder hinausgeht oder nicht.
