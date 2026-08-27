---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Aspose.PDF for Java API Referansı"
description: "Onay kutusu alanını temsil eden sınıf."
type: docs
weight: 580
url: /tr/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Onay kutusu alanını temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CheckboxField](#CheckboxField--) | CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Yeni bir onay kutusunu bir onay kutusu grubuna ekler, bu grupta aynı anda en fazla bir onay kutusu işaretlenebilir. Yeni onay kutusu grubun altına eklenir. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Yeni bir onay kutusunu bir onay kutusu grubuna ekler, bu grupta aynı anda en fazla bir onay kutusu işaretlenebilir. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Yeni bir onay kutusunu bir onay kutusu grubuna ekler, bu grupta aynı anda en fazla bir onay kutusu işaretlenebilir. |
| [deepClone](#deepClone--) | Onay kutusunu kopyala. |
| [getActiveState](#getActiveState--) | Mevcut ek açıklama görünüm durumunu alır. |
| [getAllowedStates](#getAllowedStates--) | İzin verilen durumların listesini döndürür. |
| [getChecked](#getChecked--) | Onay kutusunun durumunu alır. |
| [getExportValue](#getExportValue--) | CheckBox alanının dışa aktarma değerini alır veya ayarlar. |
| [getNormalCaption](#getNormalCaption--) | Alanının normal başlığını alır. |
| [getOnState](#getOnState--) | Onay kutusunun "Checked" durumu olan durumun adını döndürür. Bu, mevcutsa "Yes" ve "Off" dışındaki herhangi bir değer ise "No"; |
| [getStyle](#getStyle--) | Onay kutusunun stilini alır. |
| [getValue](#getValue--) | Onay kutusu alanının değerini alır. |
| [setActiveState](#setActiveState-java.lang.String-) | Geçerli ek açıklama görünüm durumunu ayarlar. |
| [setChecked](#setChecked-boolean-) | Onay kutusunun durumunu ayarlar. |
| [setExportValue](#setExportValue-java.lang.String-) | CheckBox alanının dışa aktarma değerini alır veya ayarlar. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Onay kutusunun stilini ayarlar. |
| [setValue](#setValue-java.lang.String-) | Onay kutusu alanının değerini ayarlar. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
CheckboxField örneği oluştur. @deprecated Tam alan işlevselliği için belgeye bağlama gereklidir - CheckboxField(Document doc) kullanın

### addOption {#addOption-java.lang.String-}
Yeni bir onay kutusunu bir onay kutusu grubuna ekler, bu grupta aynı anda en fazla bir onay kutusu işaretlenebilir. Yeni onay kutusu grubun altına eklenir.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Yeni bir onay kutusunu bir onay kutusu grubuna ekler, bu grupta aynı anda en fazla bir onay kutusu işaretlenebilir.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Yeni bir onay kutusunu bir onay kutusu grubuna ekler, bu grupta aynı anda en fazla bir onay kutusu işaretlenebilir.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Onay kutusunu kopyala.

**Returns:**
Klonlanmış nesne

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Mevcut ek açıklama görünüm durumunu alır.

**Returns:**
String değeri

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

İzin verilen durumların listesini döndürür.

**Returns:**
String değerlerinin listesi

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Onay kutusunun durumunu alır.

**Returns:**
boolean değer

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

CheckBox alanının dışa aktarma değerini alır veya ayarlar.

**Returns:**
String değeri

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Alanının normal başlığını alır.

**Returns:**
String değeri

### getOnState {#getOnState--}
```
public String getOnState()
```

Onay kutusunun "Checked" durumu olan durumun adını döndürür. Bu, mevcutsa "Yes" ve "Off" dışındaki herhangi bir değer ise "No";

**Returns:**
String değeri

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Onay kutusunun stilini alır.

**Returns:**
Onay kutusunun stili. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Onay kutusu alanının değerini alır.

**Returns:**
String değeri

### setActiveState {#setActiveState-java.lang.String-}
Geçerli ek açıklama görünüm durumunu ayarlar.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Onay kutusunun durumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setExportValue {#setExportValue-java.lang.String-}
CheckBox alanının dışa aktarma değerini alır veya ayarlar.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Onay kutusunun stilini ayarlar.

### setValue {#setValue-java.lang.String-}
Onay kutusu alanının değerini ayarlar.
