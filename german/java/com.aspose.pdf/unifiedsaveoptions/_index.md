---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse stellt Speicheroptionen dar, die einen einheitlichen Konvertierungsweg verwenden (mit einheitlichem internem Dokumentmodell)."
type: docs
weight: 5420
url: /de/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Diese Klasse stellt Speicheroptionen dar, die einen einheitlichen Konvertierungsweg verwenden (mit einheitlichem internem Dokumentmodell).

## Felder

| Feld | Beschreibung |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Verarbeite Seiten in wenigen Threads. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Stellt einen internen Prozessor für Fortschrittsereignisse dar, der während der Konvertierung arbeitet und Konvertierungsereignisse interner Konvertierungsstufen in externe Gesamtfortschrittsereignisse übersetzt. Außerdem sendet die Klasse Ereignisse, die das Freigeben von nicht mehr benötigten Ressourcen ermöglichen. Diese interne Klasse verarbeitet Ereignisse des Fortschritts von PDF zu APS und von APS zu [Other format], um den Gesamtfortschritt zu berechnen und den Code des Kunden über diesen Gesamtfortschritt zu informieren. Die Klasse verwendet zwei Arten von Ereignissen: ApsToExternal‑Modellkonvertierung und Ereignisse der Konvertierung PDF zu APS, um Gesamtfortschrittsereignisse zu erzeugen. Der Export besteht aus drei Phasen: 1) PDF zu APS, 2) APS‑Erkennung, 3) APS‑Export zum Zielformat. Der Konstruktor ermöglicht die Einstellung, wie viele Seiten konvertiert werden und welchen ungefähren Anteil diese oder jene Phase am Gesamtfortschritt hat. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bild oder Text aus PDF-Dokumenten mit OCR-Unterschicht. Wert: {@code true} Der Text wird im Ergebnisdokument extrahiert; andernfalls {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer von Zielformaten (z. B. MsWord für das DOCS‑Format) manchmal sichtbare Grenzen zwischen den Teilen der Hintergrundbilder, da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von der von Acrobat Reader abweichen. Wenn das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen desselben Hintergrundbildes aufweist, versuchen Sie bitte, diese Einstellung zu verwenden, um den unerwünschten Effekt zu entfernen. ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich, verwenden Sie diese Option daher nur, wenn sie wirklich notwendig ist. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Dieses Attribut aktiviert die Funktion zum Extrahieren von Bild oder Text aus PDF-Dokumenten mit OCR-Unterschicht. </p>Wert: {@code true} Der Text wird im Ergebnisdokument extrahiert; andernfalls {@code false}. <hr> Standardwert == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Stellt einen internen Prozessor für Fortschrittsereignisse dar, der während der Konvertierung arbeitet und Konvertierungsereignisse interner Konvertierungsstufen in externe Gesamtfortschrittsereignisse übersetzt. Außerdem sendet die Klasse Ereignisse, die das Freigeben von nicht mehr benötigten Ressourcen ermöglichen. Diese interne Klasse verarbeitet Ereignisse des Fortschritts von PDF zu APS und von APS zu [Other format], um den Gesamtfortschritt zu berechnen und den Code des Kunden über diesen Gesamtfortschritt zu informieren. Die Klasse verwendet zwei Arten von Ereignissen: ApsToExternal‑Modellkonvertierung und Ereignisse der Konvertierung PDF zu APS, um Gesamtfortschrittsereignisse zu erzeugen. Der Export besteht aus drei Phasen: 1) PDF zu APS, 2) APS‑Erkennung, 3) APS‑Export zum Zielformat. Der Konstruktor ermöglicht die Einstellung, wie viele Seiten konvertiert werden und welchen ungefähren Anteil diese oder jene Phase am Gesamtfortschritt hat. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer von Zielformaten (z. B. MsWord für das DOCS‑Format) manchmal sichtbare Grenzen zwischen den Teilen der Hintergrundbilder, da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von der von Acrobat Reader abweichen. Wenn das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen desselben Hintergrundbildes aufweist, versuchen Sie bitte, diese Einstellung zu verwenden, um den unerwünschten Effekt zu entfernen. ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich, verwenden Sie diese Option daher nur, wenn sie wirklich notwendig ist. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Verarbeite Seiten in wenigen Threads.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Stellt einen internen Prozessor für Fortschrittsereignisse dar, der während der Konvertierung arbeitet und Konvertierungsereignisse interner Konvertierungsstufen in externe Gesamtfortschrittsereignisse übersetzt. Außerdem sendet die Klasse Ereignisse, die das Freigeben von nicht mehr benötigten Ressourcen ermöglichen. Diese interne Klasse verarbeitet Ereignisse des Fortschritts von PDF zu APS und von APS zu [Other format], um den Gesamtfortschritt zu berechnen und den Code des Kunden über diesen Gesamtfortschritt zu informieren. Die Klasse verwendet zwei Arten von Ereignissen: ApsToExternal‑Modellkonvertierung und Ereignisse der Konvertierung PDF zu APS, um Gesamtfortschrittsereignisse zu erzeugen. Der Export besteht aus drei Phasen: 1) PDF zu APS, 2) APS‑Erkennung, 3) APS‑Export zum Zielformat. Der Konstruktor ermöglicht die Einstellung, wie viele Seiten konvertiert werden und welchen ungefähren Anteil diese oder jene Phase am Gesamtfortschritt hat.

