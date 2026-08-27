---
title: "IDocument"
linktitle: "IDocument"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesini temsil eden arayüz"
type: docs
weight: 2230
url: /tr/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

PDF belgesini temsil eden arayüz

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [afterImport](#afterImport--) | Tüm kayıtlı açıklamaları enumerate eder ve her biri için AfterImport metodunu çağırır. |
| [bindXml](#bindXml-java.io.InputStream-) | XML'i belgeye bağla |
| [bindXml](#bindXml-java.lang.String-) | XML'i belgeye bağla |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL'i belgeye bağla |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Belge şifrelerini değiştirir. |
| [check](#check-boolean-) | Belgeyi doğrular. |
| [close](#close--) | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Belgeyi aranabilir belgeye dönüştürür. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. <p> Bu, sayfada aranabilir metni gösterme/gizleme olanağı sağlar. Varsayılan değer FALSE'tur. Bu, pdf'den orijinal görüntüyü almayı sağlar. Varsayılan değer FALSE'tur. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. <p> Bu, sayfada aranabilir metni gösterme/gizleme olanağı sağlar. Varsayılan değer FALSE'tur. Bu, pdf'den orijinal görüntüyü almayı sağlar. Varsayılan değer FALSE'tur. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Belgeyi belirtilen dönüşüm seçeneklerini kullanarak dönüştür |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Dahili yöntem |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar. |
| [decrypt](#decrypt--) | Belgeyi şifre çözer. |
| [dispose](#dispose--) | Kullanımdan kaldırıldı. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Belgeyi şifreler. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Belgeyi şifreler. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Belgeyi şifreler. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Tüm belge ek açıklamalarını XFDF dosyasına dışa aktarır |
| [flatten](#flatten--) | Belgeden tüm alanları (ve ek açıklamaları) kaldırır ve yerine değerlerini yerleştirir. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Belgeden tüm alanları kaldırır ve yerine değerlerini yerleştirir. |
| [flattenTransparency](#flattenTransparency--) | Şeffaf içeriği şeffaf olmayan raster ve vektör grafiklerle değiştirir. |
| [freeMemory](#freeMemory--) | Belleği temizler |
| [getActions](#getActions--) | Belge eylemlerini alır. |
| [getBackground](#getBackground--) | Belgenin arka plan rengini alır. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Katalog sözlüğünden öğe değerini döndürür. |
| [getCollection](#getCollection--) | Belgenin koleksiyonunu alır. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Belge şifrelenmişse güvenlik ayarlarını alır. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Özel bir güvenlik işleyicisini alır. |
| [getDefaultCopier](#getDefaultCopier--) | Bu belgeye sayfaları kopyalamak için kullanılan kopyalayıcıyı döndürür. |
| [getDestinations](#getDestinations--) | Hedeflerin koleksiyonunu alır. |
| [getDirection](#getDirection--) | Metnin okuma sırasını alır: L2R (soldan sağa) veya R2L (sağdan sola). |
| [getDuplex](#getDuplex--) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Belgeye gömülü dosyaların koleksiyonunu alır. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar. |
| [getEngineDoc](#getEngineDoc--) | Dahili belge yapısına erişmek için kullanılan IPdfDocument örneği. |
| [getFileName](#getFileName--) | Bu belgeyi oluşturan PDF dosyasının adı |
| [getForm](#getForm--) | Belgenin Acro Formunu alır. |
| [getId](#getId--) | Kimliği alır. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Kaynak dosyalardaki hataları yok sayma bayrağını alır veya ayarlar. |
| [getInfo](#getInfo--) | Belge bilgilerini alır. |
| [getLogicalStructure](#getLogicalStructure--) | Belgenin mantıksal yapısını alır. |
| [getMetadata](#getMetadata--) | Belge meta verileri. |
| [getMetadataStream](#getMetadataStream--) | Ham meta veri akışını döndürür |
| [getNamedDestinations](#getNamedDestinations--) | Belgedeki Adlandırılmış Hedeflerin koleksiyonu. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu alır. |
| [getObjectById](#getObjectById-java.lang.String-) | Belgedeki belirtilen kimliğe sahip nesneyi alır. |
| [getOpenAction](#getOpenAction--) | Belge açıldığında gerçekleştirilen eylemi alır. |
| [getOptimizeSize](#getOptimizeSize--) | Optimizasyon bayrağını alır. |
| [getOutlines](#getOutlines--) | Belge taslaklarını alır. |
| [getPageInfo](#getPageInfo--) | Sayfa bilgilerini alır.(yalnızca oluşturucu için, belge okunduğunda doldurulmaz) |
| [getPageLabels](#getPageLabels--) | Belgedeki sayfa etiketlerini alır. |
| [getPageLayout](#getPageLayout--) | Belge açıldığında kullanılacak sayfa düzenini alır. |
| [getPageMode](#getPageMode--) | Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu alır. |
| [getPages](#getPages--) | Belge sayfalarının koleksiyonunu alır. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Belgenin izinlerini alır. |
| [getPrintScaling](#getPrintScaling--) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini alır. |
| [getTaggedContent](#getTaggedContent--) | TaggedPdf içeriğine erişimi alır. |
| [getVersion](#getVersion--) | Pdf dosya başlığından Pdf sürümünü alır. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Belgeden XMP meta verilerini al. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | XFDF dosyasından belgeye açıklamaları içe aktarır. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Belgeleri işlerken eksik yazı tipleri hakkında bildirim |
| [isCenterWindow](#isCenterWindow--) | Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı alır. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır. |
| [isEncrypted](#isEncrypted--) | Belgenin şifreli durumunu alır. |
| [isFitWindow](#isFitWindow--) | Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı alır. |
| [isHideMenubar](#isHideMenubar--) | Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır. |
| [isHideToolBar](#isHideToolBar--) | Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır. |
| [isHideWindowUI](#isHideWindowUI--) | Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [isLinearized](#isLinearized--) | Belgenin lineerleştirilip lineerleştirilmediğini gösteren değeri alır veya ayarlar. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Varsayılan olarak save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirilmişse, save yönteminden sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz. |
| [isPdfaCompliant](#isPdfaCompliant--) | Belgenin pdf/a uyumlu olup olmadığını alır. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Belgenin pdfua uyumlu olup olmadığını alır. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı alır. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar. |
| [optimize](#optimize--) | Belgeyi lineerleştirerek - ilk sayfayı mümkün olan en hızlı şekilde açmak; - sonraki sayfayı göstermek veya bir sonraki sayfaya bağlantıyı mümkün olan en hızlı şekilde takip etmek; - sayfa verileri yavaş bir kanaldan iletildiğinde sayfa geldiği anda sayfayı kademeli olarak göstermek (en faydalı verileri önce göstermek); - bir bağlantıyı takip etmek gibi kullanıcı etkileşiminin, sayfanın tamamı alınmadan ve görüntülenmeden önce bile gerçekleşmesine izin vermek. |
| [optimizeResources](#optimizeResources--) | Belgedeki kaynakları optimize et: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Belgedeki kaynakları tanımlı optimizasyon stratejisine göre optimize et. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Bir belgedeki sayfa ağacı düğümlerini dengeli bir ağaçta düzenler. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Bir belgedeki sayfa ağacı düğümlerini dengeli bir ağaçta düzenler. |
| [processParagraphs](#processParagraphs--) | Belgeyi akışa kaydeder. |
| [removeMetadata](#removeMetadata--) | Belgeden meta verileri kaldırır. |
| [removePdfaCompliance](#removePdfaCompliance--) | Belgeden pdfa uyumluluğunu kaldır. |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Belgeden pdfUa uyumluluğunu kaldır. |
| [repair](#repair--) | Bozuk belgeyi onarır. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Belgeyi artımlı olarak kaydet (ör. |
| [save](#save-java.io.OutputStream-) | Belgeyi akışa kaydeder. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Belgeyi kaydet |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Belgeyi yeni bir adla kaydeder ve kaydetme seçeneklerini ayarlar. |
| [save](#save-java.lang.String-) | Belgeyi belirtilen dosyaya kaydeder. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Belgeyi yeni bir adla kaydeder ve kaydetme seçeneklerini ayarlar. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | PDF Belgesini belirtilen akışa artımlı olarak kaydeder. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | PDF Belgesini belirtilen akışa artımlı olarak kaydeder. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | PDF Belgesini belirtilen akışa artımlı olarak kaydeder. |
| [saveXml](#saveXml-java.lang.String-) | Belgeyi XML olarak kaydet. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Belgenin belirli sayfalarını işleme için belge cihazına gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Belgenin tamamını işleme için belge cihazına gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Belgenin tamamını işleme için belge cihazına gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Belgenin tamamını işleme için belge cihazına gönderir. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Yazı tipi yoksa program tarafından belirlenen yazı tipini ayarlamak için bayrak ayarlanıyor. |
| [setBackground](#setBackground-java.awt.Color-) | Belgenin arka plan rengini ayarlar. |
| [setCenterWindow](#setCenterWindow-boolean-) | Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı ayarlar. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Belgenin koleksiyonunu ayarlar. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | pdf/ua dönüştürücü için dönüştürme parametresini alır (true ayarlanırsa yalnızca Meta Verileri ve Belge Kataloğu dönüştürülür) |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı ayarlar. |
| [setDuplex](#setDuplex-int-) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar. |
| [setFitWindow](#setFitWindow-boolean-) | Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı ayarlar. |
| [setHideMenubar](#setHideMenubar-boolean-) | Belge etkin olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar. |
| [setHideToolBar](#setHideToolBar-boolean-) | Belge etkin olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Belge etkin olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı ayarlar. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer ayarlar. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Varsayılan olarak save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirilirse, save yöntemi çağrıldıktan sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz. Ancak Document örneği artık ihtiyaç duyulmadığında dispose yönteminin çağrılması şiddetle tavsiye edilir. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu ayarlar. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Belge açıldığında gerçekleştirilecek eylemi ayarlar. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Optimizasyon bayrağını ayarlar. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sayfa bilgilerini ayarlar. (yalnızca oluşturucu için, belge okunurken doldurulmaz) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Belge açıldığında kullanılacak sayfa düzenini ayarlar. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu ayarlar. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı ayarlar. |
| [setPrintScaling](#setPrintScaling-int-) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | Pdf Belgesi için Başlık ayarla |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Belgenin XMP meta verilerini ayarla. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Belgeyi belirtilen dosyaya doğrula. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Belgeyi belirtilen dosyaya doğrula. |

### afterImport {#afterImport--}
```
void afterImport()
```

Tüm kayıtlı açıklamaları enumerate eder ve her biri için AfterImport metodunu çağırır.

### bindXml {#bindXml-java.io.InputStream-}
XML'i belgeye bağla

### bindXml {#bindXml-java.lang.String-}
XML'i belgeye bağla

### bindXml {#bindXml-java.lang.String-java.lang.String-}
XML/XSL'i belgeye bağla

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Belge şifrelerini değiştirir.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

Belgeyi doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| doRepair |  | Doğru ise bulunan sorunlar onarılacak. |

**Returns:**
boolean değer

### close {#close--}
```
void close()
```

Bu belge tarafından kullanılan tüm kaynakları kapatır.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Belgeyi aranabilir belgeye dönüştürür.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. <p> Bu, sayfada aranabilir metni gösterme/gizleme olanağı sağlar. Varsayılan değer FALSE'tur. Bu, pdf'den orijinal görüntüyü almayı sağlar. Varsayılan değer FALSE'tur.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. <p> Bu, sayfada aranabilir metni gösterme/gizleme olanağı sağlar. Varsayılan değer FALSE'tur. Bu, pdf'den orijinal görüntüyü almayı sağlar. Varsayılan değer FALSE'tur.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Belgeyi belirtilen dönüşüm seçeneklerini kullanarak dönüştür

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Dahili yöntem

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar.

### decrypt {#decrypt--}
```
void decrypt()
```

Belgeyi şifre çözer.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Kullanımdan kaldırıldı.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Belgeyi şifreler.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Belgeyi şifreler.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Belgeyi şifreler.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Tüm belge ek açıklamalarını XFDF dosyasına dışa aktarır

### flatten {#flatten--}
```
void flatten()
```

Belgeden tüm alanları (ve ek açıklamaları) kaldırır ve yerine değerlerini yerleştirir.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Belgeden tüm alanları kaldırır ve yerine değerlerini yerleştirir.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Şeffaf içeriği şeffaf olmayan raster ve vektör grafiklerle değiştirir.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Belleği temizler

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Belge eylemlerini alır.

**Returns:**
DocumentActionCollection nesnesi

### getBackground {#getBackground--}
```
Color getBackground()
```

Belgenin arka plan rengini alır.

**Returns:**
java.awt.Color nesnesi

### getCatalogValue {#getCatalogValue-java.lang.String-}
Katalog sözlüğünden öğe değerini döndürür.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Belgenin koleksiyonunu alır.

**Returns:**
Collection nesnesi

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Belge şifrelenmişse güvenlik ayarlarını alır.

**Returns:**
CryptoAlgorithm öğesi veya null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Özel bir güvenlik işleyicisini alır.

**Returns:**
ICustomSecurityHandler örneği

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Bu belgeye sayfaları kopyalamak için kullanılan kopyalayıcıyı döndürür.

**Returns:**
Copier nesnesi

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Hedeflerin koleksiyonunu alır.

**Returns:**
DestinationCollection nesnesi

### getDirection {#getDirection--}
```
Direction getDirection()
```

Metnin okuma sırasını alır: L2R (soldan sağa) veya R2L (sağdan sola).

**Returns:**
Direction öğesi

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar.

**Returns:**
PrintDuplex öğesi

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Belgeye gömülü dosyaların koleksiyonunu alır.

**Returns:**
EmbeddedFileCollection nesnesi

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik.

**Returns:**
boolean değer

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar.

**Returns:**
boolean değer

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Dahili belge yapısına erişmek için kullanılan IPdfDocument örneği.

**Returns:**
IPdfDocument nesnesi

### getFileName {#getFileName--}
```
String getFileName()
```

Bu belgeyi oluşturan PDF dosyasının adı

**Returns:**
Dize nesnesi

### getForm {#getForm--}
```
Form getForm()
```

Belgenin Acro Formunu alır.

**Returns:**
Form nesnesi

### getId {#getId--}
```
Id getId()
```

Kimliği alır.

**Returns:**
Id nesnesi

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Kaynak dosyalardaki hataları yok sayma bayrağını alır veya ayarlar.

**Returns:**
boolean değer

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Belge bilgilerini alır.

**Returns:**
DocumentInfo nesnesi

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Belgenin mantıksal yapısını alır.

**Returns:**
RootElement nesnesi

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Belge meta verileri.

**Returns:**
Metadata nesnesi

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Ham meta veri akışını döndürür

**Returns:**
IPdfStreamAccessor nesnesi

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Belgedeki Adlandırılmış Hedeflerin koleksiyonu.

**Returns:**
NamedDestinationCollection örneği

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu alır.

**Returns:**
PageMode öğesi

### getObjectById {#getObjectById-java.lang.String-}
Belgedeki belirtilen kimliğe sahip nesneyi alır.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Belge açıldığında gerçekleştirilen eylemi alır.

**Returns:**
IAppointment nesnesi

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Optimizasyon bayrağını alır.

**Returns:**
boolean değer

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Belge taslaklarını alır.

**Returns:**
OutlineCollection nesnesi

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Sayfa bilgilerini alır.(yalnızca oluşturucu için, belge okunduğunda doldurulmaz)

**Returns:**
Sayfa bilgisi.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Belgedeki sayfa etiketlerini alır.

**Returns:**
PageLabelCollection nesnesi

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Belge açıldığında kullanılacak sayfa düzenini alır.

**Returns:**
PageLayout öğesi

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu alır.

**Returns:**
PageMode öğesi

### getPages {#getPages--}
```
PageCollection getPages()
```

Belge sayfalarının koleksiyonunu alır.

**Returns:**
boolean değer

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
PdfFormat öğesi

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Belgenin izinlerini alır.

**Returns:**
int değer

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini alır.

**Returns:**
PrintScaling öğesi

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

TaggedPdf içeriğine erişimi alır.

**Returns:**
ITaggedContent örneği

### getVersion {#getVersion--}
```
String getVersion()
```

Pdf dosya başlığından Pdf sürümünü alır.

**Returns:**
Dize nesnesi

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Belgeden XMP meta verilerini al.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
XFDF dosyasından belgeye açıklamaları içe aktarır.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Belgeleri işlerken eksik yazı tipleri hakkında bildirim

**Returns:**
boolean değer

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı alır.

**Returns:**
boolean değer

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez.

**Returns:**
boolean değer Varsayılan olarak false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır.

**Returns:**
boolean değer

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Belgenin şifreli durumunu alır.

**Returns:**
boolean değer

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı alır.

**Returns:**
boolean değer

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır.

**Returns:**
boolean değer

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır.

**Returns:**
boolean değer

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar.

**Returns:**
boolean değer

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Belgenin lineerleştirilip lineerleştirilmediğini gösteren değeri alır veya ayarlar.

**Returns:**
boolean değer

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Varsayılan olarak save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirilmişse, save yönteminden sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz.

**Returns:**
boolean değer. (Varsayılan değer == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Belgenin pdf/a uyumlu olup olmadığını alır.

**Returns:**
boolean değer

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Belgenin pdfua uyumlu olup olmadığını alır.

**Returns:**
boolean değer

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı alır.

**Returns:**
boolean değer

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar.

**Returns:**
boolean değer

### optimize {#optimize--}
```
void optimize()
```

Belgeyi lineerleştirerek - ilk sayfayı mümkün olan en hızlı şekilde açmak; - sonraki sayfayı göstermek veya bir sonraki sayfaya bağlantıyı mümkün olan en hızlı şekilde takip etmek; - sayfa verileri yavaş bir kanaldan iletildiğinde sayfa geldiği anda sayfayı kademeli olarak göstermek (en faydalı verileri önce göstermek); - bir bağlantıyı takip etmek gibi kullanıcı etkileşiminin, sayfanın tamamı alınmadan ve görüntülenmeden önce bile gerçekleşmesine izin vermek.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Belgedeki kaynakları optimize et: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Belgedeki kaynakları tanımlı optimizasyon stratejisine göre optimize et.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Bir belgedeki sayfa ağacı düğümlerini dengeli bir ağaçta düzenler.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Bir belgedeki sayfa ağacı düğümlerini dengeli bir ağaçta düzenler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodesNumInSubtrees |  | İstenen alt düğüm sayısı. Varsayılan değer ondur. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Belgeyi akışa kaydeder.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Belgeden meta verileri kaldırır.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Belgeden pdfa uyumluluğunu kaldır.

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Belgeden pdfUa uyumluluğunu kaldır.

### repair {#repair--}
```
void repair()
```

Bozuk belgeyi onarır.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Belgeyi artımlı olarak kaydet (ör.

### save {#save-java.io.OutputStream-}
Belgeyi akışa kaydeder.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Belgeyi kaydet

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Belgeyi yeni bir adla kaydeder ve kaydetme seçeneklerini ayarlar.

### save {#save-java.lang.String-}
Belgeyi belirtilen dosyaya kaydeder.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Belgeyi yeni bir adla kaydeder ve kaydetme seçeneklerini ayarlar.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
PDF Belgesini belirtilen akışa artımlı olarak kaydeder.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
PDF Belgesini belirtilen akışa artımlı olarak kaydeder.

### saveIncrementally {#saveIncrementally-java.lang.String-}
PDF Belgesini belirtilen akışa artımlı olarak kaydeder.

### saveXml {#saveXml-java.lang.String-}
Belgeyi XML olarak kaydet.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Belgenin belirli sayfalarını işleme için belge cihazına gönderir.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Belgenin tamamını işleme için belge cihazına gönderir.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Belgenin tamamını işleme için belge cihazına gönderir.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Belgenin tamamını işleme için belge cihazına gönderir.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Yazı tipi yoksa program tarafından belirlenen yazı tipini ayarlamak için bayrak ayarlanıyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | boolean değer |

### setBackground {#setBackground-java.awt.Color-}
Belgenin arka plan rengini ayarlar.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Belgenin koleksiyonunu ayarlar.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

pdf/ua dönüştürücü için dönüştürme parametresini alır (true ayarlanırsa yalnızca Meta Verileri ve Belge Kataloğu dönüştürülür)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer Varsayılan olarak false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PrintDuplex öğesi |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Belge etkin olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Belge etkin olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Belge etkin olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Varsayılan olarak save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirilirse, save yöntemi çağrıldıktan sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz. Ancak Document örneği artık ihtiyaç duyulmadığında dispose yönteminin çağrılması şiddetle tavsiye edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| manualDisposeEnabled |  | boolean değer. (Varsayılan değer == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu ayarlar.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Belge açıldığında gerçekleştirilecek eylemi ayarlar.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

Optimizasyon bayrağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Sayfa bilgilerini ayarlar. (yalnızca oluşturucu için, belge okunurken doldurulmaz)

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Belge açıldığında kullanılacak sayfa düzenini ayarlar.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu ayarlar.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
void setPickTrayByPdfSize(boolean value)
```

PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PrintDuplex öğesi |

### setTitle {#setTitle-java.lang.String-}
Pdf Belgesi için Başlık ayarla

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Belgenin XMP meta verilerini ayarla.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Belgeyi belirtilen dosyaya doğrula.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Belgeyi belirtilen dosyaya doğrula.
