---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe astratta che rappresenta l'oggetto di aspetto personalizzato della firma."
type: docs
weight: 4500
url: /it/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

Una classe astratta che rappresenta l'oggetto di aspetto personalizzato della firma.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Inizializza una nuova istanza della classe {@link SignatureCustomAppearance}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene/imposta il colore di sfondo. Valore predefinito: Trasparente. |
| [getContactInfoLabel](#getContactInfoLabel--) | Ottiene/imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact". |
| [getCulture](#getCulture--) | Ottiene/imposta il valore delle informazioni culturali. Valore predefinito: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Ottiene/imposta l'etichetta della data di firma. Valore predefinito: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Ottiene/imposta il formato data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Ottiene/imposta il formato locale data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Ottiene/imposta l'etichetta della firma digitale. Valore predefinito: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Ottiene/imposta il formato per l'ordine degli elementi nella stringa Subject. Esempi di risultato: C=UK, CN=Org, O=Organization oppure CN=Org, C=UK, O=Organization oppure O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Ottiene/imposta il nome della famiglia di caratteri. Deve esistere nel documento. Valore predefinito: Arial. |
| [getFontSize](#getFontSize--) | Ottiene/imposta la dimensione del carattere. Valore predefinito: 10. |
| [getForegroundColor](#getForegroundColor--) | Ottiene/imposta il colore di primo piano (colore del testo). Valore predefinito: Blu. |
| [getLocationLabel](#getLocationLabel--) | Ottiene/imposta l'etichetta della posizione. Valore predefinito: "Location". |
| [getReasonLabel](#getReasonLabel--) | Ottiene/imposta l'etichetta del motivo. Valore predefinito: "Reason". |
| [getRotation](#getRotation--) | Ottiene o imposta la rotazione della firma. |
| [isForegroundImage](#isForegroundImage--) | Ottiene o imposta un valore che indica se l'immagine nell'aspetto della firma è disegnata come immagine di primo piano. Valore predefinito: false. |
| [isShowContactInfo](#isShowContactInfo--) | Ottiene/imposta la visibilità delle informazioni di contatto. Valore predefinito: true. |
| [isShowLocation](#isShowLocation--) | Ottiene/imposta la visibilità della posizione. Valore predefinito: true. |
| [isShowReason](#isShowReason--) | Ottiene/imposta la visibilità del motivo. Valore predefinito: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Ottiene/imposta lo stato di utilizzo di {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ottiene/imposta il colore di sfondo. Valore predefinito: Trasparente. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Ottiene/imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Ottiene/imposta il valore delle informazioni culturali. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Ottiene/imposta l'etichetta della data di firma. Valore predefinito: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Ottiene/imposta il formato data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Ottiene/imposta il formato locale data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Ottiene/imposta l'etichetta della firma digitale. Valore predefinito: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Ottiene/imposta il formato per l'ordine degli elementi nella stringa Subject. Esempi di risultato: C=UK, CN=Org, O=Organization oppure CN=Org, C=UK, O=Organization oppure O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Ottiene/imposta il nome della famiglia di caratteri. Deve esistere nel documento. Valore predefinito: Arial. |
| [setFontSize](#setFontSize-double-) | Ottiene/imposta la dimensione del carattere. Valore predefinito: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Ottiene/imposta il colore di primo piano (colore del testo). Valore predefinito: Blu. |
| [setForegroundImage](#setForegroundImage-boolean-) | Ottiene o imposta un valore che indica se l'immagine nell'aspetto della firma è disegnata come immagine di primo piano. Valore predefinito: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Ottiene/imposta l'etichetta della posizione. Valore predefinito: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Ottiene/imposta l'etichetta del motivo. Valore predefinito: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Ottiene o imposta la rotazione della firma. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Ottiene/imposta la visibilità delle informazioni di contatto. Valore predefinito: true. |
| [setShowLocation](#setShowLocation-boolean-) | Ottiene/imposta la visibilità della posizione. Valore predefinito: true. |
| [setShowReason](#setShowReason-boolean-) | Ottiene/imposta la visibilità del motivo. Valore predefinito: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Ottiene/imposta lo stato di utilizzo di {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Inizializza una nuova istanza della classe {@link SignatureCustomAppearance}.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Ottiene/imposta il colore di sfondo. Valore predefinito: Trasparente.

**Returns:**
istanza di com.aspose.pdf.Color

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Ottiene/imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact".

**Returns:**
valore String

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Ottiene/imposta il valore delle informazioni culturali. Valore predefinito: InvariantCulture.

**Returns:**
Valore della locale

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Ottiene/imposta l'etichetta della data di firma. Valore predefinito: "Date".

**Returns:**
valore String

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Ottiene/imposta il formato data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss".

**Returns:**
valore String

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Ottiene/imposta il formato locale data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
valore String

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Ottiene/imposta l'etichetta della firma digitale. Valore predefinito: "Digitally signed by".

**Returns:**
valore String

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Ottiene/imposta il formato per l'ordine degli elementi nella stringa Subject. Esempi di risultato: C=UK, CN=Org, O=Organization oppure CN=Org, C=UK, O=Organization oppure O=Organization

**Returns:**
array di int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Ottiene/imposta il nome della famiglia di caratteri. Deve esistere nel documento. Valore predefinito: Arial.

**Returns:**
valore String

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Ottiene/imposta la dimensione del carattere. Valore predefinito: 10.

**Returns:**
valore double

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Ottiene/imposta il colore di primo piano (colore del testo). Valore predefinito: Blu.

**Returns:**
istanza di com.aspose.pdf.Color

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Ottiene/imposta l'etichetta della posizione. Valore predefinito: "Location".

**Returns:**
valore String

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Ottiene/imposta l'etichetta del motivo. Valore predefinito: "Reason".

**Returns:**
valore String

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Ottiene o imposta la rotazione della firma.

**Returns:**
Elemento di rotazione

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Ottiene o imposta un valore che indica se l'immagine nell'aspetto della firma è disegnata come immagine di primo piano. Valore predefinito: false.

**Returns:**
valore booleano

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Ottiene/imposta la visibilità delle informazioni di contatto. Valore predefinito: true.

**Returns:**
valore booleano

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Ottiene/imposta la visibilità della posizione. Valore predefinito: true.

**Returns:**
valore booleano

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Ottiene/imposta la visibilità del motivo. Valore predefinito: true.

**Returns:**
valore booleano

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Ottiene/imposta lo stato di utilizzo di {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
valore booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ottiene/imposta il colore di sfondo. Valore predefinito: Trasparente.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Ottiene/imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Ottiene/imposta il valore delle informazioni culturali.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Ottiene/imposta l'etichetta della data di firma. Valore predefinito: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Ottiene/imposta il formato data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Ottiene/imposta il formato locale data/ora. Valore predefinito: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Ottiene/imposta l'etichetta della firma digitale. Valore predefinito: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Ottiene/imposta il formato per l'ordine degli elementi nella stringa Subject. Esempi di risultato: C=UK, CN=Org, O=Organization oppure CN=Org, C=UK, O=Organization oppure O=Organization

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Ottiene/imposta il nome della famiglia di caratteri. Deve esistere nel documento. Valore predefinito: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Ottiene/imposta la dimensione del carattere. Valore predefinito: 10.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Ottiene/imposta il colore di primo piano (colore del testo). Valore predefinito: Blu.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Ottiene o imposta un valore che indica se l'immagine nell'aspetto della firma è disegnata come immagine di primo piano. Valore predefinito: false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Ottiene/imposta l'etichetta della posizione. Valore predefinito: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Ottiene/imposta l'etichetta del motivo. Valore predefinito: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Ottiene o imposta la rotazione della firma.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Ottiene/imposta la visibilità delle informazioni di contatto. Valore predefinito: true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Ottiene/imposta la visibilità della posizione. Valore predefinito: true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Ottiene/imposta la visibilità del motivo. Valore predefinito: true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Ottiene/imposta lo stato di utilizzo di {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
