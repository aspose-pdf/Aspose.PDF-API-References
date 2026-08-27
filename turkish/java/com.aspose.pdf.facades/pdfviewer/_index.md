---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF'i görüntülemek veya yazdırmak için bir sınıfı temsil eder."
type: docs
weight: 610
url: /tr/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

PDF'i görüntülemek veya yazdırmak için bir sınıfı temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Son sayfa yazdırma olayına aboneliği ekler/kaldırır. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Son sayfa yazdırma olayına aboneliği ekler/kaldırır. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Yeni {@code PdfViewer} nesnesini başlatır. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Yeni {@code PdfViewer} nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.lang.String-) | Facade'i başlatır. |
| [close](#close--) | Mevcut PDF dosyasını kapatır. |
| [closePdfFile](#closePdfFile--) | Mevcut PDF dosyasını kapatır. |
| [decodeAllPages](#decodeAllPages--) | Mevcut PDF dosyasının sayfalarını al. |
| [decodePage](#decodePage-int-) | Bir PDF dosyasının sayfasını çözer. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Sayfayı BufferedImage'a çözer |
| [dispose](#dispose--) | Facade kaynaklarını serbest bırakır. Bu yöntem artık kullanılmıyor, yerine close() kullanın. |
| [getAutoResize](#getAutoResize--) | Dosyanın optimize edilmiş boyutla yazdırılıp yazdırılmayacağını gösteren bir bool değeri ayarlar. |
| [getAutoRotate](#getAutoRotate--) | Otomatik döndürme ile dosyanın yazdırılıp yazdırılmayacağını gösteren bir bool değeri alır |
| [getAutoRotateMode](#getAutoRotateMode--) | Dönüş yönünü gösteren bir AutoRotateMode değeri alır |
| [getCoordinateType](#getCoordinateType--) | Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [getCopiesPrinted](#getCopiesPrinted--) | Yazdırılan kopyaları alır |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Varsayılan sayfa ayarlarını alır. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Varsayılan yazıcı ayarlarını alır. |
| [getFormPresentationMode](#getFormPresentationMode--) | Form sunum modunu alır. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Yatay hizalamayı gösteren bir değer alır |
| [getPageCount](#getPageCount--) | Mevcut Pdf dosyasının sayfa sayısını alır. |
| [getPassword](#getPassword--) | Girdi belge şifresini alır. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Sayfanın gri tonlamalı olarak yazdırılıp yazdırılmadığını gösteren bir bool değeri alır veya ayarlar. Varsayılan olarak false'tur. </p> <hr> Varsayılan false false'tur. |
| [getPrintAsImage](#getPrintAsImage--) | <p> PdfViewer'ın görüntü olarak yazdırması için bir mod alır. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Belge yazdırıldığında yazıcı kuyruğundaki belge adını alır. Varsayılan değer dosya adıdır. |
| [getPrintPageDialog](#getPrintPageDialog--) | Yazdırma sırasında sayfa numarası iletişim kutusunun üretilip üretilmeyeceğini gösteren bir bool değeri alır. |
| [getPrintStatus](#getPrintStatus--) | Yazdırma işinin sonucunu alır. Başarılıysa null; aksi takdirde istisna nesnesi. |
| [getRenderingOptions](#getRenderingOptions--) | Renderleme seçeneklerini alır. |
| [getResolution](#getResolution--) | Viewing ve yazdırma sırasında çözünürlüğü alır veya ayarlar. Çözünürlük ne kadar yüksek olursa hız o kadar yavaş olur. Varsayılan değer 150'dir. Bu özellik, sayfadan görüntüye dönüşüm akışlarında görüntü çözünürlüğünü değiştirir: {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) {@code } olarak ayarlandığında veya {@link #decodePage(int)} ya da {@link #decodeAllPages} yöntemi çağrıldığında. Bir yazıcıya doğrudan yazdırma için yazıcı çözünürlüğünü ayarlamak istiyorsanız, {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) özelliğini {@code PageSettings} sınıfında kullanın. |
| [getScaleFactor](#getScaleFactor--) | Ölçek faktörünü gösteren bir kayan nokta değeri alır. Varsayılan değer 1.0'dır. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Dosya modunda yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülmesini alır. Çıktı dosyasının boyutu önemli olduğunda kullanın. |
| [getVerticalAlignment](#getVerticalAlignment--) | Dikey hizalamayı gösteren bir değer alır |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Bu yöntem kullanımdan kaldırılmıştır. Sayfadaki gizli alanların görünürlüğünü kontrol eden bayrağı alır. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Bir Pdf dosya akışı açar. Ancak Pdf dosyasının sayfalarını gerçekten çözmez. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Bir Pdf dosyası açar, ancak Pdf dosyasının sayfalarını gerçekten çözmez. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Pdf belgesini varsayılan yazıcıyla yazdırır. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false); //yazdırma sırasında sayfa numarası iletişim kutusunu üretme viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Pdf belgesini yazıcı ayarlarıyla yazdırır. Çıktı sayfa boyutu, belgenin ilk sayfa boyutuna uyacaktır. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false); //yazdırma sırasında sayfa numarası iletişim kutusunu üretme PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Ayarlarla Pdf belgesini yazdırır. Belge boyutu sayfa boyutuyla uyumlu değilse, pdf.kit sayfa boyutuna sığdırmak için genişletecektir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutta yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false);//yazdırırken sayfa numarası iletişim kutusunu oluşturma PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazla sayfa içeriyorsa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutta yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.printPageDialog=false;//yazdırırken sayfa numarası iletişim kutusunu oluşturma viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Bu yöntem, dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek kalmaz. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Belirtilen yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazla sayfa içeriyorsa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // dosyayı ayarlanmış boyutta yazdır viewer.setAutoRotate(true); // dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog(false); // sayfa numarası iletişim kutusunu oluşturma // yazdırma PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem, dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek kalmaz. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazla sayfa içeriyorsa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutta yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false);//yazdırırken sayfa numarası iletişim kutusunu oluşturma PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem, dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek kalmaz. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazla sayfa içeriyorsa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // dosyayı ayarlanmış boyutta yazdır viewer.setAutoRotate(true); // dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog(false);// sayfa numarası iletişim kutusunu oluşturma // yazdırma viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Belirtilen yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek kalmaz. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek kalmaz. |
| [save](#save-java.io.InputStream-) | Sonuç PDF belgesini akışa kaydeder. |
| [save](#save-java.lang.String-) | Sonuç PDF belgesini dosyaya kaydeder. |
| [setAutoResize](#setAutoResize-boolean-) | Dosyanın optimize edilmiş boyutla yazdırılıp yazdırılmayacağını gösteren bir bool değeri ayarlar. |
| [setAutoRotate](#setAutoRotate-boolean-) | Dosyanın otomatik döndürme ile yazdırılıp yazdırılmayacağını belirten bir bool değeri ayarlar |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Dönüş yönünü belirten bir AutoRotateMode değeri ayarlar |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Form sunum modunu ayarlar. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Yatay hizalamayı belirten bir değer ayarlar |
| [setPassword](#setPassword-java.lang.String-) | Giriş belgesi şifresini ayarlar. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Sayfanın gri tonlamalı olarak yazdırılıp yazdırılmadığını gösteren bir bool değeri alır veya ayarlar. Varsayılan olarak false'tur. </p> <hr> Varsayılan false false'tur. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> PdfViewer'ın görüntü olarak yazdırılması için bir mod ayarlar. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Belge yazdırıldığında yazıcı kuyruğundaki belge adını ayarlar. Varsayılan değer dosya adıdır. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Yazdırma sırasında sayfa numarası iletişim kutusunun üretilip üretilmeyeceğini belirten bir boolean değer ayarlar. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Renderleme seçeneklerini ayarlar. |
| [setResolution](#setResolution-int-) | İzleme ve yazdırma sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa hız o kadar yavaş olur. Varsayılan değer 150'dir. Bu özellik, sayfa‑görüntü dönüşüm akışlarında görüntü çözünürlüğünü değiştirir: {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) {@code } olarak ayarlandığında veya {@link #decodePage(int)} ya da {@link #decodeAllPages} yöntemi çağrıldığında. Yazıcıya doğrudan yazdırma için bir yazıcı çözünürlüğü ayarlamak istiyorsanız, {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) özelliğini {@code PageSettings} sınıfında kullanın. |
| [setScaleFactor](#setScaleFactor-float-) | Ölçek faktörünü belirten bir kayan nokta değeri ayarlar. Varsayılan değer 1.0'dır. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Kullanımdan kaldırıldı. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Dosya modunda yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülmesini ayarlar. Çıktı dosyasının boyutu önemli olduğunda kullanın. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Dikey hizalamayı belirten bir değer ayarlar |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Son sayfa yazdırma olayına aboneliği ekler/kaldırır.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Son sayfa yazdırma olayına aboneliği ekler/kaldırır.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Yeni {@code PdfViewer} nesnesini başlatır.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Yeni {@code PdfViewer} nesnesini başlatır.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.io.InputStream-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.lang.String-}
Facade'i başlatır.

### close {#close--}
```
public void close()
```

Mevcut PDF dosyasını kapatır.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Mevcut PDF dosyasını kapatır.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Mevcut PDF dosyasının sayfalarını al.

**Returns:**
Pdf sayfa görüntülerinin dizisini döndürür.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Bir PDF dosyasının sayfasını çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Bir Pdf dosyasının sayfa numarası, 1 ile PageCount arasında olmalıdır. |

**Returns:**
Pdf sayfa görüntüsünü döndürür.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Sayfayı BufferedImage'a çözer

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Facade kaynaklarını serbest bırakır. Bu yöntem artık kullanılmıyor, yerine close() kullanın.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Dosyanın optimize edilmiş boyutla yazdırılıp yazdırılmayacağını gösteren bir bool değeri ayarlar.

**Returns:**
boolean değer: false ise sayfayı ölçeklendirme olmadan yazar. true ise sayfayı yazdırılabilir alana sığacak şekilde ölçeklendirerek yazar.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Otomatik döndürme ile dosyanın yazdırılıp yazdırılmayacağını gösteren bir bool değeri alır

**Returns:**
boolean değer

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Dönüş yönünü gösteren bir AutoRotateMode değeri alır

**Returns:**
AutoRotateMode öğesi @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

**Returns:**
PageCoordinateType öğesi @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Yazdırılan kopyaları alır

**Returns:**
int değer

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Varsayılan sayfa ayarlarını alır.

**Returns:**
Sayfa ayarları nesnesi.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Varsayılan yazıcı ayarlarını alır.

**Returns:**
Sayfa ayarları nesnesi.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Form sunum modunu alır.

**Returns:**
FormPresentationMode öğesi @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Yatay hizalamayı gösteren bir değer alır

**Returns:**
HorizontalAlignment öğesi @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Mevcut Pdf dosyasının sayfa sayısını alır.

**Returns:**
sayfa sayısını döndür.

### getPassword {#getPassword--}
```
public String getPassword()
```

Girdi belge şifresini alır.

**Returns:**
String değeri

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Sayfanın gri tonlamalı olarak yazdırılıp yazdırılmadığını gösteren bir bool değeri alır veya ayarlar. Varsayılan olarak false'tur. </p> <hr> Varsayılan false false'tur.

**Returns:**
boolean değer

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> PdfViewer'ın görüntü olarak yazdırması için bir mod alır. </p>

**Returns:**
boolean değer <hr> true ise her zaman görüntü olarak yazar (yazdırılan görüntüyü oluşturur) false ise tüm özellikler destekleniyorsa doğrudan cihaza yazar. Belge desteklenmeyen özellikler içeriyorsa sistem otomatik olarak görüntü olarak yazdırmaya karar verebilir. Varsayılan değer false'tur.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Belge yazdırıldığında yazıcı kuyruğundaki belge adını alır. Varsayılan değer dosya adıdır.

**Returns:**
String değeri

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Yazdırma sırasında sayfa numarası iletişim kutusunun üretilip üretilmeyeceğini gösteren bir bool değeri alır.

**Returns:**
boolean değer

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Yazdırma işinin sonucunu alır. Başarılıysa null; aksi takdirde istisna nesnesi.

**Returns:**
istisna nesnesi veya null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Renderleme seçeneklerini alır.

**Returns:**
RenderingOptions nesnesi

### getResolution {#getResolution--}
```
public int getResolution()
```

Viewing ve yazdırma sırasında çözünürlüğü alır veya ayarlar. Çözünürlük ne kadar yüksek olursa hız o kadar yavaş olur. Varsayılan değer 150'dir. Bu özellik, sayfadan görüntüye dönüşüm akışlarında görüntü çözünürlüğünü değiştirir: {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) {@code } olarak ayarlandığında veya {@link #decodePage(int)} ya da {@link #decodeAllPages} yöntemi çağrıldığında. Bir yazıcıya doğrudan yazdırma için yazıcı çözünürlüğünü ayarlamak istiyorsanız, {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) özelliğini {@code PageSettings} sınıfında kullanın.

**Returns:**
int değer

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Ölçek faktörünü gösteren bir kayan nokta değeri alır. Varsayılan değer 1.0'dır.

**Returns:**
kayan nokta değeri.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Dosya modunda yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülmesini alır. Çıktı dosyasının boyutu önemli olduğunda kullanın.

**Returns:**
boolean değer.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Dikey hizalamayı gösteren bir değer alır

**Returns:**
VerticalAlignment öğesi @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Bu yöntem kullanımdan kaldırılmıştır. Sayfadaki gizli alanların görünürlüğünü kontrol eden bayrağı alır.

**Returns:**
boolean değer

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Bir Pdf dosya akışı açar. Ancak Pdf dosyasının sayfalarını gerçekten çözümlemez. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Bir Pdf dosyası açar, ancak Pdf dosyasının sayfalarını gerçekten çözümlemez. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Varsayılan yazıcıyı kullanarak Pdf belgesini yazdırır. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false); //yazdırırken sayfa numarası iletişim kutusunu üretme viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Pdf belgesini yazıcı ayarlarıyla yazdırır. Çıktı sayfa boyutu, belgenin ilk sayfa boyutuna uyacaktır. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false); //yazdırırken sayfa numarası iletişim kutusunu üretme PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Pdf belgesini ayarlarla yazdırır. Belge boyutu sayfa boyutuna uygun değilse, pdf.kit sayfa boyutuna sığdırmak için genişletecektir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog ( false);//yazdırırken sayfa numarası iletişim kutusunu üretme PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans için önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate ( true); //dosyayı ayarlanmış dönüşle yazdır viewer.printPageDialog=false;//yazdırırken sayfa numarası iletişim kutusunu üretme viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek yoktur.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Belirtilen yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans için önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // dosyayı ayarlanmış boyutla yazdır viewer.setAutoRotate(true); // dosyayı ayarlanmış dönüşle yazdır viewer.setPrintPageDialog(false); // sayfa numarası iletişim kutusunu üretme // yazdırırken PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek yoktur.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek yoktur.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Belirtilen yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek yoktur.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanızda yüzlerce sayfa veya daha fazla varsa ya da boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Bu yöntem dosyanın açılmasını ve yazdırılmasını bütünleştirir ve OpenPdfFile() metodunu açıkça çağırmanıza gerek yoktur.

### save {#save-java.io.InputStream-}
Sonuç PDF belgesini akışa kaydeder.

### save {#save-java.lang.String-}
Sonuç PDF belgesini dosyaya kaydeder.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Dosyanın optimize edilmiş boyutla yazdırılıp yazdırılmayacağını gösteren bir bool değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer: false ise sayfayı ölçeklendirme olmadan yazar. true ise sayfayı yazdırılabilir alana sığacak şekilde ölçeklendirerek yazar. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Dosyanın otomatik döndürme ile yazdırılıp yazdırılmayacağını belirten bir bool değeri ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Dönüş yönünü belirten bir AutoRotateMode değeri ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | AutoRotateMode öğesi @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Form sunum modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | FormPresentationMode öğesi |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Yatay hizalamayı belirten bir değer ayarlar

### setPassword {#setPassword-java.lang.String-}
Giriş belgesi şifresini ayarlar.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Sayfanın gri tonlamalı olarak yazdırılıp yazdırılmadığını gösteren bir bool değeri alır veya ayarlar. Varsayılan olarak false'tur. </p> <hr> Varsayılan false false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> PdfViewer'ın görüntü olarak yazdırılması için bir mod ayarlar. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer <hr> true ise her zaman görüntü olarak yazar (yazdırılan görüntüyü oluşturur) false ise tüm özellikler destekleniyorsa doğrudan cihaza yazar. Belge desteklenmeyen özellikler içeriyorsa sistem otomatik olarak görüntü olarak yazdırmaya karar verebilir. Varsayılan değer false'tur. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Belge yazdırıldığında yazıcı kuyruğundaki belge adını ayarlar. Varsayılan değer dosya adıdır.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Yazdırma sırasında sayfa numarası iletişim kutusunun üretilip üretilmeyeceğini belirten bir boolean değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Renderleme seçeneklerini ayarlar.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

İzleme ve yazdırma sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa hız o kadar yavaş olur. Varsayılan değer 150'dir. Bu özellik, sayfa‑görüntü dönüşüm akışlarında görüntü çözünürlüğünü değiştirir: {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) {@code } olarak ayarlandığında veya {@link #decodePage(int)} ya da {@link #decodeAllPages} yöntemi çağrıldığında. Yazıcıya doğrudan yazdırma için bir yazıcı çözünürlüğü ayarlamak istiyorsanız, {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) özelliğini {@code PageSettings} sınıfında kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Ölçek faktörünü belirten bir kayan nokta değeri ayarlar. Varsayılan değer 1.0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | kayan nokta değeri. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Kullanımdan kaldırıldı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Dosya modunda yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülmesini ayarlar. Çıktı dosyasının boyutu önemli olduğunda kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Dikey hizalamayı belirten bir değer ayarlar
