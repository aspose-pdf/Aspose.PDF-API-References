---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine abstrakte Klasse, die ein benutzerdefiniertes Signaturdarstellungsobjekt repräsentiert."
type: docs
weight: 4500
url: /de/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

Eine abstrakte Klasse, die ein benutzerdefiniertes Signaturdarstellungsobjekt repräsentiert.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Initialisiert eine neue Instanz der {@link SignatureCustomAppearance}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Abrufen/Setzen Hintergrundfarbe. Standardwert: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | Abrufen/Setzen Kontaktinfo-Beschriftung. Standardwert: "Contact". |
| [getCulture](#getCulture--) | Abrufen/Setzen Kulturinfo-Wert. Standardwert: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Abrufen/Setzen Beschriftung des unterschriebenen Datums. Standardwert: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Abrufen/Setzen Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Abrufen/Setzen lokales Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Abrufen/Setzen Beschriftung für digital signiert. Standardwert: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Abrufen/Setzen Format für die Reihenfolge der Elemente in der Betreff-Zeichenkette. Ergebnisbeispiele: C=UK, CN=Org, O=Organization oder CN=Org, C=UK, O=Organization oder O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Abrufen/Setzen Schriftfamilienname. Er muss im Dokument vorhanden sein. Standardwert: Arial. |
| [getFontSize](#getFontSize--) | Abrufen/Setzen Schriftgröße. Standardwert: 10. |
| [getForegroundColor](#getForegroundColor--) | Abrufen/Setzen Vordergrundfarbe (Farbe des Textes). Standardwert: Blue. |
| [getLocationLabel](#getLocationLabel--) | Abrufen/Setzen Ortsbeschriftung. Standardwert: "Location". |
| [getReasonLabel](#getReasonLabel--) | Abrufen/Setzen Grundbeschriftung. Standardwert: "Reason". |
| [getRotation](#getRotation--) | Abrufen oder Setzen der Signaturrotation. |
| [isForegroundImage](#isForegroundImage--) | Abrufen oder Setzen eines Werts, der angibt, ob das Bild in der Signaturdarstellung als Vordergrundbild gezeichnet wird. Standardwert: false. |
| [isShowContactInfo](#isShowContactInfo--) | Abrufen/Setzen Sichtbarkeit der Kontaktinfo. Standardwert: true. |
| [isShowLocation](#isShowLocation--) | Abrufen/Setzen Sichtbarkeit des Ortes. Standardwert: true. |
| [isShowReason](#isShowReason--) | Abrufen/Setzen Sichtbarkeit des Grundes. Standardwert: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Liest/Schreibt den Nutzungsstatus von {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Abrufen/Setzen Hintergrundfarbe. Standardwert: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Abrufen/Setzen Kontaktinfo-Beschriftung. Standardwert: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Liest/Schreibt den Kulturinfo-Wert. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Abrufen/Setzen Beschriftung des unterschriebenen Datums. Standardwert: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Abrufen/Setzen Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Abrufen/Setzen lokales Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Abrufen/Setzen Beschriftung für digital signiert. Standardwert: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Abrufen/Setzen Format für die Reihenfolge der Elemente in der Betreff-Zeichenkette. Ergebnisbeispiele: C=UK, CN=Org, O=Organization oder CN=Org, C=UK, O=Organization oder O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Abrufen/Setzen Schriftfamilienname. Er muss im Dokument vorhanden sein. Standardwert: Arial. |
| [setFontSize](#setFontSize-double-) | Abrufen/Setzen Schriftgröße. Standardwert: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Abrufen/Setzen Vordergrundfarbe (Farbe des Textes). Standardwert: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | Abrufen oder Setzen eines Werts, der angibt, ob das Bild in der Signaturdarstellung als Vordergrundbild gezeichnet wird. Standardwert: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Abrufen/Setzen Ortsbeschriftung. Standardwert: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Abrufen/Setzen Grundbeschriftung. Standardwert: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Abrufen oder Setzen der Signaturrotation. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Abrufen/Setzen Sichtbarkeit der Kontaktinfo. Standardwert: true. |
| [setShowLocation](#setShowLocation-boolean-) | Abrufen/Setzen Sichtbarkeit des Ortes. Standardwert: true. |
| [setShowReason](#setShowReason-boolean-) | Abrufen/Setzen Sichtbarkeit des Grundes. Standardwert: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Liest/Schreibt den Nutzungsstatus von {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Initialisiert eine neue Instanz der {@link SignatureCustomAppearance}-Klasse.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Abrufen/Setzen Hintergrundfarbe. Standardwert: Transparent.

**Returns:**
com.aspose.pdf.Color-Instanz

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Abrufen/Setzen Kontaktinfo-Beschriftung. Standardwert: "Contact".

**Returns:**
String Wert

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Abrufen/Setzen Kulturinfo-Wert. Standardwert: InvariantCulture.

**Returns:**
Locale-Wert

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Abrufen/Setzen Beschriftung des unterschriebenen Datums. Standardwert: "Date".

**Returns:**
String Wert

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Abrufen/Setzen Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss".

**Returns:**
String Wert

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Abrufen/Setzen lokales Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
String Wert

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Abrufen/Setzen Beschriftung für digital signiert. Standardwert: "Digitally signed by".

**Returns:**
String Wert

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Abrufen/Setzen Format für die Reihenfolge der Elemente in der Betreff-Zeichenkette. Ergebnisbeispiele: C=UK, CN=Org, O=Organization oder CN=Org, C=UK, O=Organization oder O=Organization

**Returns:**
Array von int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Abrufen/Setzen Schriftfamilienname. Er muss im Dokument vorhanden sein. Standardwert: Arial.

**Returns:**
String Wert

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Abrufen/Setzen Schriftgröße. Standardwert: 10.

**Returns:**
double-Wert

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Abrufen/Setzen Vordergrundfarbe (Farbe des Textes). Standardwert: Blue.

**Returns:**
com.aspose.pdf.Color-Instanz

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Abrufen/Setzen Ortsbeschriftung. Standardwert: "Location".

**Returns:**
String Wert

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Abrufen/Setzen Grundbeschriftung. Standardwert: "Reason".

**Returns:**
String Wert

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Abrufen oder Setzen der Signaturrotation.

**Returns:**
Rotations-Element

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Abrufen oder Setzen eines Werts, der angibt, ob das Bild in der Signaturdarstellung als Vordergrundbild gezeichnet wird. Standardwert: false.

**Returns:**
boolescher Wert

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Abrufen/Setzen Sichtbarkeit der Kontaktinfo. Standardwert: true.

**Returns:**
boolescher Wert

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Abrufen/Setzen Sichtbarkeit des Ortes. Standardwert: true.

**Returns:**
boolescher Wert

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Abrufen/Setzen Sichtbarkeit des Grundes. Standardwert: true.

**Returns:**
boolescher Wert

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Liest/Schreibt den Nutzungsstatus von {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
boolescher Wert

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Abrufen/Setzen Hintergrundfarbe. Standardwert: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Abrufen/Setzen Kontaktinfo-Beschriftung. Standardwert: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Liest/Schreibt den Kulturinfo-Wert.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Abrufen/Setzen Beschriftung des unterschriebenen Datums. Standardwert: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Abrufen/Setzen Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Abrufen/Setzen lokales Datumszeitformat. Standardwert: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Abrufen/Setzen Beschriftung für digital signiert. Standardwert: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Abrufen/Setzen Format für die Reihenfolge der Elemente in der Betreff-Zeichenkette. Ergebnisbeispiele: C=UK, CN=Org, O=Organization oder CN=Org, C=UK, O=Organization oder O=Organization

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Array von int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Abrufen/Setzen Schriftfamilienname. Er muss im Dokument vorhanden sein. Standardwert: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Abrufen/Setzen Schriftgröße. Standardwert: 10.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Abrufen/Setzen Vordergrundfarbe (Farbe des Textes). Standardwert: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Abrufen oder Setzen eines Werts, der angibt, ob das Bild in der Signaturdarstellung als Vordergrundbild gezeichnet wird. Standardwert: false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Abrufen/Setzen Ortsbeschriftung. Standardwert: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Abrufen/Setzen Grundbeschriftung. Standardwert: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Abrufen oder Setzen der Signaturrotation.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Abrufen/Setzen Sichtbarkeit der Kontaktinfo. Standardwert: true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Abrufen/Setzen Sichtbarkeit des Ortes. Standardwert: true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Abrufen/Setzen Sichtbarkeit des Grundes. Standardwert: true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Liest/Schreibt den Nutzungsstatus von {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
