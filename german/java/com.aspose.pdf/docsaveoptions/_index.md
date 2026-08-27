---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export in das Doc-Format"
type: docs
weight: 1030
url: /de/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Speicheroptionen für den Export in das Doc-Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Dieser Handler kann verwendet werden, um Konvertierungsfortschrittsereignisse zu behandeln, z. B. um eine Fortschrittsanzeige oder Meldungen über die aktuelle Anzahl verarbeiteter Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, der den Fortschritt in der Konsole anzeigt, ist : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Ausgabeformat abrufen |
| [getImageResolutionX](#getImageResolutionX--) | Auflösung X der konvertierten Bilder. |
| [getImageResolutionY](#getImageResolutionY--) | Auflösung Y der konvertierten Bilder. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Dieser Parameter wird verwendet, um Textzeilen zu Absätzen zu gruppieren. Bestimmt, wie weit zwei relative Textzeilen auseinander liegen können. Angegeben in Hundertprozent der Höhe der Textzeilen. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Definiert den Pfad (Dateiname oder Verzeichnisname), um temporäre Daten im Speicher‑Speichermodus zu speichern. |
| [getMode](#getMode--) | Erkennungsmodus. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | In PDF können Wörter intern durch Operatoren dargestellt werden, die Wörter durch das unabhängige Drucken ihrer Buchstaben oder Silben ausgeben. Daher müssen wir zum Erkennen von Wörtern manchmal Gruppen unabhängiger Zeichen erkennen, die tatsächlich Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben), die als Abstand zwischen Wörtern während der Erkennung von Wörtern im Quell‑PDF behandelt werden muss. (Das Vorhandensein eines leeren Raums von mindestens dieser Breite zwischen Buchstaben bedeutet, dass die Textelemente zu verschiedenen Wörtern gehören). Sie ist an die Schriftgröße normiert – 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes. ACHTUNG! Sie wird nur in Fällen verwendet, wenn das Quell‑PDF spezifische, selten genutzte Schriften enthält, für die kein optimaler Wert aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter das Ergebnisdokument nicht. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Wird für Absatz- oder Zeilenumbrüche verwendet. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Liest oder setzt die Konvertierung für Type3‑Schriften. In Type‑3‑Schriften werden Glyphen durch Streams von Grafik‑Operatoren definiert. Das bedeutet, dass im DOC/DOCX‑Ausgabeformat Bilder anstelle von Text angezeigt werden. Setzen Sie dieses Flag auf true, um Type3‑Schriften in TTF zu konvertieren und Text in der resultierenden Datei zu erhalten. |
| [isRecognizeBullets](#isRecognizeBullets--) | Schaltet die Erkennung von Aufzählungszeichen ein. |
| [isReSaveFonts](#isReSaveFonts--) | Liest oder setzt das Verfahren zum erneuten Speichern von Schriften. Wenn auf true gesetzt, werden die Schriften auf jeder Seite neu geladen, um den Einfluss vorheriger Schrift‑Eigenschaften zu vermeiden, und die neu erstellte Schrift wird von Grund auf geladen. Setzen Sie diese Option auf false, wenn Sie die Leistung verbessern möchten. Der Standardwert ist true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Verwende Absatz- oder Zeilenumbrüche |
| [setBatchSize](#setBatchSize-int-) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Liest oder setzt die Konvertierung für Type3‑Schriften. In Type‑3‑Schriften werden Glyphen durch Streams von Grafik‑Operatoren definiert. Das bedeutet, dass im DOC/DOCX‑Ausgabeformat Bilder anstelle von Text angezeigt werden. Setzen Sie dieses Flag auf true, um Type3‑Schriften in TTF zu konvertieren und Text in der resultierenden Datei zu erhalten. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Dieser Handler kann verwendet werden, um Konvertierungs‑Fortschrittsereignisse zu behandeln, z. b. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Ausgabeformat festlegen |
| [setImageResolutionX](#setImageResolutionX-int-) | Auflösung X der konvertierten Bilder. |
| [setImageResolutionY](#setImageResolutionY-int-) | Auflösung Y der konvertierten Bilder. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Dieser Parameter wird verwendet, um Textzeilen zu Absätzen zu gruppieren. Bestimmt, wie weit zwei relative Textzeilen auseinander liegen können. Angegeben in Hundertprozent der Höhe der Textzeilen. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Definiert den Pfad (Dateiname oder Verzeichnisname), um temporäre Daten im Speicher‑Speichermodus zu speichern. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Erkennungsmodus. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Schaltet die Erkennung von Aufzählungszeichen ein. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | In PDF können Wörter intern durch Operatoren dargestellt werden, die Wörter durch das unabhängige Drucken ihrer Buchstaben oder Silben ausgeben. Daher müssen wir zum Erkennen von Wörtern manchmal Gruppen unabhängiger Zeichen erkennen, die tatsächlich Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben), die als Abstand zwischen Wörtern während der Erkennung von Wörtern im Quell‑PDF behandelt werden muss. (Das Vorhandensein eines leeren Raums von mindestens dieser Breite zwischen Buchstaben bedeutet, dass die Textelemente zu verschiedenen Wörtern gehören). Sie ist an die Schriftgröße normiert – 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes. ACHTUNG! Sie wird nur in Fällen verwendet, wenn das Quell‑PDF spezifische, selten genutzte Schriften enthält, für die kein optimaler Wert aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter das Ergebnisdokument nicht. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Liest oder setzt das Verfahren zum erneuten Speichern von Schriften. Wenn auf true gesetzt, werden die Schriften auf jeder Seite neu geladen, um den Einfluss vorheriger Schrift‑Eigenschaften zu vermeiden, und die neu erstellte Schrift wird von Grund auf geladen. Setzen Sie diese Option auf false, wenn Sie die Leistung verbessern möchten. Der Standardwert ist true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Konstruktor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Returns:**
int-Wert

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Dieser Handler kann verwendet werden, um Konvertierungsfortschrittsereignisse zu behandeln, z. B. kann er verwendet werden, um eine Fortschrittsleiste oder Meldungen über die aktuelle Anzahl verarbeiteter Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, der den Fortschritt in der Konsole anzeigt, ist : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler‑Instanz

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Ausgabeformat abrufen

**Returns:**
DocFormat Element @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Auflösung X der konvertierten Bilder.

**Returns:**
int-Wert

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Auflösung Y der konvertierten Bilder.

**Returns:**
int-Wert

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Dieser Parameter wird verwendet, um Textzeilen zu Absätzen zu gruppieren. Bestimmt, wie weit zwei relative Textzeilen auseinander liegen können. Angegeben in Hundertprozent der Höhe der Textzeilen.

**Returns:**
float-Wert

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Definiert den Pfad (Dateiname oder Verzeichnisname), um temporäre Daten im Speicher‑Speichermodus zu speichern.

**Returns:**
String Wert

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Erkennungsmodus.

**Returns:**
RecognitionMode Wert @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

In PDF können Wörter intern durch Operatoren dargestellt werden, die Wörter durch das unabhängige Drucken ihrer Buchstaben oder Silben ausgeben. Daher müssen wir zum Erkennen von Wörtern manchmal Gruppen unabhängiger Zeichen erkennen, die tatsächlich Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben), die als Abstand zwischen Wörtern während der Erkennung von Wörtern im Quell‑PDF behandelt werden muss. (Das Vorhandensein eines leeren Raums von mindestens dieser Breite zwischen Buchstaben bedeutet, dass die Textelemente zu verschiedenen Wörtern gehören). Sie ist an die Schriftgröße normiert – 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes. ACHTUNG! Sie wird nur in Fällen verwendet, wenn das Quell‑PDF spezifische, selten genutzte Schriften enthält, für die kein optimaler Wert aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter das Ergebnisdokument nicht.

**Returns:**
Relative Nähe

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Wird für Absatz- oder Zeilenumbrüche verwendet.

**Returns:**
boolescher Wert.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Liest oder setzt die Konvertierung für Type3‑Schriften. In Type‑3‑Schriften werden Glyphen durch Streams von Grafik‑Operatoren definiert. Das bedeutet, dass im DOC/DOCX‑Ausgabeformat Bilder anstelle von Text angezeigt werden. Setzen Sie dieses Flag auf true, um Type3‑Schriften in TTF zu konvertieren und Text in der resultierenden Datei zu erhalten.

**Returns:**
boolescher Wert

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Schaltet die Erkennung von Aufzählungszeichen ein.

**Returns:**
boolescher Wert

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Liest oder setzt das Verfahren zum erneuten Speichern von Schriften. Wenn auf true gesetzt, werden die Schriften auf jeder Seite neu geladen, um den Einfluss vorheriger Schrift‑Eigenschaften zu vermeiden, und die neu erstellte Schrift wird von Grund auf geladen. Setzen Sie diese Option auf false, wenn Sie die Leistung verbessern möchten. Der Standardwert ist true;

**Returns:**
boolescher Wert

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Verwende Absatz- oder Zeilenumbrüche

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Liest oder setzt die Konvertierung für Type3‑Schriften. In Type‑3‑Schriften werden Glyphen durch Streams von Grafik‑Operatoren definiert. Das bedeutet, dass im DOC/DOCX‑Ausgabeformat Bilder anstelle von Text angezeigt werden. Setzen Sie dieses Flag auf true, um Type3‑Schriften in TTF zu konvertieren und Text in der resultierenden Datei zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Dieser Handler kann verwendet werden, um Konvertierungs‑Fortschrittsereignisse zu behandeln, z. b.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Ausgabeformat festlegen

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Auflösung X der konvertierten Bilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Auflösung Y der konvertierten Bilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Dieser Parameter wird verwendet, um Textzeilen zu Absätzen zu gruppieren. Bestimmt, wie weit zwei relative Textzeilen auseinander liegen können. Angegeben in Hundertprozent der Höhe der Textzeilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Definiert den Pfad (Dateiname oder Verzeichnisname), um temporäre Daten im Speicher‑Speichermodus zu speichern.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Erkennungsmodus.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Schaltet die Erkennung von Aufzählungszeichen ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

In PDF können Wörter intern durch Operatoren dargestellt werden, die Wörter durch das unabhängige Drucken ihrer Buchstaben oder Silben ausgeben. Daher müssen wir zum Erkennen von Wörtern manchmal Gruppen unabhängiger Zeichen erkennen, die tatsächlich Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben), die als Abstand zwischen Wörtern während der Erkennung von Wörtern im Quell‑PDF behandelt werden muss. (Das Vorhandensein eines leeren Raums von mindestens dieser Breite zwischen Buchstaben bedeutet, dass die Textelemente zu verschiedenen Wörtern gehören). Sie ist an die Schriftgröße normiert – 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes. ACHTUNG! Sie wird nur in Fällen verwendet, wenn das Quell‑PDF spezifische, selten genutzte Schriften enthält, für die kein optimaler Wert aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter das Ergebnisdokument nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Relative Nähe |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Liest oder setzt das Verfahren zum erneuten Speichern von Schriften. Wenn auf true gesetzt, werden die Schriften auf jeder Seite neu geladen, um den Einfluss vorheriger Schrift‑Eigenschaften zu vermeiden, und die neu erstellte Schrift wird von Grund auf geladen. Setzen Sie diese Option auf false, wenn Sie die Leistung verbessern möchten. Der Standardwert ist true;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
