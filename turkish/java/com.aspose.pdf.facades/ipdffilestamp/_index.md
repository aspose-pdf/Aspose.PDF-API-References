---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyalarına damga (filigran veya arka plan) eklemek için arabirim."
type: docs
weight: 320
url: /tr/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

PDF dosyalarına damga (filigran veya arka plan) eklemek için arabirim.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Alt sol konum. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Alt orta konum. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Alt sağ konum. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Sol konum. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Sağ konum. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Üst let konumu. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Üst orta konum. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Sağ üst konum. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Belgenin sayfalarına alt bilgi ekler. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Belgenin sayfalarına alt bilgi ekler. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Sayfanın alt bilgisi olarak resmi ekler. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Sayfanın alt bilgisi olarak resmi ekler. |
| [addFooter](#addFooter-java.lang.String-float-) | Belgenin sayfalarına alt bilgi olarak resmi ekler. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Sayfaların alt bilgisi olarak resmi ekler. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Sayfaya üst bilgi ekler. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Dosyanın sayfalarına üst bilgi ekler. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Sayfalarda üst bilgi olarak resmi ekler. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Sayfanın üst kısmına resmi ekler. |
| [addHeader](#addHeader-java.lang.String-float-) | Dosyanın sayfalarına üst bilgi olarak resmi ekler. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Sayfalarda üst bilgi olarak resmi ekler. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Sayfaya sayfa numarası ekler. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Sayfada belirtilen konuma sayfa numarası ekler. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Sayfalara sayfa numarası ekler. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Belgenin sayfalarına sayfa numarası ekler. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Dosyaya sayfa numarası ekle. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Sayfada belirtilen konuma sayfa numarası ekler. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Sayfalara sayfa numarası ekler. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Belgenin sayfalarına sayfa numarası ekler. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Dosyaya damga ekler. |
| [close](#close--) | Açılan dosyaları kapatır ve değişiklikleri kaydeder. |
| [dispose](#dispose--) | Kullanımdan kaldırıldı. |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. |
| [getDocument](#getDocument--) | PdfFileStamp'in çalıştığı belgeyi alır. |
| [getInputFile](#getInputFile--) | Girdi dosyasının adını ve yolunu alır. |
| [getInputStream](#getInputStream--) | Giriş akışını alır. |
| [getKeepSecurity](#getKeepSecurity--) | Doğru ise güvenliği korur. |
| [getOutputFile](#getOutputFile--) | Çıktı dosyasının adını ve yolunu alır. |
| [getOutputStream](#getOutputStream--) | Çıktı akışını alır. |
| [getPageHeight](#getPageHeight--) | Kaynak dosyadaki ilk sayfanın yüksekliğini alır. |
| [getPageNumberRotation](#getPageNumberRotation--) | Sayfa numarasının dönüşünü alır. |
| [getPageWidth](#getPageWidth--) | Giriş dosyasındaki ilk sayfanın genişliğini alır. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır. |
| [getStartingNumber](#getStartingNumber--) | Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. |
| [setInputFile](#setInputFile-java.lang.String-) | Giriş dosyasının adını ve yolunu ayarlar. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Giriş akışını ayarlar. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Güvenliği korumayı ayarlar. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Çıktı dosyasının adını ve yolunu ayarlar. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Çıktı akışını ayarlar veya ayarlar. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Sayfa numarasının dönüşünü ayarlar. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini ayarlar. |
| [setStartingNumber](#setStartingNumber-int-) | Giriş dosyasındaki ilk sayfa için başlangıç numarasını ayarlar. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Alt sol konum.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Alt orta konum.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Alt sağ konum.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Sol konum.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Sağ konum.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Üst let konumu.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Üst orta konum.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Sağ üst konum.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Belgenin sayfalarına alt bilgi ekler.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Belgenin sayfalarına alt bilgi ekler.

### addFooter {#addFooter-java.io.InputStream-float-}
Sayfanın alt bilgisi olarak resmi ekler.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Sayfanın alt bilgisi olarak resmi ekler.

### addFooter {#addFooter-java.lang.String-float-}
Belgenin sayfalarına alt bilgi olarak resmi ekler.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Sayfaların alt bilgisi olarak resmi ekler.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Sayfaya üst bilgi ekler.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Dosyanın sayfalarına üst bilgi ekler.

### addHeader {#addHeader-java.io.InputStream-float-}
Sayfalarda üst bilgi olarak resmi ekler.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Sayfanın üst kısmına resmi ekler.

### addHeader {#addHeader-java.lang.String-float-}
Dosyanın sayfalarına üst bilgi olarak resmi ekler.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Sayfalarda üst bilgi olarak resmi ekler.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Sayfaya sayfa numarası ekler.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Sayfada belirtilen konuma sayfa numarası ekler.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Sayfalara sayfa numarası ekler.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Belgenin sayfalarına sayfa numarası ekler.

### addPageNumber {#addPageNumber-java.lang.String-}
Dosyaya sayfa numarası ekle.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Sayfada belirtilen konuma sayfa numarası ekler.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Sayfalara sayfa numarası ekler.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Belgenin sayfalarına sayfa numarası ekler.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Dosyaya damga ekler.

### close {#close--}
```
void close()
```

Açılan dosyaları kapatır ve değişiklikleri kaydeder.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Kullanımdan kaldırıldı.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
String değeri

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır.

**Returns:**
ContentDisposition öğesi

### getDocument {#getDocument--}
```
IDocument getDocument()
```

PdfFileStamp'in çalıştığı belgeyi alır.

**Returns:**
IDocument nesnesi

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Girdi dosyasının adını ve yolunu alır.

**Returns:**
Dize nesnesi

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Giriş akışını alır.

**Returns:**
InputStream nesnesi

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Doğru ise güvenliği korur.

**Returns:**
boolean değer

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Çıktı dosyasının adını ve yolunu alır.

**Returns:**
Dize nesnesi

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Çıktı akışını alır.

**Returns:**
OutputStream nesnesi

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Kaynak dosyadaki ilk sayfanın yüksekliğini alır.

**Returns:**
float değer

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Sayfa numarasının dönüşünü alır.

**Returns:**
float değer

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Giriş dosyasındaki ilk sayfanın genişliğini alır.

**Returns:**
float değer

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır.

**Returns:**
SaveOptions nesnesi

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar.

**Returns:**
int değer

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine saklandığında içeriğin nasıl depolanacağını ayarlar.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar.

### setInputFile {#setInputFile-java.lang.String-}
Giriş dosyasının adını ve yolunu ayarlar.

### setInputStream {#setInputStream-java.io.InputStream-}
Giriş akışını ayarlar.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Güvenliği korumayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOutputFile {#setOutputFile-java.lang.String-}
Çıktı dosyasının adını ve yolunu ayarlar.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Çıktı akışını ayarlar veya ayarlar.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Sayfa numarasının dönüşünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini ayarlar.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Giriş dosyasındaki ilk sayfa için başlangıç numarasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
