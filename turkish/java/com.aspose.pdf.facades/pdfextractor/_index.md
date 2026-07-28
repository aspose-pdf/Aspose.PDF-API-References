---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinden görüntü ve metin çıkarmak için sınıf."
type: docs
weight: 400
url: /tr/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

PDF belgesinden görüntü ve metin çıkarmak için sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Bir Pdf belgesini düzenleme için bağlar. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Bir Pdf belgesini düzenleme için bağlar. / * / * / * |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Akıştan PDF belgesini bağlar. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream(\"sample.pdf\"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Giriş PDF dosyasını bağla. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf(\"sample.pdf\"); </pre> |
| [extractAttachment](#extractAttachment--) | Bir Pdf belgesinden ekleri çıkarır. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Bir Pdf belgesinden ekleri çıkarır. |
| [extractImage](#extractImage--) | <p> PDF dosyasından görüntüleri çıkar. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Tüm İşaretlenmiş İçerik konteynerlerini ayrı görüntüler olarak alır. </p> <p> Her İşaretlenmiş İçerik, sayfa bloğu için {@code MCID_<ID number of block for the page>.png} adıyla png formatında bir görüntü olarak kaydedilir. |
| [extractText](#extractText--) | <p> Bir Pdf belgesinden metin çıkarır. </p> <hr> <pre> İlk örnek, PDF dosyasından tüm metnin nasıl çıkarılacağını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> İkinci örnek, her sayfanın metninin tek bir txt dosyasına nasıl çıkarılacağını gösterir. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Bir Pdf belgesinden metin çıkarır. </p> <hr> <pre> İlk örnek, PDF dosyasından tüm metnin nasıl çıkarılacağını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> İkinci örnek, her sayfanın metninin tek bir txt dosyasına nasıl çıkarılacağını gösterir. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Yalnızca dahili kullanım için |
| [getAttachment](#getAttachment--) | <p> Tüm ek dosyalarını akışlara kaydeder. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Tüm ek dosyalarını akışlara kaydeder. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Eklerin listesini alır. |
| [getAttachNames](#getAttachNames--) | <p> PDF dosyasındaki eklerin listesini döndürür. Not: Bu yöntemi kullanmadan önce ExtractAttachments çağrılmalıdır. </p> <hr> <pre> Örnek, PDF dosyasından ek adlarının nasıl çıkarılacağını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile(\"sample.pdf\")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Çıkarma işleminin gerçekleştirileceği sayfa aralığındaki son sayfayı alır. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Görüntü çıkarma işlemi için modu ayarlar. </p> <hr> Varsayılan değer, kaynaklarda tanımlı tüm görüntüleri çıkaran ExtractImageMode.DefinedInResources'dir. Gerçekten gösterilen görüntüleri çıkarmak için ExtractImageMode.ActuallyUsed modu kullanılmalıdır. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Metin çıkarma sonucunun modunu alır. </p> <hr> <pre> Örnek, {@code ExtractTextMode} özelliğinin metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> <p> Değer: 0 saf metin modudur ve 1 ham sıralama modudur. Varsayılan 0'dır.</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | PDF dosyasından sonraki görüntüyü alır ve akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | PDF dosyasından sonraki görüntüyü alır ve verilen görüntü formatıyla akışa kaydeder. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> PDF belgesinden sonraki görüntüyü alır. Not: ExtractImage bu yöntemi kullanmadan önce çağrılmalıdır. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | PDF belgesinden sonraki görüntüyü verilen görüntü formatıyla alır. Not: ExtractImage bu yöntemi kullanmadan önce çağrılmalıdır. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Bir sayfanın metnini akışa kaydeder. </p> <hr> <pre> Örnek, {@code GetNextPageText} metodunun metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Bir sayfanın metnini dosyaya kaydeder. </p> <hr> <pre> Örnek, GetNextPageText metodunun metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Girdi dosyasının şifresini alır. |
| [getResolution](#getResolution--) | Çıkarılan görüntüler için çözünürlüğü alır. Varsayılan değer 150'dir. Daha yüksek çözünürlük değerine sahip görüntüler daha net olur. Ancak çözünürlük değerinin artırılması, görüntüleri çıkarmak için gereken süre ve belleği artırır. Genellikle net bir görüntü elde etmek için çözünürlüğü 150 veya 300 olarak ayarlamak yeterlidir. |
| [getStartPage](#getStartPage--) | PDF belgesini temsil eden Pdf.Engine nesnesi. |
| [getText](#getText-java.io.OutputStream-) | Metni akışa kaydeder. ayrıca bakınız:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Metni akışa kaydeder. ayrıca bakınız:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Metni dosyaya kaydeder. ayrıca bakınız:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Metin arama seçeneklerini alır. |
| [hasNextImage](#hasNextImage--) | <p> PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: ExtractImage bu yöntemi kullanmadan önce çağrılmalıdır. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Daha fazla metin alınabilir olup olmadığını gösterir. </p> <hr> <pre> Örnek, {@code HasNextPageText} özelliğinin metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Metin İbranice veya Arapça semboller içerdiğinde doğrudur. Bu durum özellikle dikkate alınmalıdır çünkü dize fonksiyonları davranışlarını değiştirir ve metni sağdan sola (rakamlar ve diğer metin dışı karakterler hariç) işlemeye başlar. |
| [setEndPage](#setEndPage-int-) | <p> Çıkarma işleminin gerçekleştirileceği sayfa aralığında son sayfayı ayarlar. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Görüntü çıkarma işlemi için modu ayarlar. </p> <hr> Varsayılan değer, kaynaklarda tanımlı tüm görüntüleri çıkaran ExtractImageMode.DefinedInResources'dir. Gerçekten gösterilen görüntüleri çıkarmak için ExtractImageMode.ActuallyUsed modu kullanılmalıdır. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Metin çıkarma sonucunun modunu ayarlar. </p> <hr> <pre> Örnek, {@code ExtractTextMode} özelliğinin metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> Değer: 0 saf metin modudur ve 1 ham sıralama modudur. Varsayılan 0'dır. |
| [setPassword](#setPassword-java.lang.String-) | Girdi dosyasının şifresini ayarlar. |
| [setResolution](#setResolution-int-) | Çıkarılan görüntüler için çözünürlüğü ayarlayın. Varsayılan değer 150'dir. Daha yüksek çözünürlük değerine sahip görüntüler daha net olur. Ancak çözünürlük değerini artırmak, görüntüleri çıkarmak için gereken zaman ve belleği artırır. Genellikle net bir görüntü elde etmek için çözünürlüğü 150 veya 300 olarak ayarlamak yeterlidir. |
| [setStartPage](#setStartPage-int-) | <p> Çıkarma işleminin gerçekleştirileceği sayfa aralığında başlangıç sayfasını ayarlar. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Metin arama seçeneklerini ayarlar. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Bir Pdf belgesini düzenleme için bağlar. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Bir Pdf belgesini düzenleme için bağlar. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Akıştan PDF belgesini bağlar. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream(\"sample.pdf\"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Giriş PDF dosyasını bağla. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf(\"sample.pdf\"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Bir Pdf belgesinden ekleri çıkarır.

### extractAttachment {#extractAttachment-java.lang.String-}
Bir Pdf belgesinden ekleri çıkarır.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> PDF dosyasından görüntüleri çıkar. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Tüm İşaretlenmiş İçerik konteynerlerini ayrı görüntüler olarak alır. </p> <p> Her İşaretlenmiş İçerik, sayfa bloğu için {@code MCID_<ID number of block for the page>.png} adıyla png formatında bir görüntü olarak kaydedilir.

### extractText {#extractText--}
```
public void extractText()
```

<p> Pdf belgesinden metni çıkarır. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> İkinci örnek, her sayfanın metninin tek bir txt dosyasına nasıl çıkarılacağını gösterir. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Pdf belgesinden metni çıkarır. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> İkinci örnek, her sayfanın metninin tek bir txt dosyasına nasıl çıkarılacağını gösterir. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Yalnızca dahili kullanım için

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Tüm ek dosyalarını akışlara kaydeder. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Pdf belgesindeki ek dosyanın akış dizisi.

### getAttachment {#getAttachment-java.lang.String-}
<p> Tüm ek dosyalarını akışlara kaydeder. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Pdf belgesindeki ek dosyanın akış dizisi.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Eklerin listesini alır.

**Returns:**
Bir List<FileSpecificatio> döndürür.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> PDF dosyasındaki eklerin listesini döndürür. Not: Bu yöntemi kullanmadan önce ExtractAttachments çağrılmalıdır. </p> <hr> <pre> Örnek, PDF dosyasından ek adlarının nasıl çıkarılacağını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile(\"sample.pdf\")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Eklerin listesi

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Çıkarma işleminin gerçekleştirileceği sayfa aralığındaki son sayfayı alır. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
bitiş sayfası.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Görüntü çıkarma işlemi için modu ayarlar. </p> <hr> Varsayılan değer, kaynaklarda tanımlı tüm görüntüleri çıkaran ExtractImageMode.DefinedInResources'dir. Gerçekten gösterilen görüntüleri çıkarmak için ExtractImageMode.ActuallyUsed modu kullanılmalıdır.

**Returns:**
ExtractImageMode değeri @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Metin çıkarma sonucunun modunu alır. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> Değer: 0 saf metin modudur ve 1 ham sıralama modudur. Varsayılan 0.

**Returns:**
metin çıkarma sonucu.

### getNextImage {#getNextImage-java.io.OutputStream-}
PDF dosyasından sonraki görüntüyü alır ve akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
PDF dosyasından sonraki görüntüyü alır ve verilen görüntü formatıyla akışa kaydeder.

### getNextImage {#getNextImage-java.lang.String-}
<p> PDF belgesinden sonraki görüntüyü alır. Not: ExtractImage bu yöntemi kullanmadan önce çağrılmalıdır. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
PDF belgesinden sonraki görüntüyü verilen görüntü formatıyla alır. Not: ExtractImage bu yöntemi kullanmadan önce çağrılmalıdır.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Bir sayfanın metnini akışa kaydeder. </p> <hr> <pre> Örnek, {@code GetNextPageText} metodunun metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Bir sayfanın metnini dosyaya kaydeder. </p> <hr> <pre> Örnek, GetNextPageText metodunun metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Girdi dosyasının şifresini alır.

**Returns:**
String değeri

### getResolution {#getResolution--}
```
public int getResolution()
```

Çıkarılan görüntüler için çözünürlüğü alır. Varsayılan değer 150'dir. Daha yüksek çözünürlük değerine sahip görüntüler daha net olur. Ancak çözünürlük değerinin artırılması, görüntüleri çıkarmak için gereken süre ve belleği artırır. Genellikle net bir görüntü elde etmek için çözünürlüğü 150 veya 300 olarak ayarlamak yeterlidir.

**Returns:**
int değer

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

PDF belgesini temsil eden Pdf.Engine nesnesi.

**Returns:**
sayfa aralığındaki başlangıç sayfası.

### getText {#getText-java.io.OutputStream-}
Metni akışa kaydeder. ayrıca bakınız:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Metni akışa kaydeder. ayrıca bakınız:{@code ExtractText}

### getText {#getText-java.lang.String-}
Metni dosyaya kaydeder. ayrıca bakınız:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Metin arama seçeneklerini alır.

**Returns:**
metin arama seçenekleri.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: ExtractImage bu yöntemi kullanmadan önce çağrılmalıdır. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Daha fazla görüntüye erişilebiliyorsa true

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Daha fazla metin alınabilir olup olmadığını gösterir. </p> <hr> <pre> Örnek, {@code HasNextPageText} özelliğinin metin çıkarma senaryosundaki kullanımını gösterir. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Daha fazla metin alınıp alınamayacağını belirtir, true ise alabilir, false ise almaz.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Metin İbranice veya Arapça semboller içerdiğinde doğrudur. Bu durum özellikle dikkate alınmalıdır çünkü dize fonksiyonları davranışlarını değiştirir ve metni sağdan sola (rakamlar ve diğer metin dışı karakterler hariç) işlemeye başlar.

**Returns:**
boolean değer

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Çıkarma işleminin gerçekleştirileceği sayfa aralığında son sayfayı ayarlar. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | bitiş sayfası. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Görüntü çıkarma işlemi için modu ayarlar. </p> <hr> Varsayılan değer, kaynaklarda tanımlı tüm görüntüleri çıkaran ExtractImageMode.DefinedInResources'dir. Gerçekten gösterilen görüntüleri çıkarmak için ExtractImageMode.ActuallyUsed modu kullanılmalıdır.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Metin çıkarma sonucunun modunu ayarlar. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> Değer: 0 saf metin modudur ve 1 ham sıralama modudur. Varsayılan 0.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | metin çıkarma sonucu. |

### setPassword {#setPassword-java.lang.String-}
Girdi dosyasının şifresini ayarlar.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Çıkarılan görüntüler için çözünürlüğü ayarlayın. Varsayılan değer 150'dir. Daha yüksek çözünürlük değerine sahip görüntüler daha net olur. Ancak çözünürlük değerini artırmak, görüntüleri çıkarmak için gereken zaman ve belleği artırır. Genellikle net bir görüntü elde etmek için çözünürlüğü 150 veya 300 olarak ayarlamak yeterlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Çıkarma işleminin gerçekleştirileceği sayfa aralığında başlangıç sayfasını ayarlar. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | sayfa aralığındaki başlangıç sayfası. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Metin arama seçeneklerini ayarlar.
