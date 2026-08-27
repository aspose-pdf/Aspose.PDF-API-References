---
title: "Belge"
linktitle: "Belge"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesini temsil eden sınıf."
type: docs
weight: 1060
url: /tr/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

PDF belgesini temsil eden sınıf.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Bir yazı tipi, belgede başka bir yazı tipinin yerini aldığında oluşur. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Document](#Document--) | Boş belgeyi başlatır. |
| [Document](#Document-byte:A-) | Yeni Document örneğini {@code input} bayt dizisinden başlatır. |
| [Document](#Document-java.io.InputStream-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-boolean-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-java.lang.String-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Boş belgeyi başlatır. |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Boş belgeyi başlatır. |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | Boş belgeyi başlatır. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | Boş belgeyi başlatır. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | Boş belgeyi başlatır. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Boş belgeyi başlatır. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Boş belgeyi başlatır. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-boolean-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-java.lang.String-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Boş belgeyi başlatır. |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Boş belgeyi başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [afterImport](#afterImport--) | Tüm kayıtlı açıklamaları enumerate eder ve her biri için AfterImport metodunu çağırır. |
| [bindXml](#bindXml-java.io.InputStream-) | XML'i belgeye bağla |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | XML/XSL'i belgeye bağla |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | XML/XSL'i belgeye bağla |
| [bindXml](#bindXml-java.lang.String-) | XML'i belgeye bağla |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL'i belgeye bağla |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Belge şifrelerini değiştirir. Bu işlem yalnızca sahibi şifresi kullanılarak yapılabilir. |
| [check](#check-boolean-) | Belgeyi doğrular. |
| [close](#close--) | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Belge içindeki görüntüleri tanır ve üzerine hocr dizgileri ekler. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Fixup uygulayarak belgeyi dönüştür. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Fixup uygulayarak belgeyi dönüştür. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Fixup uygulayarak belgeyi dönüştür. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Fixup uygulayarak belgeyi dönüştür. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Kaynak biçimdeki akışı hedef biçimdeki akışa dönüştürür. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Kaynak biçimdeki akışı hedef biçimdeki hedef dosyaya dönüştürür. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Belgeyi dönüştür ve hataları belirtilen akışa kaydet. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Belgeyi belirtilen dönüşüm seçeneklerini kullanarak dönüştür |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Kaynak biçimdeki kaynak dosyayı hedef biçimdeki akışa dönüştürür. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Kaynak biçimdeki kaynak dosyayı hedef biçimdeki hedef dosyaya dönüştürür. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Belgeyi dönüştür ve hataları belirtilen akışa kaydet. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Sayfayı DSR, OMR, OCR görüntü akışı için PNG'ye dönüştür. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar. |
| [decrypt](#decrypt--) | Belgeyi şifre çözer. Ardından belgeyi şifre çözülmüş sürüm olarak elde etmek için Save'i çağırın. |
| [dispose](#dispose--) | Bu belge tarafından kullanılan tüm kaynakları kapatır. Bu yöntem artık kullanılmıyor, bunun yerine close() kullanın. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Belgeyi şifreler. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Belgeyi şifreler. Ardından belgeyi şifrelenmiş sürüm olarak almak için Save'i çağırın. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Belgeyi şifreler. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Belgeyi şifreler. Ardından belgeyi şifrelenmiş sürüm olarak almak için Save'i çağırın. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Belgeyi şifreler. Ardından belgeyi şifrelenmiş sürüm olarak almak için Save'i çağırın. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Belgeyi şifreler. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Tüm belge açıklamalarını akışa dışa aktar. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Tüm belge ek açıklamalarını XFDF dosyasına dışa aktarır |
| [flatten](#flatten--) | Belgeden tüm alanları (ve ek açıklamaları) kaldırır ve yerine değerlerini yerleştirir. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Belgeden tüm alanları (ve ek açıklamaları) kaldırır ve yerine değerlerini yerleştirir. |
| [flattenTransparency](#flattenTransparency--) | Şeffaf içeriği şeffaf olmayan raster ve vektör grafiklerle değiştirir. |
| [freeMemory](#freeMemory--) | Belleği temizler |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Belgeleri işlerken eksik yazı tipleri hakkında bildirim. |
| [getActions](#getActions--) | <p> Belge eylemlerini alır. Bu özellik, BeforClosing, BeforSaving vb. eylemlere get/set yapmayı sağlayan DocumentActions sınıfının bir örneğidir. </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Sayfa içeriklerini birleştirerek belge boyutunu optimize etmeye izin verir. |
| [getBackground](#getBackground--) | Belgenin arka plan rengini alır. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Katalog sözlüğünden öğe değerini döndürür. |
| [getCollection](#getCollection--) | Belgenin koleksiyonunu alır. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Belge şifreli ise güvenlik ayarlarını alır. Belge şifreli değilse, .net 1.1'de ilgili istisna yükseltilir veya diğer .net sürümlerinde CryptoAlgorithm null olur. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Özel bir güvenlik işleyicisini alır. |
| [getDefaultCopier](#getDefaultCopier--) | Bu belgeye sayfaları kopyalamak için kullanılan kopyalayıcıyı döndürür. |
| [getDestinations](#getDestinations--) | Hedeflerin koleksiyonunu alır. |
| [getDirection](#getDirection--) | Metnin okuma sırasını alır: L2R (soldan sağa) veya R2L (sağdan sola). |
| [getDuplex](#getDuplex--) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Belgeye gömülü dosyaların koleksiyonunu alır. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar. |
| [getEngineDoc](#getEngineDoc--) | IPdfDocument örneği, iç belge yapısına erişmek için kullanılır. Yalnızca dahili. |
| [getFileName](#getFileName--) | Bu belgeyi oluşturan PDF dosyasının adı |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Bir dosyanın tamamını belleğe yüklemek için dosya boyutu limitini al ve ayarla. |
| [getFontUtilities](#getFontUtilities--) | IDocumentFontUtilities örneği |
| [getForm](#getForm--) | Belgenin Acro Formunu alır. |
| [getId](#getId--) | Kimliği alır. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Kaynak dosyalardaki hataları yoksayma bayrağını alır veya ayarlar. Kaynak belgeden sayfalar hedef belgeye kopyalandığında, bu bayrak false olduğunda kaynak dosyalardaki bazı nesneler bozuksa kopyalama işlemi bir istisna ile durur. örnek: dest.Pages.Add(src.Pages); Bayrak true olarak ayarlanırsa bozuk nesneler boş değerlerle değiştirilir. Varsayılan: true. |
| [getInfo](#getInfo--) | Belge bilgilerini alır. |
| [getJavaScript](#getJavaScript--) | Belge düzeyindeki JavaScript koleksiyonu. |
| [getLogicalStructure](#getLogicalStructure--) | Belgenin mantıksal yapısını alır. |
| [getMetadata](#getMetadata--) | Belge meta verileri. (Bir PDF belgesi, belgenin başlığı, yazarı ve oluşturulma ve değiştirilme tarihleri gibi genel bilgileri içerebilir. Belgenin içeriği veya yapısı yerine bu tür küresel bilgi meta veri olarak adlandırılır ve dış veri tabanlarında belgelerin kataloglanması ve aranmasına yardımcı olması amaçlanır.) |
| [getMetadataStream](#getMetadataStream--) | Ham meta veri akışını döndürür |
| [getNamedDestinations](#getNamedDestinations--) | Belgedeki Adlandırılmış Hedeflerin koleksiyonu. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu alır. |
| [getObjectById](#getObjectById-java.lang.String-) | Belgedeki belirtilen kimliğe sahip nesneyi alır. |
| [getOpenAction](#getOpenAction--) | <p> Belge açıldığında gerçekleştirilen eylemi alır. </p> <hr> <pre> Örnek, CenterWindow bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | Optimizasyon bayrağını alır. Sayfalar belgeye eklendiğinde, bu bayrak ayarlıysa sonuç dosyasındaki eşit kaynak akışları tek bir PDF nesnesi içinde birleştirilir. Bu, sonuç dosya boyutunun azalmasını sağlar ancak daha yavaş yürütme ve daha fazla bellek gereksinimine neden olabilir. Varsayılan değer: false. |
| [getOutlines](#getOutlines--) | Belge taslaklarını alır. |
| [getOutputIntents](#getOutputIntents--) | Belgedeki Output niyetlerinin koleksiyonunu alır. |
| [getPageInfo](#getPageInfo--) | Sayfa bilgilerini alır.(yalnızca oluşturucu için, belge okunduğunda doldurulmaz) |
| [getPageLabels](#getPageLabels--) | Belgedeki sayfa etiketlerini alır. |
| [getPageLayout](#getPageLayout--) | Belge açıldığında kullanılacak sayfa düzenini alır. |
| [getPageMode](#getPageMode--) | Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu alır. |
| [getPages](#getPages--) | <p> Belge sayfalarının koleksiyonunu alır. Sayfaların koleksiyonda 1'den başladığını unutmayın. </p> |
| [getPdfFormat](#getPdfFormat--) | pdfa formatını alır |
| [getPermissions](#getPermissions--) | Belgenin izinlerini alır. |
| [getPrintScaling](#getPrintScaling--) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini alır. |
| [getTaggedContent](#getTaggedContent--) | TaggedPdf içeriğine erişim sağlar. Örnek, başlık, paragraf ve görseller içeren yeni bir belge oluşturmak için etiketli içeriğin nasıl kullanılacağını gösterir. // Yeni belge oluştur Document document = new Document(); // Etiketli içeriği al ITaggedContent taggedContent = document.getTaggedContent(); // Belge için dili ayarla taggedContent.setLanguage("en-US"); // PDF belgesi için başlığı ayarla taggedContent.setTitle("Example document"); // Bölüm oluşturma ve ekleme SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Başlık oluştur HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("The Header"); sect.appendChild(h1); // Paragraf oluştur ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("The text of paragraph."); sect.appendChild(p); // Açıklama oluştur IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figure 1"); figure1.setTitle("Image 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Belgeyi kaydet document.save("example.pdf"); |
| [getVersion](#getVersion--) | Pdf dosya başlığından Pdf sürümünü alır. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Belgeden XMP meta verilerini al. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Mevcut PDF belgesinin artımlı güncellemelerle kaydedilip kaydedilmediğini kontrol eder. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Akıştan belgeye açıklamaları içe aktarır. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | XFDF dosyasından belgeye açıklamaları içe aktarır. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Eksik yazı tipinin yerine konulması hakkında bilgi veren bayrak. |
| [isCenterWindow](#isCenterWindow--) | <p> Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı alır. </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır. </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Bildirimlerin kaydedilmesini etkinleştirip etkinleştirilmeyeceğini gösteren bir değeri alır veya ayarlar. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Belgenin kısmen bellekten boşaltılmasını sağlayan bayrağı alır veya ayarlar. |
| [isEncrypted](#isEncrypted--) | Belgenin şifreli durumunu alır. Belge şifreliyse doğru (true). |
| [isFitWindow](#isFitWindow--) | <p> Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılması gerekip gerekmediğini belirten bayrağı alır. </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Belge değişikliklerle ve imza içeriyorsa İstisna fırlat. |
| [isHideMenubar](#isHideMenubar--) | <p> Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır. </p> |
| [isHideToolBar](#isHideToolBar--) | <p> Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır. </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır. </p> |
| [isLicensed](#isLicensed--) | Sistemin lisans durumunu alır. |
| [isLinearized](#isLinearized--) | Belgenin lineerleştirilmiş olup olmadığını gösteren bir değeri alır. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Varsayılan olarak, save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirildiğinde, save yöntemi çağrıldıktan sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz. |
| [isPdfaCompliant](#isPdfaCompliant--) | Belgenin PDF/A uyumlu olup olmadığını alır. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Belgenin pdfua uyumlu olup olmadığını alır. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı alır. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Belgenin Repair yönteminin çağrılmasını gerekip gerektirmediğini kontrol eder. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Varsayılan olarak, bazı kurallar ihlal edildiğinde PDF/A uyumlu verileri güncellemek veya kaldırmak için PDF/A doğrulama süreci gereklidir. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Bir dosyayı yükler ve PDF'ye dönüştürür. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Belgeleri birleştirir. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Belgeleri birleştirir. |
| [merge](#merge-com.aspose.pdf.Document...-) | Belgeleri birleştirir. |
| [merge](#merge-java.lang.String...-) | PDF dosyalarını birleştirir. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Belgeleri birleştirir. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Belgeleri birleştirir. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Belgeleri birleştirir. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | PDF dosyalarını birleştirir. |
| [optimize](#optimize--) | Belgeyi lineerleştirerek - ilk sayfayı mümkün olduğunca hızlı açmak; - sonraki sayfayı göstermek veya bir sonraki sayfaya bağlantıyı mümkün olduğunca hızlı takip etmek; - bir sayfanın verileri yavaş bir kanaldan iletildiğinde sayfayı kademeli olarak göstermek (en faydalı verileri önce göstermek); - bir bağlantıyı takip etmek gibi kullanıcı etkileşiminin, sayfanın tamamı alınmadan ve görüntülenmeden önce gerçekleşmesine izin vermek amaçlanır. Bu yöntemin çağrılması aslında belgeyi kaydetmez. Aksine, belge yalnızca optimize edilmiş bir yapıya hazırlanır, ardından Optimize edilmiş belgeyi elde etmek için Save çağrılır. |
| [optimizeResources](#optimizeResources--) | Belgedeki kaynakları optimize eder: 1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır; 2. Aynı kaynaklar tek bir nesne içinde birleştirilir; 3. Kullanılmayan nesneler silinir. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Belgedeki kaynakları optimize eder: 1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır; 2. Aynı kaynaklar tek bir nesne içinde birleştirilir; 3. Kullanılmayan nesneler silinir. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Belgedeki sayfa ağacı düğümlerini dengeli bir ağaç hâline getirir. Yalnızca belge, nodesNumInSubtrees sayısından fazla sayfa nesnesine sahipse uygulanır, aksi takdirde hiçbir şey yapmaz. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Belgedeki sayfa ağacı düğümlerini dengeli bir ağaç hâline getirir. Yalnızca belge, nodesNumInSubtrees sayısından fazla sayfa nesnesine sahipse uygulanır, aksi takdirde hiçbir şey yapmaz. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Dahili yöntem |
| [processParagraphs](#processParagraphs--) | Belgeyi akışa kaydeder. |
| [removeMetadata](#removeMetadata--) | Belgeden meta verileri kaldırır. |
| [removePdfaCompliance](#removePdfaCompliance--) | Belgeden pdfa uyumluluğunu kaldır. |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Belgeden pdfUa uyumluluğunu kaldır. |
| [repair](#repair--) | Bozuk belgeyi onarır. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Bozuk belgeyi onarır. |
| [resumeUpdate](#resumeUpdate--) | belge güncellemesini devam ettirir |
| [save](#save--) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-java.io.OutputStream-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-java.lang.String-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | PDF Belgesini belirtilen akışa artımlı olarak kaydeder. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | PDF Belgesini belirtilen akışa artımlı olarak kaydeder. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | PDF Belgesini belirtilen akışa artımlı olarak kaydeder. |
| [saveXml](#saveXml-java.lang.String-) | Belgeyi XML olarak kaydet. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Belgenin belirli sayfalarını işleme için belge cihazına gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Belgenin tamamını işleme için belge cihazına gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Belgenin tamamını işleme için belge cihazına gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Belgenin tamamını işleme için belge cihazına gönderir. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Belgeleri işlerken eksik yazı tipleri hakkında bildirim. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Font eksikliği durumunda program tarafından belirlenen fontu ayarlamak için bayrak ayarlanıyor. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Sayfa içeriklerini birleştirerek belge boyutunu optimize etmeye izin verir. |
| [setBackground](#setBackground-java.awt.Color-) | Belgenin arka plan rengini ayarlar. |
| [setCenterWindow](#setCenterWindow-boolean-) | Belgenin pencere konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı ayarlar. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Belgenin koleksiyonunu ayarlar. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | pdf/ua dönüştürücü için dönüştürme parametresini alır (true ayarlanırsa yalnızca Meta Verileri ve Belge Kataloğu dönüştürülür) |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Tüm dosyayı belleğe yüklemek için dosya boyutu limitini varsayılan değer olan 210 MB olarak ayarlar. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı ayarlar. |
| [setDuplex](#setDuplex-int-) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Bildirimlerin kaydedilmesini etkinleştirip etkinleştirilmeyeceğini gösteren bir değeri alır veya ayarlar. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Belgenin kısmen bellekten boşaltılmasını sağlayan bayrağı alır veya ayarlar. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Bir dosyanın tamamını belleğe yüklemek için dosya boyutu limitini al ve ayarla. |
| [setFitWindow](#setFitWindow-boolean-) | Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı ayarlar. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Belge değişikliklerle ve imza içeriyorsa İstisna fırlat. |
| [setHideMenubar](#setHideMenubar-boolean-) | Belge etkin olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar. |
| [setHideToolBar](#setHideToolBar-boolean-) | Belge etkin olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Belge etkin olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı ayarlar. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Kaynak dosyalardaki hataları yoksayma bayrağını alır veya ayarlar. Kaynak belgeden sayfalar hedef belgeye kopyalandığında, bu bayrak false olduğunda kaynak dosyalardaki bazı nesneler bozuksa kopyalama işlemi bir istisna ile durur. örnek: dest.Pages.Add(src.Pages); Bayrak true olarak ayarlanırsa bozuk nesneler boş değerlerle değiştirilir. Varsayılan: true. |
| [setLinearized](#setLinearized-boolean-) | Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer ayarlar. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Varsayılan olarak, save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirildiğinde, save yöntemi çağrıldıktan sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz. Ancak Document örneği artık ihtiyaç duyulmadığında dispose yönteminin çağrılması şiddetle tavsiye edilir. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu ayarlar. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> Belge açıldığında gerçekleştirilen eylemi ayarlar. <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Optimizasyon bayrağını ayarlar. Sayfalar belgeye eklendiğinde, bu bayrak ayarlıysa sonuç dosyadaki eşit kaynak akışları tek bir PDF nesnesi içinde birleştirilir. Bu, sonuç dosya boyutunun azalmasını sağlar ancak daha yavaş yürütme ve daha fazla bellek gereksinimine yol açabilir. Varsayılan değer: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sayfa bilgilerini ayarlar. (yalnızca oluşturucu için, belge okunurken doldurulmaz) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Belge açıldığında kullanılacak sayfa düzenini ayarlar. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu ayarlar. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı ayarlar. |
| [setPrintScaling](#setPrintScaling-int-) | Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini ayarlar. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Varsayılan olarak, bazı kurallar ihlal edildiğinde PDF/A'yı güncellemek veya kaldırmak için PDF/A doğrulama süreci gereklidir. |
| [setTitle](#setTitle-java.lang.String-) | Pdf Belgesi için Başlık ayarla |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Belgenin XMP meta verilerini ayarla. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar. |
| [suppressUpdate](#suppressUpdate--) | Tüm sayfalar için içerik güncelleme verilerini bastırır. İçerik, ResumeUpdate çağrılana kadar güncellenmez. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Belgeyi belirtilen dosyaya doğrula. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Belgeyi belirtilen dosyaya doğrula. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Belgeyi belirtilen dosyaya doğrula. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Bir yazı tipi, belgede başka bir yazı tipinin yerini aldığında oluşur.

### Document {#Document--}
```
public Document()
```

Boş belgeyi başlatır.

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

Yeni Document örneğini {@code input} bayt dizisinden başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| girdi |  | PDF belgesi içeren bayt dizisi. |

### Document {#Document-java.io.InputStream-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-boolean-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-java.lang.String-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Boş belgeyi başlatır.

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Boş belgeyi başlatır.

### Document {#Document-com.aspose.pdf.PdfVersion-}
Boş belgeyi başlatır.

### Document {#Document-com.aspose.ms.System.IO.Stream-}
Boş belgeyi başlatır.

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
Boş belgeyi başlatır.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
Boş belgeyi başlatır.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Boş belgeyi başlatır.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-boolean-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-java.lang.String-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-java.lang.String-boolean-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Boş belgeyi başlatır.

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Boş belgeyi başlatır.

### afterImport {#afterImport--}
```
public void afterImport()
```

Tüm kayıtlı açıklamaları enumerate eder ve her biri için AfterImport metodunu çağırır.

### bindXml {#bindXml-java.io.InputStream-}
XML'i belgeye bağla

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
XML/XSL'i belgeye bağla

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
XML/XSL'i belgeye bağla

### bindXml {#bindXml-java.lang.String-}
XML'i belgeye bağla

### bindXml {#bindXml-java.lang.String-java.lang.String-}
XML/XSL'i belgeye bağla

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Belge şifrelerini değiştirir. Bu işlem yalnızca sahibi şifresi kullanılarak yapılabilir.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
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
public void close()
```

Bu belge tarafından kullanılan tüm kaynakları kapatır.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Belge içindeki görüntüleri tanır ve üzerine hocr dizgileri ekler.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Fixup uygulayarak belgeyi dönüştür.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Fixup uygulayarak belgeyi dönüştür.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Fixup uygulayarak belgeyi dönüştür.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Fixup uygulayarak belgeyi dönüştür.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Kaynak biçimdeki akışı hedef biçimdeki akışa dönüştürür.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Kaynak biçimdeki akışı hedef biçimdeki hedef dosyaya dönüştürür.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Belgeyi dönüştür ve hataları belirtilen akışa kaydet.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Belgeyi belirtilen dönüşüm seçeneklerini kullanarak dönüştür

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Kaynak biçimdeki kaynak dosyayı hedef biçimdeki akışa dönüştürür.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Kaynak biçimdeki kaynak dosyayı hedef biçimdeki hedef dosyaya dönüştürür.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Belgeyi dönüştür ve hataları belirtilen akışa kaydet.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Sayfayı DSR, OMR, OCR görüntü akışı için PNG'ye dönüştür.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Belgeyi aranabilir belgeye dönüştürür ve dönüştürülemeyen hochr hatalarını atlar.

### decrypt {#decrypt--}
```
public void decrypt()
```

Belgeyi şifre çözer. Ardından belgeyi şifre çözülmüş sürüm olarak elde etmek için Save'i çağırın.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Bu belge tarafından kullanılan tüm kaynakları kapatır. Bu yöntem artık kullanılmıyor, bunun yerine close() kullanın.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Belgeyi şifreler.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Belgeyi şifreler. Ardından belgeyi şifrelenmiş sürüm olarak almak için Save'i çağırın.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Belgeyi şifreler.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Belgeyi şifreler. Ardından belgeyi şifrelenmiş sürüm olarak almak için Save'i çağırın.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Belgeyi şifreler. Ardından belgeyi şifrelenmiş sürüm olarak almak için Save'i çağırın.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Belgeyi şifreler.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Tüm belge açıklamalarını akışa dışa aktar.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Tüm belge ek açıklamalarını XFDF dosyasına dışa aktarır

### flatten {#flatten--}
```
public void flatten()
```

Belgeden tüm alanları (ve ek açıklamaları) kaldırır ve yerine değerlerini yerleştirir.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Belgeden tüm alanları (ve ek açıklamaları) kaldırır ve yerine değerlerini yerleştirir.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Şeffaf içeriği şeffaf olmayan raster ve vektör grafiklerle değiştirir.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Belleği temizler

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Belgeleri işlerken eksik yazı tipleri hakkında bildirim.

**Returns:**
ADocument.AbsentFontHandler örneği

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> Belge eylemlerini alır. Bu özellik, BeforClosing, BeforSaving vb. eylemlere get/set yapmayı sağlayan DocumentActions sınıfının bir örneğidir. </p>

**Returns:**
DocumentActionCollection nesnesi <hr> <pre> Bu örnek, belgenin açıldıktan sonraki eylemini nasıl alacağınızı gösterir: Document document = new Document(\"PdfWithOpenAction.pdf\"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Sayfa içeriklerini birleştirerek belge boyutunu optimize etmeye izin verir.

**Returns:**
değer boolean değer

### getBackground {#getBackground--}
```
public Color getBackground()
```

Belgenin arka plan rengini alır.

**Returns:**
Color nesnesi

### getCatalogValue {#getCatalogValue-java.lang.String-}
Katalog sözlüğünden öğe değerini döndürür.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Belgenin koleksiyonunu alır.

**Returns:**
Collection nesnesi

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Belge şifreli ise güvenlik ayarlarını alır. Belge şifreli değilse, .net 1.1'de ilgili istisna yükseltilir veya diğer .net sürümlerinde CryptoAlgorithm null olur.

**Returns:**
CryptoAlgorithm öğesi @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Özel bir güvenlik işleyicisini alır.

**Returns:**
ICustomSecurityHandler örneği

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Bu belgeye sayfaları kopyalamak için kullanılan kopyalayıcıyı döndürür.

**Returns:**
Copier nesnesi

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

Hedeflerin koleksiyonunu alır.

**Returns:**
DestinationCollection öğesi

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Metnin okuma sırasını alır: L2R (soldan sağa) veya R2L (sağdan sola).

**Returns:**
Direction öğesi @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar.

**Returns:**
PrintDuplex öğesi

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Belgeye gömülü dosyaların koleksiyonunu alır.

**Returns:**
EmbeddedFileCollection nesnesi

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik.

**Returns:**
boolean değer

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar.

**Returns:**
boolean değer

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

IPdfDocument örneği, iç belge yapısına erişmek için kullanılır. Yalnızca dahili.

**Returns:**
IPdfDocument nesnesi

### getFileName {#getFileName--}
```
public String getFileName()
```

Bu belgeyi oluşturan PDF dosyasının adı

**Returns:**
Dize nesnesi

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Bir dosyanın tamamını belleğe yüklemek için dosya boyutu limitini al ve ayarla.

**Returns:**
int değer

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

IDocumentFontUtilities örneği

**Returns:**
IDocumentFontUtilities örneği

### getForm {#getForm--}
```
public Form getForm()
```

Belgenin Acro Formunu alır.

**Returns:**
Form nesnesi

### getId {#getId--}
```
public Id getId()
```

Kimliği alır.

**Returns:**
Id nesnesi

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Kaynak dosyalardaki hataları yoksayma bayrağını alır veya ayarlar. Kaynak belgeden sayfalar hedef belgeye kopyalandığında, bu bayrak false olduğunda kaynak dosyalardaki bazı nesneler bozuksa kopyalama işlemi bir istisna ile durur. örnek: dest.Pages.Add(src.Pages); Bayrak true olarak ayarlanırsa bozuk nesneler boş değerlerle değiştirilir. Varsayılan: true.

**Returns:**
boolean değer

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Belge bilgilerini alır.

**Returns:**
DocumentInfo nesnesi

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Belge düzeyindeki JavaScript koleksiyonu.

**Returns:**
JavaScriptCollection nesnesi

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Belgenin mantıksal yapısını alır.

**Returns:**
RootElement nesnesi

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Belge meta verileri. (Bir PDF belgesi, belgenin başlığı, yazarı ve oluşturulma ve değiştirilme tarihleri gibi genel bilgileri içerebilir. Belgenin içeriği veya yapısı yerine bu tür küresel bilgi meta veri olarak adlandırılır ve dış veri tabanlarında belgelerin kataloglanması ve aranmasına yardımcı olması amaçlanır.)

**Returns:**
Metadata nesnesi

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Ham meta veri akışını döndürür

**Returns:**
IPdfStreamAccessor nesnesi

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Belgedeki Adlandırılmış Hedeflerin koleksiyonu.

**Returns:**
NamedDestinationCollection örneği

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu alır.

**Returns:**
PageMode öğesi @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
Belgedeki belirtilen kimliğe sahip nesneyi alır.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> Belge açıldığında gerçekleştirilen eylemi alır. </p> <hr> <pre> Örnek, CenterWindow bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment nesnesi

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Optimizasyon bayrağını alır. Sayfalar belgeye eklendiğinde, bu bayrak ayarlıysa sonuç dosyasındaki eşit kaynak akışları tek bir PDF nesnesi içinde birleştirilir. Bu, sonuç dosya boyutunun azalmasını sağlar ancak daha yavaş yürütme ve daha fazla bellek gereksinimine neden olabilir. Varsayılan değer: false.

**Returns:**
boolean değer

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Belge taslaklarını alır.

**Returns:**
OutlineCollection nesnesi

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Belgedeki Output niyetlerinin koleksiyonunu alır.

**Returns:**
OutputIntents örneği

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Sayfa bilgilerini alır.(yalnızca oluşturucu için, belge okunduğunda doldurulmaz)

**Returns:**
Sayfa bilgisi.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Belgedeki sayfa etiketlerini alır.

**Returns:**
PageLabelCollection nesnesi

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Belge açıldığında kullanılacak sayfa düzenini alır.

**Returns:**
PageLayout öğesi @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu alır.

**Returns:**
PageMode öğesi @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> Belge sayfalarının koleksiyonunu alır. Sayfaların koleksiyonda 1'den başladığını unutmayın. </p>

**Returns:**
PageCollection nesnesi <hr> <pre> Aşağıdaki örnek, belge sayfalarıyla nasıl çalışılacağını gösterir: Sayfa sayısını ve belgenin başlangıç sayfasının dikdörtgenini nasıl alacağınızı gösterir. Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

pdfa formatını alır

**Returns:**
PdfFormat öğesi @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Belgenin izinlerini alır.

**Returns:**
int değer

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini alır.

**Returns:**
PrintScaling öğesi

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

TaggedPdf içeriğine erişim sağlar. Örnek, başlık, paragraf ve görseller içeren yeni bir belge oluşturmak için etiketli içeriğin nasıl kullanılacağını gösterir. // Yeni belge oluştur Document document = new Document(); // Etiketli içeriği al ITaggedContent taggedContent = document.getTaggedContent(); // Belge için dili ayarla taggedContent.setLanguage("en-US"); // PDF belgesi için başlığı ayarla taggedContent.setTitle("Example document"); // Bölüm oluşturma ve ekleme SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Başlık oluştur HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("The Header"); sect.appendChild(h1); // Paragraf oluştur ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("The text of paragraph."); sect.appendChild(p); // Açıklama oluştur IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figure 1"); figure1.setTitle("Image 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Belgeyi kaydet document.save("example.pdf");

**Returns:**
ITaggedContent örneği

### getVersion {#getVersion--}
```
public String getVersion()
```

Pdf dosya başlığından Pdf sürümünü alır.

**Returns:**
String değeri

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Belgeden XMP meta verilerini al.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Mevcut PDF belgesinin artımlı güncellemelerle kaydedilip kaydedilmediğini kontrol eder.

**Returns:**
PDF belgesinde artımlı güncellemeler varsa true; aksi takdirde false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Akıştan belgeye açıklamaları içe aktarır.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
XFDF dosyasından belgeye açıklamaları içe aktarır.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Eksik yazı tipinin yerine konulması hakkında bilgi veren bayrak.

**Returns:**
boolean değer

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı alır. </p>

**Returns:**
boolean değer <hr> <pre> Örnek, CenterWindow bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez.

**Returns:**
boolean değer Varsayılan olarak false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır. </p>

**Returns:**
boolean değer <hr> <pre> Örnek, DisplayDocTitle bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Bildirimlerin kaydedilmesini etkinleştirip etkinleştirilmeyeceğini gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean değer

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Belgenin kısmen bellekten boşaltılmasını sağlayan bayrağı alır veya ayarlar.

**Returns:**
boolean değer

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Belgenin şifreli durumunu alır. Belge şifreliyse doğru (true).

**Returns:**
boolean değer

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılması gerekip gerekmediğini belirten bayrağı alır. </p>

**Returns:**
boolean değer <hr> <pre> Örnek, FitWindow bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Belge değişikliklerle ve imza içeriyorsa İstisna fırlat.

**Returns:**
boolean değer

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır. </p>

**Returns:**
boolean değer <hr> <pre> Örnek, HideMenubar bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır. </p>

**Returns:**
boolean değer <hr> <pre> Örnek, HideToolBar bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır. </p>

**Returns:**
boolean değer <hr> <pre> Örnek, HideWindowUI bayrağının nasıl alınacağını gösterir: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Sistemin lisans durumunu alır.

**Returns:**
boolean değer

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Belgenin lineerleştirilmiş olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Varsayılan olarak, save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirildiğinde, save yöntemi çağrıldıktan sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz.

**Returns:**
boolean değer. (Varsayılan değer == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Belgenin PDF/A uyumlu olup olmadığını alır.

**Returns:**
boolean değer

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Belgenin pdfua uyumlu olup olmadığını alır.

**Returns:**
boolean değer

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı alır.

**Returns:**
boolean değer

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Belgenin Repair yönteminin çağrılmasını gerekip gerektirmediğini kontrol eder.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Varsayılan olarak, bazı kurallar ihlal edildiğinde PDF/A uyumlu verileri güncellemek veya kaldırmak için PDF/A doğrulama süreci gereklidir.

**Returns:**
boolean değer

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar.

**Returns:**
boolean değer

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Bir dosyayı yükler ve PDF'ye dönüştürür.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Belgeleri birleştirir.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Belgeleri birleştirir.

### merge {#merge-com.aspose.pdf.Document...-}
Belgeleri birleştirir.

### merge {#merge-java.lang.String...-}
PDF dosyalarını birleştirir.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Belgeleri birleştirir.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Belgeleri birleştirir.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Belgeleri birleştirir.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
PDF dosyalarını birleştirir.

### optimize {#optimize--}
```
public void optimize()
```

Belgeyi lineerleştirerek - ilk sayfayı mümkün olduğunca hızlı açmak; - sonraki sayfayı göstermek veya bir sonraki sayfaya bağlantıyı mümkün olduğunca hızlı takip etmek; - bir sayfanın verileri yavaş bir kanaldan iletildiğinde sayfayı kademeli olarak göstermek (en faydalı verileri önce göstermek); - bir bağlantıyı takip etmek gibi kullanıcı etkileşiminin, sayfanın tamamı alınmadan ve görüntülenmeden önce gerçekleşmesine izin vermek amaçlanır. Bu yöntemin çağrılması aslında belgeyi kaydetmez. Aksine, belge yalnızca optimize edilmiş bir yapıya hazırlanır, ardından Optimize edilmiş belgeyi elde etmek için Save çağrılır.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Belgedeki kaynakları optimize eder: 1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır; 2. Aynı kaynaklar tek bir nesne içinde birleştirilir; 3. Kullanılmayan nesneler silinir.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Belgedeki kaynakları optimize eder: 1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır; 2. Aynı kaynaklar tek bir nesne içinde birleştirilir; 3. Kullanılmayan nesneler silinir.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Belgedeki sayfa ağacı düğümlerini dengeli bir ağaç hâline getirir. Yalnızca belge, nodesNumInSubtrees sayısından fazla sayfa nesnesine sahipse uygulanır, aksi takdirde hiçbir şey yapmaz.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Belgedeki sayfa ağacı düğümlerini dengeli bir ağaç hâline getirir. Yalnızca belge, nodesNumInSubtrees sayısından fazla sayfa nesnesine sahipse uygulanır, aksi takdirde hiçbir şey yapmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodesNumInSubtrees |  | İstenen alt düğüm sayısı. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Dahili yöntem

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Belgeyi akışa kaydeder.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Belgeden meta verileri kaldırır.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Belgeden pdfa uyumluluğunu kaldır.

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Belgeden pdfUa uyumluluğunu kaldır.

### repair {#repair--}
```
public void repair()
```

Bozuk belgeyi onarır.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Bozuk belgeyi onarır.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

belge güncellemesini devam ettirir

### save {#save--}
```
public void save()
```

<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-java.io.OutputStream-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-com.aspose.pdf.SaveOptions-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-java.lang.String-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> Belgeyi artımlı olarak kaydedin (yani artımlı güncelleme tekniği kullanılarak). </p> <hr> <p> Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma modunda açmalıyız. Bu nedenle Document, InputStream ile değil, dosya yoluyla başlatılmalıdır; aşağıdaki kod örneğinde olduğu gibi: Document doc = new Document(\"document.pdf\"); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.save(); </p> Document InputStream ile başlatıldıysa, InputStream'e yazma mümkün değildir, bu yüzden belgeyi kaydetmek için ayrı \"save\" yöntemini veya belgeyi artımlı kaydetmek için \"saveIncrementally\" yöntemini kullanmanızı öneririz.

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

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Belgeleri işlerken eksik yazı tipleri hakkında bildirim.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Font eksikliği durumunda program tarafından belirlenen fontu ayarlamak için bayrak ayarlanıyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Sayfa içeriklerini birleştirerek belge boyutunu optimize etmeye izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBackground {#setBackground-java.awt.Color-}
Belgenin arka plan rengini ayarlar.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Belgenin pencere konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Belgenin koleksiyonunu ayarlar.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

pdf/ua dönüştürücü için dönüştürme parametresini alır (true ayarlanırsa yalnızca Meta Verileri ve Belge Kataloğu dönüştürülür)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Tüm dosyayı belleğe yüklemek için dosya boyutu limitini varsayılan değer olan 210 MB olarak ayarlar.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa yürütülemez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer Varsayılan olarak false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PrintDuplex öğesi |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini ve IsEmbedded bayrağının true olarak ayarlandığını belirten özellik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Bildirimlerin kaydedilmesini etkinleştirip etkinleştirilmeyeceğini gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Belgenin kısmen bellekten boşaltılmasını sağlayan bayrağı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Bir dosyanın tamamını belleğe yüklemek için dosya boyutu limitini al ve ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Belge değişikliklerle ve imza içeriyorsa İstisna fırlat.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Belge etkin olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Belge etkin olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Belge etkin olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Kaynak dosyalardaki hataları yoksayma bayrağını alır veya ayarlar. Kaynak belgeden sayfalar hedef belgeye kopyalandığında, bu bayrak false olduğunda kaynak dosyalardaki bazı nesneler bozuksa kopyalama işlemi bir istisna ile durur. örnek: dest.Pages.Add(src.Pages); Bayrak true olarak ayarlanırsa bozuk nesneler boş değerlerle değiştirilir. Varsayılan: true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Varsayılan olarak, save yöntemi iç akışları kapatır ve bellek kaynaklarını serbest bırakır. ManualDispose parametresi etkinleştirildiğinde, save yöntemi çağrıldıktan sonra bazı işlemler yapabilir ve belgeyle çalışmaya devam edebiliriz. Ancak Document örneği artık ihtiyaç duyulmadığında dispose yönteminin çağrılması şiddetle tavsiye edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| manualDisposeEnabled |  | boolean değer. (Varsayılan değer == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirten sayfa modunu ayarlar.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> Belge açıldığında gerçekleştirilen eylemi ayarlar. <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Optimizasyon bayrağını ayarlar. Sayfalar belgeye eklendiğinde, bu bayrak ayarlıysa sonuç dosyadaki eşit kaynak akışları tek bir PDF nesnesi içinde birleştirilir. Bu, sonuç dosya boyutunun azalmasını sağlar ancak daha yavaş yürütme ve daha fazla bellek gereksinimine yol açabilir. Varsayılan değer: false.

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
public final void setPickTrayByPdfSize(boolean value)
```

PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Yazdırma iletişim kutusundan dosya yazdırılırken kullanılacak baskı ölçekleme işleme seçeneğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PrintDuplex öğesi |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Varsayılan olarak, bazı kurallar ihlal edildiğinde PDF/A'yı güncellemek veya kaldırmak için PDF/A doğrulama süreci gereklidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | boolean değer |

### setTitle {#setTitle-java.lang.String-}
Pdf Belgesi için Başlık ayarla

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Belgenin XMP meta verilerini ayarla.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Tüm sayfalar için içerik güncelleme verilerini bastırır. İçerik, ResumeUpdate çağrılana kadar güncellenmez.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Belgeyi belirtilen dosyaya doğrula.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Belgeyi belirtilen dosyaya doğrula.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Belgeyi belirtilen dosyaya doğrula.
