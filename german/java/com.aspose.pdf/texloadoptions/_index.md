---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen für das Laden/Importieren einer TeX-Datei in ein PDF-Dokument dar."
type: docs
weight: 4870
url: /de/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Stellt Optionen für das Laden/Importieren einer TeX-Datei in ein PDF-Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Erstellt Standard-Ladeoptionen zum Konvertieren einer TeX-Datei in ein PDF-Dokument. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDateTime](#getDateTime--) | Liest/setzt einen bestimmten Wert für Datums-/Zeitprimitive wie Jahr, Monat, Tag und Uhrzeit. |
| [getInputDirectory](#getInputDirectory--) | Liest/setzt das TeX-Eingabeverzeichnis. |
| [getJobName](#getJobName--) | Liest/setzt den Namen des Auftrags. |
| [getLoadResult](#getLoadResult--) | Liest das Ergebnis für das Laden und Kompilieren von TeX – lief alles reibungslos oder gab es Kommentare/Fehler. |
| [getNoLigatures](#getNoLigatures--) | Liest/setzt ein Flag, das Ligaturen in allen Schriftarten deaktiviert. |
| [getOutputDirectory](#getOutputDirectory--) | Liest/setzt das TeX-Ausgabeverzeichnis. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Liest/setzt ein Flag, das das Rasterisieren von mathematischen Formeln ermöglicht. |
| [getRepeat](#getRepeat--) | Liest/setzt das Flag, das angibt, ob es notwendig ist, den TeX-Auftrag zweimal auszuführen, falls beispielsweise Verweise in Eingabe‑TeX‑Datei(en) vorhanden sind. Im Allgemeinen ist dieses Verhalten nützlich, wenn die Engine während des Satzvorgangs Daten sammelt und in einer Hilfsdatei beim ersten Durchlauf speichert. Und beim zweiten Durchlauf verwendet die Engine diese Daten irgendwie. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Liest/setzt das erforderliche TeX‑Eingabeverzeichnis. Erforderliche Eingaben sind die Dateien, die irgendwie in die Haupt‑.tex‑Datei eingebunden werden, z. B. Pakete, für die keine integrierte Unterstützung besteht. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Liest/setzt das Flag, das angibt, ob die Terminalausgabe in der Konsole angezeigt werden soll. |
| [getSubsetFonts](#getSubsetFonts--) | Liest/setzt das Flag, das angibt, ob Schriftarten im Ausgabedokument unterteilt werden sollen oder nicht. |
| [setDateTime](#setDateTime-java.util.Date-) | Liest/setzt einen bestimmten Wert für Datums-/Zeitprimitive wie Jahr, Monat, Tag und Uhrzeit. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Liest/setzt das TeX-Eingabeverzeichnis. |
| [setJobName](#setJobName-java.lang.String-) | Liest/setzt den Namen des Auftrags. |
| [setNoLigatures](#setNoLigatures-boolean-) | Liest/setzt ein Flag, das Ligaturen in allen Schriftarten deaktiviert. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Liest/setzt das TeX-Ausgabeverzeichnis. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Liest/setzt ein Flag, das das Rasterisieren von mathematischen Formeln ermöglicht. |
| [setRepeat](#setRepeat-boolean-) | Liest/setzt das Flag, das angibt, ob es notwendig ist, den TeX-Auftrag zweimal auszuführen, falls beispielsweise Verweise in Eingabe‑TeX‑Datei(en) vorhanden sind. Im Allgemeinen ist dieses Verhalten nützlich, wenn die Engine während des Satzvorgangs Daten sammelt und in einer Hilfsdatei beim ersten Durchlauf speichert. Und beim zweiten Durchlauf verwendet die Engine diese Daten irgendwie. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Liest/setzt das erforderliche TeX‑Eingabeverzeichnis. Erforderliche Eingaben sind die Dateien, die irgendwie in die Haupt‑.tex‑Datei eingebunden werden, z. B. Pakete, für die keine integrierte Unterstützung besteht. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Liest/setzt das Flag, das angibt, ob die Terminalausgabe in der Konsole angezeigt werden soll. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Liest/setzt das Flag, das angibt, ob Schriftarten im Ausgabedokument unterteilt werden sollen oder nicht. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Erstellt Standard-Ladeoptionen zum Konvertieren einer TeX-Datei in ein PDF-Dokument.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Liest/setzt einen bestimmten Wert für Datums-/Zeitprimitive wie Jahr, Monat, Tag und Uhrzeit.

**Returns:**
Datum-Instanz

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Liest/setzt das TeX-Eingabeverzeichnis.

**Returns:**
ITeXInputDirectory-Instanz

### getJobName {#getJobName--}
```
public final String getJobName()
```

Liest/setzt den Namen des Auftrags.

**Returns:**
String Wert

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Liest das Ergebnis für das Laden und Kompilieren von TeX – lief alles reibungslos oder gab es Kommentare/Fehler.

**Returns:**
TeXLoadResult-Element

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Liest/setzt ein Flag, das Ligaturen in allen Schriftarten deaktiviert.

**Returns:**
boolescher Wert

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Liest/setzt das TeX-Ausgabeverzeichnis.

**Returns:**
ITeXOutputDirectory-Instanz

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Liest/setzt ein Flag, das das Rasterisieren von mathematischen Formeln ermöglicht.

**Returns:**
boolescher Wert

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Liest/setzt das Flag, das angibt, ob es notwendig ist, den TeX-Auftrag zweimal auszuführen, falls beispielsweise Verweise in Eingabe‑TeX‑Datei(en) vorhanden sind. Im Allgemeinen ist dieses Verhalten nützlich, wenn die Engine während des Satzvorgangs Daten sammelt und in einer Hilfsdatei beim ersten Durchlauf speichert. Und beim zweiten Durchlauf verwendet die Engine diese Daten irgendwie.

**Returns:**
boolescher Wert

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Liest/setzt das erforderliche TeX‑Eingabeverzeichnis. Erforderliche Eingaben sind die Dateien, die irgendwie in die Haupt‑.tex‑Datei eingebunden werden, z. B. Pakete, für die keine integrierte Unterstützung besteht.

**Returns:**
ITeXInputDirectory-Instanz

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Liest/setzt das Flag, das angibt, ob die Terminalausgabe in der Konsole angezeigt werden soll.

**Returns:**
boolescher Wert

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Liest/setzt das Flag, das angibt, ob Schriftarten im Ausgabedokument unterteilt werden sollen oder nicht.

**Returns:**
boolescher Wert

### setDateTime {#setDateTime-java.util.Date-}
Liest/setzt einen bestimmten Wert für Datums-/Zeitprimitive wie Jahr, Monat, Tag und Uhrzeit.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Liest/setzt das TeX-Eingabeverzeichnis.

### setJobName {#setJobName-java.lang.String-}
Liest/setzt den Namen des Auftrags.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Liest/setzt ein Flag, das Ligaturen in allen Schriftarten deaktiviert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Liest/setzt das TeX-Ausgabeverzeichnis.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Liest/setzt ein Flag, das das Rasterisieren von mathematischen Formeln ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Liest/setzt das Flag, das angibt, ob es notwendig ist, den TeX-Auftrag zweimal auszuführen, falls beispielsweise Verweise in Eingabe‑TeX‑Datei(en) vorhanden sind. Im Allgemeinen ist dieses Verhalten nützlich, wenn die Engine während des Satzvorgangs Daten sammelt und in einer Hilfsdatei beim ersten Durchlauf speichert. Und beim zweiten Durchlauf verwendet die Engine diese Daten irgendwie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Liest/setzt das erforderliche TeX‑Eingabeverzeichnis. Erforderliche Eingaben sind die Dateien, die irgendwie in die Haupt‑.tex‑Datei eingebunden werden, z. B. Pakete, für die keine integrierte Unterstützung besteht.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Liest/setzt das Flag, das angibt, ob die Terminalausgabe in der Konsole angezeigt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Liest/setzt das Flag, das angibt, ob Schriftarten im Ausgabedokument unterteilt werden sollen oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