**Returns:**
ConversionProgressEventsTranslator‑Instanz

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Dieses Attribut aktiviert die Funktion zum Extrahieren von Bild oder Text aus PDF-Dokumenten mit OCR-Unterschicht. Wert: {@code true} Der Text wird im Ergebnisdokument extrahiert; andernfalls {@code false}.

**Returns:**
boolescher Wert

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer von Zielformaten (z. B. MsWord für das DOCS‑Format) manchmal sichtbare Grenzen zwischen den Teilen der Hintergrundbilder, da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von der von Acrobat Reader abweichen. Wenn das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen desselben Hintergrundbildes aufweist, versuchen Sie bitte, diese Einstellung zu verwenden, um den unerwünschten Effekt zu entfernen. ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich, verwenden Sie diese Option daher nur, wenn sie wirklich notwendig ist.

**Returns:**
boolescher Wert

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Dieses Attribut aktiviert die Funktion zum Extrahieren von Bild oder Text aus PDF-Dokumenten mit OCR-Unterschicht. </p>Wert: {@code true} Der Text wird im Ergebnisdokument extrahiert; andernfalls {@code false}. <hr> Standardwert == false

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Stellt einen internen Prozessor für Fortschrittsereignisse dar, der während der Konvertierung arbeitet und Konvertierungsereignisse interner Konvertierungsstufen in externe Gesamtfortschrittsereignisse übersetzt. Außerdem sendet die Klasse Ereignisse, die das Freigeben von nicht mehr benötigten Ressourcen ermöglichen. Diese interne Klasse verarbeitet Ereignisse des Fortschritts von PDF zu APS und von APS zu [Other format], um den Gesamtfortschritt zu berechnen und den Code des Kunden über diesen Gesamtfortschritt zu informieren. Die Klasse verwendet zwei Arten von Ereignissen: ApsToExternal‑Modellkonvertierung und Ereignisse der Konvertierung PDF zu APS, um Gesamtfortschrittsereignisse zu erzeugen. Der Export besteht aus drei Phasen: 1) PDF zu APS, 2) APS‑Erkennung, 3) APS‑Export zum Zielformat. Der Konstruktor ermöglicht die Einstellung, wie viele Seiten konvertiert werden und welchen ungefähren Anteil diese oder jene Phase am Gesamtfortschritt hat.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer von Zielformaten (z. B. MsWord für das DOCS‑Format) manchmal sichtbare Grenzen zwischen den Teilen der Hintergrundbilder, da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von der von Acrobat Reader abweichen. Wenn das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen desselben Hintergrundbildes aufweist, versuchen Sie bitte, diese Einstellung zu verwenden, um den unerwünschten Effekt zu entfernen. ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich, verwenden Sie diese Option daher nur, wenn sie wirklich notwendig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | boolescher Wert |
