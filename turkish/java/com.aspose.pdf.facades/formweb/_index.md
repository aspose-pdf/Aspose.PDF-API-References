---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Aspose.PDF for Java API Referansı"
description: "Acro form arayüzünü temsil eder."
type: docs
weight: 230
url: /tr/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Acro form arayüzünü temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Facade'i başlatır. |
| [close](#close--) | Bu belge tarafından kullanılan tüm açık kaynakları kapatır. |
| [dispose](#dispose--) | Kullanımdan kaldırıldı. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | PDF alanlarının içeriğini FDF akışına dışa aktarır. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | PDF alanlarının içeriğini XML akışına dışa aktarır. |
| [exportXml](#exportXml-java.io.OutputStream-) | PDF alanlarının içeriğini XML akışına dışa aktarır. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | XFA veri paketini çıkarır. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Tam nitelikli alan adına göre bir barkod alanını doldurur. |
| [fillField](#fillField-java.lang.String-boolean-) | Onay kutusu alanını bir boolean değerle doldurur. |
| [fillField](#fillField-java.lang.String-int-) | Tam nitelikli alan adına göre geçerli bir indeks değeriyle radyo kutusu alanını doldurur. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Tam nitelikli alan adına göre geçerli bir değerle alanı doldurur. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Bir alanı birden fazla seçimle doldurun.Not: yalnızca AcroForm Liste Kutusu Alanı için. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Belirtilen değerle alanı doldurur. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Metin kutusu alanlarını metin değerleriyle doldurur ve belgeyi kaydeder. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | FillImageField işlevini aşırı yükler. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Tam nitelikli alan adına göre mevcut düğme alanının görünümü olarak bir resmi yapıştırır. |
| [flattenAllFields](#flattenAllFields--) | Tüm alanları düzleştirir. |
| [flattenField](#flattenField-java.lang.String-) | Tam nitelikli alan adına sahip belirtilen bir alanı düzleştirir. |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Radyo düğmesi seçenek alanları için geçerli değeri döndürür. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Alan adı temelinde radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Alan adı temelinde radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. |
| [getContentDisposition](#getContentDisposition--) | Getshow içeriği, işlemin sonucu HttpResponse nesnesine kaydedildiğinde saklanacaktır. |
| [getDestFileName](#getDestFileName--) | Kullanımdan kaldırıldı. |
| [getDestStream](#getDestStream--) | Kullanımdan kaldırıldı. |
| [getField](#getField-java.lang.String-) | Alan adını temel alarak alanın değerini alır. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Tüm görünüm özelliklerini içeren FrohmFieldFacade nesnesini döndürür. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Alan bayraklarını döndürür. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Metin alanının sınırlamasını al. |
| [getFieldNames](#getFieldNames--) | Formdaki alan adlarının listesini alır. |
| [getFieldType](#getFieldType-java.lang.String-) | Alan tipini döndürür. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Form gönderme düğmelerinin tüm adlarını alır. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Kısa alan adına göre tam alan adını alır. |
| [getImportResult](#getImportResult--) | Son içe aktarma işleminin sonucu. |
| [getResponse](#getResponse--) | İşlemin sonucunun saklanacağı Response nesnesini alır veya ayarlar. |
| [getRichText](#getRichText-java.lang.String-) | Her karakterin biçimlendirme bilgilerini içeren Zengin Metin alanının değerini al. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. |
| [getSrcFileName](#getSrcFileName--) | Kullanımdan kaldırıldı. |
| [getSrcStream](#getSrcStream--) | Kaynak akışı alır. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Gönder düğmesinin gönderim bayraklarını döndürür. |
| [importFdf](#importFdf-java.io.InputStream-) | Alanların içeriğini fdf dosyasından içe aktarır ve yeni pdf'e yerleştirir. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni pdf'e yerleştirir. |
| [importXml](#importXml-java.io.InputStream-) | Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. |
| [importXml](#importXml-java.lang.String-) | Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Alanının gerekli olup olmadığını belirler. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Bir alanı yeniden adlandırır. |
| [save](#save--) | <p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Kullanımdan kaldırıldı. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Kullanımdan kaldırıldı. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | İşlemin sonucunun saklanacağı Response nesnesini alır veya ayarlar. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Kullanımdan kaldırıldı. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Kaynak akışı alır. |
| [setXfaData](#setXfaData-java.io.InputStream-) | XFA verisini belirtilen veri paketiyle değiştirir. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Parametresiz FormWeb kurucusu. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Facade'i başlatır.

### close {#close--}
```
public void close()
```

Bu belge tarafından kullanılan tüm açık kaynakları kapatır.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Kullanımdan kaldırıldı.

### exportFdf {#exportFdf-java.io.OutputStream-}
PDF alanlarının içeriğini FDF akışına dışa aktarır.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
PDF alanlarının içeriğini XML akışına dışa aktarır.

### exportXml {#exportXml-java.io.OutputStream-}
PDF alanlarının içeriğini XML akışına dışa aktarır.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
XFA veri paketini çıkarır.

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
Belirtilen değerle alanı doldurur.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Metin kutusu alanlarını metin değerleriyle doldurur ve belgeyi kaydeder.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
FillImageField işlevini aşırı yükler.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Tam nitelikli alan adına göre mevcut düğme alanının görünümü olarak bir resmi yapıştırır.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Tüm alanları düzleştirir.

### flattenField {#flattenField-java.lang.String-}
Tam nitelikli alan adına sahip belirtilen bir alanı düzleştirir.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

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
public ContentDisposition getContentDisposition()
```

Getshow içeriği, işlemin sonucu HttpResponse nesnesine kaydedildiğinde saklanacaktır.

**Returns:**
ContentDisposition öğesi

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Kullanımdan kaldırıldı.

**Returns:**
Dize nesnesi

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Kullanımdan kaldırıldı.

**Returns:**
OutputStream nesnesi

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
public String [] getFieldNames()
```

Formdaki alan adlarının listesini alır.

**Returns:**
String[] nesnesi

### getFieldType {#getFieldType-java.lang.String-}
Alan tipini döndürür.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Form gönderme düğmelerinin tüm adlarını alır.

**Returns:**
String[] nesnesi

### getFullFieldName {#getFullFieldName-java.lang.String-}
Kısa alan adına göre tam alan adını alır.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Son içe aktarma işleminin sonucu.

**Returns:**
FormImportResult[] dizisi

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

İşlemin sonucunun saklanacağı Response nesnesini alır veya ayarlar.

**Returns:**
HttpServletResponse nesnesi

### getRichText {#getRichText-java.lang.String-}
Her karakterin biçimlendirme bilgilerini içeren Zengin Metin alanının değerini al.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar.

**Returns:**
SaveOptions nesnesi

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Kullanımdan kaldırıldı.

**Returns:**
Dize nesnesi

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
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

### importXml {#importXml-java.lang.String-}
Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir.

### isRequiredField {#isRequiredField-java.lang.String-}
Alanının gerekli olup olmadığını belirler.

### renameField {#renameField-java.lang.String-java.lang.String-}
Bir alanı yeniden adlandırır.

### save {#save--}
```
public void save()
```

<p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar.

### setDestFileName {#setDestFileName-java.lang.String-}
Kullanımdan kaldırıldı.

### setDestStream {#setDestStream-java.io.OutputStream-}
Kullanımdan kaldırıldı.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
İşlemin sonucunun saklanacağı Response nesnesini alır veya ayarlar.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Kullanımdan kaldırıldı.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Kaynak akışı alır.

### setXfaData {#setXfaData-java.io.InputStream-}
XFA verisini belirtilen veri paketiyle değiştirir.
