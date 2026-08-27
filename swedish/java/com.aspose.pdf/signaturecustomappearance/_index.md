---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Aspose.PDF för Java API-referens"
description: "En abstrakt klass som representerar ett anpassat utseendeobjekt för signatur."
type: docs
weight: 4500
url: /sv/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

En abstrakt klass som representerar ett anpassat utseendeobjekt för signatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Initierar en ny instans av klassen {@link SignatureCustomAppearance}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar/inställer bakgrundsfärg. Standardvärde: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | Hämtar/inställer etikett för kontaktinformation. Standardvärde: "Contact". |
| [getCulture](#getCulture--) | Hämtar/inställer kulturinfo‑värde. Standardvärde: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Hämtar/inställer etikett för datum för signering. Standardvärde: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Hämtar/inställer datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Hämtar/inställer lokalt datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Hämtar/inställer etikett för digital signatur. Standardvärde: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Hämtar/inställer format för ordning av element i Subject‑strängen. Resultatexempel: C=UK, CN=Org, O=Organization eller CN=Org, C=UK, O=Organization eller O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Hämtar/inställer teckensnittsfamiljens namn. Det bör finnas i dokumentet. Standardvärde: Arial. |
| [getFontSize](#getFontSize--) | Hämtar/inställer teckenstorlek. Standardvärde: 10. |
| [getForegroundColor](#getForegroundColor--) | Hämtar/inställer förgrundsfärg (textfärg). Standardvärde: Blue. |
| [getLocationLabel](#getLocationLabel--) | Hämtar/inställer etikett för plats. Standardvärde: "Location". |
| [getReasonLabel](#getReasonLabel--) | Hämtar/inställer etikett för anledning. Standardvärde: "Reason". |
| [getRotation](#getRotation--) | Hämtar eller inställer signaturrotation. |
| [isForegroundImage](#isForegroundImage--) | Hämtar eller inställer ett värde som indikerar om bilden i signaturens utseende ritas som en förgrundsbild. Standardvärde: false. |
| [isShowContactInfo](#isShowContactInfo--) | Hämtar/inställer synlighet för kontaktinformation. Standardvärde: true. |
| [isShowLocation](#isShowLocation--) | Hämtar/inställer synlighet för plats. Standardvärde: true. |
| [isShowReason](#isShowReason--) | Hämtar/inställer synlighet för anledning. Standardvärde: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Hämtar/inställer användningstillståndet för {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Hämtar/inställer bakgrundsfärg. Standardvärde: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Hämtar/inställer etikett för kontaktinformation. Standardvärde: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Hämtar/inställer kulturinfo‑värde. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Hämtar/inställer etikett för datum för signering. Standardvärde: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Hämtar/inställer datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Hämtar/inställer lokalt datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Hämtar/inställer etikett för digital signatur. Standardvärde: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Hämtar/inställer format för ordning av element i Subject‑strängen. Resultatexempel: C=UK, CN=Org, O=Organization eller CN=Org, C=UK, O=Organization eller O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Hämtar/inställer teckensnittsfamiljens namn. Det bör finnas i dokumentet. Standardvärde: Arial. |
| [setFontSize](#setFontSize-double-) | Hämtar/inställer teckenstorlek. Standardvärde: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Hämtar/inställer förgrundsfärg (textfärg). Standardvärde: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | Hämtar eller inställer ett värde som indikerar om bilden i signaturens utseende ritas som en förgrundsbild. Standardvärde: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Hämtar/inställer etikett för plats. Standardvärde: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Hämtar/inställer etikett för anledning. Standardvärde: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Hämtar eller inställer signaturrotation. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Hämtar/inställer synlighet för kontaktinformation. Standardvärde: true. |
| [setShowLocation](#setShowLocation-boolean-) | Hämtar/inställer synlighet för plats. Standardvärde: true. |
| [setShowReason](#setShowReason-boolean-) | Hämtar/inställer synlighet för anledning. Standardvärde: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Hämtar/inställer användningstillståndet för {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Initierar en ny instans av klassen {@link SignatureCustomAppearance}.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Hämtar/inställer bakgrundsfärg. Standardvärde: Transparent.

**Returns:**
com.aspose.pdf.Color-instans

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Hämtar/inställer etikett för kontaktinformation. Standardvärde: "Contact".

**Returns:**
String värde

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Hämtar/inställer kulturinfo‑värde. Standardvärde: InvariantCulture.

**Returns:**
Locale-värde

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Hämtar/inställer etikett för datum för signering. Standardvärde: "Date".

**Returns:**
String värde

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Hämtar/inställer datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss".

**Returns:**
String värde

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Hämtar/inställer lokalt datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
String värde

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Hämtar/inställer etikett för digital signatur. Standardvärde: "Digitally signed by".

**Returns:**
String värde

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Hämtar/inställer format för ordning av element i Subject‑strängen. Resultatexempel: C=UK, CN=Org, O=Organization eller CN=Org, C=UK, O=Organization eller O=Organization

**Returns:**
array av int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Hämtar/inställer teckensnittsfamiljens namn. Det bör finnas i dokumentet. Standardvärde: Arial.

**Returns:**
String värde

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Hämtar/inställer teckenstorlek. Standardvärde: 10.

**Returns:**
double-värde

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Hämtar/inställer förgrundsfärg (textfärg). Standardvärde: Blue.

**Returns:**
com.aspose.pdf.Color-instans

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Hämtar/inställer etikett för plats. Standardvärde: "Location".

**Returns:**
String värde

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Hämtar/inställer etikett för anledning. Standardvärde: "Reason".

**Returns:**
String värde

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Hämtar eller inställer signaturrotation.

**Returns:**
Rotationselement

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Hämtar eller inställer ett värde som indikerar om bilden i signaturens utseende ritas som en förgrundsbild. Standardvärde: false.

**Returns:**
booleskt värde

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Hämtar/inställer synlighet för kontaktinformation. Standardvärde: true.

**Returns:**
booleskt värde

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Hämtar/inställer synlighet för plats. Standardvärde: true.

**Returns:**
booleskt värde

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Hämtar/inställer synlighet för anledning. Standardvärde: true.

**Returns:**
booleskt värde

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Hämtar/inställer användningstillståndet för {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
booleskt värde

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Hämtar/inställer bakgrundsfärg. Standardvärde: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Hämtar/inställer etikett för kontaktinformation. Standardvärde: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Hämtar/inställer kulturinfo‑värde.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Hämtar/inställer etikett för datum för signering. Standardvärde: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Hämtar/inställer datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Hämtar/inställer lokalt datum‑tid‑format. Standardvärde: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Hämtar/inställer etikett för digital signatur. Standardvärde: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Hämtar/inställer format för ordning av element i Subject‑strängen. Resultatexempel: C=UK, CN=Org, O=Organization eller CN=Org, C=UK, O=Organization eller O=Organization

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | array av int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Hämtar/inställer teckensnittsfamiljens namn. Det bör finnas i dokumentet. Standardvärde: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Hämtar/inställer teckenstorlek. Standardvärde: 10.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Hämtar/inställer förgrundsfärg (textfärg). Standardvärde: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Hämtar eller inställer ett värde som indikerar om bilden i signaturens utseende ritas som en förgrundsbild. Standardvärde: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Hämtar/inställer etikett för plats. Standardvärde: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Hämtar/inställer etikett för anledning. Standardvärde: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Hämtar eller inställer signaturrotation.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Hämtar/inställer synlighet för kontaktinformation. Standardvärde: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Hämtar/inställer synlighet för plats. Standardvärde: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Hämtar/inställer synlighet för anledning. Standardvärde: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Hämtar/inställer användningstillståndet för {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
