---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Aspose.PDF for Java API Referansı"
description: "Radyo düğmesi alanını temsil eden sınıf."
type: docs
weight: 4080
url: /tr/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Radyo düğmesi alanını temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | RadioButtonField için yapıcı. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | RadiouttonField için yapıcı. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Radyo düğmesi alanını ayarlar. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | RadioButton alanına yeni seçenek alanı ekler. |
| [addOption](#addOption-java.lang.String-) | Radion düğmesine seçenek ekle. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Belirtilen dikdörtgenle radyo düğmesi seçeneğine ekle. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Radyo düğmesinin seçili bir değeri olmamasına izin veren bayrağı alır veya ayarlar. Eğer {@code }, her zaman tam olarak bir radyo düğmesi seçili olmalıdır; mevcut seçili düğmeyi seçmek bir etki yapmaz. Eğer {@code }, seçili düğmeye tıklamak onu seçimsiz hâle getirir ve hiçbir düğme seçili kalmaz. </p> <hr> Bazı PDF okuyucular (Adobe Acrobat dahil) bu bayrağın durumunu göz ardı edebilir. |
| [getOptions](#getOptions--) | Radyo düğmesinin seçenek koleksiyonunu alır. |
| [getPageIndex](#getPageIndex--) | Bu RadioButton alanını içeren sayfanın indeksini alır. |
| [getSelected](#getSelected--) | Seçili öğenin indeksini alır. Öğelerin numaralandırması 1'den başlar. |
| [getStyle](#getStyle--) | Alan kutusunun stili. |
| [getValue](#getValue--) | Alan değerini alır. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Radyo düğmesinin seçili bir değeri olmamasına izin veren bayrağı alır veya ayarlar. Eğer {@code }, her zaman tam olarak bir radyo düğmesi seçili olmalıdır; mevcut seçili düğmeyi seçmek bir etki yapmaz. Eğer {@code }, seçili düğmeye tıklamak onu seçimsiz hâle getirir ve hiçbir düğme seçili kalmaz. </p> <hr> Bazı PDF okuyucular (Adobe Acrobat dahil) bu bayrağın durumunu göz ardı edebilir. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Radyo düğmesinin tüm alt öğelerini sayfadaki belirtilen konumlara taşır. |
| [setSelected](#setSelected-int-) | Seçili öğenin indeksini ayarlar. Öğelerin numaralandırması 1'den başlar. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Alan kutusunun stili. |
| [setValue](#setValue-java.lang.String-) | Alan değerini ayarlar. |
| [updateAppearances](#updateAppearances--) | Görünüm değerini günceller. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
RadioButtonField için yapıcı.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
RadiouttonField için yapıcı.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Radyo düğmesi alanını ayarlar.

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
RadioButton alanına yeni seçenek alanı ekler.

### addOption {#addOption-java.lang.String-}
Radion düğmesine seçenek ekle.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Belirtilen dikdörtgenle radyo düğmesi seçeneğine ekle.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Radyo düğmesinin seçili bir değeri olmamasına izin veren bayrağı alır veya ayarlar. Eğer {@code }, her zaman tam olarak bir radyo düğmesi seçili olmalıdır; mevcut seçili düğmeyi seçmek bir etki yapmaz. Eğer {@code }, seçili düğmeye tıklamak onu seçimsiz hâle getirir ve hiçbir düğme seçili kalmaz. </p> <hr> Bazı PDF okuyucular (Adobe Acrobat dahil) bu bayrağın durumunu göz ardı edebilir.

**Returns:**
boolean değer

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Radyo düğmesinin seçenek koleksiyonunu alır.

**Returns:**
OptionCollection nesnesi

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Bu RadioButton alanını içeren sayfanın indeksini alır.

**Returns:**
int değer

### getSelected {#getSelected--}
```
public int getSelected()
```

Seçili öğenin indeksini alır. Öğelerin numaralandırması 1'den başlar.

**Returns:**
int değer

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Alan kutusunun stili.

**Returns:**
BoxStyle değeri @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Alan değerini alır.

**Returns:**
String değeri

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Radyo düğmesinin seçili bir değeri olmamasına izin veren bayrağı alır veya ayarlar. Eğer {@code }, her zaman tam olarak bir radyo düğmesi seçili olmalıdır; mevcut seçili düğmeyi seçmek bir etki yapmaz. Eğer {@code }, seçili düğmeye tıklamak onu seçimsiz hâle getirir ve hiçbir düğme seçili kalmaz. </p> <hr> Bazı PDF okuyucular (Adobe Acrobat dahil) bu bayrağın durumunu göz ardı edebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Radyo düğmesinin tüm alt öğelerini sayfadaki belirtilen konumlara taşır.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Seçili öğenin indeksini ayarlar. Öğelerin numaralandırması 1'den başlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Alan kutusunun stili.

### setValue {#setValue-java.lang.String-}
Alan değerini ayarlar.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Görünüm değerini günceller.
