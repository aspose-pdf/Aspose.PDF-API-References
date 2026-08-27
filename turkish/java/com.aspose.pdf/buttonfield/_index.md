---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, itme düğmesi alanını temsil eder."
type: docs
weight: 440
url: /tr/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Sınıf, itme düğmesi alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ButtonField](#ButtonField--) | Generator için Button field yapıcısı. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Generator için Button field yapıcısı. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Generator için Button field yapıcısı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Alana kaynak olarak görüntü ekler ve çizer. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Görüntüyü alan kaynaklarına ekler ve çizer. |
| [getAlternateCaption](#getAlternateCaption--) | Aktif alanı içinde fare düğmesine basıldığında gösterilecek düğmenin alternatif başlığını alır. |
| [getAlternateIcon](#getAlternateIcon--) | Aktif alanı içinde fare düğmesine basıldığında gösterilecek alternatif simgeyi alır. |
| [getIconFit](#getIconFit--) | Widget açıklamasının simgesinin açıklama dikdörtgeni içinde nasıl görüntüleneceğini belirten ikon uyum nesnesini alır. |
| [getICPosition](#getICPosition--) | Simge başlığı konumunu alır. |
| [getNormalCaption](#getNormalCaption--) | Normal başlığı alır. |
| [getNormalIcon](#getNormalIcon--) | Kullanıcıyla etkileşime girmediğinde gösterilecek düğmenin normal simgesini alır. |
| [getRolloverCaption](#getRolloverCaption--) | Kullanıcı fare düğmesine basmadan imleci aktif alanına getirdiğinde gösterilecek düğmenin rollover başlığını alır. |
| [getRolloverIcon](#getRolloverIcon--) | Kullanıcı fare düğmesine basmadan imleci aktif alanına getirdiğinde gösterilecek düğmenin rollover simgesini alır. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Aktif alanı içinde fare düğmesine basıldığında gösterilecek düğmenin alternatif başlığını ayarlar. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Aktif alanı içinde fare düğmesine basıldığında gösterilecek alternatif simgeyi ayarlar. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Simge başlığı konumunu ayarlar. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Normal başlığı ayarlar. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Kullanıcıyla etkileşime girmediğinde gösterilecek düğmenin normal simgesini ayarlar. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Kullanıcı fare düğmesine basmadan imleci aktif alanına getirdiğinde gösterilecek düğmenin rollover başlığını ayarlar. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Kullanıcı imleci düğmenin etkin alanına bastırmadan hareket ettirdiğinde görüntülenecek düğmenin rollover simgesini ayarlar. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Generator için Button field yapıcısı.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Generator için Button field yapıcısı.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Generator için Button field yapıcısı.

### addImage {#addImage-java.awt.image.BufferedImage-}
Alana kaynak olarak görüntü ekler ve çizer.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Görüntüyü alan kaynaklarına ekler ve çizer.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Aktif alanı içinde fare düğmesine basıldığında gösterilecek düğmenin alternatif başlığını alır.

**Returns:**
String değeri

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Aktif alanı içinde fare düğmesine basıldığında gösterilecek alternatif simgeyi alır.

**Returns:**
XForm nesnesi

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Widget açıklamasının simgesinin açıklama dikdörtgeni içinde nasıl görüntüleneceğini belirten ikon uyum nesnesini alır.

**Returns:**
IconFit nesnesi

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Simge başlığı konumunu alır.

**Returns:**
ikon başlığı konumu. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Normal başlığı alır.

**Returns:**
String değeri

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Kullanıcıyla etkileşime girmediğinde gösterilecek düğmenin normal simgesini alır.

**Returns:**
XForm nesnesi

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Kullanıcı fare düğmesine basmadan imleci aktif alanına getirdiğinde gösterilecek düğmenin rollover başlığını alır.

**Returns:**
String değeri

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Kullanıcı fare düğmesine basmadan imleci aktif alanına getirdiğinde gösterilecek düğmenin rollover simgesini alır.

**Returns:**
XForm nesnesi

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Aktif alanı içinde fare düğmesine basıldığında gösterilecek düğmenin alternatif başlığını ayarlar.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Aktif alanı içinde fare düğmesine basıldığında gösterilecek alternatif simgeyi ayarlar.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Simge başlığı konumunu ayarlar.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Normal başlığı ayarlar.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Kullanıcıyla etkileşime girmediğinde gösterilecek düğmenin normal simgesini ayarlar.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Kullanıcı fare düğmesine basmadan imleci aktif alanına getirdiğinde gösterilecek düğmenin rollover başlığını ayarlar.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Kullanıcı imleci düğmenin etkin alanına bastırmadan hareket ettirdiğinde görüntülenecek düğmenin rollover simgesini ayarlar.
