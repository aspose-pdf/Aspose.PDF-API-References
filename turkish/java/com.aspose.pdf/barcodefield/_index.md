---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, barkod alanını temsil eder."
type: docs
weight: 250
url: /tr/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Sınıf, barkod alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | {@code BarcodeField} sınıfının yeni bir örneğini başlatır. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | {@code BarcodeField} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCaption](#getCaption--) | Barkod nesnesinin başlığını alır. |
| [getECC](#getECC--) | Hata düzeltme katsayısını temsil eden bir tamsayı değerini alır. PDF417 için 0 ile 8 arasında olmalıdır. QRCode için 0 ile 3 arasında olmalıdır (0 'L' için, 1 'M' için, 2 'Q' için ve 3 'H' için). |
| [getResolution](#getResolution--) | Barkod nesnesinin işlendiği çözünürlüğü, inç başına nokta (dpi) cinsinden alır. |
| [getSymbology](#getSymbology--) | Bu açıklamada kullanılacak barkod veya glif teknolojisini belirtir, ayrıntılar için {@code Symbology}'e bakın. |
| [getXSymHeight](#getXSymHeight--) | İki barkod modülü arasındaki dikey mesafeyi, piksel cinsinden alır. XSymHeight/XSymWidth oranı bir tamsayı olmalıdır. PDF417 için kabul edilen oran aralığı 1 ile 4 arasındadır. QRCode ve DataMatrix için bu oran her zaman 1 olmalıdır. |
| [getXSymWidth](#getXSymWidth--) | İki barkod modülü arasındaki yatay mesafeyi, piksel cinsinden alır. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
{@code BarcodeField} sınıfının yeni bir örneğini başlatır.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
{@code BarcodeField} sınıfının yeni bir örneğini başlatır.

### getCaption {#getCaption--}
```
public String getCaption()
```

Barkod nesnesinin başlığını alır.

**Returns:**
String değeri

### getECC {#getECC--}
```
public int getECC()
```

Hata düzeltme katsayısını temsil eden bir tamsayı değerini alır. PDF417 için 0 ile 8 arasında olmalıdır. QRCode için 0 ile 3 arasında olmalıdır (0 'L' için, 1 'M' için, 2 'Q' için ve 3 'H' için).

**Returns:**
int değer

### getResolution {#getResolution--}
```
public int getResolution()
```

Barkod nesnesinin işlendiği çözünürlüğü, inç başına nokta (dpi) cinsinden alır.

**Returns:**
int değer

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Bu açıklamada kullanılacak barkod veya glif teknolojisini belirtir, ayrıntılar için {@code Symbology}'e bakın.

**Returns:**
Symbology öğesi @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

İki barkod modülü arasındaki dikey mesafeyi, piksel cinsinden alır. XSymHeight/XSymWidth oranı bir tamsayı olmalıdır. PDF417 için kabul edilen oran aralığı 1 ile 4 arasındadır. QRCode ve DataMatrix için bu oran her zaman 1 olmalıdır.

**Returns:**
int değer

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

İki barkod modülü arasındaki yatay mesafeyi, piksel cinsinden alır.

**Returns:**
int değer
