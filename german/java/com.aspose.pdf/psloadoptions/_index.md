---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Repräsentiert Optionen zum Laden/Importieren von .mht-Dateien in ein PDF-Dokument."
type: docs
weight: 4060
url: /de/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Repräsentiert Optionen zum Laden/Importieren von .mht-Dateien in ein PDF-Dokument.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Erstellt Ladeoptionen für die Konvertierung von PostScript in ein PDF-Dokument mit leerem Basispfad. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Liefert die Pfade der Schriftordner. Die Ordner mit zusätzlichen Schriften für die Konvertierung. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Gibt an, ob nicht-TrueType-Schriften als TTF gespeichert werden sollen. Dies verringert das Volumen des resultierenden Dokuments bei der PS-zu-PDF-Konvertierung erheblich und erhöht die Geschwindigkeit der Konvertierung von PS-Dateien mit einer großen Menge an Text in nicht-TrueType-Schriften in jedes Ausgabeformat. Allerdings gibt es eine leichte vertikale Verschiebung des Textes bei der Konvertierung einer PostSctipt-Datei in ein Bild. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Gibt an, ob nicht-TrueType-Schriften als TTF gespeichert werden sollen. Dies verringert das Volumen des resultierenden Dokuments bei der PS-zu-PDF-Konvertierung erheblich und erhöht die Geschwindigkeit der Konvertierung von PS-Dateien mit einer großen Menge an Text in nicht-TrueType-Schriften in jedes Ausgabeformat. Allerdings gibt es eine leichte vertikale Verschiebung des Textes bei der Konvertierung einer PostSctipt-Datei in ein Bild. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Setzt die Pfade der Schriftordner. Die Ordner mit zusätzlichen Schriften für die Konvertierung. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Erstellt Ladeoptionen für die Konvertierung von PostScript in ein PDF-Dokument mit leerem Basispfad.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Liefert die Pfade der Schriftordner. Die Ordner mit zusätzlichen Schriften für die Konvertierung.

**Returns:**
Array von String-Werten

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Gibt an, ob nicht-TrueType-Schriften als TTF gespeichert werden sollen. Dies verringert das Volumen des resultierenden Dokuments bei der PS-zu-PDF-Konvertierung erheblich und erhöht die Geschwindigkeit der Konvertierung von PS-Dateien mit einer großen Menge an Text in nicht-TrueType-Schriften in jedes Ausgabeformat. Allerdings gibt es eine leichte vertikale Verschiebung des Textes bei der Konvertierung einer PostSctipt-Datei in ein Bild.

**Returns:**
boolescher Wert

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Gibt an, ob nicht-TrueType-Schriften als TTF gespeichert werden sollen. Dies verringert das Volumen des resultierenden Dokuments bei der PS-zu-PDF-Konvertierung erheblich und erhöht die Geschwindigkeit der Konvertierung von PS-Dateien mit einer großen Menge an Text in nicht-TrueType-Schriften in jedes Ausgabeformat. Allerdings gibt es eine leichte vertikale Verschiebung des Textes bei der Konvertierung einer PostSctipt-Datei in ein Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Setzt die Pfade der Schriftordner. Die Ordner mit zusätzlichen Schriften für die Konvertierung.
