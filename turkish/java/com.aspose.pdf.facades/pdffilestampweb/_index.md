---
title: "PdfFileStampWeb"
linktitle: "PdfFileStampWeb"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyalarına damga (filigran veya arka plan) eklemek için sınıf. HttpServletResponse ile çalışmayı etkinleştirir."
type: docs
weight: 550
url: /tr/java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

PDF dosyalarına damga (filigran veya arka plan) eklemek için sınıf. HttpServletResponse ile çalışmayı etkinleştirir.

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

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Belgenin sayfalarına alt bilgi ekler. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Belgenin sayfalarına alt bilgi ekler. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Sayfanın alt kısmına resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Sayfanın alt kısmına resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Belgenin sayfalarına alt bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Sayfaların alt bilgisi olarak resmi ekler. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Sayfaya üst bilgi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Dosyanın sayfalarına üst bilgi ekler. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Sayfalara üst bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Sayfanın üst kısmına resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Dosyanın sayfalarına üst bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Sayfalara üst bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Sayfaya sayfa numarası ekler. Sayfa numarası, sayfa numarasıyla değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanmış şekilde yerleştirilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Sayfada belirtilen konuma sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Sayfalara sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Belgenin sayfalarına sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Dosyaya sayfa numarası ekler. Sayfa numarası metni, sayfa numarasıyla değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanmış şekilde yerleştirilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Sayfada belirtilen konuma sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Sayfalara sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Belgenin sayfalarına sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Dosyaya damga ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Açık dosyaları kapatır ve değişiklikleri kaydeder. Uyarı: Giriş veya çıkış akışları belirtilmişse, Close() yöntemi tarafından kapatılmaz. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Kullanımdan kaldırıldı. |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. Olası değerler: inline / attachment. Varsayılan: inline. |
| [getInputFile](#getInputFile--) | Girdi dosyasının adını ve yolunu alır. |
| [getInputStream](#getInputStream--) | Giriş akışını alır. |
| [getKeepSecurity](#getKeepSecurity--) | Güvenliği true ise tutar. (Bu özellik sonraki sürümlerde uygulanacaktır). |
| [getNumberingStyle](#getNumberingStyle--) | Sayfa numaralandırma stilini alır veya ayarlar. |
| [getOptimizeSize](#getOptimizeSize--) | Optimizasyon bayrağını alır veya ayarlar. |
| [getOutputFile](#getOutputFile--) | Çıktı dosyasının adını ve yolunu alır. |
| [getOutputStream](#getOutputStream--) | Çıktı akışını alır. |
| [getPageHeight](#getPageHeight--) | <p> Kaynak dosyadaki ilk sayfanın yüksekliğini alır. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Height = \" + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | Sayfa numarasının dönüşünü alır. Dönüş derece cinsindendir. Varsayılan 0'dır. |
| [getPageWidth](#getPageWidth--) | <p> Girdi dosyasındaki ilk sayfanın genişliğini alır. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Width = \" + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | İşlemin sonucunun saklanacağı Response nesnesini alır. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak kaydedildiğinde kaydetme seçeneklerini alır. Varsayılan değer: PdfSaveOptions. |
| [getStampId](#getStampId--) | Sonraki eklenen damganın Damga ID'si (sayfa başlıkları/altbilgileri/sayfa numaraları dahil). |
| [getStartingNumber](#getStartingNumber--) | Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine depolandığında içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF formatında kaydedilir. |
| [setInputFile](#setInputFile-java.lang.String-) | Giriş dosyasının adını ve yolunu ayarlar. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Giriş akışını ayarlar. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Güvenliği true ise tutar. (Bu özellik sonraki sürümlerde uygulanacaktır). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Sayfa numaralandırma stilini alır veya ayarlar. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Optimizasyon bayrağını alır veya ayarlar. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Çıktı dosyasının adını ve yolunu ayarlar. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Çıktı akışını ayarlar veya ayarlar. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Sayfa numarasının dönüşünü ayarlar. Dönüş derece cinsindendir. Varsayılan 0'dır. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | İşlemin sonucunun saklanacağı Response nesnesini ayarlar. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak depolandığında kaydetme seçeneklerini ayarlar. Varsayılan değer: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | Sonraki eklenen damganın Damga ID'si (sayfa başlıkları/altbilgileri/sayfa numaraları dahil). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Girdi dosyasındaki ilk sayfa için başlangıç numarasını ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılır. Örneğin StartingNumber 100 olarak ayarlanırsa, belge sayfaları 100, 101, 102... numaralarına sahip olur. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Alt sol konum.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Alt orta konum.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Alt sağ konum.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Sol konum.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Sağ konum.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Üst let konumu.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Üst orta konum.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Sağ üst konum.

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> PdfFileStamp yapıcı metodu. Girdi dosyası ve çıktı dosyası ilgili özellikler aracılığıyla belirtilebilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Belgenin sayfalarına alt bilgi ekler. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Belgenin sayfalarına alt bilgi ekler. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Sayfanın alt kısmına resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Sayfanın alt kısmına resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Belgenin sayfalarına alt bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Sayfaların alt bilgisi olarak resmi ekler.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Sayfaya üst bilgi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Dosyanın sayfalarına üst bilgi ekler. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Sayfalara üst bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Sayfanın üst kısmına resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Dosyanın sayfalarına üst bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Sayfalara üst bilgi olarak resmi ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Sayfaya sayfa numarası ekler. Sayfa numarası, sayfa numarasıyla değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanmış şekilde yerleştirilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Sayfada belirtilen konuma sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Sayfalara sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Belgenin sayfalarına sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Dosyaya sayfa numarası ekler. Sayfa numarası metni, sayfa numarasıyla değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanmış şekilde yerleştirilir. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Sayfada belirtilen konuma sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Sayfalara sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Belgenin sayfalarına sayfa numarası ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Dosyaya damga ekler. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Açık dosyaları kapatır ve değişiklikleri kaydeder. Uyarı: Giriş veya çıkış akışları belirtilmişse, Close() yöntemi tarafından kapatılmaz. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Kullanımdan kaldırıldı.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
string nesnesi

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. Olası değerler: inline / attachment. Varsayılan: inline.

**Returns:**
ContentDisposition öğesi

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Girdi dosyasının adını ve yolunu alır.

**Returns:**
Dize nesnesi

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Giriş akışını alır.

**Returns:**
InputStream nesnesi

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Güvenliği true ise tutar. (Bu özellik sonraki sürümlerde uygulanacaktır).

**Returns:**
boolean değer

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Sayfa numaralandırma stilini alır veya ayarlar.

**Returns:**
NumberingStyle öğesi

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Optimizasyon bayrağını alır veya ayarlar.

**Returns:**
boolean değer

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

Çıktı dosyasının adını ve yolunu alır.

**Returns:**
Dize nesnesi

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

Çıktı akışını alır.

**Returns:**
OutputStream nesnesi

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Kaynak dosyadaki ilk sayfanın yüksekliğini alır. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Height = \" + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
float değer

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Sayfa numarasının dönüşünü alır. Dönüş derece cinsindendir. Varsayılan 0'dır.

**Returns:**
float değer

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Girdi dosyasındaki ilk sayfanın genişliğini alır. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Width = \" + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
float değer

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

İşlemin sonucunun saklanacağı Response nesnesini alır.

**Returns:**
HttpServletResponse nesnesi

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak kaydedildiğinde kaydetme seçeneklerini alır. Varsayılan değer: PdfSaveOptions.

**Returns:**
SaveOptions nesnesi

### getStampId {#getStampId--}
```
public int getStampId()
```

Sonraki eklenen damganın Damga ID'si (sayfa başlıkları/altbilgileri/sayfa numaraları dahil).

**Returns:**
int değer

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır.

**Returns:**
int değer

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine depolandığında içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF formatında kaydedilir.

### setInputFile {#setInputFile-java.lang.String-}
Giriş dosyasının adını ve yolunu ayarlar.

### setInputStream {#setInputStream-java.io.InputStream-}
Giriş akışını ayarlar.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Güvenliği true ise tutar. (Bu özellik sonraki sürümlerde uygulanacaktır).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Sayfa numaralandırma stilini alır veya ayarlar.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Optimizasyon bayrağını alır veya ayarlar.

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
public void setPageNumberRotation(float value)
```

Sayfa numarasının dönüşünü ayarlar. Dönüş derece cinsindendir. Varsayılan 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
İşlemin sonucunun saklanacağı Response nesnesini ayarlar.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak depolandığında kaydetme seçeneklerini ayarlar. Varsayılan değer: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Sonraki eklenen damganın Damga ID'si (sayfa başlıkları/altbilgileri/sayfa numaraları dahil).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Girdi dosyasındaki ilk sayfa için başlangıç numarasını ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılır. Örneğin StartingNumber 100 olarak ayarlanırsa, belge sayfaları 100, 101, 102... numaralarına sahip olur. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
