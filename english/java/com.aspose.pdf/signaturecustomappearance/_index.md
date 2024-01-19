---
title: SignatureCustomAppearance
second_title: Aspose.PDF for Java API Reference
description: An abstract class which represents signature custon appearance object.
type: docs
weight: 328
url: /java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object
```
public final class SignatureCustomAppearance
```

An abstract class which represents signature custon appearance object.
## Constructors

| Constructor | Description |
| --- | --- |
| [SignatureCustomAppearance()](#SignatureCustomAppearance--) | Inititalizes new instance of the [SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFontFamilyName()](#getFontFamilyName--) | Gets/sets font family name. |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Gets/sets font family name. |
| [getFontSize()](#getFontSize--) | Gets/sets font size. |
| [getForegroundColor()](#getForegroundColor--) | Gets/sets foreground color (color of text). |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | Gets/sets foreground color (color of text). |
| [getBackgroundColor()](#getBackgroundColor--) | Gets/sets background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets/sets background color. |
| [setFontSize(double value)](#setFontSize-double-) | Gets/sets font size. |
| [isShowContactInfo()](#isShowContactInfo--) | Gets/sets contact info visibility. |
| [setShowContactInfo(boolean value)](#setShowContactInfo-boolean-) | Gets/sets contact info visibility. |
| [isShowReason()](#isShowReason--) | Gets/sets reason visibility. |
| [setShowReason(boolean value)](#setShowReason-boolean-) | Gets/sets reason visibility. |
| [isShowLocation()](#isShowLocation--) | Gets/sets location visibility. |
| [setShowLocation(boolean value)](#setShowLocation-boolean-) | Gets/sets location visibility. |
| [getContactInfoLabel()](#getContactInfoLabel--) | Gets/sets contact info label. |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Gets/sets contact info label. |
| [getReasonLabel()](#getReasonLabel--) | Gets/sets reason label. |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Gets/sets reason label. |
| [getLocationLabel()](#getLocationLabel--) | Gets/sets location label. |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Gets/sets location label. |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Gets/sets digital signed label. |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Gets/sets digital signed label. |
| [isUseDigitalSubjectFormat()](#isUseDigitalSubjectFormat--) | Gets/sets the usage state of the  DigitalSubjectFormat (\#getDigitalSubjectFormat\#getDigitalSubjectFormat/\#setDigitalSubjectFormat(int[])\#setDigitalSubjectFormat(int[])). |
| [setUseDigitalSubjectFormat(boolean value)](#setUseDigitalSubjectFormat-boolean-) | Gets/sets the usage state of the  DigitalSubjectFormat (\#getDigitalSubjectFormat\#getDigitalSubjectFormat/\#setDigitalSubjectFormat(int[])\#setDigitalSubjectFormat(int[])). |
| [getDigitalSubjectFormat()](#getDigitalSubjectFormat--) | Gets/sets format for order of elements in Subject string. |
| [setDigitalSubjectFormat(int[] value)](#setDigitalSubjectFormat-int---) | Gets/sets format for order of elements in Subject string. |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Gets/sets date signed label. |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Gets/sets date signed label. |
| [getDateTimeLocalFormat()](#getDateTimeLocalFormat--) | Gets/sets datetime local format. |
| [setDateTimeLocalFormat(String value)](#setDateTimeLocalFormat-java.lang.String-) | Gets/sets datetime local format. |
| [getDateTimeFormat()](#getDateTimeFormat--) | Gets/sets datetime format. |
| [setDateTimeFormat(String value)](#setDateTimeFormat-java.lang.String-) | Gets/sets datetime format. |
| [getCulture()](#getCulture--) | Gets/sets culture info value. |
| [setCulture(Locale value)](#setCulture-java.util.Locale-) | Gets/sets culture info value. |
| [getRotation()](#getRotation--) | Gets or sets signature rotation. |
| [setRotation(int value)](#setRotation-int-) | Gets or sets signature rotation. |
### SignatureCustomAppearance() {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```


Inititalizes new instance of the [SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) class.

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Gets/sets font family name. It should be existed in the document. Default value: Arial.

**Returns:**
java.lang.String - String value
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Gets/sets font family name. It should be existed in the document. Default value: Arial.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Gets/sets font size. Default value: 10.

**Returns:**
double - double value
### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Gets/sets foreground color (color of text). Default value: Blue.

**Returns:**
[Color](../../com.aspose.pdf/color) - com.aspose.pdf.Color instance
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public final void setForegroundColor(Color value)
```


Gets/sets foreground color (color of text). Default value: Blue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | com.aspose.pdf.Color instance |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets/sets background color. Default value: Transparent.

**Returns:**
[Color](../../com.aspose.pdf/color) - com.aspose.pdf.Color instance
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Gets/sets background color. Default value: Transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | com.aspose.pdf.Color instance |

### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Gets/sets font size. Default value: 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### isShowContactInfo() {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```


Gets/sets contact info visibility. Default value: true.

**Returns:**
boolean - boolean value
### setShowContactInfo(boolean value) {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```


Gets/sets contact info visibility. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isShowReason() {#isShowReason--}
```
public final boolean isShowReason()
```


Gets/sets reason visibility. Default value: true.

**Returns:**
boolean - boolean value
### setShowReason(boolean value) {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```


Gets/sets reason visibility. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isShowLocation() {#isShowLocation--}
```
public final boolean isShowLocation()
```


Gets/sets location visibility. Default value: true.

**Returns:**
boolean - boolean value
### setShowLocation(boolean value) {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```


Gets/sets location visibility. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Gets/sets contact info label. Default value: "Contact".

**Returns:**
java.lang.String - String value
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Gets/sets contact info label. Default value: "Contact".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Gets/sets reason label. Default value: "Reason".

**Returns:**
java.lang.String - String value
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Gets/sets reason label. Default value: "Reason".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Gets/sets location label. Default value: "Location".

**Returns:**
java.lang.String - String value
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Gets/sets location label. Default value: "Location".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Gets/sets digital signed label. Default value: "Digitally signed by".

**Returns:**
java.lang.String - String value
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Gets/sets digital signed label. Default value: "Digitally signed by".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### isUseDigitalSubjectFormat() {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```


Gets/sets the usage state of the  DigitalSubjectFormat (\#getDigitalSubjectFormat\#getDigitalSubjectFormat/\#setDigitalSubjectFormat(int[])\#setDigitalSubjectFormat(int[])).

**Returns:**
boolean - boolean value
### setUseDigitalSubjectFormat(boolean value) {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```


Gets/sets the usage state of the  DigitalSubjectFormat (\#getDigitalSubjectFormat\#getDigitalSubjectFormat/\#setDigitalSubjectFormat(int[])\#setDigitalSubjectFormat(int[])).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getDigitalSubjectFormat() {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```


Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization

**Returns:**
int[] - array of int
### setDigitalSubjectFormat(int[] value) {#setDigitalSubjectFormat-int---}
```
public final void setDigitalSubjectFormat(int[] value)
```


Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | array of int |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Gets/sets date signed label. Default value: "Date".

**Returns:**
java.lang.String - String value
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Gets/sets date signed label. Default value: "Date".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDateTimeLocalFormat() {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```


Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
java.lang.String - String value
### setDateTimeLocalFormat(String value) {#setDateTimeLocalFormat-java.lang.String-}
```
public final void setDateTimeLocalFormat(String value)
```


Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDateTimeFormat() {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```


Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss".

**Returns:**
java.lang.String - String value
### setDateTimeFormat(String value) {#setDateTimeFormat-java.lang.String-}
```
public final void setDateTimeFormat(String value)
```


Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getCulture() {#getCulture--}
```
public final Locale getCulture()
```


Gets/sets culture info value. Default value: InvariantCulture.

**Returns:**
java.util.Locale - Locale value
### setCulture(Locale value) {#setCulture-java.util.Locale-}
```
public final void setCulture(Locale value)
```


Gets/sets culture info value. Default value: InvariantCulture.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale | Locale value |

### getRotation() {#getRotation--}
```
public final int getRotation()
```


Gets or sets signature rotation.

**Returns:**
int - Rotation element
### setRotation(int value) {#setRotation-int-}
```
public final void setRotation(int value)
```


Gets or sets signature rotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Rotation element |

