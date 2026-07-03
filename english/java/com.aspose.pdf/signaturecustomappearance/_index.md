---
title: SignatureCustomAppearance
second_title: Aspose.PDF for Java API Reference
description: An abstract class which represents signature custon appearance object.
type: docs
weight: 4500
url: /java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

An abstract class which represents signature custon appearance object.

## Constructors

| Constructor | Description |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Inititalizes new instance of the {@link SignatureCustomAppearance} class. |

## Methods

| Method | Description |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Gets/sets background color. Default value: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | Gets/sets contact info label. Default value: "Contact". |
| [getCulture](#getCulture--) | Gets/sets culture info value. Default value: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Gets/sets date signed label. Default value: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Gets/sets digital signed label. Default value: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Gets/sets font family name. It should be existed in the document. Default value: Arial. |
| [getFontSize](#getFontSize--) | Gets/sets font size. Default value: 10. |
| [getForegroundColor](#getForegroundColor--) | Gets/sets foreground color (color of text). Default value: Blue. |
| [getLocationLabel](#getLocationLabel--) | Gets/sets location label. Default value: "Location". |
| [getReasonLabel](#getReasonLabel--) | Gets/sets reason label. Default value: "Reason". |
| [getRotation](#getRotation--) | Gets or sets signature rotation. |
| [isForegroundImage](#isForegroundImage--) | Gets or sets a value indicating whether the image in the signature appearance is drawn as a foreground image. Default value: false. |
| [isShowContactInfo](#isShowContactInfo--) | Gets/sets contact info visibility. Default value: true. |
| [isShowLocation](#isShowLocation--) | Gets/sets location visibility. Default value: true. |
| [isShowReason](#isShowReason--) | Gets/sets reason visibility. Default value: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Gets/sets the usage state of the {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Gets/sets background color. Default value: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Gets/sets contact info label. Default value: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Gets/sets culture info value. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Gets/sets date signed label. Default value: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Gets/sets digital signed label. Default value: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Gets/sets font family name. It should be existed in the document. Default value: Arial. |
| [setFontSize](#setFontSize-double-) | Gets/sets font size. Default value: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Gets/sets foreground color (color of text). Default value: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | Gets or sets a value indicating whether the image in the signature appearance is drawn as a foreground image. Default value: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Gets/sets location label. Default value: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Gets/sets reason label. Default value: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Gets or sets signature rotation. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Gets/sets contact info visibility. Default value: true. |
| [setShowLocation](#setShowLocation-boolean-) | Gets/sets location visibility. Default value: true. |
| [setShowReason](#setShowReason-boolean-) | Gets/sets reason visibility. Default value: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Gets/sets the usage state of the {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Inititalizes new instance of the {@link SignatureCustomAppearance} class.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Gets/sets background color. Default value: Transparent.

**Returns:**
com.aspose.pdf.Color instance

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Gets/sets contact info label. Default value: "Contact".

**Returns:**
String value

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Gets/sets culture info value. Default value: InvariantCulture.

**Returns:**
Locale value

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Gets/sets date signed label. Default value: "Date".

**Returns:**
String value

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss".

**Returns:**
String value

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
String value

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Gets/sets digital signed label. Default value: "Digitally signed by".

**Returns:**
String value

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization

**Returns:**
array of int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Gets/sets font family name. It should be existed in the document. Default value: Arial.

**Returns:**
String value

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Gets/sets font size. Default value: 10.

**Returns:**
double value

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Gets/sets foreground color (color of text). Default value: Blue.

**Returns:**
com.aspose.pdf.Color instance

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Gets/sets location label. Default value: "Location".

**Returns:**
String value

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Gets/sets reason label. Default value: "Reason".

**Returns:**
String value

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Gets or sets signature rotation.

**Returns:**
Rotation element

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Gets or sets a value indicating whether the image in the signature appearance is drawn as a foreground image. Default value: false.

**Returns:**
boolean value

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Gets/sets contact info visibility. Default value: true.

**Returns:**
boolean value

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Gets/sets location visibility. Default value: true.

**Returns:**
boolean value

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Gets/sets reason visibility. Default value: true.

**Returns:**
boolean value

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Gets/sets the usage state of the {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
boolean value

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Gets/sets background color. Default value: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Gets/sets contact info label. Default value: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Gets/sets culture info value.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Gets/sets date signed label. Default value: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Gets/sets digital signed label. Default value: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Gets/sets font family name. It should be existed in the document. Default value: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Gets/sets font size. Default value: 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Gets/sets foreground color (color of text). Default value: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Gets or sets a value indicating whether the image in the signature appearance is drawn as a foreground image. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Gets/sets location label. Default value: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Gets/sets reason label. Default value: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Gets or sets signature rotation.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Gets/sets contact info visibility. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Gets/sets location visibility. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Gets/sets reason visibility. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Gets/sets the usage state of the {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
