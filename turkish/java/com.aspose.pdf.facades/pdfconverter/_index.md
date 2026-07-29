---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyasının her sayfasını görüntülere dönüştüren bir sınıfı temsil eder, şu anda BMP, JPEG, PNG ve TIFF desteklenmektedir. PDF'lerde desteklenen içerik: resimler, form, yorum."
type: docs
weight: 390
url: /tr/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

PDF dosyasının her sayfasını görüntülere dönüştürmek için bir sınıfı temsil eder, şu anda BMP, JPEG, PNG ve TIFF desteklenir. PDF'lerde desteklenen içerik: resimler, form, yorum.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Yeni {@code PdfConverter} nesnesini başlatır. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Yeni {@code PdfConverter} nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Bir PDF belgesini {@link PdfConverter} örneğine bağlar, sonraki işlemler için. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Dönüştürme için bir Pdf akışını bağlar. |
| [bindPdf](#bindPdf-java.lang.String-) | Dönüştürme için bir Pdf dosyasını bağlar. |
| [close](#close--) | PdfConverter örneğini kapatır ve kaynakları serbest bırakır. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Yalnızca dahili kullanım için |
| [dispose](#dispose--) | PdfConverter örneğini kapatır ve kaynakları serbest bırakır. Bu yöntem artık kullanılmıyor, yerine close() kullanın. |
| [doConvert](#doConvert--) | <p> PDF belgesini görüntülere dönüştürmek için bazı başlangıç işlemleri yapın. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [getEndPage](#getEndPage--) | Dönüştürmek istediğiniz son konumu alır. |
| [getFormPresentationMode](#getFormPresentationMode--) | Form sunum modunu alır. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Görüntüyü varsayılan görüntü formatı - jpeg ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Görüntüyü verilen görüntü formatı ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Görüntüyü verilen görüntü formatı, boyut ve kalite ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Görüntüyü verilen görüntü formatı ve kalite ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Görüntüyü verilen görüntü formatı, boyut ve kalite ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Görüntüyü verilen sayfa boyutu ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Görüntüyü verilen sayfa boyutu ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Görüntüyü verilen sayfa boyutu, görüntü formatı ve kalite ile akışa kaydeder. |
| [getNextImage](#getNextImage-java.lang.String-) | Görüntüyü varsayılan görüntü formatı - jpeg ile dosyaya kaydeder. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Verilen görüntü formatı ile görüntüyü dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Görseli verilen görüntü formatı, görüntü boyutu ve kalite ile dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Görseli verilen görüntü formatı ve kalite ile dosyaya kaydeder. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Görseli verilen görüntü formatı ve boyutlarla dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Görseli verilen görüntü formatı, boyutlar ve kalite ile dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Görseli verilen sayfa boyutu ve varsayılan görüntü formatı - jpeg ile dosyaya kaydeder. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Görseli verilen sayfa boyutu ve görüntü formatı ile dosyaya kaydeder. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Görseli verilen sayfa boyutu, görüntü formatı ve kalite ile dosyaya kaydeder. |
| [getPageCount](#getPageCount--) | Sayfa sayısını alır. |
| [getPassword](#getPassword--) | Belgenin OwnerPassword'ını alır. |
| [getRenderingOptions](#getRenderingOptions--) | Renderleme seçeneklerini alır. |
| [getResolution](#getResolution--) | Dönüştürme sırasında çözünürlüğü alır. Çözünürlük ne kadar yüksek olursa, dönüştürme hızı o kadar yavaş olur. Varsayılan değer 150'dir. |
| [getStartPage](#getStartPage--) | Dönüştürmek istediğiniz başlangıç konumunu alır. Minimum değer 1'dir. |
| [getUserPassword](#getUserPassword--) | Belgenin UserPassword'ını alır. |
| [hasNextImage](#hasNextImage--) | PDF dosyasının daha fazla görüntüsü olup olmadığını gösterir. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Sayfadaki gizli alanların görünürlüğünü kontrol eden bayrağı alır. Metod kullanımdan kaldırılmıştır. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Görüntü akışları listesini tek bir görüntü akışı olarak birleştirir. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Tiff akışları listesini tek bir çok çerçeveli tiff akışı olarak birleştirir. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | PDF belgesinin her sayfasını görüntülere ile dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | PDF belgesinin her sayfasını görüntülere ile dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [setEndPage](#setEndPage-int-) | Dönüştürmek istediğiniz son konumu ayarlar. setStartPage(int) metodundan önce setEndPage(int) kullanın. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Form sunum modunu ayarlar. |
| [setPassword](#setPassword-java.lang.String-) | Belgenin OwnerPassword'ını ayarlar. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Dönüştürmek istediğiniz sayfalar arasındaki aralığı ayarlar. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Renderleme seçeneklerini ayarlar. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Dönüştürme sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa, dönüştürme hızı o kadar yavaş olur. Varsayılan değer 150'dir. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Kullanımdan kaldırıldı. |
| [setStartPage](#setStartPage-int-) | Dönüştürmek istediğiniz başlangıç konumunu ayarlar. Minimum değer 1'dir. setStartPage(int) metodundan önce setEndPage(int) kullanın. |
| [setUserPassword](#setUserPassword-java.lang.String-) | Belgenin UserPassword'ını ayarlar. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Yeni {@code PdfConverter} nesnesini başlatır.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Yeni {@code PdfConverter} nesnesini başlatır.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Bir PDF belgesini {@link PdfConverter} örneğine bağlar, sonraki işlemler için.

### bindPdf {#bindPdf-java.io.InputStream-}
Dönüştürme için bir Pdf akışını bağlar.

### bindPdf {#bindPdf-java.lang.String-}
Dönüştürme için bir Pdf dosyasını bağlar.

### close {#close--}
```
public void close()
```

PdfConverter örneğini kapatır ve kaynakları serbest bırakır.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Yalnızca dahili kullanım için

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

PdfConverter örneğini kapatır ve kaynakları serbest bırakır. Bu yöntem artık kullanılmıyor, yerine close() kullanın.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Bir PDF belgesini görüntülere dönüştürmek için bazı başlangıç işlemlerini yapar. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

**Returns:**
PageCoordinateType öğesi @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Dönüştürmek istediğiniz son konumu alır.

**Returns:**
int değer

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Form sunum modunu alır.

**Returns:**
form sunum modu. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Görüntüyü varsayılan görüntü formatı - jpeg ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Görüntüyü verilen görüntü formatı ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Görüntüyü verilen görüntü formatı, boyut ve kalite ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Görüntüyü verilen görüntü formatı ve kalite ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Görüntüyü verilen görüntü formatı, boyut ve kalite ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Görüntüyü verilen sayfa boyutu ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Görüntüyü verilen sayfa boyutu ile akışa kaydeder.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Görüntüyü verilen sayfa boyutu, görüntü formatı ve kalite ile akışa kaydeder.

### getNextImage {#getNextImage-java.lang.String-}
Görüntüyü varsayılan görüntü formatı - jpeg ile dosyaya kaydeder.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Görüntüyü verilen görüntü formatı ile dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Görüntüyü verilen görüntü formatı, görüntü boyutu ve kalite ile dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Görseli verilen görüntü formatı ve kalite ile dosyaya kaydeder.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Görüntüyü verilen görüntü formatı ve boyutlarla dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile dosyaya kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Görseli verilen sayfa boyutu ve varsayılan görüntü formatı - jpeg ile dosyaya kaydeder.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Görseli verilen sayfa boyutu ve görüntü formatı ile dosyaya kaydeder.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Görseli verilen sayfa boyutu, görüntü formatı ve kalite ile dosyaya kaydeder.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Sayfa sayısını alır.

**Returns:**
int değer

### getPassword {#getPassword--}
```
public String getPassword()
```

Belgenin OwnerPassword'ını alır.

**Returns:**
String değeri

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Renderleme seçeneklerini alır.

**Returns:**
renderleme seçenekleri.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Dönüştürme sırasında çözünürlüğü alır. Çözünürlük ne kadar yüksek olursa, dönüştürme hızı o kadar yavaş olur. Varsayılan değer 150'dir.

**Returns:**
Çözünürlük öğesi

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Dönüştürmek istediğiniz başlangıç konumunu alır. Minimum değer 1'dir.

**Returns:**
int değer

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Belgenin UserPassword'ını alır.

**Returns:**
String değeri

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

PDF dosyasının daha fazla görüntüsü olup olmadığını gösterir.

**Returns:**
Daha fazla görüntü alınıp alınamayacağını belirtir, mümkünse true, aksi takdirde false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Sayfadaki gizli alanların görünürlüğünü kontrol eden bayrağı alır. Metod kullanımdan kaldırılmıştır.

**Returns:**
boolean değer

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Görüntü akışları listesini tek bir görüntü akışı olarak birleştirir.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Tiff akışları listesini tek bir çok çerçeveli tiff akışı olarak birleştirir.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
PDF belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
PDF belgesinin her sayfasını görüntülere ile dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
PDF belgesinin her sayfasını görüntülere ile dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\Test\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Her bir PDF belgesinin sayfalarını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Bir PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Dönüştürmek istediğiniz son konumu ayarlar. setStartPage(int) metodundan önce setEndPage(int) kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Form sunum modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | form sunum modu. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Belgenin OwnerPassword'ını ayarlar.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Dönüştürmek istediğiniz sayfalar arasındaki aralığı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startPage |  | int değer |
| EndPage |  | int değer |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Renderleme seçeneklerini ayarlar.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Dönüştürme sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa, dönüştürme hızı o kadar yavaş olur. Varsayılan değer 150'dir.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Kullanımdan kaldırıldı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Dönüştürmek istediğiniz başlangıç konumunu ayarlar. Minimum değer 1'dir. setStartPage(int) metodundan önce setEndPage(int) kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setUserPassword {#setUserPassword-java.lang.String-}
Belgenin UserPassword'ını ayarlar.
