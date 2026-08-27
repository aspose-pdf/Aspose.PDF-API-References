---
title: "IForm"
linktitle: "IForm"
second_title: "Aspose.PDF for Java API Referansı"
description: "Acro form nesnesini temsil eden sınıf."
type: docs
weight: 250
url: /tr/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Acro form nesnesini temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close](#close--) | Açılan dosyaları herhangi bir değişiklik yapmadan kapatır. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | PDF alanlarının içeriğini FDF akışına dışa aktarır. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | PDF alanlarının içeriğini XML akışına dışa aktarır. |
| [exportXml](#exportXml-java.io.OutputStream-) | PDF alanlarının içeriğini XML akışına dışa aktarır. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Tam nitelikli alan adına göre bir barkod alanını doldurur. |
| [fillField](#fillField-java.lang.String-boolean-) | Onay kutusu alanını bir boolean değerle doldurur. |
| [fillField](#fillField-java.lang.String-int-) | Tam nitelikli alan adına göre geçerli bir indeks değeriyle radyo kutusu alanını doldurur. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Tam nitelikli alan adına göre geçerli bir değerle alanı doldurur. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Bir alanı birden fazla seçimle doldurun.Not: yalnızca AcroForm Liste Kutusu Alanı için. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | FillImageField işlevini aşırı yükler. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Tam nitelikli alan adına göre mevcut düğme alanının görünümü olarak bir resmi yapıştırır. |
| [flattenAllFields](#flattenAllFields--) | Tüm alanları düzleştirir. |
| [flattenField](#flattenField-java.lang.String-) | Tam nitelikli alan adına sahip belirtilen bir alanı düzleştirir. |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır veya ayarlar. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Radyo düğmesi seçenek alanları için geçerli değeri döndürür. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Alan adı temelinde radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Alan adı temelinde radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır veya ayarlar. |
| [getDestFileName](#getDestFileName--) | Hedef dosya adını alır. |
| [getDestStream](#getDestStream--) | Hedef akışı alır. |
| [getDocument](#getDocument--) | Formun çalıştığı belgeyi alır. |
| [getField](#getField-java.lang.String-) | Alan adını temel alarak alanın değerini alır. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Tüm görünüm özelliklerini içeren FrohmFieldFacade nesnesini döndürür. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Alan bayraklarını döndürür. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Metin alanının sınırlamasını al. |
| [getFieldNames](#getFieldNames--) | Formdaki alan adlarının listesini alır. |
| [getFieldType](#getFieldType-java.lang.String-) | Alan tipini döndürür. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Form gönderme düğmelerinin tüm adlarını alır. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Kısa alan adına göre tam alan adını alır. |
| [getRichText](#getRichText-java.lang.String-) | Her karakterin biçimlendirme bilgilerini içeren Zengin Metin alanının değerini al. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. |
| [getSrcFileName](#getSrcFileName--) | Kaynak dosya adını alır. |
| [getSrcStream](#getSrcStream--) | Kaynak akışı alır. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Gönder düğmesinin gönderim bayraklarını döndürür. |
| [importFdf](#importFdf-java.io.InputStream-) | Alanların içeriğini fdf dosyasından içe aktarır ve yeni pdf'e yerleştirir. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni pdf'e yerleştirir. |
| [importXml](#importXml-java.io.InputStream-) | Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Bir alanı yeniden adlandırır. |
| [save](#save--) | Doldurulmuş alanların değerini kaydeder ve açılmış Pdf belgesini kapatır. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Hedef dosya adını ayarlar. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Hedef akışı alır. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Kaynak dosya adını ayarlar. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Kaynak akışı alır. |

### close {#close--}
```
void close()
```

Açılan dosyaları herhangi bir değişiklik yapmadan kapatır.

### exportFdf {#exportFdf-java.io.OutputStream-}
PDF alanlarının içeriğini FDF akışına dışa aktarır.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
PDF alanlarının içeriğini XML akışına dışa aktarır.

### exportXml {#exportXml-java.io.OutputStream-}
PDF alanlarının içeriğini XML akışına dışa aktarır.

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Tam nitelikli alan adına göre bir barkod alanını doldurur.

### fillField {#fillField-java.lang.String-boolean-}
Onay kutusu alanını bir boolean değerle doldurur.

### fillField {#fillField-java.lang.String-int-}
Tam nitelikli alan adına göre geçerli bir indeks değeriyle radyo kutusu alanını doldurur.

### fillField {#fillField-java.lang.String-java.lang.String-}
Tam nitelikli alan adına göre geçerli bir değerle alanı doldurur.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Bir alanı birden fazla seçimle doldurun.Not: yalnızca AcroForm Liste Kutusu Alanı için.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
FillImageField işlevini aşırı yükler.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Tam nitelikli alan adına göre mevcut düğme alanının görünümü olarak bir resmi yapıştırır.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Tüm alanları düzleştirir.

### flattenField {#flattenField-java.lang.String-}
Tam nitelikli alan adına sahip belirtilen bir alanı düzleştirir.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır veya ayarlar.

**Returns:**
string nesnesi

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Radyo düğmesi seçenek alanları için geçerli değeri döndürür.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Alan adı temelinde radyo düğmesi seçenek alanlarını ve ilgili değerleri alır.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Alan adı temelinde radyo düğmesi seçenek alanlarını ve ilgili değerleri alır.

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır veya ayarlar.

**Returns:**
ContentDisposition öğesi

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Hedef dosya adını alır.

**Returns:**
Dize nesnesi

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

Formun çalıştığı belgeyi alır.

**Returns:**
IDocument nesnesi

### getField {#getField-java.lang.String-}
Alan adını temel alarak alanın değerini alır.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Tüm görünüm özelliklerini içeren FrohmFieldFacade nesnesini döndürür.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Alan bayraklarını döndürür.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Metin alanının sınırlamasını al.

### getFieldNames {#getFieldNames--}
```
String [] getFieldNames()
```

Formdaki alan adlarının listesini alır.

**Returns:**
String[] nesnesi

### getFieldType {#getFieldType-java.lang.String-}
Alan tipini döndürür.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Form gönderme düğmelerinin tüm adlarını alır.

**Returns:**
String[] nesnesi

### getFullFieldName {#getFullFieldName-java.lang.String-}
Kısa alan adına göre tam alan adını alır.

### getRichText {#getRichText-java.lang.String-}
Her karakterin biçimlendirme bilgilerini içeren Zengin Metin alanının değerini al.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar.

**Returns:**
SaveOptions nesnesi

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Kaynak dosya adını alır.

**Returns:**
Dize nesnesi

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Kaynak akışı alır.

**Returns:**
InputStream nesnesi

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Gönder düğmesinin gönderim bayraklarını döndürür.

### importFdf {#importFdf-java.io.InputStream-}
Alanların içeriğini fdf dosyasından içe aktarır ve yeni pdf'e yerleştirir.

### importXfdf {#importXfdf-java.io.InputStream-}
Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni pdf'e yerleştirir.

### importXml {#importXml-java.io.InputStream-}
Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir.

### importXml {#importXml-java.io.InputStream-boolean-}
Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir.

### renameField {#renameField-java.lang.String-java.lang.String-}
Bir alanı yeniden adlandırır.

### save {#save--}
```
void save()
```

Doldurulmuş alanların değerini kaydeder ve açılmış Pdf belgesini kapatır.

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar.

### setDestFileName {#setDestFileName-java.lang.String-}
Hedef dosya adını ayarlar.

### setDestStream {#setDestStream-java.io.OutputStream-}
Hedef akışı alır.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Kaynak dosya adını ayarlar.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Kaynak akışı alır.
