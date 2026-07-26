---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export in das PDF‑Format."
type: docs
weight: 3790
url: /de/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Speicheroptionen für den Export in das PDF‑Format.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Schriftname, der standardmäßig für Schriftarten verwendet wird, die auf dem Computer fehlen. Wenn das PDF-Dokument, das als PDF gespeichert wird, Schriftarten enthält, die weder im Dokument selbst noch auf dem Gerät verfügbar sind, ersetzt die API diese Schriftarten durch die Standardschriftart (wenn eine Schriftart mit {@code DefaultFontName} auf dem Gerät gefunden wird). |
| [getTempPath](#getTempPath--) | Pfad für temporäre Dateien. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Schriftname, der standardmäßig für Schriftarten verwendet wird, die auf dem Computer fehlen. Wenn das PDF-Dokument, das als PDF gespeichert wird, Schriftarten enthält, die weder im Dokument selbst noch auf dem Gerät verfügbar sind, ersetzt die API diese Schriftarten durch die Standardschriftart (wenn eine Schriftart mit {@code DefaultFontName} auf dem Gerät gefunden wird). |
| [setTempPath](#setTempPath-java.lang.String-) | Pfad für temporäre Dateien. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Konstruktor

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Schriftname, der standardmäßig für Schriftarten verwendet wird, die auf dem Computer fehlen. Wenn das PDF-Dokument, das als PDF gespeichert wird, Schriftarten enthält, die weder im Dokument selbst noch auf dem Gerät verfügbar sind, ersetzt die API diese Schriftarten durch die Standardschriftart (wenn eine Schriftart mit {@code DefaultFontName} auf dem Gerät gefunden wird).

**Returns:**
String Wert

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Pfad für temporäre Dateien.

**Returns:**
String Wert

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Schriftname, der standardmäßig für Schriftarten verwendet wird, die auf dem Computer fehlen. Wenn das PDF-Dokument, das als PDF gespeichert wird, Schriftarten enthält, die weder im Dokument selbst noch auf dem Gerät verfügbar sind, ersetzt die API diese Schriftarten durch die Standardschriftart (wenn eine Schriftart mit {@code DefaultFontName} auf dem Gerät gefunden wird).

### setTempPath {#setTempPath-java.lang.String-}
Pfad für temporäre Dateien.
