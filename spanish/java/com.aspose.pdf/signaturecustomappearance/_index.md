---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase abstracta que representa un objeto de apariencia personalizada de firma."
type: docs
weight: 4500
url: /es/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

Una clase abstracta que representa un objeto de apariencia personalizada de firma.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Inicializa una nueva instancia de la clase {@link SignatureCustomAppearance}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene/establece el color de fondo. Valor predeterminado: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | Obtiene/establece la etiqueta de información de contacto. Valor predeterminado: "Contact". |
| [getCulture](#getCulture--) | Obtiene/establece el valor de información cultural. Valor predeterminado: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Obtiene/establece la etiqueta de fecha de firma. Valor predeterminado: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Obtiene/establece el formato de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Obtiene/establece el formato local de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Obtiene/establece la etiqueta de firmado digitalmente. Valor predeterminado: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Obtiene/establece el formato para el orden de los elementos en la cadena Subject. Ejemplos de resultados: C=UK, CN=Org, O=Organization o CN=Org, C=UK, O=Organization o O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Obtiene/establece el nombre de la familia tipográfica. Debe existir en el documento. Valor predeterminado: Arial. |
| [getFontSize](#getFontSize--) | Obtiene/establece el tamaño de fuente. Valor predeterminado: 10. |
| [getForegroundColor](#getForegroundColor--) | Obtiene/establece el color de primer plano (color del texto). Valor predeterminado: Blue. |
| [getLocationLabel](#getLocationLabel--) | Obtiene/establece la etiqueta de ubicación. Valor predeterminado: "Location". |
| [getReasonLabel](#getReasonLabel--) | Obtiene/establece la etiqueta de razón. Valor predeterminado: "Reason". |
| [getRotation](#getRotation--) | Obtiene o establece la rotación de la firma. |
| [isForegroundImage](#isForegroundImage--) | Obtiene o establece un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen de primer plano. Valor predeterminado: false. |
| [isShowContactInfo](#isShowContactInfo--) | Obtiene/establece la visibilidad de la información de contacto. Valor predeterminado: true. |
| [isShowLocation](#isShowLocation--) | Obtiene/establece la visibilidad de la ubicación. Valor predeterminado: true. |
| [isShowReason](#isShowReason--) | Obtiene/establece la visibilidad de la razón. Valor predeterminado: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Obtiene/establece el estado de uso del {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtiene/establece el color de fondo. Valor predeterminado: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Obtiene/establece la etiqueta de información de contacto. Valor predeterminado: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Obtiene/establece el valor de la información cultural. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Obtiene/establece la etiqueta de fecha de firma. Valor predeterminado: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Obtiene/establece el formato de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Obtiene/establece el formato local de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Obtiene/establece la etiqueta de firmado digitalmente. Valor predeterminado: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Obtiene/establece el formato para el orden de los elementos en la cadena Subject. Ejemplos de resultados: C=UK, CN=Org, O=Organization o CN=Org, C=UK, O=Organization o O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Obtiene/establece el nombre de la familia tipográfica. Debe existir en el documento. Valor predeterminado: Arial. |
| [setFontSize](#setFontSize-double-) | Obtiene/establece el tamaño de fuente. Valor predeterminado: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Obtiene/establece el color de primer plano (color del texto). Valor predeterminado: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | Obtiene o establece un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen de primer plano. Valor predeterminado: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Obtiene/establece la etiqueta de ubicación. Valor predeterminado: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Obtiene/establece la etiqueta de razón. Valor predeterminado: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Obtiene o establece la rotación de la firma. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Obtiene/establece la visibilidad de la información de contacto. Valor predeterminado: true. |
| [setShowLocation](#setShowLocation-boolean-) | Obtiene/establece la visibilidad de la ubicación. Valor predeterminado: true. |
| [setShowReason](#setShowReason-boolean-) | Obtiene/establece la visibilidad de la razón. Valor predeterminado: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Obtiene/establece el estado de uso del {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Inicializa una nueva instancia de la clase {@link SignatureCustomAppearance}.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtiene/establece el color de fondo. Valor predeterminado: Transparent.

**Returns:**
instancia de com.aspose.pdf.Color

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Obtiene/establece la etiqueta de información de contacto. Valor predeterminado: "Contact".

**Returns:**
valor String

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Obtiene/establece el valor de información cultural. Valor predeterminado: InvariantCulture.

**Returns:**
Valor de Locale

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Obtiene/establece la etiqueta de fecha de firma. Valor predeterminado: "Date".

**Returns:**
valor String

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Obtiene/establece el formato de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss".

**Returns:**
valor String

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Obtiene/establece el formato local de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
valor String

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Obtiene/establece la etiqueta de firmado digitalmente. Valor predeterminado: "Digitally signed by".

**Returns:**
valor String

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Obtiene/establece el formato para el orden de los elementos en la cadena Subject. Ejemplos de resultados: C=UK, CN=Org, O=Organization o CN=Org, C=UK, O=Organization o O=Organization

**Returns:**
matriz de int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Obtiene/establece el nombre de la familia tipográfica. Debe existir en el documento. Valor predeterminado: Arial.

**Returns:**
valor String

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Obtiene/establece el tamaño de fuente. Valor predeterminado: 10.

**Returns:**
valor double

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Obtiene/establece el color de primer plano (color del texto). Valor predeterminado: Blue.

**Returns:**
instancia de com.aspose.pdf.Color

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Obtiene/establece la etiqueta de ubicación. Valor predeterminado: "Location".

**Returns:**
valor String

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Obtiene/establece la etiqueta de razón. Valor predeterminado: "Reason".

**Returns:**
valor String

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Obtiene o establece la rotación de la firma.

**Returns:**
Elemento de rotación

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Obtiene o establece un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen de primer plano. Valor predeterminado: false.

**Returns:**
valor booleano

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Obtiene/establece la visibilidad de la información de contacto. Valor predeterminado: true.

**Returns:**
valor booleano

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Obtiene/establece la visibilidad de la ubicación. Valor predeterminado: true.

**Returns:**
valor booleano

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Obtiene/establece la visibilidad de la razón. Valor predeterminado: true.

**Returns:**
valor booleano

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Obtiene/establece el estado de uso del {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtiene/establece el color de fondo. Valor predeterminado: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Obtiene/establece la etiqueta de información de contacto. Valor predeterminado: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Obtiene/establece el valor de la información cultural.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Obtiene/establece la etiqueta de fecha de firma. Valor predeterminado: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Obtiene/establece el formato de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Obtiene/establece el formato local de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Obtiene/establece la etiqueta de firmado digitalmente. Valor predeterminado: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Obtiene/establece el formato para el orden de los elementos en la cadena Subject. Ejemplos de resultados: C=UK, CN=Org, O=Organization o CN=Org, C=UK, O=Organization o O=Organization

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Obtiene/establece el nombre de la familia tipográfica. Debe existir en el documento. Valor predeterminado: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Obtiene/establece el tamaño de fuente. Valor predeterminado: 10.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Obtiene/establece el color de primer plano (color del texto). Valor predeterminado: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Obtiene o establece un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen de primer plano. Valor predeterminado: false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Obtiene/establece la etiqueta de ubicación. Valor predeterminado: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Obtiene/establece la etiqueta de razón. Valor predeterminado: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Obtiene o establece la rotación de la firma.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Obtiene/establece la visibilidad de la información de contacto. Valor predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Obtiene/establece la visibilidad de la ubicación. Valor predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Obtiene/establece la visibilidad de la razón. Valor predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Obtiene/establece el estado de uso del {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
