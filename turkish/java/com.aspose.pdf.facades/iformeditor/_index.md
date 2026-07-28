---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "Formları düzenlemek için sınıf (alan ekleme/silme vb.)"
type: docs
weight: 260
url: /tr/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Formları düzenlemek için sınıf (alan ekleme/silme vb.)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Form'a belirtilen türde alan ekle. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Form'a belirtilen türde alan ekle. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Liste kutusuna yeni öğe ekler. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Mevcut liste kutusu alanına Export değeriyle yeni bir öğe ekler, yalnızca AcroForm combo kutusu alanı için. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Form üzerine gönder düğmesi ekle. |
| [close](#close--) | Nesneyi kapatır |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Mevcut bir alanı sayfa numarası ve koordinatlarla belirtilen yeni konuma kopyalar. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Mevcut bir alanı bir PDF belgesinden diğer belgeye, orijinal sayfa numarası ve koordinatlarıyla kopyalar. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Mevcut bir alanı bir PDF belgesinden diğer belgeye, belirtilen sayfa numarası ve orijinal koordinatlarla kopyalar. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Mevcut bir alanı bir PDF belgesinden diğer belgeye, belirtilen sayfa numarası ve koordinatlarla kopyalar. |
| [decorateField](#decorateField--) | PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Belirtilen alan türüne sahip tüm alanların görsel özelliklerini değiştirir. |
| [decorateField](#decorateField-java.lang.String-) | Belirtilen alanın görsel özelliklerini değiştirir. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Liste alanından öğeyi sil. |
| [dispose](#dispose--) | Nesneyi kapatır |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. |
| [getDestFileName](#getDestFileName--) | Hedef dosya adını alır. |
| [getDestStream](#getDestStream--) | Hedef akışı alır. |
| [getDocument](#getDocument--) | FormEditor'ın çalıştığı belgeyi alır. |
| [getExportItems](#getExportItems--) | Dışa aktarma değerlerine sahip combo kutusu için seçenekleri alır. |
| [getFacade](#getFacade--) | Alanının görsel özniteliklerini alır. |
| [getItems](#getItems--) | Öğe dizisini döndürür. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesinin boyutunu alır veya ayarlar. |
| [getRadioGap](#getRadioGap--) | İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydeden üyeyi al, varsayılan 50'dir. |
| [getRadioHoriz](#getRadioHoriz--) | Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrağı al, varsayılan değer true. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır. |
| [getSrcFileName](#getSrcFileName--) | Kaynak dosyanın adını alır. |
| [getSrcStream](#getSrcStream--) | Kaynak akışı alır. |
| [getSubmitFlag](#getSubmitFlag--) | Gönder düğmesinin gönderim bayraklarını al |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Alanı yeni konuma ayarla. |
| [removeField](#removeField-java.lang.String-) | Alanı formdan kaldır. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Alanın gönderme eylemini kaldır. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Alan adını değiştir. |
| [resetFacade](#resetFacade--) | Tüm görsel öznitelikleri boş değere sıfırla. |
| [resetInnerFacade](#resetInnerFacade--) | İç yüzeyin tüm görsel özniteliklerini boş değere sıfırla. |
| [save](#save--) | Değişiklikleri hedef dosyaya kaydeder. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PdfFormat PDF dosya formatını ayarlar. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Hedef dosya adını ayarlar. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Hedef akışı ayarlar. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Dışa aktarma değerlerine sahip combo kutusu için seçenekleri ayarlar. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Alanının görsel özniteliklerini ayarlar. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Metin alanının hizalama stilini ayarla. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Metin alanının dikey hizalama stilini ayarla. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Alan bayraklarını ayarla. |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Alan özniteliklerini ayarla. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Düzenli tek satırlık metin alanı için tarak (comb) sayısını ayarlar (alan, combNumber parametresinin değeri kadar eşit aralıklı konuma otomatik olarak bölünür). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Metin alanının azami karakter sayısını ayarlar. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | PushButton alanı için JavaScript ayarla. |
| [setItems](#setItems-java.lang.String:A-) | Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri ayarlar. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesinin boyutunu alır veya ayarlar. |
| [setRadioGap](#setRadioGap-float-) | İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydedecek üyeyi ayarla, varsayılan 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrağı ayarla, varsayılan değer true. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini ayarlar. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Kaynak dosyanın adını ayarlar. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Kaynak akışı ayarlar. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Gönder düğmesinin submit bayrağını ayarlar. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Gönder düğmesinin gönderim bayraklarını ayarlayın |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Düğmenin URL'sini ayarlar. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Tek satırlı metin alanını çok satırlı bir alana dönüştür. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Form'a belirtilen türde alan ekle.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Form'a belirtilen türde alan ekle.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Liste kutusuna yeni öğe ekler.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Mevcut liste kutusu alanına Export değeriyle yeni bir öğe ekler, yalnızca AcroForm combo kutusu alanı için.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Form üzerine gönder düğmesi ekle.

### close {#close--}
```
void close()
```

Nesneyi kapatır

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Mevcut bir alanı sayfa numarası ve koordinatlarla belirtilen yeni konuma kopyalar.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Mevcut bir alanı bir PDF belgesinden diğer belgeye, orijinal sayfa numarası ve koordinatlarıyla kopyalar.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Mevcut bir alanı bir PDF belgesinden diğer belgeye, belirtilen sayfa numarası ve orijinal koordinatlarla kopyalar.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Mevcut bir alanı bir PDF belgesinden diğer belgeye, belirtilen sayfa numarası ve koordinatlarla kopyalar.

### decorateField {#decorateField--}
```
void decorateField()
```

PDF belgesindeki tüm alanların görsel özelliklerini değiştirir.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Belirtilen alan türüne sahip tüm alanların görsel özelliklerini değiştirir.

### decorateField {#decorateField-java.lang.String-}
Belirtilen alanın görsel özelliklerini değiştirir.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Liste alanından öğeyi sil.

### dispose {#dispose--}
```
void dispose()
```

Nesneyi kapatır

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
Dize nesnesi

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır.

**Returns:**
ContentDisposition öğesi

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Hedef dosya adını alır.

**Returns:**
string value

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Hedef akışı alır.

**Returns:**
OutputStream nesnesi

### getDocument {#getDocument--}
```
IDocument getDocument()
```

FormEditor'ın çalıştığı belgeyi alır.

**Returns:**
IDocument nesnesi

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Dışa aktarma değerlerine sahip combo kutusu için seçenekleri alır.

**Returns:**
String[][] nesnesi

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Alanının görsel özniteliklerini alır.

**Returns:**
FormFieldFacade nesnesi

### getItems {#getItems--}
```
String [] getItems()
```

Öğe dizisini döndürür.

**Returns:**
String[] nesnesi

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesinin boyutunu alır veya ayarlar.

**Returns:**
boolean değer

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydeden üyeyi al, varsayılan 50'dir.

**Returns:**
float değer

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrağı al, varsayılan değer true.

**Returns:**
boolean değer

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır.

**Returns:**
SaveOptions nesnesi

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Kaynak dosyanın adını alır.

**Returns:**
string value

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Kaynak akışı alır.

**Returns:**
InputStream nesnesi

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
```

Gönder düğmesinin gönderim bayraklarını al

**Returns:**
SubmitFormFlag öğesi

### moveField {#moveField-java.lang.String-float-float-float-float-}
Alanı yeni konuma ayarla.

### removeField {#removeField-java.lang.String-}
Alanı formdan kaldır.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Alanın gönderme eylemini kaldır.

### renameField {#renameField-java.lang.String-java.lang.String-}
Alan adını değiştir.

### resetFacade {#resetFacade--}
```
void resetFacade()
```

Tüm görsel öznitelikleri boş değere sıfırla.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

İç yüzeyin tüm görsel özniteliklerini boş değere sıfırla.

### save {#save--}
```
void save()
```

Değişiklikleri hedef dosyaya kaydeder.

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PdfFormat PDF dosya formatını ayarlar.

### setDestFileName {#setDestFileName-java.lang.String-}
Hedef dosya adını ayarlar.

### setDestStream {#setDestStream-java.io.OutputStream-}
Hedef akışı ayarlar.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Dışa aktarma değerlerine sahip combo kutusu için seçenekleri ayarlar.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Alanının görsel özniteliklerini ayarlar.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Metin alanının hizalama stilini ayarla.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Metin alanının dikey hizalama stilini ayarla.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Alan bayraklarını ayarla.

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Alan özniteliklerini ayarla.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Düzenli tek satırlık metin alanı için tarak (comb) sayısını ayarlar (alan, combNumber parametresinin değeri kadar eşit aralıklı konuma otomatik olarak bölünür).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Metin alanının azami karakter sayısını ayarlar.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
PushButton alanı için JavaScript ayarla.

### setItems {#setItems-java.lang.String:A-}
Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri ayarlar.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
void setRadioButtonItemSize(double value)
```

Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesinin boyutunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydedecek üyeyi ayarla, varsayılan 50.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrağı ayarla, varsayılan değer true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini ayarlar.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Kaynak dosyanın adını ayarlar.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Kaynak akışı ayarlar.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Gönder düğmesinin submit bayrağını ayarlar.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Gönder düğmesinin gönderim bayraklarını ayarlayın

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Düğmenin URL'sini ayarlar.

### single2Multiple {#single2Multiple-java.lang.String-}
Tek satırlı metin alanını çok satırlı bir alana dönüştür.
