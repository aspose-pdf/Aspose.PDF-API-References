---
title: "com.aspose.pdf"
second_title: "Aspose.PDF for Java API Referansı"
description: "com.aspose.pdf, Aspose.PDF for Java kütüphanesindeki tüm sınıflar için kök pakettir; bu sınıflar Document gibi doğrudan içinde bulunabilir veya çeşitli alt paketler aracılığıyla dolaylı olarak bulunabilir."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf/
---
com.aspose.pdf, Aspose.PDF for Java kütüphanesindeki tüm sınıflar için kök pakettir; bu sınıflar Document gibi doğrudan içinde bulunabilir veya çeşitli alt paketler aracılığıyla dolaylı olarak bulunabilir.

## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | hocr tanıma için geri çağırma prosedürü. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | hocr tanıma için geri çağırma prosedürü. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | hocr tanıma için geri çağırma prosedürü. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Yazı tiplerini ayarlama işlevselliğini tutar |
| [IAnnotationVisitor](./iannotationvisitor/) | Farklı belge ek açıklamalarını ziyaret etmek için Visitor'ı tanımlar. |
| [IAppointment](./iappointment/) | Eylemler ve hedefler için genel arayüzü temsil eder. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Renk uzayı dönüşüm stratejileri için arayüz. |
| [IDocument](./idocument/) | PDF belgesini temsil eden arayüz |
| [IFontOptions](./ifontoptions/) | Yazı tipi davranışını ayarlamak için faydalı özellikler |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Bu arayüz, kantizasyon özelleştirme algoritmaları için tanımlanmıştır. Kullanıcılar bu algoritmaların kendi gerçekleştirmelerini (örneğin yönetilmeyen kod tabanlı algoritmalar) uygulayabilir. |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Bu arayüz, kantizasyon özelleştirme algoritmaları için tanımlanmıştır. Kullanıcılar bu algoritmaların kendi gerçekleştirmelerini (örneğin yönetilmeyen kod tabanlı algoritmalar) uygulayabilir. |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Farklı pdf operatörlerini ziyaret etmek için Visitor'ı tanımlar. |
| [IPageSetOptions](./ipagesetoptions/) | Dönüştürülecek sayfa kümesiyle ilgili dönüşüm seçeneklerini tanımlar. |
| [IPipelineOptions](./ipipelineoptions/) | İş akışı yapılandırmasıyla ilgili dönüşüm seçeneklerini tanımlar. |
| [ITableElement](./itableelement/) | Bu arayüz, TableAbsorber tarafından çıkarılan mevcut tablonun bir öğesini temsil eder. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Bazen dış kaynakların (görüntüler veya CSS gibi) dahili yükleyicisinin kullanılmasından kaçınmak ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir. Örneğin, bulutta Aspose.PDf kullanılırken başvurulan dosyalara doğrudan erişim mümkün değildir ve özel bir kodun özel bir yönteme yerleştirilmesi gerekir. Bu temsilci, böyle bir özel yöntemin imzasını tanımlar. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Geçici klasörün geçici yazı tipi verilerini barındırmak için kullanılıp kullanılmayacağını belirten bayrağı ayarlayın. / * Varsayılan olarak true. / * Değer false ise yığın belleği kullanılır; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Bu tür bir özelliğe, PDF'den oluşturulan SVG'den çıkarılan ve PDF'den HTML'ye dönüştürme sırasında harici bir kaynak olarak kaydedilmesi gereken görüntünün dışa kaydedilmesini işleyen özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Böyle bir durumda, (akışa veya diske kendi yapmış olduğunuz kaydetme gibi) işleme, o özel kod içinde yapılabilir ve bu özel kod, daha sonra oluşturulan SVG'ye orijinal varsayılan görüntü kaynağı yolunun yerine eklenecek yolu (veya tırnak işareti olmayan başka bir dize) döndürmelidir. Bu durumda, görüntünün kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda yapılmalıdır, çünkü dönüştürücünün kodundaki kaydetme kullanılmayacaktır. Eğer bu ya da o dosyanın işlenmesi bir sebeple dönüştürücünün kodu tarafından, özel kodda değil yapılmalıysa, lütfen özel kod içinde 'imageSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dış bir özel kod olmadığı gibi dönüştürücü içinde yapılması gerektiğini bildirir. |
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Sayfada bulunan tablonun hücresini temsil eder |
| [AbsorbedRow](./absorbedrow/) | Sayfada bulunan tablonun satırını temsil eder |
| [AbsorbedTable](./absorbedtable/) | Sayfada bulunan tabloyu temsil eder |
| [ActionCollection](./actioncollection/) | Eylemlerin koleksiyonu |
| [Annotation](./annotation/) | Bir açıklama nesnesini temsil eden sınıf. |
| [AnnotationActionCollection](./annotationactioncollection/) | Açıklama eylemlerinin koleksiyonunu temsil eder. |
| [AnnotationCollection](./annotationcollection/) | Açıklama koleksiyonunu temsil eden sınıf. |
| [AnnotationFlags](./annotationflags/) | Bayraklar Açıklamanın çeşitli özelliklerini belirten bir dizi ikili bayrak. |
| [AnnotationSelector](./annotationselector/) | Bu sınıf, Visitor şablonu fikri kullanılarak açıklamaları seçmek için kullanılır. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Normal ve zengin metni renderlamak için sınıf. |
| [AppearanceDictionary](./appearancedictionary/) | Açıklamanın sayfada görsel olarak nasıl sunulacağını belirten açıklama görünüm sözlüğü. |
| [ApsLoadOptions](./apsloadoptions/) | Sınıf, aps yükleme seçeneklerini tanımlar. APS XML formatından içe aktarma seçeneği. |
| [ApsSaveOptions](./apssaveoptions/) | APS XML formatına dışa aktarma için kaydetme seçenekleri. |
| [ApsToFlowConverter](./apstoflowconverter/) | APS'den Flow'a Dönüştürme |
| [Artifact](./artifact/) | Sınıf, PDF Artifact nesnesini temsil eder. |
| [ArtifactCollection](./artifactcollection/) | Sınıf, artifact koleksiyonunu temsil eder. |
| [AutoTaggingSettings](./autotaggingsettings/) | PDF belgelerinde otomatik etiketleme işlevi için ayarları sağlar. {@link AutoTaggingSettings} sınıfı, PDF içeriğinin otomatik etiketlenmesi için seçeneklerin yapılandırılmasına izin verir. Otomatik etiketlemeyi etkinleştirme veya devre dışı bırakma, başlık tanıma stratejisini belirleme ve yazı tipi boyutlarına göre başlık seviyelerini tanımlama özelliklerini içerir. |
| [BackgroundArtifact](./backgroundartifact/) | Sınıf, arka plan artifact'ını tanımlar. Bu artifact, sayfanın arka planını ayarlamayı sağlar. |
| [BarcodeField](./barcodefield/) | Sınıf, barkod alanını temsil eder. |
| [BaseActionCollection](./baseactioncollection/) | Sınıf, sayfa/açıklama/alan etkileşimli eylemleriyle temel eylemleri kapsar |
| [BaseOperatorCollection](./baseoperatorcollection/) | Operatör koleksiyonu için temel sınıfı temsil eder. |
| [BaseParagraph](./baseparagraph/) | Sayfaya (doc.Paragraphs.Add()) eklenebilen soyut bir temel nesneyi temsil eder. |
| [BatesNArtifact](./batesnartifact/) | Sınıf, Bates Numaralandırma eserini tanımlar. |
| [BitmapInfo](./bitmapinfo/) | Piksel dizisi ve bitmap bilgisi içeren nesne. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Bitmap piksel biçimi. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Bir Bleed Mark açıklamasını temsil eder. Bleed işaretleri, sayfanın nerede kesileceğini ve kesim işaretlerinden ne kadar sapmasına izin verildiğini göstermek için basılı sayfanın köşelerine yerleştirilir. |
| [Border](./border/) | Açıklama kenarlığının özelliklerini temsil eden sınıf. |
| [BorderInfo](./borderinfo/) | Bu sınıf, grafik öğeleri için kenarı temsil eder. |
| [BorderSide](./borderside/) | Bayraklar, kenar taraflarını ikili olarak listeler. |
| [BorderStyleConverter](./borderstyleconverter/) | BorderStyleConverter sınıfını temsil eder. |
| [Brush](./brush/) | Bu sınıf soyut fırçayı temsil eder. |
| [BuildVersionInfo](./buildversioninfo/) | Bu sınıf, mevcut ürün derlemesi hakkında bilgi sağlar. |
| [ButtonField](./buttonfield/) | Sınıf, itme düğmesi alanını temsil eder. |
| [CaretAnnotation](./caretannotation/) | Caret açıklamasını temsil eden sınıf. |
| [CaretSymbolConverter](./caretsymbolconverter/) | CaretSymbolConverter sınıfını temsil eder. |
| [CdrLoadOptions](./cdrloadoptions/) | Sınıf, CDR yükleme seçeneklerini tanımlar. |
| [Cell](./cell/) | Tablonun satırındaki bir hücreyi temsil eder. |
| [Cells](./cells/) | Satırın hücre koleksiyonunu temsil eder. |
| [CgmImportOptions](./cgmimportoptions/) | Computer Graphics Metafile (CGM) formatından içe aktarma seçeneği. |
| [CgmLoadOptions](./cgmloadoptions/) | CGM dosyasını PDF belgesine yükleme/ithal etme seçeneklerini içerir. |
| [Characteristics](./characteristics/) | Açıklama özelliklerini temsil eder |
| [CharInfo](./charinfo/) | Bir karakter bilgisi nesnesini temsil eder. Karakter konumlandırma bilgisi sağlar. |
| [CharInfoCollection](./charinfocollection/) | <p> CharInfo nesneleri koleksiyonunu temsil eder. </p> <hr> <pre> Örnek, tüm karakterler üzerinde nasıl döngü yapılacağını ve karakterin nasıl alınacağını gösterir. //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Metin segmenti karakterlerinin konumlandırma bilgisine erişim sağlar. </p> |
| [CheckboxField](./checkboxfield/) | Onay kutusu alanını temsil eden sınıf. |
| [ChoiceField](./choicefield/) | Seçim alanları için temel sınıfı temsil eder. |
| [CircleAnnotation](./circleannotation/) | Daire açıklamasını temsil eden sınıf. |
| [Collection](./collection/) | Collection(12.3.5 Collections) sınıfını temsil eder. |
| [CollectionField](./collectionfield/) | Bir belge koleksiyonu şema alan sınıfını temsil eder. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Bir şema koleksiyonundaki bir alanın alt tip parametresini temsil eder. |
| [CollectionItem](./collectionitem/) | Bir koleksiyon öğesi sınıfını temsil eder. Koleksiyon öğesi, koleksiyon şeması tarafından tanımlanan verileri içerir. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Koleksiyon öğesinin değeri için bir sınıfı temsil eder. |
| [CollectionSchema](./collectionschema/) | Bir belge koleksiyonunun "Şema"sını tanımlayan bir sınıfı temsil eder. |
| [Color](./color/) | Farklı renk uzaylarında ifade edilebilen renk değeri için bir sınıfı temsil eder. |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation açıklamasını temsil eden sınıf. Property Color göz ardı edilir, bunun yerine ColorsOfCMYK rengi kullanılır. Oluşturulurken, genişlik ve yükseklik oranı açıklamanın yönünü belirler - yatay veya dikey. Sonra, annotation rectangle'ın TrimBox dışına çıkıp çıkmadığı kontrol edilir; çıkmazsa, açıklama en yakın TrimBox dışı konuma, açıklamanın yönü dikkate alınarak kaydırılır. Genişlik (yükseklik) azaltılarak açıklamanın TrimBox dışına sığması sağlanabilir. Yerleşim için alan yoksa, genişlik/yükseklik sıfıra ayarlanabilir (bu durumda açıklama sayfada bulunur ancak görüntülenmez). |
| [ColumnInfo](./columninfo/) | Bu sınıf bir sütunun bilgilerini temsil eder. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Olayları temsil eden sınıf |
| [ComboBoxField](./comboboxfield/) | Formun Combobox alanını temsil eden sınıf. |
| [ComHelper](./comhelper/) | <p> COM istemcilerine bir belgeyi Aspose.PDF'ye yüklemek için yöntemler sağlar. </p> <hr> <p> COM uygulamasında bir dosya veya akıştan bir Document nesnesine belge yüklemek için ComHelper sınıfını kullanın. Document sınıfı yeni bir belge oluşturmak için varsayılan bir yapıcı sağlar ve ayrıca bir dosya veya akıştan belge yüklemek için aşırı yüklenmiş yapıcılar sunar. .NET uygulamasında Aspose.Words kullanıyorsanız, Document yapıcılarının tümünü doğrudan kullanabilirsiniz, ancak bir COM uygulamasında Aspose.PDF kullanıyorsanız yalnızca varsayılan Document yapıcısı mevcuttur. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Ortak şekil açıklamasını temsil eden soyut sınıf. |
| [CompositingParameters](./compositingparameters/) | Mevcut grafik durumunun grafik birleştirme parametrelerini içeren bir nesneyi temsil eder. |
| [ContentsAppender](./contentsappender/) | Yalnızca APPEND modunda içerik değişiklikleri yapar. Bu mod, içeriklere bir değişiklik yapılmadan önce gereksiz ve ağır içerik ayrıştırmasını önlemeye olanak tanır. Yeni operatörleri yalnızca içeriğin sonuna ya da başına ekler. |
| [Copier](./copier/) | Nesneyi kopyalamak için sınıf. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Yazdırılan sayfanın köşelerine yerleştirilen açıklama türlerini temsil eder. |
| [CustomExplicitDestination](./customexplicitdestination/) | Özel açık hedefi temsil eder. |
| [CustomSign](./customsign/) | Belgeyi özel imzalamak için temsilci (Beta). |
| [Dash](./dash/) | Çizgi kesik desenini temsil eden sınıf. |
| [DateField](./datefield/) | Takvim görünümüne sahip tarih alanı. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Alanının (yazı tipi, metin boyutu ve renk) varsayılan görünümünü açıklar. |
| [DefaultDirectory](./defaultdirectory/) | Bazı amaçlar için varsayılan yolu belirtir. |
| [DestinationCollection](./destinationcollection/) | PDF belgesindeki tüm hedeflerin koleksiyonunu temsil eden sınıf (ad dizelerini hedeflere eşleyen bir ad ağacı (bkz. 12.3.2.3, "Named Destinations") ve (bkz. 7.7.4, "Name Dictionary")) |
| [DestinationFactory](./destinationfactory/) | DestinationFactory sınıfını temsil eder. |
| [DjvuLoadOptions](./djvuloadoptions/) | DJVU yükleme seçeneklerini açıklayan sınıf. |
| [DocMDPSignature](./docmdpsignature/) | Belge MDP (modification detection and prevention) imza türünün sınıfını temsil eder. |
| [DocSaveOptions](./docsaveoptions/) | Doc formatına dışa aktarma için kaydetme seçenekleri. |
| [Document](./document/) | PDF belgesini temsil eden sınıf. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği OptimizeResources() metodunun parametresi olarak kullanılabilir. @deprecated Bu sınıf artık kullanılmamaktadır. Lütfen com.aspose.pdf.optimization.OptimizationOptions kullanın. |
| [Document.RepairOptions](./document.repairoptions/) | PDF belgesinin onarımı için seçenekleri temsil eder. Bu sınıf, bir PDF belgesinin onarım sürecini özelleştirmenin bir yolunu sağlar. |
| [DocumentActionCollection](./documentactioncollection/) | Belge üzerindeki bazı eylemlerle gerçekleştirilen işlemleri tanımlayan sınıf. |
| [DocumentExtensions](./documentextensions/) | Document sınıfı için ek yetenekler sağlar. |
| [DocumentFactory](./documentfactory/) | Farklı tipte belgeler oluşturmayı/yüklemeyi sağlayan sınıf. |
| [DocumentInfo](./documentinfo/) | PDF belgesinin meta bilgilerini temsil eder. |
| [DocumentWeb](./documentweb/) | DocumentWeb sınıfını temsil eder. |
| [Element](./element/) | Mantıksal yapının temel öğesini temsil eden sınıf. |
| [ElementCollection](./elementcollection/) | Mantıksal yapı temel öğelerinin koleksiyonu. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Gömülü dosyalar koleksiyonunu temsil eden sınıf. |
| [EncryptedPayload](./encryptedpayload/) | Dosya tanımında şifrelenmiş yükü temsil eder. |
| [EpubLoadOptions](./epubloadoptions/) | EPUB dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini içerir. |
| [EpubSaveOptions](./epubsaveoptions/) | EPUB formatına dışa aktarma için kaydetme seçenekleri. |
| [ExcelSaveOptions](./excelsaveoptions/) | Excel formatına dışa aktarma için kaydetme seçenekleri. |
| [ExplicitDestination](./explicitdestination/) | PDF belgesindeki açık hedefler için temel sınıfı temsil eder. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | ExplicitDestinationTypeConverter sınıfını temsil eder. |
| [ExportFieldsOptions](./exportfieldsoptions/) | Form alanlarını dışa aktarma seçenekleri için temel sınıfı temsil eder. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Form alanlarını Json formatına dışa aktarma seçeneklerini temsil eder. {@link ExportFieldsOptions} sınıfından miras alır ve Json dışa aktarma için özel seçenekler ekler. |
| [ExportImportMessages](./exportimportmessages/) | Form alanlarının dışa ve içe aktarma işlemleri için çeşitli hata mesajlarını içerir. |
| [ExternalSignature](./externalsignature/) | Bir X509Certificate2 kullanarak ayrık PKCS#7Detached imzası oluşturur. USB akıllı kartları, dışa aktarılabilir özel anahtarı olmayan tokenları destekler. |
| [FdfReader](./fdfreader/) | FDF formatını okuyan sınıf. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | Acro form alanları için temel sınıf. |
| [FieldSerializationResult](./fieldserializationresult/) | Bir form alanı serileştirme işleminin sonucunu temsil eder. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Form alanı serileştirmenin durumunu temsil eder. |
| [FieldValueType](./fieldvaluetype/) | Şema koleksiyonundaki alan değerinin türünü temsil eder. |
| [FigureElement](./figureelement/) | Mantıksal yapı figürünü temsil eden sınıf. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Dosya ek açıklamasını tanımlayan sınıf. |
| [FileFontSource](./filefontsource/) | Tek bir yazı tipi dosyası kaynağını temsil eder. |
| [FileHyperlink](./filehyperlink/) | Dosya hiperlink nesnesini temsil eder. |
| [FileIconConverter](./fileiconconverter/) | FileIconConverter sınıfını temsil eder |
| [FileParams](./fileparams/) | Ek dosya parametre sözlüğünü tanımlar; bu sözlük ek dosyaya özgü ek bilgileri içermelidir. |
| [FileSelectBoxField](./fileselectboxfield/) | Dosya seçim kutusu öğesi için alan. |
| [FileSpecification](./filespecification/) | Gömülü dosyayı temsil eden sınıf. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Sayfanın içeriğini, yatay ve dikey olarak pencereye tamamen sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Gereken yatay ve dikey büyütme faktörleri farklıysa, ikisinden küçüğünü kullanarak, diğer boyutta sınırlayıcı kutuyu pencere içinde ortalar. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Sayfayı, dikey koordinat üst (top) pencerenin üst kenarına yerleştirilmiş ve sayfa içeriği, sınırlayıcı kutusunun tüm genişliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Üst (top) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Sayfayı, yatay koordinat sol (left) pencerenin sol kenarına yerleştirilmiş ve sayfa içeriği, sınırlayıcı kutusunun tüm yüksekliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Sol (left) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. |
| [FitExplicitDestination](./fitexplicitdestination/) | Sayfanın içeriğini, yatay ve dikey olarak pencereye tamamen sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Gereken yatay ve dikey büyütme faktörleri farklıysa, ikisinden küçüğünü kullanarak, diğer boyutta sayfayı pencere içinde ortalar. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Sayfayı, dikey koordinat üst (top) pencerenin üst kenarına yerleştirilmiş ve sayfa içeriği, sayfanın tüm genişliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Üst (top) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Sayfanın içeriğini, sol, alt, sağ ve üst (left, bottom, right, top) koordinatlarıyla belirtilen dikdörtgeni pencereye hem yatay hem de dikey olarak tamamen sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Gereken yatay ve dikey büyütme faktörleri farklıysa, ikisinden küçüğünü kullanarak, diğer boyutta dikdörtgeni pencere içinde ortalar. Parametrelerden herhangi biri için null değer, öngörülemeyen davranışlara yol açabilir. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Sayfayı, yatay koordinat sol (left) pencerenin sol kenarına yerleştirilmiş ve sayfa içeriği, sayfanın tüm yüksekliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Sol (left) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. |
| [FixedPrint](./fixedprint/) | Watermark (filigran) açıklamasının sabit baskı verilerini temsil eder. |
| [FloatingBox](./floatingbox/) | Pdf belgesindeki bir FloatingBox'ı temsil eder. FloatingBox özel konumlandırılmıştır. |
| [FlowConverter](./flowconverter/) | PDF belgesini Flow formatlarına (XLSX, ODS, XMLSpreedSheet2003, CSV) ve EnchanedFlow modunda DOCX'e, FlowEngine modunda ise TableAbsorber'a dönüştür. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Flow kütüphanesinden TableAbsorber'a veri aktarımı |
| [FolderFontSource](./folderfontsource/) | Yazı tipi dosyalarını içeren klasörü temsil eder. |
| [Font](./font/) | <p> Yazı tipi nesnesini temsil eder. </p> <hr> <pre> Örnek, ilk sayfada metin aramayı ve ilk arama sonucunun yazı tipini değiştirmeyi gösterir. // Open document Document doc = new Document("input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Yazı tiplerinin bir emici nesnesini temsil eder. Yazı tipleri için arama yapar ve {@code FontAbsorber.Fonts} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. |
| [FontCollection](./fontcollection/) | <p> Yazı tipi koleksiyonunu temsil eder. </p> <hr> <pre> Örnek, sayfada bildirilen tüm yazı tiplerinin gömülü olmasını gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> {@code FontCollection} sınıfı tarafından temsil edilen yazı tipi koleksiyonları çeşitli senaryolarda kullanılır. Örneğin, {@code Resources.Fonts} özelliğine sahip kaynaklarda. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | PDF/A standardı, tüm yazı tiplerinin belgeye gömülmesini gerektirir. Bu sınıf, bazı yazı tiplerinin hedef bilgisayarda bulunmadığı için gömülemeyeceği durumlar için bayraklar içerir. |
| [FontRepository](./fontrepository/) | <p> Yazı tipi araması gerçekleştirir. Sistem yüklü yazı tiplerinde ve standart PDF yazı tiplerinde arama yapar. Ayrıca özel yazı tiplerini açma işlevi sağlar. </p> <hr> <pre> Örnek, yazı tipini bulmayı ve ilk sayfanın metninin yazı tipini değiştirmeyi gösterir. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Yazı tipi kaynağı için temel bir sınıfı temsil eder. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Metne uygulanan stil bilgilerini belirtir. </p> <hr> <p> Bu enum, üye değerlerinin bir kombinasyonuna izin veren bir {@code FlagsAttribute} özniteliğine sahiptir. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag, yazı tipi alt kümeleme stratejilerini listeler. |
| [FooterArtifact](./footerartifact/) | Alt bilgi öğesini tanımlar. Sayfanın alt bilgisini ayarlamak için kullanılabilir. |
| [Form](./form/) | Form nesnesini temsil eden sınıf. |
| [Form.FlattenSettings](./form.flattensettings/) | Form düzleştirme prosedürü için ayarları tanımlayan sınıf. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Formlar imzalama bilgisi içerebilir ve imzalı ya da imzasız olabilir. Bazen görüntüleyicideki form görünümü, formun imzalı olup olmamasına bağlı olmalıdır. Bu enum, form tipinin dönüşümü sırasında imzaya ilişkin olası render modlarını listeler. |
| [FormattedFragment](./formattedfragment/) | Soyut biçimlendirilmiş parçayı temsil eder. |
| [FreeTextAnnotation](./freetextannotation/) | Sayfada doğrudan metin gösteren bir serbest metin açıklamasını temsil eder. Normal bir metin açıklamasının aksine, serbest metin açıklamasının açık ya da kapalı durumu yoktur; bir açılır pencerede gösterilmek yerine metin her zaman görünür. |
| [GoToAction](./gotoaction/) | Belirtilen bir hedefe (sayfa, konum ve büyütme faktörü) görünümü değiştiren bir gitme eylemini temsil eder. |
| [GoToRemoteAction](./gotoremoteaction/) | Mevcut dosya yerine başka bir PDF dosyasındaki bir hedefe atlayan, normal bir gitme eylemine benzer bir uzak gitme eylemini temsil eder. |
| [GoToURIAction](./gotouriaction/) | Bir URI'nın çözülmesini sağlayan bir URI eylemini temsil eder. |
| [GraphInfo](./graphinfo/) | Grafik bilgilerini temsil eder. |
| [Group](./group/) | Şeffaf görüntüleme modelinde kullanılmak üzere sayfanın sayfa grubunun özniteliklerini belirten bir grup öznitelik sınıfı. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | Sınıf, Başlık artefaktını tanımlar. Bu artefakt, sayfanın başlığını ayarlamak için kullanılabilir. |
| [HeaderFooter](./headerfooter/) | Sınıf, PDF sayfasının başlık veya altbilgisini temsil eder. |
| [Heading](./heading/) | Başlığı temsil eder. |
| [HideAction](./hideaction/) | Bir veya daha fazla ek açıklamayı ekranda gizleyen veya gösteren, gizli bayraklarını ayarlayarak veya temizleyerek bir gizleme eylemini temsil eder. |
| [HighlightAnnotation](./highlightannotation/) | Belgedeki bir metin aralığını vurgulayan bir vurgulama ek açıklamasını temsil eder. |
| [HtmlFragment](./htmlfragment/) | HTML parçacığını temsil eder. |
| [HtmlLoadOptions](./htmlloadoptions/) | HTML dosyasının PDF belgesine yüklenmesi/ithal edilmesi için seçenekleri temsil eder. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binary Flag, sayfaların boyutlarını ve düzenlerini belirleyen diğer seçeneklerle birlikte bayrakları tanımlar. |
| [HtmlSaveOptions](./htmlsaveoptions/) | HTML formatına dışa aktarma için kaydetme seçenekleri |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Bu enum, dönüşüm sırasında olası antialiasing önlemlerini tanımlar |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Bu sınıf, PDF'ten HTML formatına dönüşüm sırasında CSS'in özel kaydedilmesiyle ilgili veri kümesini temsil eder |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Bu özelliğe, PDF'ten HTML'e dönüşüm sırasında oluşturulan bir CSS parçasının işlenmesini ve/veya kaydedilmesini uygulayan özel bir strateji atayabilirsiniz. Bu durumda işleme (akışa veya diske kaydetme gibi) o özel kod içinde yapılmalıdır. |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Bu özelliğe, oluşturulan HTML belgesinde başvurulan CSS'in URL'sinin oluşturulmasını uygulayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Örneğin, HTML'de "otherPage.ASPX?CssID=zjjkklj" şeklinde bir CSS referansı yapmak isterseniz, bu özel strateji "otherPage.ASPX?CssID=zjjkklj" döndürmelidir. |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | İlgili CSS'in istenen URL'sini (veya URL şablonunu) elde etmeyi amaçlayan dönüştürücünün özel koda yaptığı isteğe ilişkin veri kümesini temsil eder |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Bu enum, kodlama mantığını ayarlayan kuralları tanımlar |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Kayıtlı PDF'de başvurulan yazı tiplerinin kaydedilmesinde kullanılabilecek modları listeler. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Bu sınıf, PDF'ten HTML'e dönüşüm sırasında harici kaynak görüntü dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | PDF'ten HTML'e dönüşüm sırasında harici kaynak olarak kaydedilebilecek olası görüntü dosyası türlerini listeler. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Bazen oluşturulan HTML için belirli gereksinimler bulunur. Bu enum, PDF'ten HTML'e dönüşüm sırasında bu özel gereksinimlere uyacak HTML hazırlama modlarını tanımlar. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | HtmlSaveOptions sınıfının SplitToPages özelliği etkinse, PDF'ten HTML'e dönüşüm sırasında birden fazla HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu sınıf, PDF'ten HTML'e dönüşüm sırasında bir HTML sayfasının işaretlemesinin özel olarak kaydedilmesiyle ilgili veri kümesini temsil eder. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Dönüşüm sonucu bir veya birkaç HTML sayfası (görüntüler veya yazı tipleri gibi harici dosyalara da başvurabilir) içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan HTML sayfasının (HTML'in kendisinin) işlenmesini uygulayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Bu durumda işleme (akışa veya diske kaydetme gibi) o özel kod içinde yapılabilir. Bu durumda, HTML sayfasının işaretlemesinin kaydedilmesi için gerekli tüm eylemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü dönüştürücünün kodundaki kaydetme kullanılmayacaktır. Eğer bu veya o durum için işleme bir sebeple dönüştürücünün kodu tarafından, özel kod yerine yapılması gerekiyorsa, lütfen özel kod içinde 'htmlSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların, dışsal bir özel kaydetme kodu yokmuş gibi, dönüştürücü içinde yapılması gerektiğini bildirir. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Bir görüntünün ebeveyninin olabileceği olası tipleri listeler; Görüntü, HTML sayfasına veya SVG ebeveyn görüntüsüne ait olabilir. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Bu enum, HTML içinde başvurulan dosyaların gömülme olası modlarını listeler. Başvurulan dosyaların (HTML, Yazı tipleri, Görüntüler, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak oluşturulup oluşturulmayacağını kontrol etmeyi sağlar. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | Dönüştürülmüş PDF raster görüntüler (.png, *.jpeg vb.) içerebilir. Bu enum, raster görüntülerin PDF'ten HTML'e dönüşüm sırasında nasıl işleneceğini tanımlayan yöntemleri belirler. |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | Bu özelliğe, PDF'den çıkarılan ve PDF'den HTML'ye dönüşüm sırasında harici kaynak olarak kaydedilmesi gereken dış kaynağın (Yazı tipi veya Görüntü) işlenmesini uygulayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Böyle bir durumda işleme (akışa veya diske kaydetme gibi) bu özel kod içinde yapılabilir ve bu özel kod, daha sonra oluşturulan HTML'ye, o görüntü kaynağına ait orijinal varsayılan yol yerine dahil edilecek yolu (veya tırnak işareti olmayan başka bir dizeyi) döndürmelidir. Bu durumda görüntünün kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda yapılmalıdır, çünkü dönüştürücünün kodunda sonucun kaydedilmesi kullanılmayacaktır. Eğer bu veya o dosyanın işlenmesi bir sebeple dönüştürücünün kodu tarafından, özel kod yerine yapılması gerekiyorsa, lütfen özel kod içinde 'CustomProcessingCancelled' bayrağını 'resourceSavingInfo' parametresinin değişkenine ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların, dış bir özel kod yokmuş gibi, dönüştürücü içinde yapılması gerektiğini bildirir. |
| [Hyperlink](./hyperlink/) | Soyut bir köprüyi temsil eder. |
| [IconFit](./iconfit/) | Widget açıklamasının simgesinin açıklama dikdörtgeni içinde nasıl görüntüleneceğini açıklar. |
| [Id](./id/) | <p> Dosya tanımlayıcı yapısını temsil eder. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Görüntüyü temsil eder. |
| [ImageDeleteAction](./imagedeleteaction/) | Görüntü nesnesi koleksiyondan kaldırıldığında görüntü nesnesiyle gerçekleştirilen eylem. Görüntü nesnesi kaldırıldığında |
| [ImagePlacement](./imageplacement/) | <p> Pdf belge sayfasına yerleştirilen bir görüntünün özelliklerini temsil eder. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Bir görüntü bir sayfaya yerleştirildiğinde, {@code Resources} içinde tanımlanan fiziksel boyutlardan farklı boyutlara sahip olabilir. {@code ImagePlacement} nesnesi, boyutlar, çözünürlük vb. gibi bu tür bilgileri sağlamak için tasarlanmıştır. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Bir görüntü yerleştirme nesnesi emici nesneyi temsil eder. Görüntü kullanımını arar ve {@code ImagePlacementAbsorber.ImagePlacements} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasındaki görüntüleri nasıl bulacağını ve görüntü yerleştirme özelliklerini nasıl alacağını gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber} nesnesi temel olarak görüntü arama senaryosunda kullanılır. Arama tamamlandığında, oluşumlar {@code ImagePlacement} nesneleriyle temsil edilir ve bu nesneler {@code ImagePlacementAbsorber.ImagePlacements} koleksiyonunda bulunur. {@code ImagePlacement} nesnesi görüntü yerleştirme özelliklerine erişim sağlar: boyutlar, çözünürlük vb. </p> Görüntünün pozitif dönüşü saat yönünün tersidir, sayfa için ise saat yönündedir. Burada, görüntü dönüş açısını temsil etmemiz gerekiyor, bu yüzden sayfa açısını görüntü açısından çıkarıyoruz. |
| [ImagePlacementCollection](./imageplacementcollection/) | Bir görüntü yerleştirme koleksiyonunu temsil eder |
| [ImageStamp](./imagestamp/) | Bir grafik damgasını temsil eder. |
| [ImageType](./imagetype/) | Görüntü formatı türlerini temsil eder. |
| [ImportDataAction](./importdataaction/) | Bir import-data eylemi çağrıldığında, Forms Data Format (FDF) verileri belirtilen bir dosyadan belgenin etkileşimli formuna aktarılır. |
| [ImportFieldsOptions](./importfieldsoptions/) | Form alanlarını içe aktarma seçenekleri için temel sınıfı temsil eder. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Form alanlarını Json formatına içe aktarma seçeneklerini temsil eder. {@code ImportFieldsOptions} sınıfından miras alır ve Json içe aktarımı için özel seçenekler ekler. |
| [ImportOptions](./importoptions/) | ImportOptions türü, bireysel içe aktarma seçenekleri üzerinde bir soyutlama düzeyi tutar. |
| [InkAnnotation](./inkannotation/) | Bir veya daha fazla ayrı yoldan oluşan serbest el "karalama"yı temsil eder. |
| [InternalHelper](./internalhelper/) | İç sınıf |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | Form türüyle yapılan bir işlem geçerli olmadığında atılan istisna. |
| [JavascriptAction](./javascriptaction/) | JavaScript eylemini temsil eden sınıf. |
| [JavaScriptCollection](./javascriptcollection/) | Bu sınıf JavaScript koleksiyonunu temsil eder. |
| [LatexFragment](./latexfragment/) | TeX parçacığını temsil eder. @deprecated Lütfen bunun yerine TeXFragment kullanın |
| [LatexLoadOptions](./latexloadoptions/) | PDF belgesine TeX dosyası yükleme/ithal etme seçeneklerini temsil eder. @deprecated Bunun yerine TeXLoadOptions kullanın. |
| [LaTeXSaveOptions](./latexsaveoptions/) | TeX formatına dışa aktarma için kaydetme seçenekleri. @deprecated Bunun yerine TeXSaveOptions kullanın |
| [LaunchAction](./launchaction/) | Bir uygulamayı başlatan veya bir belgeyi açan ya da yazdıran başlatma eylemini temsil eder. |
| [Layer](./layer/) | PDF sayfası içinde bir katmanı temsil eder. |
| [LevelFormat](./levelformat/) | İçindekiler tablosunun formatını temsil eder. |
| [License](./license/) | Bileşeni lisanslamak için yöntemler sağlar. Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Bir lisans bilgisini temsil eder. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Hafif operatör koleksiyonu. Alt içerik akışı ekli olmadığında, yalnızca operatör koleksiyonunun gerektiği senaryolarda kullanılmak üzere tasarlanmıştır. |
| [LineAnnotation](./lineannotation/) | Çizgi açıklamasını temsil eden sınıf. |
| [LineEndingConverter](./lineendingconverter/) | LineEndingConverter sınıfını temsil eder |
| [LineEndingsDrawer](./lineendingsdrawer/) | Açıklamalar için çizgi uçlarını çizer. Yalnızca dahili kullanım için iç sınıf. |
| [LinkAnnotation](./linkannotation/) | Belge içinde başka bir konuma bir hiper metin bağlantısını veya gerçekleştirilecek bir eylemi temsil eder. |
| [ListBoxField](./listboxfield/) | Sınıf, ListBox alanını temsil eder. |
| [LoadOptions](./loadoptions/) | LoadOptions türü, bireysel yükleme seçenekleri üzerinde soyutlama seviyesini tutar. |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Dönüşüm sırasında kenar boşlukları alanının kullanım modunu temsil eder (HTML, EPUB vb. gibi) ve kenar boşluklarının kullanımına ilişkin içe aktarılan format talimatlarının işlenmesini tanımlar. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ATTENTION! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB vb. gibi formatlar genellikle akış tasarımına sahiptir, bu yüzden gerekli sayfa boyutuna sığdırmaya izin verir. Ancak bazen içerik, yatay konumları veya boyutu belirttiği için içeriği gerekli sayfa boyutuna yerleştirmeye izin vermez. Böyle bir durumda ne yapılması gerektiğini tanımlayabiliriz (ör. içeriğin boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Kaynağın özel yüklenmesinin sonucu |
| [LocaleOptions](./localeoptions/) | LocaleOptions türü, Aspose.PDF için yerel ayar yapılandırmasını belirtir. |
| [LocalHyperlink](./localhyperlink/) | Yerel hiperlink nesnesini temsil eder. |
| [MarginInfo](./margininfo/) | Bu sınıf, farklı nesneler için bir kenar boşluğunu temsil eder. |
| [MarkupAnnotation](./markupannotation/) | İşaretleme açıklamasını temsil eden soyut sınıf. |
| [MarkupParagraph](./markupparagraph/) | Bir paragrafı temsil eder. |
| [MarkupSection](./markupsection/) | Bir işaretleme bölümünü temsil eder - metin içeren ve görsel olarak diğer metin bloklarından ayrılabilen bir sayfanın dikdörtgen bölgesi. |
| [Matrix](./matrix/) | Sınıf, dönüşüm matrisini temsil eder. |
| [Matrix3D](./matrix3d/) | Sınıf, dönüşüm matrisini temsil eder. |
| [MdLoadOptions](./mdloadoptions/) | Markdown formatı dönüşümü için yükleme seçenekleri. |
| [Measure](./measure/) | Ölçüm koordinat sistemini tanımlayan sınıf. |
| [Measure.NumberFormat](./measure.numberformat/) | Ölçüm için sayı formatı. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Sayı formatları listesini temsil eder. |
| [MediaClip](./mediaclip/) | Sınıf, sunumun medya klip nesnesini tanımlar. |
| [MediaClipData](./mediaclipdata/) | Sınıf, medya klip verisini tanımlar. |
| [MediaClipSection](./mediaclipsection/) | Bu sınıf, Medya klip bölümünü açıklar. |
| [MediaRendition](./mediarendition/) | Sınıf, medya sunumunu tanımlar. |
| [MemoryCleaner](./memorycleaner/) | MemoryCleaner sınıfını temsil eder |
| [MemoryExtender](./memoryextender/) | MemoryExtender sınıfını temsil eder. Sınırlı yığın belleğine sahip bir sistemde büyük dosyalar kullanılırken, geçici takas belleği olarak disk alanı kullanılabilir. |
| [MemoryFontSource](./memoryfontsource/) | Tek bir yazı tipi dosyası kaynağını temsil eder. |
| [Metadata](./metadata/) | XMP meta veri akışına erişim sağlar. |
| [Metered](./metered/) | <p> Ölçülen anahtarı ayarlamak için yöntemler sağlar. </p> <hr> Bu örnekte, ölçülen genel ve özel anahtarın ayarlanması denenecek <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | .mht dosyasının pdf belgesine yüklenmesi/içe aktarılması seçeneklerini temsil eder. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Xml formatına dışa aktarma için kaydetme seçenekleri |
| [MovieAnnotation](./movieannotation/) | Bilgisayar ekranında ve hoparlörler aracılığıyla sunulacak animasyonlu grafikler ve ses içeren bir film ek açıklamasını temsil eder. Ek açıklama etkinleştirildiğinde film oynatılır. |
| [NamedAction](./namedaction/) | PDF görüntüleyici uygulamalarının desteklemesi beklenen adlandırılmış eylemleri temsil eder. |
| [NamedDestination](./nameddestination/) | Açık sözdizimiyle doğrudan tanımlanmak yerine, bir hedef isim nesnesi veya bayt dizisi aracılığıyla dolaylı olarak referans verilebilir. |
| [Note](./note/) | Bu sınıf, jeneratör paragraf notunu temsil eder. |
| [NumberField](./numberfield/) | Belirtilen geçerli karakterlere sahip Metin Alanı @see TextBoxField |
| [NumberTree](./numbertree/) | PDF dosyasının Sayı ağacı yapısını temsil eden sınıf. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | İmzalama sürecinde kullanılan ocsp ayarlarını temsil eder. |
| [OfdLoadOptions](./ofdloadoptions/) | OFD formatı için yükleme seçenekleri. |
| [Operator](./operator/) | Operatörü temsil eden soyut sınıf. |
| [OperatorCollection](./operatorcollection/) | Sınıf, operatörlerin koleksiyonunu temsil eder |
| [OperatorSelector](./operatorselector/) | Bu sınıf, Visitor şablon fikri kullanılarak operatörleri seçmek için kullanılır. |
| [Opi](./opi/) | Open Prepress Interface (OPI), yüksek çözünürlüklü görüntüler için düşük çözünürlüklü yer tutucular veya vekiller oluşturma mekanizmasını temsil eder. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Daha standart kapasite içerebilen bir MemoryStream tanımlar |
| [Option](./option/) | Sınıf, seçim alanının seçeneğini temsil eder. |
| [OptionCollection](./optioncollection/) | Seçim alanının seçenek koleksiyonunu temsil eden sınıf. |
| [OutlineCollection](./outlinecollection/) | Belge taslak hiyerarşisini temsil eder. |
| [OutlineItemCollection](./outlineitemcollection/) | PDF belgesinin taslak hiyerarşisindeki taslak girişini temsil eder. |
| [Outlines](./outlines/) | Sınıf, taslakların koleksiyonunu tanımlar. |
| [OutputIntent](./outputintent/) | PDF belgesinin renk özelliklerini, belgenin basılacağı hedef çıktı cihazı veya üretim ortamının özellikleriyle eşleştiren bir çıktı niyetini temsil eder. |
| [OutputIntents](./outputintents/) | {@link OutputIntent} koleksiyonunu temsil eder. |
| [Page](./page/) | PDF belgesinin sayfasını temsil eden sınıf. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Üstbilgi ve altbilgi özelleştirme prosedürü. |
| [PageActionCollection](./pageactioncollection/) | Bu sınıf sayfa eylemlerini tanımlar |
| [PageCollection](./pagecollection/) | PDF belge sayfalarının koleksiyonu. |
| [PageExtensions](./pageextensions/) | Page sınıfı için ek yetenekler sağlar. |
| [PageInfo](./pageinfo/) | pdf oluşturucu için sayfa bilgilerini temsil eder. |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF belgesinde bir Sayfa Bilgisi ek açıklamasını temsil eder. Bu ek açıklama dosya adını, sayfa numarasını ve ek açıklamanın oluşturulma tarih ve saatini içerir. Bu sınıf, PDF belgesindeki belirli bir sayfaya meta verileri eklemek için öncelikle kullanılır; bu, izleme ve referans amaçları için faydalı olabilir. Örneğin, baskı sürecinde sayfaları işaretlemek veya belgeyi görüntülerken sayfa hakkında ek bilgi sağlamak için kullanılabilir. |
| [PageLabel](./pagelabel/) | Sayfa Etiketi aralığını temsil eden sınıf. |
| [PageLabelCollection](./pagelabelcollection/) | Sayfa etiketi koleksiyonunu temsil eden sınıf. |
| [PageMarkup](./pagemarkup/) | {@code MarkupSection} ve {@code MarkupParagraph} koleksiyonlarıyla temsil edilen sayfa işaretlemesi. |
| [PageNumberStamp](./pagenumberstamp/) | Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır. |
| [PageSize](./pagesize/) | PDF belgesindeki sayfa boyutunu temsil eden sınıf. |
| [PaginationArtifact](./paginationartifact/) | Bir belgede sayfalama öğeleri için soyut temel sınıfı temsil eder. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Bölümler ve paragraflar gibi sayfa yapı nesnelerinin bir absorber nesnesini temsil eder. Metin bölümleri ve paragrafları arar ve metin koordinat uzayında tanımlayan dikdörtgenler ve çokgenlere erişim sağlar. Ayrıca metin segmentleri araması yapar ve yapı öğeleriyle gruplanmış {@code TextFragments} koleksiyonları aracılığıyla arama sonuçlarına erişim sunar. </p> Örnek, ilk PDF belge sayfasındaki her paragrafın ilk metin segmentini bulup vurgulamayı gösterir. <p> // Belgeyi aç Document doc = new Document("input.pdf"); // ParagraphAbsorber nesnesi oluştur ParagraphAbsorber absorber = new ParagraphAbsorber(); // İlk sayfa için absorber'ı kabul et absorber.visit(doc.getPages.get_Item(1)); // İlk sayfanın işaretleme nesnesini al PageMarkup markup = absorber.getPageMarkups().get(0); // Sayfa metninin yapı öğeleri arasında döngü yaparak her paragrafın ilk metin fragmentini bul for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Metin özelliklerini güncelle fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Belgeyi kaydet doc.save(GetOutputPath("output.pdf")); </p> <hr> Arama tamamlandığında {@code ParagraphAbsorber.PageMarkups} koleksiyonu {@code MarkupSection} ve {@code MarkupParagraph} koleksiyonlarıyla sayfa yapısını temsil eden {@code PageMarkup} nesnelerini içerir. {@code TextFragment} nesnesi arama gerçekleşen metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | {@link ParagraphAbsorber} için seçenekleri temsil eder. |
| [Paragraphs](./paragraphs/) | Bu sınıf paragraf koleksiyonunu temsil eder. |
| [PasswordBoxField](./passwordboxfield/) | Parola girişi için metin alanını tanımlayan sınıf. |
| [PclLoadOptions](./pclloadoptions/) | PCL dosyasını pdf belgesine yükleme (import) seçeneklerini temsil eder. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Dönüşüm için kullanılabilecek dönüşüm motorlarını listeler. |
| [PDF3DAnnotation](./pdf3dannotation/) | PDF3DAnnotation sınıfı. Bu sınıf miras alınamaz. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | PDF3DArtwork sınıfı. |
| [PDF3DContent](./pdf3dcontent/) | PDF3DContent sınıfı. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | PDF3DCrossSection sınıfı. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | PDF3DCrossSectionArray sınıfı. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | PDF3DCuttingPlaneOrientation sınıfı. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | PDF3DLightingScheme sınıfı. |
| [PDF3DRenderMode](./pdf3drendermode/) | PDF3DRenderMode sınıfı. |
| [PDF3DStream](./pdf3dstream/) | PDF3DStream sınıfı. |
| [PDF3DView](./pdf3dview/) | PDF3DView sınıfı. |
| [PDF3DViewArray](./pdf3dviewarray/) | Sınıf PDF3DViewArray. |
| [PdfAction](./pdfaction/) | PDF belgesindeki Action'ı temsil eder |
| [PdfActionCollection](./pdfactioncollection/) | Sınıf eylemlerin listesini tanımlar. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Bu sınıf, TrueType sembolik yazı tipinin birden fazla kodlamaya sahip olduğu durumlarda kodlama verilerinin kopyalanma sürecini ayarlamak için kullanılabilecek kuralları açıklar. Bazı PDF belgeleri PDF/A formatına dönüştürüldükten sonra "Sembolik TrueType yazı tipinin cmap'inde birden fazla kodlama" hatasını verebilir. Bu hatanın nedeni nedir? Tüm TrueType sembolik yazı tiplerinin dahili verilerinde özel bir "cmap" tablosu bulunur. Bu tablo karakter kodlarını glif indekslerine eşler. Ve bu tablo, kullanılan kodlamaları tanımlayan farklı kodlama alt tablolarını içerebilir. cmap tabloları hakkında ileri düzey bilgiyi https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html adresinde görebilirsiniz. Genellikle cmap tablosu birden fazla kodlama alt tablosu içerir, ancak PDF/A standardı, bu yazı tipi için PDF/A belgesinde yalnızca bir kodlama alt tablosunun bırakılmasını ya da bu yazı tipinin alt tabloları arasında bir (3,0) kodlama alt tablosunun bulunmasını şart koşar. Ve burada kilit soru - başka alt tablolardan hangi veriler alınarak hedef kodlama tablosu (3,0)'a kopyalanmalıdır? Çoğu yazı tipinde, her kodlama alt tablosunun diğer alt tabloyla tamamen tutarlı olduğu 'iyi yapılandırılmış' cmap tabloları bulunur. Ancak bazı yazı tiplerinde çakışmalar içeren cmap tabloları vardır - örneğin bir alt tablo unicode 100 için glif indeksi 100'ü, diğer alt tablo ise aynı unicode 100 için glif indeksi 200'ü içerir. Bu sorunları çözmek için özel bir strateji gereklidir. Varsayılan olarak aşağıdaki strateji kullanılır: mac alt tablosu (1,0) aranır. Bu tablo bulunursa, yalnızca bu veri hedef tablo (3,0)'ı doldurmak için kullanılır. Mac alt tablosu bulunamazsa, (3,0) dışındaki tüm alt tablolar döngüye alınır ve verileri hedef (3,0) alt tablosuna kopyalamak için kullanılır. Ayrıca her unicode (unicode, glif indeksi) eşlemesi, hedef tablo şu anda bu unicode'ı içermiyorsa hedef tabloya kopyalanır. Dolayısıyla, örneğin ilk alt tablo unicode 100 için glif indeksi 100'ü, sonraki alt tablo aynı unicode 100 için glif indeksi 200'ü içeriyorsa, yalnızca ilk alt tablodan (unicode=100, glif indeksi = 100) gelen veri kopyalanır. Bu yüzden her önceki alt tablo, sonraki alt tabloya göre öncelik kazanır. Bu sınıfın { PdfASymbolicFontEncodingStrategy} özellikleri, varsayılan davranışı ayarlamaya yardımcı olur. Eğer {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) özelliği { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} tipinde ayarlanmışsa, ilgili alt tablo mac alt tablosu (1,0)'a göre öncelikli olarak kullanılacaktır. Bu durumda {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} enumarasyonundaki 'MacTable' değeri bir anlam ifade etmez, çünkü varsayılan olarak kullanılacak aynı mac alt tablosuna (1,0) işaret eder. {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) özelliği, herhangi bir alt tablo için tüm öncelikleri göz ardı eder. Bu özellik ayarlanırsa, yalnızca bildirilen kuyruktaki alt tablolar belirtilen sırayla kullanılacaktır. Belirtilen alt tablolar bulunamazsa, tüm alt tabloların varsayılan iterasyonu ve yukarıda açıklanan kopyalama stratejisi kullanılacaktır. { PdfASymbolicFontEncodingStrategy.QueueItem} nesnesi kullanılan kodlama alt tablosunu belirtir. Bu alt tablo, üyeler (PlatformID, PlatformSpecificId) kombinasyonu ile ya da { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} enumarasyonu aracılığıyla ayarlanabilir. Yazı tipinde (3,0) alt tablosu bulunmadığında, PDF/A uyumluluğunu sürdürmek için başka bir alt tablo kullanılacaktır. Kullanılacak alt tablonun seçimi, daha önce açıklanan aynı kurallar çerçevesinde yapılır; böylece {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) ve {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) özellikleri sonuç alt tabloyu belirlemek için kullanılır ve yazı tipi istenen alt tablo(ları)na sahip değilse, mevcut herhangi bir alt tablo kullanılacaktır. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Kodlama alt tablosunu belirtir. Her kodlama alt tablosu, (PlatformID, PlatformSpecificID) parametrelerinin benzersiz bir kombinasyonuna sahiptir. {@code CMapEncodingTableType} enum'ı ve {@code CMapEncodingTable} özelliği, gerekli kodlama alt tablosunu ayarlamayı kolaylaştırmak için uygulanmıştır. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Bazı bilinen kodlama alt tablolarının kümesini bildirir. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | PDF belgesini dönüştürmek için seçenekler kümesini temsil eder. |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Bu sınıf, kaynak PDF belgesi PDF spesifikasyonuna uymadığında PDF/A dönüşümünü kontrol etmek için bayraklar tutar. Bu sınıfın bayrakları kullanıldığında performans düşer ancak kaynak PDF belgesi normal yolla PDF/A formatına dönüştürülemediğinde gereklidir. Varsayılan olarak tüm bayraklar false olarak ayarlanmıştır. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Bazı PDF belgelerinde, Özel Kullanım Alanı (PUA)'na ait özel unicode sembolleri bulunur; https://en.wikipedia.org/wiki/Private_Use_Areas adresindeki açıklamaya bakın. Bu semboller, "Text is mapped to Unicode Private Use Area but no ActualText entry is present" gibi PDF/A uyum hatalarına neden olur. Bu enum, PUA sembollerini ele almak için kullanılabilecek stratejileri bildirir. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Bazı belgeler PDF/A formatına dönüştürüldükten sonra büyük boyuta sahiptir. Bu belgeler için dosya boyutunu azaltmak, yazı tipi kaldırma stratejisini tanımlamayı gerektirir. Bu enum, yazı tiplerinin kullanımını optimize etmek için kullanılabilecek stratejileri bildirir. Bu enumdaki her strateji yalnızca {@code OptimizeFileSize} bayrağı ayarlandığında anlamlıdır. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Belge metin segmentlerini hizalamak için kullanılan stratejileri açıklar. Şu anda yalnızca segmentleri orijinal sınırlara geri getiren strateji desteklenmektedir. Gelecekte başka stratejiler eklenebilir. |
| [PdfPageStamp](./pdfpagestamp/) | Sınıf, PDF sayfasını damga olarak kullanan damgayı temsil eder. |
| [PdfSaveOptions](./pdfsaveoptions/) | Pdf formatına dışa aktarma için kaydetme seçenekleri. |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | PdfXml formatı için yükleme seçenekleri. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | PdfXml formatı için kaydetme seçenekleri. |
| [Permissions](./permissions/) | Binary Flag Bu enum, bir pdf için kullanıcının izinlerini temsil eder. |
| [PKCS1](./pkcs1/) | PKCS#1 standardına ilişkin imza nesnesini temsil eder. İmzalama için RSA şifreleme algoritması ve SHA-1 özet yöntemi kullanılır. |
| [PKCS7](./pkcs7/) | PKCS#7 spesifikasyonuna (Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5) uygun PKCS#7 nesnesini temsil eder. Belgenin bayt aralığının SHA1 özeti, PKCS#7 SignedData alanına kapsüllenmiştir. |
| [PKCS7Detached](./pkcs7detached/) | PKCS#7 spesifikasyonuna (Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5) uygun PKCS#7 nesnesini temsil eder. Belgenin bayt aralığının orijinal imzalı mesaj özeti, normal PKCS#7 SignedData alanı olarak dahil edilir. PKCS#7 SignedData alanına hiçbir veri kapsüllenmez. |
| [Point](./point/) | Kesirli koordinatlara sahip bir noktayı temsil eder. |
| [Point3D](./point3d/) | Kesirli koordinatlara sahip bir noktayı temsil eder. |
| [PolyAnnotation](./polyannotation/) | Poli-annotasyonlar için soyut temel sınıf. |
| [PolygonAnnotation](./polygonannotation/) | Poligon ek açıklamasını temsil eden sınıf. |
| [PolylineAnnotation](./polylineannotation/) | İlk ve son köşenin dolaylı olarak bağlanmadığı, poligon benzeri bir çoklu çizgi ek açıklamasını temsil eder. |
| [PopupAnnotation](./popupannotation/) | Metni giriş ve düzenleme için bir açılır pencerede gösteren açılır ek açıklamayı temsil eder. |
| [Position](./position/) | Bir konum nesnesini temsil eder. |
| [PptxSaveOptions](./pptxsaveoptions/) | SVG formatına dışa aktarma için kaydetme seçenekleri. |
| [PrintController](./printcontroller/) | Yazdırma denetleyicisini temsil eder. |
| [PrintDuplex](./printduplex/) | Yazdırma iletişim kutusundan dosyayı yazdırırken kullanılacak kağıt işleme seçeneği.. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Yazıcı işareti ek açıklamasını temsil eden soyut sınıf. |
| [PrinterMarksKind](./printermarkskind/) | Belirtilen belgeye eklenecek yazıcı işaretlerinin türlerini belirtir. Bu enum, üye değerlerinin bit düzeyinde birleştirilmesine izin veren bir {@link FlagsAttribute} özniteliğine sahiptir. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | {@link PrinterMarksKind} enumu için uzantı metodları sağlar. |
| [PrintScaling](./printscaling/) | Bu belge için bir yazdırma iletişim kutusu görüntülendiğinde seçilecek sayfa ölçekleme seçeneği. |
| [ProgressEventType](./progresseventtype/) | Bu enum, dönüşüm sırasında meydana gelebilecek olası ilerleme olayı türlerini tanımlar. |
| [PsLoadOptions](./psloadoptions/) | .mht dosyasının pdf belgesine yüklenmesi/içe aktarılması seçeneklerini temsil eder. |
| [PsSaveOptions](./pssaveoptions/) | PS (PostScript) veya EPS formatına dışa aktarma için kaydetme seçenekleri. |
| [RadioButtonField](./radiobuttonfield/) | Radyo düğmesi alanını temsil eden sınıf. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Radyo Düğmesi alanının öğesini temsil eden sınıf. |
| [Rectangle](./rectangle/) | Dikdörtgeni temsil eden sınıf. |
| [Redaction](./redaction/) | Yalnızca dahili kullanım için @author User |
| [RedactionAnnotation](./redactionannotation/) | Redact açıklamasını temsil eder. |
| [RegexManager](./regexmanager/) | Yapılandırılabilir zaman aşımı ayarlarıyla düzenli ifade işlemleri için bir sarmalayıcı sağlar. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Kayıt İşareti açıklamasını temsil eder. Kayıt işaretleri, baskı sürecinde renklerin doğru hizalanmasını sağlamak için baskı plakalarına veya ekranlara eklenen sembollerdir. |
| [RenderingOptions](./renderingoptions/) | Renderleme seçeneklerini temsil eder. |
| [RenderModeType](./rendermodetype/) | RenderModeType enumu: render modu türlerinin kümesi |
| [Rendition](./rendition/) | RendtionAnnotation'ın sunum nesnesini tanımlayan sınıf. |
| [RenditionAction](./renditionaction/) | Multimedya içeriğinin oynatılmasını kontrol eden bir sunum eylemi. |
| [RenditionOperation](./renditionoperation/) | Eylem tetiklendiğinde gerçekleştirilecek işlem. |
| [RenditionType](./renditiontype/) | Bu enum, Rendition'ın olası türlerini tanımlar. |
| [Resources](./resources/) | Sayfa kaynaklarını temsil eden sınıf. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Bazı değerlerle ExtGStates'i temsil eder. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | RGB'den cihaz gri renk uzayına dönüşüm stratejisini temsil eder. |
| [RichMediaAnnotation](./richmediaannotation/) | PDF belgesine video/audio verisi gömmeye izin veren RichMediaAnnotation'ı tanımlayan sınıf. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Açıklamayı etkinleştiren olay. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Multimedyanın türü. |
| [RichTextBoxField](./richtextboxfield/) | Zengin metin düzenleyici bileşenini tanımlayan sınıf. |
| [RichTextFontStyles](./richtextfontstyles/) | RichText içinde metin parçacıklarını biçimlendirme seçenekleri. |
| [RootElement](./rootelement/) | Kök yapı öğesi. |
| [Row](./row/) | Tablonun bir satırını temsil eder. |
| [Rows](./rows/) | Tablonun satır koleksiyonunu temsil eder. |
| [RtfLoadOptions](./rtfloadoptions/) | RTF formatı için yükleme seçenekleri. |
| [SaveOptions](./saveoptions/) | SaveOptions türü, bireysel kaydetme seçenekleri üzerinde soyutlama seviyesini tutar. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Bu sınıfın örneği, bazı sonuç belgelerinde çizilebilen kenar hakkında bilgi temsil eder. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Kenara ait bir parçanın (üst, alt, sol yan veya sağ yan) bilgisini temsil eder. |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Bu sınıfın örneği, bazı sonuç belgelerinde çizilebilen sayfa kenar boşluğu hakkında bilgi temsil eder. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Kenar boşluğunun bir parçasının (üst, alt, sol yan veya sağ yan) bilgisini temsil eder. |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Bu sınıf, PDF'nin başka bir formata (ör. HTML) dönüştürülmesi sırasında gerçekleşen dış kaynak dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder. |
| [ScalingMode](./scalingmode/) | Kullanılması gereken ölçekleme türü. |
| [ScalingReason](./scalingreason/) | İkonun dikdörtgen içinde ölçeklendirileceği koşullar. |
| [ScreenAnnotation](./screenannotation/) | Sayfanın medya kliplerinin oynatılabileceği bir bölgeyi belirten ekran açıklaması. |
| [SelectorRendition](./selectorrendition/) | Sınıf, seçici sunumunu açıklar. |
| [Signature](./signature/) | PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. İmzalar, imza nesnelerinin değerlerine sahip alanlardır; sonuncusu belge geçerliliğini doğrulamak için kullanılan verileri içerir. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | İmza özel görünüm nesnesini temsil eden soyut bir sınıf. |
| [SignatureField](./signaturefield/) | İmza form alanını temsil eder. |
| [SignHash](./signhash/) | Belge karmasını özel imzalamak için temsilci (Beta). |
| [SoundAnnotation](./soundannotation/) | Bilgisayar mikrofonundan kaydedilen veya bir dosyadan içe aktarılan sesi içeren ses açıklamasını temsil eder. |
| [SoundData](./sounddata/) | Açıklama etkinleştirildiğinde çalınacak sesi tanımlayan ses verisini temsil eder. |
| [SoundEncoding](./soundencoding/) | Örnek veri için kodlama biçimi. |
| [SoundIcon](./soundicon/) | Açıklamayı görüntülerken kullanılacak ikonları listeler. |
| [SoundIconConverter](./soundiconconverter/) | SoundIconConverter sınıfını temsil eder. |
| [SoundSampleData](./soundsampledata/) | Bir ses nesnesine özgü ek girişleri temsil eder (Bölüm 9.2 PDF1-7). |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Ses örnek verileri için kodlama biçimi. |
| [SquareAnnotation](./squareannotation/) | Kare açıklamayı temsil eden sınıf. |
| [SquigglyAnnotation](./squigglyannotation/) | Belgenin metninde pürüzlü bir alt çizgi olarak görülen dalgalı açıklamayı temsil eder. |
| [Stamp](./stamp/) | Alt sınıflar olarak gelen çeşitli damga türleri için soyut bir sınıf. |
| [StampAnnotation](./stampannotation/) | <p> Lastik damga açıklamasını temsil eder. Bu tür açıklama, sayfaya bir lastik damga ile basılmış gibi görünmesi amaçlanan metin veya grafik gösterir. </p> <hr> <pre> Next code snippet demonstrates how to add 2 stamps into the first pdf document page. Input document comes from inFile and changes are saved into the outFile. The first stamp has icon NotForPublicRelease and the second comes with image from rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | StampIconConverter sınıfını temsil eder |
| [StrikeOutAnnotation](./strikeoutannotation/) | Belge metninde üstü çizili olarak görülen bir üstü çizili açıklamayı temsil eder. |
| [StructElement](./structelement/) | Genel yapı öğesi. |
| [SubjectNameElements](./subjectnameelements/) | Enum, imza konu dizesindeki öğeleri tanımlar. |
| [SubmitFormAction](./submitformaction/) | Submit-form eylemini tanımlayan sınıf. |
| [SvgLoadOptions](./svgloadoptions/) | SVG dosyasını PDF belgesine yükleme/ithal etme seçeneklerini temsil eder. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Dönüşüm için kullanılabilecek dönüşüm motorlarını listeler. |
| [SvgSaveOptions](./svgsaveoptions/) | SVG formatına dışa aktarma için kaydetme seçenekleri. |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Bu sınıf, PDF'ten HTML'e dönüşüm sırasında harici kaynak görüntü dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder. |
| [Symbology](./symbology/) | Bir (Barkod) Semboloji, belirli bir barkod türünün teknik ayrıntılarını tanımlar: çubukların genişliği, karakter seti, kodlama yöntemi, kontrol toplamı özellikleri vb. |
| [SystemFontSource](./systemfontsource/) | Sisteme yüklü tüm yazı tiplerini temsil eder. |
| [TabAlignmentType](./tabalignmenttype/) | Sekme hizalama türlerini listeler. |
| [Table](./table/) | Sayfaya eklenebilen bir tabloyu temsil eder. |
| [TableAbsorber](./tableabsorber/) | <p> Tablo öğelerinin bir absorber nesnesini temsil eder. Arama gerçekleştirir ve {@code TableAbsorber.TableList} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> The example demonstrates how to find table on the first PDF document page and replace the text in a table cell. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Sekme lideri türlerini listeler. |
| [TableBroken](./tablebroken/) | Tablo kırılmalarını listeler. |
| [TabOrder](./taborder/) | Sayfadaki sekme sırası |
| [TabStop](./tabstop/) | Paragrafta özel bir sekme durak konumunu temsil eder. |
| [TabStops](./tabstops/) | {@code TabStop} nesnelerinin bir koleksiyonunu temsil eder. |
| [TeXFragment](./texfragment/) | LaTeX parçacığını temsil eder. |
| [TeXLoadOptions](./texloadoptions/) | TeX dosyasını PDF belgesine yükleme/ithal etme seçeneklerini temsil eder. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Bellekten bir çıktı akışı almayı uygular. Örneğin, eşlik eden çıktının (günlük dosyası gibi) diske yazılmasını istemediğinizde, ancak daha sonra bellekte okuyabilmek istediğinizde kullanabilirsiniz. |
| [TeXSaveOptions](./texsaveoptions/) | TeX formatına dışa aktarma için kaydetme seçenekleri |
| [TextAbsorber](./textabsorber/) | <p> Bir metin emici nesneyi temsil eder. Metin çıkarımı gerçekleştirir ve sonucu {@code TextAbsorber.Text} nesnesi aracılığıyla erişilebilir kılar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> {@code TextAbsorber} nesnesi, bir Pdf belgesinden veya belgenin sayfasından metin çıkarmak için kullanılır. </p> |
| [TextAnnotation](./textannotation/) | PDF belgesindeki bir noktaya eklenmiş "yapışkan not" olan bir metin açıklamasını temsil eder. |
| [TextBoxField](./textboxfield/) | Metin kutusu alanını temsil eden sınıf. |
| [TextBuilder](./textbuilder/) | Metin nesnesini Pdf sayfasına ekler. |
| [TextDefaults](./textdefaults/) | Metin alt sisteminin varsayılanlarını tanımlar |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Metin alt sisteminin varsayılan türünü belirtir |
| [TextEditOptions](./texteditoptions/) | Metin düzenleme işlemlerinin seçeneklerini açıklar. |
| [TextElement](./textelement/) | Belgenin mantıksal yapısındaki genel metin öğesi. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | PDF belgesinde ortaya çıkan metin çıkarma hatasını açıklar. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Metin çıkarma hatasının ortaya çıktığı PDF belgesindeki konumu temsil eder. |
| [TextExtractionOptions](./textextractionoptions/) | Metin çıkarma seçeneklerini temsil eder |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | PDF belgesini metne dönüştürürken kullanılabilecek farklı modları tanımlar. {@code TextDevice} sınıfına bakın. |
| [TextFormattingOptions](./textformattingoptions/) | Metin biçimlendirme seçeneklerini temsil eder |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Satır aralığı özelliklerini tanımlar |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Kelime kaydırma stratejilerini tanımlar |
| [TextFragment](./textfragment/) | <p> PDF metninin bir parçasını temsil eder. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document(\"input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"output.pdf\"); </pre> <hr> <pre> In a few words, {@code TextFragment} object contains list of {@code TextSegment} objects. In details: Text of pdf document in {@code com.aspose.pdf} is represented by two basic objects: {@code TextFragment} and {@code TextSegment} The differences between them is mostly context-dependent. Let's consider following scenario. User searches text \"hello world\" to operate with it, change it's properties, look etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> Fiziksel pdf metni temsili çok karmaşıktır. \"hello world\" metni birkaç fiziksel bağımsız metin segmentinden oluşabilir. Aspose.Pdf metin modeli temelde {@code TextFragment} nesnesinin, kullanıcının sorgusunu temsil eden fiziksel {@code TextSegment} nesneleri kümesi üzerinde tek bir mantıksal işlem kümesi sağladığını belirler. Metin arama senaryosunda, {@code TextFragment} mantıksal \"hello world\" metin temsili iken, {@code TextSegment} nesne koleksiyonu \"hello world\" metin nesnesini oluşturan tüm fiziksel segmentleri temsil eder. Böylece {@code TextFragment}, mantıksal metin temsiline yakındır. {@code TextSegment} ise fiziksel metin temsiline yakındır. Açıkça her {@code TextSegment} nesnesinin kendi yazı tipi, renk ve konumlandırma özellikleri olabilir. {@code TextFragment}, metni özellikleriyle birlikte değiştirmek için basit bir yol sağlar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada {@code TextSegment} nesneleri erişilebilir ve kullanıcılar {@code TextSegment} nesneleriyle bağımsız olarak işlem yapabilir. <p> TextFragment özelliklerini değiştirmek, TextFragment bir toplama nesnesi olduğundan ve iç {@code Segments} koleksiyonunu yeniden düzenleyebileceğinden veya tek bir segmente birleştirebileceğinden iç {@code Segments} koleksiyonunu değiştirebilir. Gereksiniminiz {@code Segments} koleksiyonunu değiştirmemekse, lütfen iç segmentleri ayrı ayrı değiştirin. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Metin parçacıklarının bir absorber nesnesini temsil eder. Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasındaki metni bulmayı ve metni ve yazı tipini değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> {@code TextFragmentAbsorber} nesnesi temel olarak metin arama senaryosunda kullanılır. Arama tamamlandığında, oluşumlar {@code TextFragment} nesneleriyle temsil edilir ve bu nesneler {@code TextFragmentAbsorber.TextFragments} koleksiyonunda bulunur. {@code TextFragment} nesnesi, arama oluşum metnine, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye olanak tanır. </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Metin parçacıkları koleksiyonunu temsil eder |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Bir metin parçacığının metin durumunu temsil eder. </p> <hr> <pre> Örnek, {@code TextState} nesnesiyle metnin renk ve yazı tipi boyutunu nasıl değiştireceğini gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: yazı tipi ({@code TextFragmentState.Font} özelliği) yazı tipi boyutu ({@code TextFragmentState.FontSize} özelliği) yazı tipi stili ({@code TextFragmentState.FontStyle} özelliği) ön plan rengi ({@code TextFragmentState.ForegroundColor} özelliği) arka plan rengi ({@code TextFragmentState.BackgroundColor} özelliği) <p> {@code TextFragmentState} özelliklerini değiştirmenin {@code TextFragment.Segments} iç koleksiyonunu etkileyebileceğini unutmayın çünkü TextFragment bir toplama nesnesidir ve iç segmentleri yeniden düzenleyebilir veya tek bir segmente birleştirebilir. Eğer gereksiniminiz {@code TextFragment.Segments} koleksiyonunu değiştirmeden bırakmaksa, lütfen iç segmentleri ayrı ayrı değiştirin. </p> |
| [TextIcon](./texticon/) | Açıklamayı görüntülerken kullanılacak ikonları listeler. |
| [TextIconConverter](./texticonconverter/) | TextIconConverter sınıfını temsil eder |
| [TextMarkupAnnotation](./textmarkupannotation/) | Metin işaretleme ek açıklamaları için soyut temel sınıf. |
| [TextOptions](./textoptions/) | Metin işleme seçeneklerini temsil eder |
| [TextParagraph](./textparagraph/) | <p> Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder. </p> <hr> <pre> Bu örnek, bir metin paragrafı nesnesi oluşturmayı ve bunu Pdf sayfasına eklemeyi gösterir. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // metin paragrafı oluştur TextParagraph paragraph = new TextParagraph(); // paragraf dikdörtgenini ayarla paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // kelime kaydırma seçeneklerini ayarla paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // dize satırlarını ekle paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // paragrafı TextBuilder ile Pdf sayfasına ekle TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // Pdf belgesini kaydet doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | TextParagraph için arka plan modu |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Metin paragraflarının bir absorber nesnesini temsil eder. Metin araması gerçekleştirir ve {@code TextParagraphAbsorber.TextParagraphs} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. |
| [TextParagraphCollection](./textparagraphcollection/) | Metin paragrafları koleksiyonunu temsil eder |
| [TextReplaceOptions](./textreplaceoptions/) | Metin değiştirme seçeneklerini temsil eder |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Metin parçacığının daha kısa bir hale getirilmesinden sonra yapılacak eylemi belirler. None - hiçbir eylem yok, değiştirilen metin satırın geri kalanıyla çakışabilir; AdjustSpaceWidth - satır uzunluğunu korumak için kelimeler arasındaki boşlukları ayarlamaya çalışır; WholeWordsHyphenation - paragrafın sağ alanını korumak için kelimeleri paragraf satırları arasında dağıtmaya çalışır; ShiftRestOfLine - metnin uzunluğundaki değişime göre satırın geri kalanını kaydırır, satır uzunluğu değişebilir; Varsayılan değer ShiftRestOfLine'dir. |
| [TextSearchOptions](./textsearchoptions/) | Metin arama seçeneklerini temsil eder |
| [TextSegment](./textsegment/) | <p> PDF metninin bir segmentini temsil eder. </p> <hr> <pre> Örnek, {@code TextSegment} nesnesinin {@code TextState} nesnesiyle metnin renk ve yazı tipi boyutunu nasıl değiştireceğini gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> Kısaca, {@code TextSegment} nesneleri {@code TextFragment} nesnesinin alt nesneleridir. Ayrıntılı olarak: {@code Aspose.Pdf} içindeki PDF belgesinin metni iki temel nesneyle temsil edilir: {@code TextFragment} ve {@code TextSegment} Aralarındaki farklar çoğunlukla bağlama bağlıdır. Aşağıdaki senaryoyu ele alalım. Kullanıcı, "hello world" metnini arar, onunla işlem yapar, özelliklerini değiştirir, görüntüler vb. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> PDF metninin fiziksel temsili çok karmaşıktır. "hello world" metni, birkaç fiziksel bağımsız metin segmentinden oluşabilir. Aspose.PDF metin modeli temelde, {@code TextFragment} nesnesinin, kullanıcının sorgusunu temsil eden fiziksel {@code TextSegment} nesneleri kümesi üzerinde tek bir mantıksal işlem kümesi sağladığını belirler. Metin arama senaryosunda, {@code TextFragment} mantıksal "hello world" metin temsili iken, {@code TextSegment} nesne koleksiyonu "hello world" metin nesnesini oluşturan tüm fiziksel segmentleri temsil eder. Dolayısıyla, {@code TextFragment} mantıksal metin temsiline yakındır. Ve {@code TextSegment} fiziksel metin temsiline yakındır. Açıkça her {@code TextSegment} nesnesi kendi yazı tipi, renkleme ve konumlandırma özelliklerine sahip olabilir. {@code TextFragment}, metni özellikleriyle değiştirmek için basit bir yol sağlar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada {@code TextSegment} nesneleri erişilebilirdir ve kullanıcılar {@code TextSegment} nesneleriyle bağımsız olarak işlem yapabilir. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Metin segmentleri koleksiyonunu temsil eder |
| [TextStamp](./textstamp/) | Metinsel damgayı temsil eder. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Yazı tipi gerekli karakteri içermiyorsa gerçekleştirilecek eylem. |
| [TextState](./textstate/) | Bir metnin metin durumunu temsil eder |
| [TextStyle](./textstyle/) | Onay kutusu alanını temsil eden sınıf. |
| [TimestampSettings](./timestampsettings/) | İmzalama sürecinde kullanılan ocsp ayarlarını temsil eder. |
| [TocInfo](./tocinfo/) | İçindekiler tablosu bilgisini temsil eder. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Bu sınıf, Adobe Preflight hatası "Metin Unicode'a eşlenemiyor" sorununu çözmek için kullanılabilecek kuralları tanımlar. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Bir Kesim İşareti açıklamasını temsil eder. Kesim işaretleri, sayfanın nereden kesileceğini göstermek için basılı sayfanın köşelerine yerleştirilir. |
| [TxtLoadOptions](./txtloadoptions/) | TXT'den PDF'ye dönüşüm için yükleme seçenekleri. |
| [UnderlineAnnotation](./underlineannotation/) | Belgenin metninde alt çizgi olarak görünen bir alt çizgi açıklamasını temsil eder. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Bu sınıf, birleşik dönüşüm yöntemi (birleşik iç belge modeli ile) kullanan kaydetme seçeneklerini temsil eder. |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Dönüştürücünden gelen ilerleme olaylarını işleyen ve genellikle çağıran tarafça sağlanan soyut bir metoda sahip sınıfı temsil eder. Böyle sağlanan müşterinin işleyicisi, toplam dönüşüm ilerlemesini konsolda veya ilerleme çubuğunda göstermek için kullanılabilir. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Bu sınıf, dış uygulamalarda son kullanıcıya dönüşüm ilerlemesini göstermek için kullanılabilecek dönüşüm ilerleme bilgilerini temsil eder. |
| [WarningCallback](./warningcallback/) | Kullanıcının geri çağırma mekanizması desteği için arayüz. |
| [WarningInfo](./warninginfo/) | Uyarı bilgisini kapsülleyen değişmez nesne. |
| [WarningType](./warningtype/) | / * Enum represented warning type. / * / |
| [Watermark](./watermark/) | Sayfanın bir filigranını temsil eder. |
| [WatermarkAnnotation](./watermarkannotation/) | Sınıf, Watermark açıklama nesnesini tanımlar. |
| [WatermarkArtifact](./watermarkartifact/) | Filigran eserini tanımlayan sınıf. Bu şu amaçla kullanılabilir: |
| [WebHyperlink](./webhyperlink/) | Web hiperlink nesnesini temsil eder. |
| [WidgetAnnotation](./widgetannotation/) | Widget açıklamasını temsil eden sınıf. |
| [XFA](./xfa/) | XML Forms Architecture (XFA) ile ilgili XML formunu temsil eder. |
| [XfaParserOptions](./xfaparseroptions/) | ilgili veri kapsüllemeyi işlemek için sınıf |
| [XfdfReader](./xfdfreader/) | <p> XFDF formatının okunmasını gerçekleştiren sınıf. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | XFDF dosya formatına açıklamaları ve alanları yazma yöntemlerini toplar |
| [XForm](./xform/) | XForm'u temsil eden sınıf |
| [XFormCollection](./xformcollection/) | XFormCollection koleksiyonunu temsil eden sınıf. |
| [XImage](./ximage/) | görüntü X-Object'ini temsil eden sınıf. |
| [XImage.RawParameters](./ximage.rawparameters/) | görüntü ham XImage parametrelerini temsil eden sınıf. |
| [XImageCollection](./ximagecollection/) | XImage koleksiyonunu temsil eden sınıf. |
| [XmlLoadOptions](./xmlloadoptions/) | XML dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder. |
| [XmlSaveOptions](./xmlsaveoptions/) | Xml formatına dışa aktarma için kaydetme seçenekleri |
| [XmpField](./xmpfield/) | XMP alanını temsil eder. |
| [XmpFieldType](./xmpfieldtype/) | Bu enum, bir XMP alanının türlerini temsil eder. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Özellik kategorisi: iç veya dış. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Bu şema, yapılandırılmış bir türdeki bir alanı tanımlar. PDF/A Property Value Type şemasına çok benzer, ancak bir özelliği yerine bir yapıda alan tanımlar. Şema ad alanı URI: http://www.aiim.org/pdfa/ns/field# Gerekli şema ad alanı öneki: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Alan, özellik ve değer türü örnekleri için temel sınıfı temsil eder. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Tek bir özelliği tanımlar. Şema ad alanı URI: http://www.aiim.org/pdfa/ns/property# Gerekli şema ad alanı öneki: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | PDF/A-1 tarafından sağlanan XMP uzantı şemasını tanımlar. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | PDF/A-1 tarafından sağlanan XMP uzantı şemasının açıklamasını temsil eder. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | PDF/A ValueType şeması, XMP 2004 spesifikasyonunda tanımlanmamış tüm özellik değer türleri için gereklidir, yani aşağıdaki listedeki değer türlerinin dışındaki türler için:
- Dizi türleri (bir veya daha fazla alan içerebilen kapsayıcı türler): Alt, Bag, Seq
- Temel değer türleri: Boolean, (açık ve kapalı) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath
- Medya Yönetimi değer türleri: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
- Temel İş/İş Akışı değer türü: Job
- EXIF şema değer türleri: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational
Şema ad alanı URI: http://www.aiim.org/pdfa/ns/type# Gerekli şema ad alanı öneki: pdfaType |
| [XmpValue](./xmpvalue/) | XMP değerini temsil eder |
| [XpsLoadOptions](./xpsloadoptions/) | xps dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder. |
| [XpsSaveOptions](./xpssaveoptions/) | Xps formatına dışa aktarma için kaydetme seçenekleri |
| [XslFoLoadOptions](./xslfoloadoptions/) | XSL-FO dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu tür biçimlendirme hatalarını ele almanın olası stratejilerini listeler. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Pencerenin sol üst köşesine konumlandırılmış (sol, üst) koordinatlarıyla sayfayı gösteren ve sayfa içeriğini zoom faktörüyle büyüten açık hedefi temsil eder. left, top veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. 0 zoom değeri, null değerle aynı anlama gelir. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Açıklama |
| --- | --- |
| [AFRelationship](./afrelationship/) | Sıralama, ilişkili dosyalar arasındaki ilişkiyi tanımlar. |
| [AnnotationState](./annotationstate/) | Orijinal ek açıklamanın ayarlanabileceği durumların sıralaması. |
| [AnnotationStateModel](./annotationstatemodel/) | Ek açıklamanın durumuna karşılık gelen durum modeli. |
| [AnnotationType](./annotationtype/) | Ek açıklama türlerinin sıralaması. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Olası artefakt alt tiplerinin sıralaması. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Olası artefakt türlerinin sıralaması. |
| [BlendMode](./blendmode/) | Karışım modlarının sıralaması. |
| [BorderCornerStyle](./bordercornerstyle/) | Kenarlık köşe stillerini sıralar. |
| [BorderEffect](./bordereffect/) | Ek açıklamaların kenarlığına uygulanması gereken etkiyi tanımlar. |
| [BorderStyle](./borderstyle/) | Ek açıklama kenarlığının stilini tanımlar. |
| [BoxStyle](./boxstyle/) | Onay kutusunda işaret çizimi için stilleri temsil eder. |
| [CapStyle](./capstyle/) | Mürekkep ek açıklama çizgisinin uç stili. |
| [CaptionPosition](./captionposition/) | Ek açıklama başlığının konumlandırmasının sıralaması. |
| [CaretSymbol](./caretsymbol/) | İmleç ile ilişkilendirilecek bir sembol. |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK renk modeline dahil edilen renkler. |
| [ColorSpace](./colorspace/) | Renk uzaylarının sıralaması. |
| [ColorType](./colortype/) | Sayfadaki öğelerin renk tipini belirtir. |
| [ColumnAdjustment](./columnadjustment/) | Sütun ayarlama tiplerini sıralar. |
| [ContentDisposition](./contentdisposition/) | MIME protokolü Content-Disposition başlığı. |
| [ConvertErrorAction](./converterroraction/) | Bu sınıf, dönüşüm hataları için eylemi temsil eder. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Bu eylem, yumuşak maske içeren görüntülerin dönüşümü için eylemleri temsil eder. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Bu sınıf, şeffaflığın dönüşümü için eylemi temsil eder. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Şifreleme/şifre çözme rutinlerinde kullanılan kriptografik algoritma tipini temsil eder. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * Bu {@code Aspose.Pdf.Security } ad alanı şifreleme ve dijital imzalama için kullanılan sınıfları içerir. / * / |
| [DefaultState](./defaultstate/) | Bir PDF katmanının varsayılan durumunu temsil eder. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Verileri bir "hash"e eşleyen algoritma türünü temsil eder |
| [Direction](./direction/) | Metin yönü. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Bu belgeye verilen erişim izinleri. Geçerli değerler: 1 - Belgeye hiçbir değişiklik yapılmasına izin verilmez; belgeye yapılan herhangi bir değişiklik imzayı geçersiz kılar. 2 - İzin verilen değişiklikler form doldurma, sayfa şablonlarını örnekleme ve imzalama; diğer değişiklikler imzayı geçersiz kılar. 3 - İzin verilen değişiklikler 2 ile aynı olup, ek olarak açıklama oluşturma, silme ve değiştirme; diğer değişiklikler imzayı geçersiz kılar. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | .doc veya .docx dosya formatını belirtmeye izin verir. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Bir PDF belgesinin bir kelime işlem belgesine nasıl dönüştürüleceğini kontrol etmeye izin verir. Ortaya çıkan belge yoğun bir şekilde düzenlenmeyecekse RecognitionMode.Textbox modunu kullanın. Metin kutuları, yapılacak çok az şey olduğunda kolayca değiştirilebilir. Çıktı belgesinin daha fazla düzenlenmesi gerekiyorsa RecognitionMode.Flow modunu kullanın. Akış modundaki paragraflar ve metin satırları metnin kolayca değiştirilmesini sağlar, ancak desteklenmeyen biçimlendirme nesneleri RecognitionMode.Textbox moduna göre daha kötü görünecektir. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | PDF dosyası (genellikle sabit düzenli) dönüştürülürken, dönüşüm motoru orijinal belge yazarının niyetini geri kazandırmak ve sonucu akış düzeninde üretmek için gruplama ve çok seviyeli analiz yapmaya çalışır. Bu özellik, içeriğin tanınması için istenen yönteme göre bu dönüşümü ayarlar. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Açık hedeflerin türlerini sıralar. |
| [ExtendedBoolean](./extendedboolean/) | Undefined değerini destekleyen boolean türünü temsil eder. |
| [ExtractImageMode](./extractimagemode/) | Belgelerden görüntü çıkarılırken kullanılabilecek farklı modları tanımlar. |
| [FileEncoding](./fileencoding/) | Ekli dosyanın kodlaması. Olası değerler: Zip - dosya ZIP ile sıkıştırılmıştır, None - dosya sıkıştırılmamıştır. |
| [FileIcon](./fileicon/) | Açıklamayı görüntülerken kullanılacak bir simge. |
| [Fixup](./fixup/) | Bu enum bir Fixup türünü temsil eder. |
| [FormType](./formtype/) | Acro Form'un olası türlerinin enum'ı. |
| [FreeTextIntent](./freetextintent/) | Serbest metin açıklamasının amaçlarını sıralar. |
| [HighlightingMode](./highlightingmode/) | Açıklamanın vurgulama modunu sıralar, fare düğmesi etkin alan içinde basıldığında veya tutulduğunda kullanılacak görsel etki. |
| [HorizontalAlignment](./horizontalalignment/) | Yatay hizalamayı tanımlar. |
| [HtmlDocumentType](./htmldocumenttype/) | Html belge türlerinin enum'ını temsil eder. |
| [HtmlMediaType](./htmlmediatype/) | Renderleme sırasında kullanılan olası medya türlerini belirtir. |
| [IconCaptionPosition](./iconcaptionposition/) | Simgelerin konumunu tanımlar. |
| [ImageFileType](./imagefiletype/) | Görüntü dosyası türlerini sıralar. |
| [ImageFilterType](./imagefiltertype/) | Görüntü filtresi türünü temsil eden enum. |
| [ImageFormat](./imageformat/) | Bu enum görüntü formatlarını temsil eder. |
| [ImportFormat](./importformat/) | İçe aktarma formatını belirtir. |
| [Justification](./justification/) | Açıklamanın metnini görüntülerken kullanılacak hizalama (justification) biçimlerini sıralar. |
| [LaunchActionOperation](./launchactionoperation/) | Başlatma eylemi yürütülürken belgeyle yapılacak işlemleri listeler. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Sonuç HTML'de kelimelerde harflerin konumlandırılabileceği olası modları listeler. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: aydınlatma şeması türlerinin kümesi. |
| [LineEnding](./lineending/) | Çizgi çizilirken kullanılacak satır sonu stillerini listeler. |
| [LineIntent](./lineintent/) | Çizgi açıklamasının amaçlarını listeler. |
| [LoadFormat](./loadformat/) | Yükleme biçimini belirtir. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Kesir değerlerinin hangi şekilde görüntüleneceğini gösteren değer. |
| [NumberingStyle](./numberingstyle/) | PageLabel sınıfı için desteklenen sayfa numaralandırma stilinin enum'ı. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Arama için kullanılacak akıştaki konumu belirtir. |
| [PageCoordinateType](./pagecoordinatetype/) | Sayfa koordinat tipini açıklar. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Sayfa düzenini tanımlar. |
| [PageMode](./pagemode/) | Sınıf, belge sayfasının kullanılan bileşenlerini tanımlar. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Sayfadaki öğenin konumunu belirlemek için varyantı belirtir. |
| [PasswordType](./passwordtype/) | Bu enum, şifre korumalı pdf belgelerinde kullanılan bilinen şifre türlerini temsil eder. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: 3D açıklama etkinleştirme modlarının kümesi. |
| [PdfFormat](./pdfformat/) | Bu sınıf bir pdf formatını temsil eder. |
| [PdfVersion](./pdfversion/) | Bu enum, pdf dosyasının sürümünü temsil eder. |
| [PolyIntent](./polyintent/) | Poligon veya çoklu çizgi açıklamasının amaçlarını listeler. |
| [PredefinedAction](./predefinedaction/) | Bir PDF dosyasından tetiklenebilecek farklı eylemleri tanımlar. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Bir işaretin sayfanın köşesindeki konumunu temsil eder. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Bir kayıt işaretinin sayfadaki konumunu temsil eder. |
| [ReplyType](./replytype/) | Açıklama ile InReplyTo tarafından belirtilen açıklama arasındaki ilişkilerin (\"yanıt türü\") çeşitlerini listeler. |
| [ReturnAction](./returnaction/) | Enum, {@code IWarningCallback.Warning(WarningInfo)} yöntemi çağrıldığında bir program iş akışı eylemini temsil eder. |
| [Rotation](./rotation/) | Olası döndürme değerlerinin enum'ı. |
| [SaveFormat](./saveformat/) | Biçimi belirtir. |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Sonuç belgesinde kenarlıklar veya diğer çizgileri çizmek için kullanılabilecek satır türlerini temsil eder |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | kaydedilen harici kaynakların olası türlerini listeler |
| [StampIcon](./stampicon/) | Açıklamayı görüntülerken kullanılacak ikonları listeler. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | Pdf'den SVG'ye dönüşüm sırasında harici kaynaklar olarak kaydedilebilecek görüntü dosyası türlerini listeler |
| [TextAlignment](./textalignment/) | Ek açıklamadaki metnin hizalaması. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Kırpma yolu işleme modları |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Yazı tipi değiştirme davranışı. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Dil dönüşüm modları |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Yazı tipi gerekli karakteri içermediğinde yapılacak eylem |
| [TextRenderingMode](./textrenderingmode/) | Metin işleme modu, Tmode, metnin gösterilmesinin glif konturlarının çizilmesi, doldurulması, kırpma sınırı olarak kullanılması ya da üçünün bir kombinasyonu olup olmayacağını belirler. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Metnin yazı tipi boyutunun, içinde bulunduğu alan içine sığacak şekilde nasıl ayarlanacağına dair bir politika belirtir. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Metin değiştirme işleminin uygulandığı kapsam REPLACE_FIRST varsayılan olarak. Bu eski seçenek uyumluluk için tutulmuştur. PdfContentEditor'i etkiler ve TextFragmentAbsorber'ı etkilemez. |
| [VerticalAlignment](./verticalalignment/) | Olası dikey hizalama değerlerinin listesi. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
