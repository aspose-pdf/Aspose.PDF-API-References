---
title: Document
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesini temsil eden sınıf
type: docs
weight: 1870
url: /tr/net/aspose.pdf/document/
---
## Document class

PDF belgesini temsil eden sınıf

```csharp
public sealed class Document : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Document](document#constructor)() | Boş belgeyi başlatır. |
| [Document](document#constructor_1)(Stream) | Yeni Belge örneğini*input* akış. |
| [Document](document#constructor_6)(string) | Sadece kullanarak Belgeyi başlat*filename* . Aynı[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Yeni Belge örneğini*input* akış. |
| [Document](document#constructor_2)(Stream, LoadOptions) | PDF belgesi almak için gerekli dönüştürmeyi sağlayan bir akıştan mevcut bir belgeyi açar. |
| [Document](document#constructor_4)(Stream, string) | Yeni Belge örneğini*input* akış. |
| [Document](document#constructor_7)(string, LoadOptions) | pdf belgesi almak için gerekli dönüştürme seçeneklerini sağlayan bir dosyadan mevcut bir belgeyi açar. |
| [Document](document#constructor_8)(string, string) | Yeni örneğini başlatır[`Document`](../document) şifreli belgeyle çalışmak için sınıf. |
| [Document](document#constructor_5)(Stream, string, bool) | Yeni Belge örneğini*input* akış. |
| [Document](document#constructor_9)(string, string, bool) | Yeni örneğini başlatır[`Document`](../document) şifreli belgeyle çalışmak için sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Belge eylemlerini alır. Bu özellik, BeforClosing, BeforSaving, vb. eylemlerin alınmasına/ayarlanmasına izin veren DocumentActions sınıfının bir örneğidir. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Belge boyutunu optimize etmek için sayfa içeriğinin birleştirilmesine izin verir. Kullanılırsa, farklı ancak yinelenen sayfalar aynı içerik nesnesine başvurabilir. Lütfen bu modun diğer sayfa değiştirildiğinde sayfa içeriğinin değiştirilmesi gibi yan etkilere neden olabileceğini unutmayın. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Belgenin arka plan rengini alır veya ayarlar. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı alır veya ayarlar. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Belge koleksiyonunu alır. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Belge şifrelenmişse güvenlik ayarlarını alır. Belge şifrelenmemişse, .net 1.1 'de ilgili istisna oluşturulacak veya diğer .net sürümleri için CryptoAlgorithm null olacaktır. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Hedeflerin koleksiyonunu alır. Eski. Lütfen NamedDestinations. kullanın |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Metnin okuma sırasını alır veya ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | Bu yazı tipinin lisansı tarafından yasaklanmışsa, yazı tipi ile birçok işlem yürütülemez. Örneğin, lisans kuralları bu yazı tipi için yerleştirmeyi devre dışı bırakırsa, bazı yazı tipleri PDF belgesine gömülemez. Bu bayrak, geçerli PDF belgesindeki tüm yazı tipleri için herhangi bir lisans kısıtlamasını devre dışı bırakmak için kullanılır. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı koyan kişinin, olası lisans/kanun ihlallerinin tüm sorumluluğunu kendisinin üstlendiği anlamına gelir. Bu yüzden kendi riskini alır. Bu bayrağı yalnızca telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuzda kullanmanız şiddetle önerilir. Varsayılan olarak false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Belgenin pencere başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır veya ayarlar. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Dosyayı yazdırma iletişim kutusundan yazdırırken kullanılacak yazdırma dupleks modu işleme seçeneğini alır veya ayarlar. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Belgeye katıştırılmış dosya koleksiyonunu alır. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Belgenin, IsEmbedded bayrağı true olarak ayarlanmış tüm standart Type1 yazı tiplerini gömmesi gerektiğini bildiren özellik. Tüm PDF fontları, yalnızca IsEmbedded işaretini true olarak ayarlayarak belgeye gömülebilir, ancak PDF standart Type1 fontları bu kuralın bir istisnasıdır. Standart Type1 font yerleştirme çok zaman gerektirir, bu yüzden bu fontları gömmek için gereklidir yalnızca bayrak ayarlamakla kalmaz Belirtilen yazı tipi için true olarak Gömülüdür, ancak belge düzeyinde ek bir bayrak ayarlar - EmbedStandardFonts = true; Bu özellik tüm yazı tipleri için yalnızca bir kez ayarlanabilir. Varsayılan olarak false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Belgenin bellekten kısmen boşaltılmasını sağlayan bayrağı al veya ayarla. Bu, bellek kullanımını azaltmaya izin verir ancak performans üzerinde olumsuz etkisi olabilir. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | İmza alanlarının temizliğini yönetmek için bayrak alır veya ayarlar. Varsayılan olarak etkindir. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Bu belgeye neden olan PDF dosyasının adı |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılması gerekip gerekmediğini belirten bayrağı alır veya ayarlar. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | IDocumentFontUtilities instance |
| [Form](../../aspose.pdf/document/form) { get; } | Belgenin Acro Formunu alır. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Belge değişikliklerle kaydedilecek ve imzaya sahip olacaksa İstisnayı Atın |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Belge etkinken menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Belge etkinken araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Belge etkinken kullanıcı arabirimi öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [Id](../../aspose.pdf/document/id) { get; } | Kimliği alır. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Kaynak dosyalardaki hataları yoksayma bayrağını alır veya ayarlar. Kaynak belgedeki sayfalar hedef belgeye kopyalandığında, bu işaret yanlış olduğunda kaynak dosyalardaki bazı nesneler bozulursa istisnası dışında kopyalama işlemi durdurulur. örnek: dest.Pages.Add(src.Pages); Bu işaret true olarak ayarlanırsa, bozuk nesneler boş değerlerle değiştirilir. Varsayılan olarak: true. |
| [Info](../../aspose.pdf/document/info) { get; } | Belge bilgilerini alır. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Belgenin şifrelenmiş durumunu alır. Belge şifrelenmişse doğrudur. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Belgenin doğrusallaştırılmış olup olmadığını gösteren bir değer alır veya ayarlar. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | pdfa uyumlu belgeyi alır. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | pdfua uyumlu belgeyi alır. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | pdfa uyumlu belgeyi alır veya ayarlar. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Belge düzeyinde JavaScript koleksiyonu. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Belgenin mantıksal yapısını alır. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Belge meta verileri. (Bir PDF belgesi, belgenin başlığı, yazarı ve oluşturulma ve değiştirilme tarihleri gibi genel bilgileri içerebilir. Belge hakkındaki bu tür genel bilgilere (içeriği veya yapısının aksine) metadata adı verilir ve harici veritabanlarında kataloglama ve belge aramada yardımcı olmayı amaçlamaktadır.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Belgede Adlandırılmış Hedef Koleksiyonu. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirterek sayfa modunu alır veya ayarlar. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Belge açılışında gerçekleştirilen eylemi alır veya ayarlar. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Optimizasyon bayrağını alır veya ayarlar. Sayfalar belgeye eklendiğinde, bu bayrak ayarlanırsa sonuç dosyasındaki eşit kaynak akışları tek bir PDF nesnesinde birleştirilir. Bu, sonuçta ortaya çıkan dosya boyutunu küçültmeye izin verir ancak daha yavaş yürütmeye ve daha büyük bellek gereksinimlerine neden olabilir. Varsayılan değer: false. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Belge ana hatlarını alır. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Sayfa bilgisini alır veya ayarlar.(yalnızca jeneratör için) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Belgedeki sayfa etiketlerini alır. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Belge açıldığında kullanılacak olan sayfa düzenini alır veya ayarlar. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Açıldığında belgenin nasıl görüntüleneceğini belirterek sayfa modunu alır veya ayarlar. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Belge sayfaları koleksiyonunu alır veya ayarlar. Sayfaların koleksiyonda 1'den itibaren numaralandırıldığını unutmayın. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | PDF biçimini alır |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Belgenin izinlerini alır. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | TaggedPdf içeriğine erişim sağlar. |
| [Version](../../aspose.pdf/document/version) { get; } | Pdf dosya başlığından bir Pdf sürümünü alır. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Sistemin lisanslı durumunu alır. Sistem lisanslı modda çalışıyorsa true, aksi halde false döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | xml'yi document 'ye bağla |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | xml'yi document 'ye bağla |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | xml/xsl dosyasını document öğesine bağlayın |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | xml/xsl dosyasını document öğesine bağlayın |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | xml/xsl dosyasını document öğesine bağlayın |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Belge parolalarını değiştirir. Bu eylem yalnızca sahip parolası kullanılarak yapılabilir. |
| [Check](../../aspose.pdf/document/check)(bool) | Belgeyi doğrular. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Belirtilen dönüştürme seçeneklerini kullanarak belgeyi dönüştürün |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Belgeyi dönüştürün ve hataları belirtilen akışa kaydedin. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Düzeltmeyi uygulayarak belgeyi dönüştürün. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Düzeltmeyi uygulayarak belgeyi dönüştürün. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | DSR, OMR, OCR görüntü akışı için sayfayı PNG'ye dönüştürün. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Belgenin şifresini çözer. Belgenin şifresi çözülmüş sürümünü almak için Arayın ve Kaydet'i tıklayın. |
| [Dispose](../../aspose.pdf/document/dispose)() | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Belgeyi şifreler. Belgenin şifrelenmiş sürümünü almak için Arayın ve Kaydet'i tıklayın. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Belgeyi şifreler. Belgenin şifrelenmiş sürümünü almak için Arayın ve Kaydet'i tıklayın. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Belgeyi şifreler. Belgenin şifrelenmiş sürümünü almak için Arayın ve Kaydet'i tıklayın. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Tüm belge ek açıklamalarını akışa aktarın. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Tüm belge açıklamalarını XFDF file dosyasına aktarır |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Belgedeki tüm alanları kaldırır ve bunun yerine değerlerini yerleştirir. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Belgedeki tüm alanları kaldırır ve bunun yerine değerlerini yerleştirir. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Belleği temizler |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Katalog sözlüğünden öğe değerini döndürür. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Belgede belirtilen kimliğe sahip bir nesne alır. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | Belgeden XMP meta verilerini alın. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Ek açıklamaları akıştan belgeye aktarır. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Ek açıklamaları XFDF dosyasından belgeye aktarır. |
| [Optimize](../../aspose.pdf/document/optimize)() | Belgeyi şu şekilde doğrusallaştırın - ilk sayfayı mümkün olduğunca çabuk açın; - sonraki sayfayı görüntüleyin veya sonraki sayfaya giden bağlantıyı takip edin; - bir sayfanın verileri teslim edildiğinde sayfayı geldiği gibi aşamalı olarak görüntüleyin yavaş bir kanal üzerinden (önce en yararlı verileri görüntüleyin); - bir bağlantıyı takip etme gibi kullanıcı etkileşiminin, sayfanın tamamı alınmadan ve görüntülenmeden önce gerçekleştirilmesine izin verir. Bu yöntemi çağırmak belgeyi gerçekten kaydetmez . Aksine, belge yalnızca optimize edilmiş yapıya sahip olacak şekilde hazırlanır, optimize edilmiş belgeyi almak için Kaydet'i çağırın. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Belgedeki kaynakları optimize edin: 1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır; 2. Eşit kaynaklar tek bir nesnede birleştirilir; 3. Kullanılmayan nesneler silinir. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Belgedeki kaynakları, tanımlanan optimizasyon stratejisine göre optimize edin. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Oluşturucu için paragrafları işle. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Belgeden meta verileri kaldırır. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | pdfa uyumluluğunu belgeden kaldırın |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | pdfUa uyumluluğunu belgeden kaldırın |
| [Repair](../../aspose.pdf/document/repair)() | Bozuk belgeyi onarır. |
| [Save](../../aspose.pdf/document/save#save)() | Belgeyi aşamalı olarak kaydedin (yani artımlı güncelleme tekniğini kullanarak). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Belgeyi kaydetme seçenekleriyle kaydeder. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Belgeyi akışta depolar. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Belgeyi belirtilen dosyaya kaydeder. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Belgeyi bir dosya biçimiyle birlikte yeni bir adla kaydeder. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Belgeyi kaydetme seçenekleriyle bir akışa kaydeder. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Belgeyi bir dosya biçimiyle birlikte yeni bir adla kaydeder. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Belgeyi, kaydetme seçeneklerini ayarlayan yeni bir adla kaydeder. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Belgeyi, kaydetme seçenekleriyle bir yanıt akışına kaydeder. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Belgeyi XML'e kaydedin. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Belgenin tamamını işlenmek üzere belge aygıtına gönderir. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Belgenin tamamını işlenmek üzere belge aygıtına gönderir. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Belgenin belirli sayfalarını işlenmek üzere belge aygıtına gönderir. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Belgenin tamamını işlenmek üzere belge aygıtına gönderir. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Pdf Belgesi için Başlık Ayarlayın |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | Belgenin XMP meta verilerini ayarlayın. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Belgeyi belirtilen dosyada doğrulayın. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Belgeyi belirtilen dosyada doğrulayın. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Belgeyi belirtilen dosyada doğrulayın. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Kaynak biçimindeki akışı hedef biçimindeki akışa dönüştürür. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Kaynak biçimindeki akışı hedef biçimindeki hedef dosyaya dönüştürür. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Kaynak biçimindeki kaynak dosyayı hedef biçimindeki akışa dönüştürür. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Kaynak biçimindeki kaynak dosyayı, hedef biçimindeki hedef dosyaya dönüştürür. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | hocr tanıma için geri arama prosedürü. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | FontSubstitution olayını işleyecek yöntemi temsil eder. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Fonts 'yi ayarlamak için işlevsellik içerir |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
