---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Menge von Optionen zum Konvertieren von PDF-Dokumenten dar."
type: docs
weight: 3730
url: /de/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

Stellt eine Menge von Optionen zum Konvertieren von PDF-Dokumenten dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Strategie zum Ausrichten von Text. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code AlignText} auf true gesetzt ist. |
| [getAlignText](#getAlignText--) | Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig beeinflusst die Dokumentkonvertierung die Textausrichtung nicht und lässt den Text unverändert. In einigen Fällen führt die Schriftartsubstitution jedoch zu überlappendem Text oder zusätzlichen Leerzeichen im konvertierten Dokument. Wenn dieses Flag gesetzt ist, werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden, die Probleme mit überlappendem Text oder zusätzlichen Leerzeichen haben, da die Verwendung dieses Flags die Leistung verringert und in einigen Fällen den Textinhalt beschädigen könnte. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Liefert oder setzt die Einstellungen für das automatische Tagging während der PDF-Formatkonvertierung. Die automatischen Tagging-Einstellungen werden verwendet, um das Verhalten des Auto-Tagging-Prozesses zu konfigurieren, der typischerweise eingesetzt wird, um die Barrierefreiheit und Struktur eines PDF-Dokuments bei der Konvertierung in ein bestimmtes PDF-Format zu verbessern. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Aktion für Bilder mit Soft-Maske. |
| [getDefault](#getDefault--) | Liefert ein PdfFormatConversionOptions-Objekt mit Standardparametern. |
| [getErrorAction](#getErrorAction--) | Aktion für Objekte, die nicht konvertiert werden können. |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Strategie(n) zum Ausschließen überflüssiger Schriftarten und zur Reduzierung der Dateigröße des Dokuments. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code OptimizeFileSize} auf true gesetzt ist. Standardmäßig wird die Kombination der Strategien {@code SubsetFonts} und {@code RemoveDuplicatedFonts} verwendet. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Optionen für Fälle, in denen es nicht möglich ist, einige Schriftarten in ein PDF-Dokument einzubetten. |
| [getFormat](#getFormat--) | PDF-Format. |
| [getIccProfileFileName](#getIccProfileFileName--) | Liefert den Dateinamen des ICC-Profilnamens. Im Falle von null wird das Standard-ICC-Profil verwendet. |
| [getLogFileName](#getLogFileName--) | Pfad zur Datei, in der Kommentare gespeichert werden. |
| [getLogStream](#getLogStream--) | Stream, in dem Kommentare gespeichert werden. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Enthält Flags zur Steuerung des PDF/A-Konvertierungsprozesses für Fälle, in denen das Quelldokument nicht der PDF/A-Spezifikation entspricht. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Diese Eigenschaft ist eine Out-Property. Sie enthält alle Schriftarten (Schriftartnamen), die beim letzten PDF/A-Konvertierungsvorgang nicht auf dem Computer gefunden wurden. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Liefert ein Flag, das den speziellen Konvertierungsmodus zum Erzeugen eines PDF/A-Dokuments mit reduzierter Dateigröße aktiviert/deaktiviert. Dieses Flag wirkt sich derzeit auf die Optimierung der im PDF-Dokument verwendeten Schriftarten aus; möglicherweise wird es in Zukunft auch zur Optimierung anderer Datenstrukturen, wie Grafiken, verwendet werden. Die Kombination dieses Flags und des Modus kann die Dateigröße erheblich reduzieren, gleichzeitig kann sie die Konvertierungsleistung deutlich verringern. |
| [getOutputIntent](#getOutputIntent--) | Liest oder setzt das {@link OutputIntent} für die PDF-Formatkonvertierung. Das {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) gibt das beabsichtigte Ausgabegerät oder die Bedingung an, für die das PDF-Dokument erstellt wird. Es wird verwendet, um sicherzustellen, dass die Farben im Dokument auf dem Zielgerät korrekt wiedergegeben werden. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Strategie zur Verarbeitung von Symbolen aus dem Unicode Private Use Area (PUA). |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Strategie zum Kopieren von Kodierungsdaten für symbolische Schriften, wenn die symbolische TrueType-Schrift mehr als eine Kodierungstabelle enthält. |
| [getTransparencyAction](#getTransparencyAction--) | Aktion für maskierte Bildobjekte |
| [getTransparencyResolution](#getTransparencyResolution--) | Setzt die Auflösung beim Konvertieren transparenter Bilder. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Regeln zur Lösung von Problemen mit Unicode-Mapping. Kann null sein. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Liest/setzt den Durchlauf von Bildströmen im asynchronen Modus. |
| [isLowMemoryMode](#isLowMemoryMode--) | Ist der Low-Memory-Konvertierungsmodus aktiviert |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Ist die Schriftanalyse im seitenweisen Modus aktiviert? Standardwert = false |
| [isTransferInfo](#isTransferInfo--) | Liest oder setzt, ob Daten von Info zu Metadaten beim Konvertieren zu PDF 2.0 übergeben werden. Standardmäßig true. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Standardwert FALSE und die Transparenzfarbe wird beibehalten, um das Dokumentaussehen zu erhalten. Bei Wert TRUE wird die Transparenzfarbe in Nicht-Transparenz umgewandelt, wodurch einige Objekte überdeckt werden könnten. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Strategie zum Ausrichten von Text. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code AlignText} auf true gesetzt ist. |
| [setAlignText](#setAlignText-boolean-) | Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig beeinflusst die Dokumentkonvertierung die Textausrichtung nicht und lässt den Text unverändert. In einigen Fällen führt die Schriftartsubstitution jedoch zu überlappendem Text oder zusätzlichen Leerzeichen im konvertierten Dokument. Wenn dieses Flag gesetzt ist, werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden, die Probleme mit überlappendem Text oder zusätzlichen Leerzeichen haben, da die Verwendung dieses Flags die Leistung verringert und in einigen Fällen den Textinhalt beschädigen könnte. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Liest/setzt den Durchlauf von Bildströmen im asynchronen Modus. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Liefert oder setzt die Einstellungen für das automatische Tagging während der PDF-Formatkonvertierung. Die automatischen Tagging-Einstellungen werden verwendet, um das Verhalten des Auto-Tagging-Prozesses zu konfigurieren, der typischerweise eingesetzt wird, um die Barrierefreiheit und Struktur eines PDF-Dokuments bei der Konvertierung in ein bestimmtes PDF-Format zu verbessern. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Aktion für Bilder mit Soft-Maske. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Aktion für Objekte, die nicht konvertiert werden können. |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Strategie(n) zum Ausschließen überflüssiger Schriftarten und zur Reduzierung der Dateigröße des Dokuments. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code OptimizeFileSize} auf true gesetzt ist. Standardmäßig wird die Kombination der Strategien {@code SubsetFonts} und {@code RemoveDuplicatedFonts} verwendet. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | PDF-Format. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Setzt den Dateinamen des ICC-Profilnamens. Im Falle von null wird das Standard-ICC-Profil verwendet. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Pfad zur Datei, in der Kommentare gespeichert werden. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Stream, in dem Kommentare gespeichert werden. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Ist der Low-Memory-Konvertierungsmodus aktiviert |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Setzt ein Flag, das den speziellen Konvertierungsmodus zum Erzeugen eines PDF/A-Dokuments mit reduzierter Dateigröße aktiviert/deaktiviert. Dieses Flag wirkt sich derzeit auf die Optimierung der im PDF-Dokument verwendeten Schriften aus, möglicherweise wird es in Zukunft auch zur Optimierung anderer Datenstrukturen, wie Grafiken, verwendet werden. Die Kombination aus diesem Flag und dem Modus kann die Dateigröße erheblich reduzieren, gleichzeitig jedoch die Konvertierungsleistung deutlich verringern. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Liest oder setzt das {@link OutputIntent} für die PDF-Formatkonvertierung. Das {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) gibt das beabsichtigte Ausgabegerät oder die Bedingung an, für die das PDF-Dokument erstellt wird. Es wird verwendet, um sicherzustellen, dass die Farben im Dokument auf dem Zielgerät korrekt wiedergegeben werden. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Setzt die Schriftanalyse im seitenweisen Modus auf aktiviert. Standardwert = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Strategie zur Verarbeitung von Symbolen aus dem Unicode Private Use Area (PUA). |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Strategie zum Kopieren von Kodierungsdaten für symbolische Schriften, wenn die symbolische TrueType-Schrift mehr als eine Kodierungstabelle enthält. |
| [setTransferInfo](#setTransferInfo-boolean-) | Liest oder setzt, ob Daten von Info zu Metadaten beim Konvertieren zu PDF 2.0 übergeben werden. Standardmäßig true. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Aktion für maskierte Bildobjekte |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Standardwert FALSE und die Transparenzfarbe wird beibehalten, um das Dokumentaussehen zu erhalten. Bei Wert TRUE wird die Transparenzfarbe in Nicht-Transparenz umgewandelt, wodurch einige Objekte überdeckt werden könnten. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Setzt die Auflösung beim Konvertieren transparenter Bilder. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Regeln zur Lösung von Problemen mit Unicode-Mapping. Kann null sein. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konstruktor

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Strategie zum Ausrichten von Text. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code AlignText} auf true gesetzt ist.

**Returns:**
SegmentAlignStrategy-Element @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig beeinflusst die Dokumentkonvertierung die Textausrichtung nicht und lässt den Text unverändert. In einigen Fällen führt die Schriftartsubstitution jedoch zu überlappendem Text oder zusätzlichen Leerzeichen im konvertierten Dokument. Wenn dieses Flag gesetzt ist, werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden, die Probleme mit überlappendem Text oder zusätzlichen Leerzeichen haben, da die Verwendung dieses Flags die Leistung verringert und in einigen Fällen den Textinhalt beschädigen könnte.

**Returns:**
boolescher Wert

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Liefert oder setzt die Einstellungen für das automatische Tagging während der PDF-Formatkonvertierung. Die automatischen Tagging-Einstellungen werden verwendet, um das Verhalten des Auto-Tagging-Prozesses zu konfigurieren, der typischerweise eingesetzt wird, um die Barrierefreiheit und Struktur eines PDF-Dokuments bei der Konvertierung in ein bestimmtes PDF-Format zu verbessern.

**Returns:**
AutoTaggingSettings-Instanz

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Aktion für Bilder mit Soft-Maske.

**Returns:**
int-Wert

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Liefert ein PdfFormatConversionOptions-Objekt mit Standardparametern.

**Returns:**
PdfFormatConversionOptions-Objekt

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Aktion für Objekte, die nicht konvertiert werden können.

**Returns:**
ConvertErrorAction-Element @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Strategie(n) zum Ausschließen überflüssiger Schriftarten und zur Reduzierung der Dateigröße des Dokuments. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code OptimizeFileSize} auf true gesetzt ist. Standardmäßig wird die Kombination der Strategien {@code SubsetFonts} und {@code RemoveDuplicatedFonts} verwendet.

**Returns:**
Byte-Wert @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Optionen für Fälle, in denen es nicht möglich ist, einige Schriftarten in ein PDF-Dokument einzubetten.

**Returns:**
FontEmbeddingOptions-Objekt

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

PDF-Format.

**Returns:**
PdfFormat Element @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Liefert den Dateinamen des ICC-Profilnamens. Im Falle von null wird das Standard-ICC-Profil verwendet.

**Returns:**
String-Objekt

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Pfad zur Datei, in der Kommentare gespeichert werden.

**Returns:**
String-Objekt

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Stream, in dem Kommentare gespeichert werden.

**Returns:**
OutputStream-Objekt

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Enthält Flags zur Steuerung des PDF/A-Konvertierungsprozesses für Fälle, in denen das Quelldokument nicht der PDF/A-Spezifikation entspricht.

**Returns:**
PdfANonSpecificationFlags-Objekt

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Diese Eigenschaft ist eine Out-Property. Sie enthält alle Schriftarten (Schriftartnamen), die beim letzten PDF/A-Konvertierungsvorgang nicht auf dem Computer gefunden wurden.

**Returns:**
Array von Zeichenketten

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Liefert ein Flag, das den speziellen Konvertierungsmodus zum Erzeugen eines PDF/A-Dokuments mit reduzierter Dateigröße aktiviert/deaktiviert. Dieses Flag wirkt sich derzeit auf die Optimierung der im PDF-Dokument verwendeten Schriftarten aus; möglicherweise wird es in Zukunft auch zur Optimierung anderer Datenstrukturen, wie Grafiken, verwendet werden. Die Kombination dieses Flags und des Modus kann die Dateigröße erheblich reduzieren, gleichzeitig kann sie die Konvertierungsleistung deutlich verringern.

**Returns:**
boolescher Wert

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Liest oder setzt das {@link OutputIntent} für die PDF-Formatkonvertierung. Das {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) gibt das beabsichtigte Ausgabegerät oder die Bedingung an, für die das PDF-Dokument erstellt wird. Es wird verwendet, um sicherzustellen, dass die Farben im Dokument auf dem Zielgerät korrekt wiedergegeben werden.

**Returns:**
OutputIntent-Instanz

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Strategie zur Verarbeitung von Symbolen aus dem Unicode Private Use Area (PUA).

**Returns:**
PuaProcessingStrategy-Element @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Strategie zum Kopieren von Kodierungsdaten für symbolische Schriften, wenn die symbolische TrueType-Schrift mehr als eine Kodierungstabelle enthält.

**Returns:**
PdfASymbolicFontEncodingStrategy-Objekt

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Aktion für maskierte Bildobjekte

**Returns:**
ConvertTransparencyAction-Element @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Setzt die Auflösung beim Konvertieren transparenter Bilder. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 300.

**Returns:**
Auflösungswert

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Regeln zur Lösung von Problemen mit Unicode-Mapping. Kann null sein.

**Returns:**
ToUnicodeProcessingRules-Objekt

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Liest/setzt den Durchlauf von Bildströmen im asynchronen Modus.

**Returns:**
boolescher Wert

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Ist der Low-Memory-Konvertierungsmodus aktiviert

**Returns:**
boolescher Wert

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Ist die Schriftanalyse im seitenweisen Modus aktiviert? Standardwert = false

**Returns:**
boolescher Wert

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Liest oder setzt, ob Daten von Info zu Metadaten beim Konvertieren zu PDF 2.0 übergeben werden. Standardmäßig true.

**Returns:**
boolescher Wert

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Standardwert FALSE und die Transparenzfarbe wird beibehalten, um das Dokumentaussehen zu erhalten. Bei Wert TRUE wird die Transparenzfarbe in Nicht-Transparenz umgewandelt, wodurch einige Objekte überdeckt werden könnten.

**Returns:**
boolescher Wert

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Strategie zum Ausrichten von Text. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code AlignText} auf true gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignStrategy |  | SegmentAlignStrategy-Element @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig beeinflusst die Dokumentkonvertierung die Textausrichtung nicht und lässt den Text unverändert. In einigen Fällen führt die Schriftartsubstitution jedoch zu überlappendem Text oder zusätzlichen Leerzeichen im konvertierten Dokument. Wenn dieses Flag gesetzt ist, werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden, die Probleme mit überlappendem Text oder zusätzlichen Leerzeichen haben, da die Verwendung dieses Flags die Leistung verringert und in einigen Fällen den Textinhalt beschädigen könnte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Liest/setzt den Durchlauf von Bildströmen im asynchronen Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Liefert oder setzt die Einstellungen für das automatische Tagging während der PDF-Formatkonvertierung. Die automatischen Tagging-Einstellungen werden verwendet, um das Verhalten des Auto-Tagging-Prozesses zu konfigurieren, der typischerweise eingesetzt wird, um die Barrierefreiheit und Struktur eines PDF-Dokuments bei der Konvertierung in ein bestimmtes PDF-Format zu verbessern.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Aktion für Bilder mit Soft-Maske.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Aktion für Objekte, die nicht konvertiert werden können.

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Strategie(n) zum Ausschließen überflüssiger Schriftarten und zur Reduzierung der Dateigröße des Dokuments. Dieser Parameter ist nur sinnvoll, wenn das Flag {@code OptimizeFileSize} auf true gesetzt ist. Standardmäßig wird die Kombination der Strategien {@code SubsetFonts} und {@code RemoveDuplicatedFonts} verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
PDF-Format.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Setzt den Dateinamen des ICC-Profilnamens. Im Falle von null wird das Standard-ICC-Profil verwendet.

### setLogFileName {#setLogFileName-java.lang.String-}
Pfad zur Datei, in der Kommentare gespeichert werden.

### setLogStream {#setLogStream-java.io.OutputStream-}
Stream, in dem Kommentare gespeichert werden.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Ist der Low-Memory-Konvertierungsmodus aktiviert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Setzt ein Flag, das den speziellen Konvertierungsmodus zum Erzeugen eines PDF/A-Dokuments mit reduzierter Dateigröße aktiviert/deaktiviert. Dieses Flag wirkt sich derzeit auf die Optimierung der im PDF-Dokument verwendeten Schriften aus, möglicherweise wird es in Zukunft auch zur Optimierung anderer Datenstrukturen, wie Grafiken, verwendet werden. Die Kombination aus diesem Flag und dem Modus kann die Dateigröße erheblich reduzieren, gleichzeitig jedoch die Konvertierungsleistung deutlich verringern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Liest oder setzt das {@link OutputIntent} für die PDF-Formatkonvertierung. Das {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) gibt das beabsichtigte Ausgabegerät oder die Bedingung an, für die das PDF-Dokument erstellt wird. Es wird verwendet, um sicherzustellen, dass die Farben im Dokument auf dem Zielgerät korrekt wiedergegeben werden.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Setzt die Schriftanalyse im seitenweisen Modus auf aktiviert. Standardwert = false

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| b |  | boolescher Wert |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Strategie zur Verarbeitung von Symbolen aus dem Unicode Private Use Area (PUA).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PuaProcessingStrategy-Element @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Strategie zum Kopieren von Kodierungsdaten für symbolische Schriften, wenn die symbolische TrueType-Schrift mehr als eine Kodierungstabelle enthält.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Liest oder setzt, ob Daten von Info zu Metadaten beim Konvertieren zu PDF 2.0 übergeben werden. Standardmäßig true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Aktion für maskierte Bildobjekte

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Standardwert FALSE und die Transparenzfarbe wird beibehalten, um das Dokumentaussehen zu erhalten. Bei Wert TRUE wird die Transparenzfarbe in Nicht-Transparenz umgewandelt, wodurch einige Objekte überdeckt werden könnten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Setzt die Auflösung beim Konvertieren transparenter Bilder. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 300.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpi |  | Auflösungswert |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Regeln zur Lösung von Problemen mit Unicode-Mapping. Kann null sein.
