---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Konvertierte PDF kann Rasterbilder (.png, *.jpeg usw.) enthalten. Dieses Enum definiert Methoden, wie Rasterbilder während der Konvertierung von PDF zu HTML behandelt werden können."
type: docs
weight: 2140
url: /de/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

Konvertierte PDF kann Rasterbilder (.png, *.jpeg usw.) enthalten. Dieses Enum definiert Methoden, wie Rasterbilder während der Konvertierung von PDF zu HTML behandelt werden können.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Es wird für jede Ergebnisseite eine große PNG-Hintergrunddatei erzeugt. Rasterbilder werden in diese Datei eingebettet und als Regionen dieses Bildes gerendert. Es werden keine externen PNG-Dateien für jedes Bild erzeugt, sondern pro Seite nur eine PNG-Datei im Ergebnisdateisatz der Konvertierung vorhanden sein. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Unterschiedliche Rasterbilder werden als PNG-Dateien getrennt abgelegt, aber über umhüllende SVG-Bilder referenziert, d. h. für jedes Rasterbild wird eine PNG-Datei und ein SVG erzeugt, und jedes dieser SVGs enthält Links zur entsprechenden PNG-Datei. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Für jede unterschiedliche Rasterdatei wird ein Wrapper‑SVG‑Bild erzeugt, und das Rasterbild wird als Base64‑kodierte Zeichenfolge in dieses SVG‑Bild eingebettet. |
| [DontSave](#DontSave) | Bilder für Fixed Layout nicht speichern |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Es wird für jede Ergebnisseite eine große PNG-Hintergrunddatei erzeugt. Rasterbilder werden in diese Datei eingebettet und als Regionen dieses Bildes gerendert. Es werden keine externen PNG-Dateien für jedes Bild erzeugt, sondern pro Seite nur eine PNG-Datei im Ergebnisdateisatz der Konvertierung vorhanden sein.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Unterschiedliche Rasterbilder werden als PNG-Dateien getrennt abgelegt, aber über umhüllende SVG-Bilder referenziert, d. h. für jedes Rasterbild wird eine PNG-Datei und ein SVG erzeugt, und jedes dieser SVGs enthält Links zur entsprechenden PNG-Datei.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Für jede unterschiedliche Rasterdatei wird ein Wrapper‑SVG‑Bild erzeugt, und das Rasterbild wird als Base64‑kodierte Zeichenfolge in dieses SVG‑Bild eingebettet.

### DontSave {#DontSave}
```
public static final int DontSave
```

Bilder für Fixed Layout nicht speichern
