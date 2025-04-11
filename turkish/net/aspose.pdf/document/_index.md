---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Document sınıfı. PDF belgesini temsil eden sınıf
type: docs
weight: 3780
url: /tr/net/aspose.pdf/document/
---
## Document sınıfı

PDF belgesini temsil eden sınıf.

```csharp
public sealed class Document : IDisposable
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Document](document/#constructor)() | Boş belgeyi başlatır. |
| [Document](document/#constructor_1)(PdfVersion) | Versiyona göre boş belgeyi başlatır. |
| [Document](document/#constructor_2)(Stream) | *girdi* akışından yeni Document örneğini başlatır. |
| [Document](document/#constructor_7)(string) | Sadece *dosya adı* kullanarak Document'i başlatır. [`Document`](./document/) ile aynıdır. |
| [Document](document/#constructor_4)(Stream, bool) | *girdi* akışından yeni Document örneğini başlatır. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Gerekli dönüştürmeyi sağlayarak bir akıştan mevcut belgeyi açar. |
| [Document](document/#constructor_5)(Stream, string) | *girdi* akışından yeni Document örneğini başlatır. |
| [Document](document/#constructor_9)(string, bool) | Sadece *dosya adı* kullanarak Document'i başlatır. [`Document`](./document/) ile aynıdır. |
| [Document](document/#constructor_8)(string, LoadOptions) | Gerekli dönüştürme seçeneklerini sağlayarak bir dosyadan mevcut belgeyi açar. |
| [Document](document/#constructor_10)(string, string) | Şifreli belge ile çalışmak için `Document` sınıfının yeni bir örneğini başlatır. |
| [Document](document/#constructor_6)(Stream, string, bool) | *girdi* akışından yeni Document örneğini başlatır. |
| [Document](document/#constructor_11)(string, string, bool) | Şifreli belge ile çalışmak için `Document` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Belge eylemlerini alır. Bu özellik, BeforClosing, BeforSaving vb. eylemleri almak/ayarlamak için DocumentActions sınıfının bir örneğidir. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Belge boyutunu optimize etmek için sayfa içeriklerinin birleştirilmesine izin verir. Kullanıldığında, farklı ancak kopyalanmış sayfalar aynı içerik nesnesine referans verebilir. Bu modun, diğer sayfa değiştiğinde sayfa içeriğini değiştirmek gibi yan etkiler yaratabileceğini lütfen unutmayın. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Belgenin arka plan rengini alır veya ayarlar. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Belgenin penceresinin ekranın ortasında olup olmayacağını belirten bayrağı alır veya ayarlar. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Belge koleksiyonunu alır. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Belge şifreli ise güvenlik ayarlarını alır. Belge şifreli değilse, .net 1.1'de ilgili istisna oluşturulacak veya diğer .net sürümlerinde CryptoAlgorithm null olacaktır. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Hedeflerin koleksiyonunu alır. Eski. Lütfen NamedDestinations kullanın. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Metnin okuma sırasını alır veya ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Font ile ilgili birçok işlem, bu fontun lisansı tarafından yasaklanmışsa gerçekleştirilemez. Örneğin, bazı fontlar, bu font için gömme kuralları gömme işlemini devre dışı bırakıyorsa PDF belgesine gömülemez. Bu bayrak, mevcut PDF belgesindeki tüm fontlar için herhangi bir lisans kısıtlamasını devre dışı bırakmak için kullanılır. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin, olası lisans/kanun ihlalleri için tüm sorumluluğu üstlendiği anlamına gelir. Yani kendi riskiyle üstlenir. Bu bayrağı yalnızca telif hakkı yasalarını ihlal etmediğinizden tamamen emin olduğunuzda kullanmanız şiddetle tavsiye edilir. Varsayılan olarak false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Belgenin pencere başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır veya ayarlar. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Dosya yazdırılırken kullanılacak yazdırma çift taraflı modunu ayarlayan seçeneği alır veya ayarlar. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Belgeye gömülü dosyaların koleksiyonunu alır. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Belgenin, IsEmbedded bayrağı true olarak ayarlanmış tüm standart Type1 fontlarını gömmesi gerektiğini belirten özellik. Tüm PDF fontları, IsEmbedded bayrağını true olarak ayarlayarak belgeye gömülebilir, ancak PDF standart Type1 fontları bu kuralın bir istisnasıdır. Standart Type1 font gömme işlemi çok zaman alır, bu nedenle bu fontları gömmek için yalnızca belirtilen font için IsEmbedded bayrağını true olarak ayarlamakla kalmayıp, ayrıca belgenin seviyesinde ek bir bayrak ayarlamak gerekir - EmbedStandardFonts = true; Bu özellik yalnızca tüm fontlar için bir kez ayarlanabilir. Varsayılan olarak false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Belgenin kısmen bellekten boşaltılmasını sağlayan bayrağı alır veya ayarlar. Bu, bellek kullanımını azaltmaya izin verir ancak performans üzerinde olumsuz bir etki yaratabilir. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | İmza alanlarının sanitizasyonunu yönetmek için bayrağı alır veya ayarlar. Varsayılan olarak etkin. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Bu belgeyi oluşturan PDF dosyasının adı |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı alır veya ayarlar. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities örneği |
| [Form](../../aspose.pdf/document/form/) { get; } | Belgenin Acro Formunu alır. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Belge değişikliklerle kaydedilecekse istisna fırlatır ve imza vardır |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Belge aktifken menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Belge aktifken araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Belge aktifken kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| [Id](../../aspose.pdf/document/id/) { get; } | ID'yi alır. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Kaynak dosyalardaki hataları yok sayma bayrağını alır veya ayarlar. Kaynak belgeden sayfalar hedef belgeye kopyalandığında, bu bayrak false olduğunda, kaynak dosyalardaki bazı nesneler bozuksa kopyalama işlemi istisna ile durdurulur. örnek: dest.Pages.Add(src.Pages); Bu bayrak true olarak ayarlandığında, bozuk nesneler boş değerlerle değiştirilir. Varsayılan: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Belge bilgilerini alır. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Belgenin şifreli durumunu alır. Belge şifreli ise true. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Belgenin lineerleştirilip lineerleştirilmediğini belirten bir değeri alır veya ayarlar. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Belgenin pdfa uyumlu olup olmadığını alır. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Belgenin pdfua uyumlu olup olmadığını alır. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Belgenin pdfa uyumlu olup olmadığını belirten değeri alır veya ayarlar. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Belge seviyesindeki JavaScript koleksiyonu. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Belgenin mantıksal yapısını alır. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Belge meta verisi. (Bir PDF belgesi, belgenin başlığı, yazarı ve oluşturulma ve değiştirilme tarihleri gibi genel bilgileri içerebilir. Belge hakkında bu tür genel bilgiler (içeriği veya yapısı yerine) meta veri olarak adlandırılır ve belgelerin dış veritabanlarında kataloglanmasına ve aranmasına yardımcı olmak amacıyla tasarlanmıştır.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Belgedeki Adlandırılmış Hedeflerin koleksiyonu. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Sayfa modunu alır veya ayarlar, tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirtir. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Belge açıldığında gerçekleştirilen eylemi alır veya ayarlar. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Optimizasyon bayrağını alır veya ayarlar. Sayfalar belgeye eklendiğinde, bu bayrak ayarlandığında, sonuç dosyasındaki eşit kaynak akışları bir PDF nesnesinde birleştirilir. Bu, sonuç dosyasının boyutunu azaltmaya izin verir ancak daha yavaş yürütme ve daha büyük bellek gereksinimlerine neden olabilir. Varsayılan değer: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Belge taslaklarını alır. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Belgedeki Çıktı niyetlerinin koleksiyonunu alır. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Sayfa bilgisini alır veya ayarlar. (yalnızca oluşturucu için, belge okunurken doldurulmaz) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Belgedeki sayfa etiketlerini alır. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Belge açıldığında kullanılacak sayfa düzenini alır veya ayarlar. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Belge açıldığında nasıl görüntüleneceğini belirten sayfa modunu alır veya ayarlar. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Belge sayfalarının koleksiyonunu alır veya ayarlar. Sayfaların koleksiyonda 1'den itibaren numaralandığını unutmayın. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | PDF formatını alır |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Belgenin izinlerini alır. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | PDF sayfa boyutunun giriş kağıt tepsisini seçmek için kullanılıp kullanılmayacağını belirten bayrağı alır veya ayarlar. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Bu belge için yazdırma iletişim kutusu görüntülendiğinde seçilecek sayfa ölçekleme seçeneğini alır veya ayarlar. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | TaggedPdf içeriğine erişim sağlar. |
| [Version](../../aspose.pdf/document/version/) { get; } | PDF dosya başlığından bir PDF sürümünü alır. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Tüm dosyayı belleğe yüklemek için dosya boyutu sınırını alır ve ayarlar. Değer megabayt cinsindendir. Varsayılan değer 210 Mb'dir. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Sistem lisanslı durumunu alır. Sistem lisanslı modda çalışıyorsa true, aksi takdirde false döner. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Belgeleri birleştirir. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | PDF dosyalarını birleştirir. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Belgeleri birleştirir. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Belgeleri birleştirir. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | XML'i belgeye bağlar |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | XML'i belgeye bağlar |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | XML/XSL'i belgeye bağlar |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | XML/XSL'i belgeye bağlar |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | XML/XSL'i belgeye bağlar |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Belge şifrelerini değiştirir. Bu işlem yalnızca sahip şifresi kullanılarak yapılabilir. |
| [Check](../../aspose.pdf/document/check/)(bool) | Belgeyi doğrular. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Belgeyi belirtilen dönüştürme seçeneklerini kullanarak dönüştürür |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Belge içindeki görüntüleri tanır ve üzerine hocr dizelerini ekler. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Belge içindeki görüntüleri tanır ve üzerine hocr dizelerini ekler. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Belgeyi dönüştürür ve hataları belirtilen akışa kaydeder. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Belgeyi dönüştürür ve hataları belirtilen dosyaya kaydeder. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Düzeltme uygulayarak belgeyi dönüştürür. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Düzeltme uygulayarak belgeyi dönüştürür. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Belgeyi dönüştürür ve hataları belirtilen dosyaya kaydeder. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Belgeyi dönüştürür ve hataları belirtilen dosyaya kaydeder. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Sayfayı DSR, OMR, OCR görüntü akışı için PNG'ye dönüştürür. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Belgeyi şifre çözme işlemi yapar. Şifre çözülmüş belgeyi elde etmek için ardından Kaydet çağrılmalıdır. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Belgeyi şifreler. Şifreli belgeyi elde etmek için ardından Kaydet çağrılmalıdır. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Belgeyi şifreler. Şifreli belgeyi elde etmek için ardından Kaydet çağrılmalıdır. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Belgeyi şifreler. Şifreli belgeyi elde etmek için ardından Kaydet çağrılmalıdır. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Tüm belge notlarını akışa aktarır. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Tüm belge notlarını XFDF dosyasına aktarır |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Belgedeki tüm alanları kaldırır ve değerlerini yerleştirir. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Belgedeki tüm alanları (ve notları) kaldırır ve değerlerini yerleştirir. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Şeffaf içeriği şeffaf olmayan raster ve vektör grafikleri ile değiştirir. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Belleği temizler |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Katalog sözlüğünden öğe değerini döndürür. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Belgedeki belirtilen ID'ye sahip bir nesneyi alır. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Belgeden XMP meta verisini alır. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Mevcut PDF belgesinin artımlı güncellemelerle kaydedilip kaydedilmediğini kontrol eder. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Akıştan belgeye notları aktarır. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDF dosyasından belgeye notları aktarır. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Belgenin Onarım yöntemi çağrısına ihtiyaç duyup duymadığını kontrol eder. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Bir dosyayı yükler, PDF'ye dönüştürür. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Belgeleri birleştirir. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | PDF dosyalarını birleştirir. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Belgeleri birleştirir. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Belgeleri birleştirir. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Belgeyi lineerleştirir, böylece - ilk sayfayı mümkün olan en hızlı şekilde açar; - sonraki sayfayı veya bir sonraki sayfaya bağlantıyı mümkün olan en hızlı şekilde görüntüler; - sayfa verileri yavaş bir kanaldan iletildiğinde sayfayı kademeli olarak görüntüler (ilk olarak en yararlı verileri görüntüler); - kullanıcı etkileşimine izin verir, örneğin bir bağlantıyı takip etmek, tüm sayfa alınmadan ve görüntülenmeden bile gerçekleştirilebilir. Bu yöntemi çağırmak, belgeyi gerçekten kaydetmez. Aksine, belge yalnızca optimize edilmiş bir yapı için hazırlanır, ardından kaydetmek için çağrılmalıdır. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Belgedeki kaynakları optimize eder: 1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır; 2. Eşit kaynaklar bir nesneye birleştirilir; 3. Kullanılmayan nesneler silinir. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Belgedeki kaynakları tanımlanan optimizasyon stratejisine göre optimize eder. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Belgedeki sayfa ağaç düğümlerini dengeli bir ağaç haline getirir. Sadece belge, nodesNumInSubtrees sayısından fazla sayfa nesnesine sahipse, aksi takdirde hiçbir şey yapmaz. Sayfalar öğeleri üzerinde yineleme yaparken bu yöntemi çağırmayın, tahmin edilemez sonuçlar verebilir. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Oluşturucu için paragrafları işler. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Belgeden meta verileri kaldırır. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Belgeden pdfa uyumluluğunu kaldırır |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Belgeden pdfUa uyumluluğunu kaldırır |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Bozuk belgeyi onarır. |
| [Save](../../aspose.pdf/document/save/#save)() | Belgeyi artımlı olarak kaydeder (yani artımlı güncelleme tekniğini kullanarak). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Belgeyi kaydetme seçenekleri ile kaydeder. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Belgeyi akışa kaydeder. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Belgeyi belirtilen dosyaya kaydeder. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Belgeyi yeni bir adla ve dosya formatıyla kaydeder. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Belgeyi kaydetme seçenekleri ile bir akışa kaydeder. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Belgeyi yeni bir adla ve dosya formatıyla kaydeder. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Belgeyi yeni bir adla kaydeder ve kaydetme seçeneklerini ayarlar. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Belgeyi artımlı olarak kaydeder (yani artımlı güncelleme tekniğini kullanarak). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Belgeyi kaydetme seçenekleri ile kaydeder. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Belgeyi akışa kaydeder. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Belgeyi belirtilen dosyaya kaydeder. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Belgeyi yeni bir adla ve dosya formatıyla kaydeder. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Belgeyi kaydetme seçenekleri ile bir akışa kaydeder. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Belgeyi yeni bir adla ve dosya formatıyla kaydeder. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Belgeyi yeni bir adla kaydeder ve kaydetme seçeneklerini ayarlar. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Belgeyi XML olarak kaydeder. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Tüm belgeyi işlenmek üzere belge cihazına gönderir. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Tüm belgeyi işlenmek üzere belge cihazına gönderir. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Belgenin belirli sayfalarını işlenmek üzere belge cihazına gönderir. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Tüm belgeyi işlenmek üzere belge cihazına gönderir. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | PDF Belgesi için Başlık ayarlar |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Belgenin XMP meta verisini ayarlar. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Belgeyi belirtilen dosyaya doğrular. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Belgeyi belirtilen dosyaya doğrular. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Belgeyi belirtilen dosyaya doğrular. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Kaynak formatındaki akışı hedef formatındaki akışa dönüştürür. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Kaynak formatındaki akışı hedef formatındaki dosyaya dönüştürür. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Kaynak formatındaki dosyayı hedef formatındaki akışa dönüştürür. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Kaynak formatındaki dosyayı hedef formatındaki dosyaya dönüştürür. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Tüm dosyayı belleğe yüklemek için dosya boyutu sınırını varsayılan değer olan 210 Mb olarak ayarlar. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Olaylar

| İsim | Açıklama |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Belgedeki bir font başka bir font ile değiştirildiğinde meydana gelir. |

## Diğer Üyeler

| İsim | Açıklama |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | FontSubstitution olayını yönetecek yöntemi temsil eder. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Fontları ayarlamak için işlevselliği tutar |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Birleştirme yöntemleri için seçenekleri temsil eder. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Bir PDF belgesini onarmak için seçenekleri temsil eder. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)