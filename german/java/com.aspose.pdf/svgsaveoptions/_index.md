---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export in das SVG‑Format"
type: docs
weight: 4720
url: /de/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Speicheroptionen für den Export in das SVG‑Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die benutzerdefinierte Behandlung der erstellten referenzierten externen Bilddateien (wie eingebettete BMP- oder JPEG-Dateien) verwendet werden muss, die in das gespeicherte SVG eingebettet sind. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URI der gespeicherten Ressource im erzeugten SVG darstellt. Wenn die Verarbeitung dieser oder jener Datei aus irgendeinem Grund vom Code des Konverters selbst durchgeführt werden muss, nicht im benutzerdefinierten Code, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, als ob kein externer benutzerdefinierter Code vorhanden wäre. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Legt fest, ob die Ausgabe als ein ZIP-Archiv erstellt wird. Bitte beachten Sie den Kommentar zu den Optionen 'TreatTargetFileNameAsDirectory', um die Namensregeln für SVG-Dateien von Seiten eines mehrseitigen Quelldokuments zu sehen, die ebenfalls auf das gezippte Satz von Ausgabedateien angewendet werden. |
| [isScaleToPixels](#isScaleToPixels--) | Legt fest, ob das Ausgabedokument von typografischen Punkten in Pixel skaliert werden soll. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Diese Option legt fest, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei anstelle der Ausgabedatei selbst erstellt wird. Dadurch enthält das Verzeichnis alle SVG‑Bilder der Seiten (wie unten beschrieben). Wenn nein, werden die Ausgabedateien der Seiten, außer der ersten, exakt im angeforderten Verzeichnis als Hauptausgabedatei erstellt, jedoch mit dem Dateinamen‑Suffix _[2...n], das durch die Seitennummer definiert ist, z. B. wenn Sie die Ausgabedatei "C:\\AsposeTests\\output.svg" festlegen und die Ausgabe mehrere SVG‑Dateien von Seiten enthält, dann werden die Seiten‑Dateien ebenfalls im Verzeichnis "C:\\AsposeTests\\" erstellt und erhalten die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Legt fest, ob die Ausgabe als ein ZIP-Archiv erstellt wird. Bitte beachten Sie den Kommentar zu den Optionen 'TreatTargetFileNameAsDirectory', um die Namensregeln für SVG-Dateien von Seiten eines mehrseitigen Quelldokuments zu sehen, die ebenfalls auf das gezippte Satz von Ausgabedateien angewendet werden. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die benutzerdefinierte Behandlung der erstellten referenzierten externen Bilddateien (wie eingebettete BMP- oder JPEG-Dateien) verwendet werden muss, die in das gespeicherte SVG eingebettet sind. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Legt fest, ob das Ausgabedokument von typografischen Punkten in Pixel skaliert werden soll. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Diese Option legt fest, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei anstelle der Ausgabedatei selbst erstellt wird. Dadurch enthält das Verzeichnis alle SVG‑Bilder der Seiten (wie unten beschrieben). Wenn nein, werden die Ausgabedateien der Seiten, außer der ersten, exakt im angeforderten Verzeichnis als Hauptausgabedatei erstellt, jedoch mit dem Dateinamen‑Suffix _[2...n], das durch die Seitennummer definiert ist, z. B. wenn Sie die Ausgabedatei "C:\\AsposeTests\\output.svg" festlegen und die Ausgabe mehrere SVG‑Dateien von Seiten enthält, dann werden die Seiten‑Dateien ebenfalls im Verzeichnis "C:\\AsposeTests\\" erstellt und erhalten die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Konstruktor

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die benutzerdefinierte Behandlung der erstellten referenzierten externen Bilddateien (wie eingebettete BMP- oder JPEG-Dateien) verwendet werden muss, die in das gespeicherte SVG eingebettet sind. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URI der gespeicherten Ressource im erzeugten SVG darstellt. Wenn die Verarbeitung dieser oder jener Datei aus irgendeinem Grund vom Code des Konverters selbst durchgeführt werden muss, nicht im benutzerdefinierten Code, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, als ob kein externer benutzerdefinierter Code vorhanden wäre.

**Returns:**
EmbeddedImagesSavingStrategy Instanz

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Legt fest, ob die Ausgabe als ein ZIP-Archiv erstellt wird. Bitte beachten Sie den Kommentar zu den Optionen 'TreatTargetFileNameAsDirectory', um die Namensregeln für SVG-Dateien von Seiten eines mehrseitigen Quelldokuments zu sehen, die ebenfalls auf das gezippte Satz von Ausgabedateien angewendet werden.

**Returns:**
boolescher Wert

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Legt fest, ob das Ausgabedokument von typografischen Punkten in Pixel skaliert werden soll.

**Returns:**
boolescher Wert

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Diese Option legt fest, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei anstelle der Ausgabedatei selbst erstellt wird. Dadurch enthält das Verzeichnis alle SVG‑Bilder der Seiten (wie unten beschrieben). Wenn nein, werden die Ausgabedateien der Seiten, außer der ersten, exakt im angeforderten Verzeichnis als Hauptausgabedatei erstellt, jedoch mit dem Dateinamen‑Suffix _[2...n], das durch die Seitennummer definiert ist, z. B. wenn Sie die Ausgabedatei "C:\\AsposeTests\\output.svg" festlegen und die Ausgabe mehrere SVG‑Dateien von Seiten enthält, dann werden die Seiten‑Dateien ebenfalls im Verzeichnis "C:\\AsposeTests\\" erstellt und erhalten die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw.

**Returns:**
boolescher Wert

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Legt fest, ob die Ausgabe als ein ZIP-Archiv erstellt wird. Bitte beachten Sie den Kommentar zu den Optionen 'TreatTargetFileNameAsDirectory', um die Namensregeln für SVG-Dateien von Seiten eines mehrseitigen Quelldokuments zu sehen, die ebenfalls auf das gezippte Satz von Ausgabedateien angewendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compressOutputToZipArchive |  | boolescher Wert |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die benutzerdefinierte Behandlung der erstellten referenzierten externen Bilddateien (wie eingebettete BMP- oder JPEG-Dateien) verwendet werden muss, die in das gespeicherte SVG eingebettet sind.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Legt fest, ob das Ausgabedokument von typografischen Punkten in Pixel skaliert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleToPixels |  | boolescher Wert |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Diese Option legt fest, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei anstelle der Ausgabedatei selbst erstellt wird. Dadurch enthält das Verzeichnis alle SVG‑Bilder der Seiten (wie unten beschrieben). Wenn nein, werden die Ausgabedateien der Seiten, außer der ersten, exakt im angeforderten Verzeichnis als Hauptausgabedatei erstellt, jedoch mit dem Dateinamen‑Suffix _[2...n], das durch die Seitennummer definiert ist, z. B. wenn Sie die Ausgabedatei "C:\\AsposeTests\\output.svg" festlegen und die Ausgabe mehrere SVG‑Dateien von Seiten enthält, dann werden die Seiten‑Dateien ebenfalls im Verzeichnis "C:\\AsposeTests\\" erstellt und erhalten die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | boolescher Wert |
