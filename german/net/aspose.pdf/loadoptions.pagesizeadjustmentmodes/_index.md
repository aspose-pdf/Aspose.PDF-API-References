---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes Enum. ACHTUNG Die Funktion wurde implementiert, aber noch nicht in die öffentliche API aufgenommen, da ein Blockierungsproblem in der OSHARED-Schicht für das Beispiel-Dokument aufgetreten ist. Stellt den Modus der Verwendung der Seitengröße während der Konvertierung dar. Formate wie HTML, EPUB usw. haben normalerweise ein flexibles Design, sodass sie die erforderliche Seitengröße anpassen können. Aber manchmal hat der Inhalt spezifische horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu bringen. In diesem Fall können wir definieren, was in diesem Fall zu tun ist, d.h. wenn die Größe des Inhalts nicht in die erforderliche ursprüngliche Seitengröße des resultierenden PDF-Dokuments passt.
type: docs
weight: 6140
url: /de/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes Aufzählung

ACHTUNG! Die Funktion wurde implementiert, aber noch nicht in die öffentliche API aufgenommen, da ein Blockierungsproblem in der OSHARED-Schicht für das Beispiel-Dokument aufgetreten ist. Stellt den Modus der Verwendung der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein flexibles Design, sodass sie die erforderliche Seitengröße anpassen können. Aber manchmal hat der Inhalt spezifische horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu bringen. In diesem Fall können wir definieren, was in diesem Fall zu tun ist (d.h. wenn die Größe des Inhalts nicht in die erforderliche ursprüngliche Seitengröße des resultierenden PDF-Dokuments passt).

```csharp
public enum PageSizeAdjustmentModes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | In diesem Modus haben die Ergebnisseiten die erforderliche Seitengröße, die in LoadOptions definiert ist, unabhängig davon, ob der Inhalt nach der Konvertierung über die Seitenränder hinausgeht oder nicht. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Dieser Modus definiert folgendes Verhalten: Nach Erhalt des Konvertergebnisses und der Feststellung, dass ein Teil des Inhalts abgeschnitten wurde, wird die Breite des Ansichtsfensters vergrößert, um den Inhalt anzupassen, und die Konvertierung wird wiederholt. Dieser Modus ermöglicht es, in einem solchen Fall weniger Seiten im Ergebnis zu erhalten, erfordert jedoch eine wiederholte Darstellung (und damit mehr Verarbeitungszeit). |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)