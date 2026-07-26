---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Einstellungen für die Auto-Tagging-Funktionalität in PDF-Dokumenten bereit. Die {@link AutoTaggingSettings}-Klasse ermöglicht die Konfiguration von Optionen für das automatische Tagging von PDF-Inhalten. Sie."
type: docs
weight: 230
url: /de/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Bietet Einstellungen für die Auto-Tagging-Funktionalität in PDF-Dokumenten. Die {@link AutoTaggingSettings} Klasse ermöglicht die Konfiguration von Optionen für das automatische Tagging von PDF-Inhalten. Sie enthält Eigenschaften, um das Auto-Tagging zu aktivieren oder zu deaktivieren, eine Strategie zur Überschrifterkennung festzulegen und Überschriftenebenen basierend auf Schriftgrößen zu definieren.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefault](#getDefault--) | Ermittelt die Standardeinstellungen für die Auto-Tagging-Funktionalität in PDF-Dokumenten. Die Standardeinstellungen aktivieren das Auto-Tagging und verwenden die automatische Strategie zur Überschriftenerkennung. Diese Einstellungen können als Basis-Konfiguration für die PDF-Formatkonvertierung oder andere Vorgänge, die automatisches Tagging von PDF-Inhalten erfordern, verwendet werden. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Ermittelt oder setzt einen Wert, der angibt, ob die Auto-Tagging-Funktionalität aktiviert ist. Wenn aktiviert, erzeugt die Auto-Tagging-Funktionalität automatisch getaggte Inhalte für das PDF-Dokument, was die Barrierefreiheit und Struktur verbessern kann. |
| [getHeadingLevels](#getHeadingLevels--) | Liest oder setzt die Überschriftenebenen, die zur Bestimmung der Struktur von Überschriften in einem PDF-Dokument verwendet werden. Die {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)})-Eigenschaft ermöglicht die Konfiguration der Zuordnung von Schriftgrößen zu Überschriftenebenen. Dies wird während des Auto-Tagging-Prozesses verwendet, um anhand der Schriftgröße von Textelementen im Dokument geeignete Überschriftenebenen zu identifizieren und zuzuweisen. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Liest oder setzt die Strategie, die zur Erkennung von Überschriften im Dokument während des Auto-Taggings verwendet wird. Die {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)})-Eigenschaft bestimmt, wie Überschriften im Dokument identifiziert werden. Verfügbare Strategien umfassen die Erkennung von Überschriften basierend auf Gliederungen, heuristischer Analyse oder automatischer Erkennung. Das Setzen dieser Eigenschaft auf {@link HeadingRecognitionStrategy#None} deaktiviert die Überschriften-Erkennung. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Ermittelt oder setzt einen Wert, der angibt, ob die Auto-Tagging-Funktionalität aktiviert ist. Wenn aktiviert, erzeugt die Auto-Tagging-Funktionalität automatisch getaggte Inhalte für das PDF-Dokument, was die Barrierefreiheit und Struktur verbessern kann. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Liest oder setzt die Überschriftenebenen, die zur Bestimmung der Struktur von Überschriften in einem PDF-Dokument verwendet werden. Die {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)})-Eigenschaft ermöglicht die Konfiguration der Zuordnung von Schriftgrößen zu Überschriftenebenen. Dies wird während des Auto-Tagging-Prozesses verwendet, um anhand der Schriftgröße von Textelementen im Dokument geeignete Überschriftenebenen zu identifizieren und zuzuweisen. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Liest oder setzt die Strategie, die zur Erkennung von Überschriften im Dokument während des Auto-Taggings verwendet wird. Die {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)})-Eigenschaft bestimmt, wie Überschriften im Dokument identifiziert werden. Verfügbare Strategien umfassen die Erkennung von Überschriften basierend auf Gliederungen, heuristischer Analyse oder automatischer Erkennung. Das Setzen dieser Eigenschaft auf {@link HeadingRecognitionStrategy#None} deaktiviert die Überschriften-Erkennung. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Ermittelt die Standardeinstellungen für die Auto-Tagging-Funktionalität in PDF-Dokumenten. Die Standardeinstellungen aktivieren das Auto-Tagging und verwenden die automatische Strategie zur Überschriftenerkennung. Diese Einstellungen können als Basis-Konfiguration für die PDF-Formatkonvertierung oder andere Vorgänge, die automatisches Tagging von PDF-Inhalten erfordern, verwendet werden.

**Returns:**
AutoTaggingSettings-Instanz

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Ermittelt oder setzt einen Wert, der angibt, ob die Auto-Tagging-Funktionalität aktiviert ist. Wenn aktiviert, erzeugt die Auto-Tagging-Funktionalität automatisch getaggte Inhalte für das PDF-Dokument, was die Barrierefreiheit und Struktur verbessern kann.

**Returns:**
boolescher Wert

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Liest oder setzt die Überschriftenebenen, die zur Bestimmung der Struktur von Überschriften in einem PDF-Dokument verwendet werden. Die {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)})-Eigenschaft ermöglicht die Konfiguration der Zuordnung von Schriftgrößen zu Überschriftenebenen. Dies wird während des Auto-Tagging-Prozesses verwendet, um anhand der Schriftgröße von Textelementen im Dokument geeignete Überschriftenebenen zu identifizieren und zuzuweisen.

**Returns:**
HeadingLevels Instanz

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Liest oder setzt die Strategie, die zur Erkennung von Überschriften im Dokument während des Auto-Taggings verwendet wird. Die {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)})-Eigenschaft bestimmt, wie Überschriften im Dokument identifiziert werden. Verfügbare Strategien umfassen die Erkennung von Überschriften basierend auf Gliederungen, heuristischer Analyse oder automatischer Erkennung. Das Setzen dieser Eigenschaft auf {@link HeadingRecognitionStrategy#None} deaktiviert die Überschriften-Erkennung.

**Returns:**
HeadingRecognitionStrategy Element

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Ermittelt oder setzt einen Wert, der angibt, ob die Auto-Tagging-Funktionalität aktiviert ist. Wenn aktiviert, erzeugt die Auto-Tagging-Funktionalität automatisch getaggte Inhalte für das PDF-Dokument, was die Barrierefreiheit und Struktur verbessern kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Liest oder setzt die Überschriftenebenen, die zur Bestimmung der Struktur von Überschriften in einem PDF-Dokument verwendet werden. Die {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)})-Eigenschaft ermöglicht die Konfiguration der Zuordnung von Schriftgrößen zu Überschriftenebenen. Dies wird während des Auto-Tagging-Prozesses verwendet, um anhand der Schriftgröße von Textelementen im Dokument geeignete Überschriftenebenen zu identifizieren und zuzuweisen.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Liest oder setzt die Strategie, die zur Erkennung von Überschriften im Dokument während des Auto-Taggings verwendet wird. Die {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)})-Eigenschaft bestimmt, wie Überschriften im Dokument identifiziert werden. Verfügbare Strategien umfassen die Erkennung von Überschriften basierend auf Gliederungen, heuristischer Analyse oder automatischer Erkennung. Das Setzen dieser Eigenschaft auf {@link HeadingRecognitionStrategy#None} deaktiviert die Überschriften-Erkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | HeadingRecognitionStrategy Element |
