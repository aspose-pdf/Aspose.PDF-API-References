---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Aspose.PDF for Java API Referansı"
description: "İmza özel görünüm nesnesini temsil eden soyut bir sınıf."
type: docs
weight: 4500
url: /tr/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

İmza özel görünüm nesnesini temsil eden soyut bir sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Yeni bir {@link SignatureCustomAppearance} sınıf örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Arka plan rengini alır/ayarlar. Varsayılan değer: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | İletişim bilgisi etiketini alır/ayarlar. Varsayılan değer: "Contact". |
| [getCulture](#getCulture--) | Kültür bilgisi değerini alır/ayarlar. Varsayılan değer: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | İmza tarihi etiketi alır/ayarlar. Varsayılan değer: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Yerel tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Dijital imza etiketi alır/ayarlar. Varsayılan değer: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Subject dizesindeki öğelerin sırası için biçimi alır/ayarlar. Sonuç örnekleri: C=UK, CN=Org, O=Organization veya CN=Org, C=UK, O=Organization veya O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Yazı tipi ailesi adını alır/ayarlar. Belgede mevcut olmalıdır. Varsayılan değer: Arial. |
| [getFontSize](#getFontSize--) | Yazı tipi boyutunu alır/ayarlar. Varsayılan değer: 10. |
| [getForegroundColor](#getForegroundColor--) | Ön plan rengini (metin rengi) alır/ayarlar. Varsayılan değer: Blue. |
| [getLocationLabel](#getLocationLabel--) | Konum etiketini alır/ayarlar. Varsayılan değer: "Location". |
| [getReasonLabel](#getReasonLabel--) | Sebep etiketini alır/ayar. Varsayılan değer: "Reason". |
| [getRotation](#getRotation--) | İmza dönüşünü alır veya ayarlar. |
| [isForegroundImage](#isForegroundImage--) | İmza görünümündeki görüntünün ön plan görüntüsü olarak çizilip çizilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer: false. |
| [isShowContactInfo](#isShowContactInfo--) | İletişim bilgisi görünürlüğünü alır/ayar. Varsayılan değer: true. |
| [isShowLocation](#isShowLocation--) | Konum görünürlüğünü alır/ayar. Varsayılan değer: true. |
| [isShowReason](#isShowReason--) | Sebep görünürlüğünü alır/ayar. Varsayılan değer: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | DigitalSubjectFormat'ın kullanım durumunu alır/ayar {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Arka plan rengini alır/ayarlar. Varsayılan değer: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | İletişim bilgisi etiketini alır/ayarlar. Varsayılan değer: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Kültür bilgisi değerini alır/ayar. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | İmza tarihi etiketi alır/ayarlar. Varsayılan değer: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Yerel tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Dijital imza etiketi alır/ayarlar. Varsayılan değer: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Subject dizesindeki öğelerin sırası için biçimi alır/ayarlar. Sonuç örnekleri: C=UK, CN=Org, O=Organization veya CN=Org, C=UK, O=Organization veya O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Yazı tipi ailesi adını alır/ayarlar. Belgede mevcut olmalıdır. Varsayılan değer: Arial. |
| [setFontSize](#setFontSize-double-) | Yazı tipi boyutunu alır/ayarlar. Varsayılan değer: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Ön plan rengini (metin rengi) alır/ayarlar. Varsayılan değer: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | İmza görünümündeki görüntünün ön plan görüntüsü olarak çizilip çizilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Konum etiketini alır/ayarlar. Varsayılan değer: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Sebep etiketini alır/ayar. Varsayılan değer: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | İmza dönüşünü alır veya ayarlar. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | İletişim bilgisi görünürlüğünü alır/ayar. Varsayılan değer: true. |
| [setShowLocation](#setShowLocation-boolean-) | Konum görünürlüğünü alır/ayar. Varsayılan değer: true. |
| [setShowReason](#setShowReason-boolean-) | Sebep görünürlüğünü alır/ayar. Varsayılan değer: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | DigitalSubjectFormat'ın kullanım durumunu alır/ayar {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Yeni bir {@link SignatureCustomAppearance} sınıf örneği başlatır.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Arka plan rengini alır/ayarlar. Varsayılan değer: Transparent.

**Returns:**
com.aspose.pdf.Color örneği

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

İletişim bilgisi etiketini alır/ayarlar. Varsayılan değer: "Contact".

**Returns:**
String değeri

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Kültür bilgisi değerini alır/ayarlar. Varsayılan değer: InvariantCulture.

**Returns:**
Yerel ayar değeri

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

İmza tarihi etiketi alır/ayarlar. Varsayılan değer: "Date".

**Returns:**
String değeri

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss".

**Returns:**
String değeri

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Yerel tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
String değeri

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Dijital imza etiketi alır/ayarlar. Varsayılan değer: "Digitally signed by".

**Returns:**
String değeri

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Subject dizesindeki öğelerin sırası için biçimi alır/ayarlar. Sonuç örnekleri: C=UK, CN=Org, O=Organization veya CN=Org, C=UK, O=Organization veya O=Organization

**Returns:**
int dizisi @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Yazı tipi ailesi adını alır/ayarlar. Belgede mevcut olmalıdır. Varsayılan değer: Arial.

**Returns:**
String değeri

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Yazı tipi boyutunu alır/ayarlar. Varsayılan değer: 10.

**Returns:**
double değer

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Ön plan rengini (metin rengi) alır/ayarlar. Varsayılan değer: Blue.

**Returns:**
com.aspose.pdf.Color örneği

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Konum etiketini alır/ayarlar. Varsayılan değer: "Location".

**Returns:**
String değeri

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Sebep etiketini alır/ayar. Varsayılan değer: "Reason".

**Returns:**
String değeri

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

İmza dönüşünü alır veya ayarlar.

**Returns:**
Dönüş öğesi

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

İmza görünümündeki görüntünün ön plan görüntüsü olarak çizilip çizilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer: false.

**Returns:**
boolean değer

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

İletişim bilgisi görünürlüğünü alır/ayar. Varsayılan değer: true.

**Returns:**
boolean değer

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Konum görünürlüğünü alır/ayar. Varsayılan değer: true.

**Returns:**
boolean değer

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Sebep görünürlüğünü alır/ayar. Varsayılan değer: true.

**Returns:**
boolean değer

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

DigitalSubjectFormat'ın kullanım durumunu alır/ayar {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
boolean değer

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Arka plan rengini alır/ayarlar. Varsayılan değer: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
İletişim bilgisi etiketini alır/ayarlar. Varsayılan değer: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Kültür bilgisi değerini alır/ayar.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
İmza tarihi etiketi alır/ayarlar. Varsayılan değer: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Yerel tarih saat biçimini alır/ayarlar. Varsayılan değer: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Dijital imza etiketi alır/ayarlar. Varsayılan değer: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Subject dizesindeki öğelerin sırası için biçimi alır/ayarlar. Sonuç örnekleri: C=UK, CN=Org, O=Organization veya CN=Org, C=UK, O=Organization veya O=Organization

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int dizisi @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Yazı tipi ailesi adını alır/ayarlar. Belgede mevcut olmalıdır. Varsayılan değer: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Yazı tipi boyutunu alır/ayarlar. Varsayılan değer: 10.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Ön plan rengini (metin rengi) alır/ayarlar. Varsayılan değer: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

İmza görünümündeki görüntünün ön plan görüntüsü olarak çizilip çizilmediğini gösteren bir değeri alır veya ayarlar. Varsayılan değer: false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Konum etiketini alır/ayarlar. Varsayılan değer: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Sebep etiketini alır/ayar. Varsayılan değer: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
İmza dönüşünü alır veya ayarlar.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

İletişim bilgisi görünürlüğünü alır/ayar. Varsayılan değer: true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Konum görünürlüğünü alır/ayar. Varsayılan değer: true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Sebep görünürlüğünü alır/ayar. Varsayılan değer: true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

DigitalSubjectFormat'ın kullanım durumunu alır/ayar {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
