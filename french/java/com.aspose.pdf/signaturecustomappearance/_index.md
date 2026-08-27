---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe abstraite qui représente un objet d'apparence personnalisée de signature."
type: docs
weight: 4500
url: /fr/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

Une classe abstraite qui représente un objet d'apparence personnalisée de signature.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Initialise une nouvelle instance de la classe {@link SignatureCustomAppearance}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Obtient/définit la couleur d'arrière-plan. Valeur par défaut : Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | Obtient/définit l'étiquette d'information de contact. Valeur par défaut : "Contact". |
| [getCulture](#getCulture--) | Obtient/définit la valeur d'information culturelle. Valeur par défaut : InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Obtient/définit l'étiquette de date de signature. Valeur par défaut : "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Obtient/définit le format de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Obtient/définit le format local de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Obtient/définit l'étiquette de signature numérique. Valeur par défaut : "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Obtient/définit le format d'ordre des éléments dans la chaîne Subject. Exemples de résultats : C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Obtient/définit le nom de la famille de polices. Elle doit exister dans le document. Valeur par défaut : Arial. |
| [getFontSize](#getFontSize--) | Obtient/définit la taille de la police. Valeur par défaut : 10. |
| [getForegroundColor](#getForegroundColor--) | Obtient/définit la couleur de premier plan (couleur du texte). Valeur par défaut : Blue. |
| [getLocationLabel](#getLocationLabel--) | Obtient/définit l'étiquette d'emplacement. Valeur par défaut : "Location". |
| [getReasonLabel](#getReasonLabel--) | Obtient/definit le libellé du motif. Valeur par défaut : "Reason". |
| [getRotation](#getRotation--) | Obtient ou définit la rotation de la signature. |
| [isForegroundImage](#isForegroundImage--) | Obtient ou définit une valeur indiquant si l'image dans l'apparence de la signature est dessinée comme image de premier plan. Valeur par défaut : false. |
| [isShowContactInfo](#isShowContactInfo--) | Obtient/definit la visibilité des informations de contact. Valeur par défaut : true. |
| [isShowLocation](#isShowLocation--) | Obtient/definit la visibilité de l'emplacement. Valeur par défaut : true. |
| [isShowReason](#isShowReason--) | Obtient/definit la visibilité du motif. Valeur par défaut : true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Obtient/definit l'état d'utilisation de {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtient/définit la couleur d'arrière-plan. Valeur par défaut : Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Obtient/définit l'étiquette d'information de contact. Valeur par défaut : "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Obtient/definit la valeur des informations culturelles. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Obtient/définit l'étiquette de date de signature. Valeur par défaut : "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Obtient/définit le format de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Obtient/définit le format local de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Obtient/définit l'étiquette de signature numérique. Valeur par défaut : "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Obtient/définit le format d'ordre des éléments dans la chaîne Subject. Exemples de résultats : C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Obtient/définit le nom de la famille de polices. Elle doit exister dans le document. Valeur par défaut : Arial. |
| [setFontSize](#setFontSize-double-) | Obtient/définit la taille de la police. Valeur par défaut : 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Obtient/définit la couleur de premier plan (couleur du texte). Valeur par défaut : Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | Obtient ou définit une valeur indiquant si l'image dans l'apparence de la signature est dessinée comme image de premier plan. Valeur par défaut : false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Obtient/définit l'étiquette d'emplacement. Valeur par défaut : "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Obtient/definit le libellé du motif. Valeur par défaut : "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Obtient ou définit la rotation de la signature. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Obtient/definit la visibilité des informations de contact. Valeur par défaut : true. |
| [setShowLocation](#setShowLocation-boolean-) | Obtient/definit la visibilité de l'emplacement. Valeur par défaut : true. |
| [setShowReason](#setShowReason-boolean-) | Obtient/definit la visibilité du motif. Valeur par défaut : true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Obtient/definit l'état d'utilisation de {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Initialise une nouvelle instance de la classe {@link SignatureCustomAppearance}.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtient/définit la couleur d'arrière-plan. Valeur par défaut : Transparent.

**Returns:**
com.aspose.pdf.Color instance

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Obtient/définit l'étiquette d'information de contact. Valeur par défaut : "Contact".

**Returns:**
valeur String

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Obtient/définit la valeur d'information culturelle. Valeur par défaut : InvariantCulture.

**Returns:**
Valeur de la locale

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Obtient/définit l'étiquette de date de signature. Valeur par défaut : "Date".

**Returns:**
valeur String

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Obtient/définit le format de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss".

**Returns:**
valeur String

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Obtient/définit le format local de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
valeur String

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Obtient/définit l'étiquette de signature numérique. Valeur par défaut : "Digitally signed by".

**Returns:**
valeur String

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Obtient/définit le format d'ordre des éléments dans la chaîne Subject. Exemples de résultats : C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization

**Returns:**
tableau d'entiers @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Obtient/définit le nom de la famille de polices. Elle doit exister dans le document. Valeur par défaut : Arial.

**Returns:**
valeur String

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Obtient/définit la taille de la police. Valeur par défaut : 10.

**Returns:**
valeur double

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Obtient/définit la couleur de premier plan (couleur du texte). Valeur par défaut : Blue.

**Returns:**
com.aspose.pdf.Color instance

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Obtient/définit l'étiquette d'emplacement. Valeur par défaut : "Location".

**Returns:**
valeur String

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Obtient/definit le libellé du motif. Valeur par défaut : "Reason".

**Returns:**
valeur String

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Obtient ou définit la rotation de la signature.

**Returns:**
Élément de rotation

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Obtient ou définit une valeur indiquant si l'image dans l'apparence de la signature est dessinée comme image de premier plan. Valeur par défaut : false.

**Returns:**
valeur booléenne

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Obtient/definit la visibilité des informations de contact. Valeur par défaut : true.

**Returns:**
valeur booléenne

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Obtient/definit la visibilité de l'emplacement. Valeur par défaut : true.

**Returns:**
valeur booléenne

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Obtient/definit la visibilité du motif. Valeur par défaut : true.

**Returns:**
valeur booléenne

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Obtient/definit l'état d'utilisation de {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
valeur booléenne

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtient/définit la couleur d'arrière-plan. Valeur par défaut : Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Obtient/définit l'étiquette d'information de contact. Valeur par défaut : "Contact".

### setCulture {#setCulture-java.util.Locale-}
Obtient/definit la valeur des informations culturelles.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Obtient/définit l'étiquette de date de signature. Valeur par défaut : "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Obtient/définit le format de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Obtient/définit le format local de date-heure. Valeur par défaut : "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Obtient/définit l'étiquette de signature numérique. Valeur par défaut : "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Obtient/définit le format d'ordre des éléments dans la chaîne Subject. Exemples de résultats : C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau d'entiers @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Obtient/définit le nom de la famille de polices. Elle doit exister dans le document. Valeur par défaut : Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Obtient/définit la taille de la police. Valeur par défaut : 10.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Obtient/définit la couleur de premier plan (couleur du texte). Valeur par défaut : Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Obtient ou définit une valeur indiquant si l'image dans l'apparence de la signature est dessinée comme image de premier plan. Valeur par défaut : false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Obtient/définit l'étiquette d'emplacement. Valeur par défaut : "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Obtient/definit le libellé du motif. Valeur par défaut : "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Obtient ou définit la rotation de la signature.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Obtient/definit la visibilité des informations de contact. Valeur par défaut : true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Obtient/definit la visibilité de l'emplacement. Valeur par défaut : true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Obtient/definit la visibilité du motif. Valeur par défaut : true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Obtient/definit l'état d'utilisation de {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
