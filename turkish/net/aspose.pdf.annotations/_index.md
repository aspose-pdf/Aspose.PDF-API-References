---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations ad alanı, kullanıcıların belge ile etkileşimde bulunmasını sağlayan çeşitli türde eylem hedefleri ve diğer özelliklerle çalışmak için sınıflar sağlar.
type: docs
weight: 50
url: /tr/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** ad alanı, kullanıcıların belge ile etkileşimde bulunmasını sağlayan çeşitli türde eylem, hedefler ve diğer özelliklerle çalışmak için sınıflar sağlar.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [ActionCollection](./actioncollection/) | Eylemler koleksiyonu |
| [Annotation](./annotation/) | Not nesnesini temsil eden sınıf. |
| [AnnotationActionCollection](./annotationactioncollection/) | Not eylemleri koleksiyonunu temsil eder. |
| [AnnotationCollection](./annotationcollection/) | Not koleksiyonunu temsil eden sınıf. |
| [AnnotationSelector](./annotationselector/) | Bu sınıf, Ziyaretçi şablon fikrini kullanarak notları seçmek için kullanılır. |
| [AppearanceDictionary](./appearancedictionary/) | Notun sayfada görsel olarak nasıl sunulacağını belirten not görünüm sözlüğü. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Bir Bleed Mark notunu temsil eder. |
| [Border](./border/) | Not sınırının özelliklerini temsil eden sınıf. |
| [CaretAnnotation](./caretannotation/) | Caret notunu temsil eden sınıf. |
| [Characteristics](./characteristics/) | Not özelliklerini temsil eder |
| [CircleAnnotation](./circleannotation/) | Daire notunu temsil eden sınıf. |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation notunu temsil eden sınıf. Color özelliği göz ardı edilir, bunun yerine ColorsOfCMYK rengi kullanılır. Oluşturulurken, genişlik ve yükseklik oranı notun yönünü belirler - yatay veya dikey. Sonra, not dikdörtgeninin TrimBox'un dışında olup olmadığını kontrol eder ve değilse, notun yönünü dikkate alarak TrimBox'un dışındaki en yakın konuma kaydırılır. Notun TrimBox'un dışında sığması için genişlik (yükseklik) azaltılabilir. Düzen için yer yoksa, genişlik/yükseklik sıfıra ayarlanabilir (bu durumda, not sayfada mevcut, ancak görüntülenmez). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Ortak şekil notunu temsil eden soyut sınıf. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Baskı sayfasının köşelerine yerleştirilen not türlerini temsil eder. |
| [CustomExplicitDestination](./customexplicitdestination/) | Özel açık hedefi temsil eder. |
| [Dash](./dash/) | Çizgi kesik desenini temsil eden sınıf. |
| [DefaultAppearance](./defaultappearance/) | Alanın varsayılan görünümünü (yazı tipi, metin boyutu ve rengi) tanımlar. |
| [DocumentActionCollection](./documentactioncollection/) | Belge ile bazı eylemler üzerinde gerçekleştirilen eylemleri tanımlayan sınıf |
| [ExplicitDestination](./explicitdestination/) | PDF belgesindeki açık hedefler için temel sınıfı temsil eder. |
| [FdfReader](./fdfreader/) | FDF formatını okumayı gerçekleştiren sınıf. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Dosya ekleme notunu tanımlayan sınıf. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Sayfayı içeriği, pencere içinde tamamen sığacak şekilde yeterince büyütülmüş olarak görüntüleyen açık hedefi temsil eder. Gerekli yatay ve dikey büyütme faktörleri farklıysa, ikisinden daha küçüğünü kullanarak, diğer boyutta dikdörtgeni pencere içinde ortalar. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Sayfayı, dikey koordinatın pencerenin üst kenarında konumlandığı ve sayfanın içeriğinin, dikdörtgeninin tam genişliğini pencere içinde sığacak şekilde yeterince büyütüldüğü açık hedefi temsil eder. Üst için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Sayfayı, yatay koordinatın pencerenin sol kenarında konumlandığı ve sayfanın içeriğinin, dikdörtgeninin tam yüksekliğini pencere içinde sığacak şekilde yeterince büyütüldüğü açık hedefi temsil eder. Sol için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| [FitExplicitDestination](./fitexplicitdestination/) | Sayfayı içeriği, pencere içinde tamamen sığacak şekilde yeterince büyütülmüş olarak görüntüleyen açık hedefi temsil eder. Gerekli yatay ve dikey büyütme faktörleri farklıysa, ikisinden daha küçüğünü kullanarak, sayfayı diğer boyutta pencere içinde ortalar. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Sayfayı, dikey koordinatın pencerenin üst kenarında konumlandığı ve sayfanın içeriğinin, sayfanın tam genişliğini pencere içinde sığacak şekilde yeterince büyütüldüğü açık hedefi temsil eder. Üst için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Sayfayı, belirtilen sol, alt, sağ ve üst koordinatları tarafından tanımlanan dikdörtgenin tamamen pencere içinde yatay ve dikey olarak sığacak şekilde yeterince büyütüldüğü açık hedefi temsil eder. Gerekli yatay ve dikey büyütme faktörleri farklıysa, ikisinden daha küçüğünü kullanarak, dikdörtgeni diğer boyutta pencere içinde ortalar. Herhangi bir parametre için null değeri, öngörülemeyen davranışa neden olabilir. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Sayfayı, yatay koordinatın pencerenin sol kenarında konumlandığı ve sayfanın içeriğinin, sayfanın tam yüksekliğini pencere içinde sığacak şekilde yeterince büyütüldüğü açık hedefi temsil eder. Sol için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| [FixedPrint](./fixedprint/) | Su işareti notunun sabit baskı verilerini temsil eder. |
| [FreeTextAnnotation](./freetextannotation/) | Sayfanın üzerinde doğrudan metin gösteren serbest metin notunu temsil eder. Sıradan bir metin notunun aksine, serbest metin notunun açık veya kapalı bir durumu yoktur; metin her zaman görünür. |
| [GoToAction](./gotoaction/) | Görünümü belirli bir hedefe (sayfa, konum ve büyütme faktörü) değiştiren bir git eylemini temsil eder. |
| [GoToRemoteAction](./gotoremoteaction/) | Sıradan bir git eylemine benzer, ancak mevcut dosya yerine başka bir PDF dosyasındaki bir hedefe atlayan uzaktan git eylemini temsil eder. |
| [GoToURIAction](./gotouriaction/) | Bir URI'nin çözülmesine neden olan bir URI eylemini temsil eder. |
| [HideAction](./hideaction/) | Bir veya daha fazla notu ekranda gizleyen veya gösteren bir gizleme eylemini temsil eder. |
| [HighlightAnnotation](./highlightannotation/) | Belgedeki bir metin aralığını vurgulayan bir vurgulama notunu temsil eder. |
| [ImportDataAction](./importdataaction/) | Bir veri içe aktarma eylemi çağrıldığında, Formlar Veri Formatı (FDF) verileri belirtilen dosyadan belgenin etkileşimli formuna içe aktarılacaktır. |
| [InkAnnotation](./inkannotation/) | Bir veya daha fazla ayrı yol içeren serbest el "karalama" notunu temsil eder. |
| [JavascriptAction](./javascriptaction/) | Javascript eylemini temsil eden sınıf. |
| [LaunchAction](./launchaction/) | Bir uygulamayı başlatan veya bir belgeyi açan veya yazdıran bir başlatma eylemini temsil eder. |
| [LineAnnotation](./lineannotation/) | Çizgi notunu temsil eden sınıf. |
| [LinkAnnotation](./linkannotation/) | Belgedeki başka bir yere bir hiper metin bağlantısını veya gerçekleştirilmesi gereken bir eylemi temsil eder. |
| [MarkupAnnotation](./markupannotation/) | İşaretleme notunu temsil eden soyut sınıf. |
| [Measure](./measure/) | Ölçüm koordinat sistemini tanımlayan sınıf. |
| [MediaClip](./mediaclip/) | Sunumun medya klip nesnesini tanımlayan sınıf. |
| [MediaClipData](./mediaclipdata/) | Medya klip verilerini tanımlayan sınıf. |
| [MediaClipSection](./mediaclipsection/) | Bu sınıf, medya klip bölümünü tanımlar. |
| [MediaRendition](./mediarendition/) | Medya sunumunu tanımlayan sınıf. |
| [MovieAnnotation](./movieannotation/) | Bilgisayar ekranında ve hoparlörlerden sunulacak animasyonlu grafikler ve ses içeren bir film notunu temsil eder. Not etkinleştirildiğinde, film oynatılır. |
| [NamedAction](./namedaction/) | PDF görüntüleyici uygulamalarının desteklemesi beklenen adlandırılmış eylemleri temsil eder. |
| [NamedDestination](./nameddestination/) | Açık sözdizimi ile doğrudan tanımlanmak yerine, bir ad nesnesi veya bir bayt dizesi aracılığıyla dolaylı olarak atıfta bulunulabilir. |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF belgesindeki Sayfa Bilgisi notunu temsil eder. Bu not, dosya adını, sayfa numarasını ve notun oluşturulma tarihini ve saatini içerir. |
| [PDF3DAnnotation](./pdf3dannotation/) | PDF3DAnnotation sınıfı. Bu sınıf miras alınamaz. |
| [PDF3DArtwork](./pdf3dartwork/) | PDF3DArtwork sınıfı. |
| [PDF3DContent](./pdf3dcontent/) | PDF3DContent sınıfı. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | PDF3DCrossSection sınıfı. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | PDF3DCrossSectionArray sınıfı. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | PDF3DCuttingPlaneOrientation sınıfı. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | PDF3DLightingScheme sınıfı. |
| [PDF3DRenderMode](./pdf3drendermode/) | PDF3DRenderMode sınıfı. |
| [PDF3DStream](./pdf3dstream/) | PDF3DStream sınıfı. |
| [PDF3DView](./pdf3dview/) | PDF3DView sınıfı. |
| [PDF3DViewArray](./pdf3dviewarray/) | PDF3DViewArray sınıfı. |
| [PdfAction](./pdfaction/) | PDF belgesindeki Eylemi temsil eder |
| [PdfActionCollection](./pdfactioncollection/) | Eylemler listesini tanımlayan sınıf. |
| [PolyAnnotation](./polyannotation/) | Poligon notları için soyut temel sınıf. |
| [PolygonAnnotation](./polygonannotation/) | Çokgen notunu temsil eden sınıf. |
| [PolylineAnnotation](./polylineannotation/) | İlk ve son köşenin açıkça bağlı olmadığı çoklu çizgi notunu temsil eder. |
| [PopupAnnotation](./popupannotation/) | Metni giriş ve düzenleme için bir açılır pencerede gösteren açılır notu temsil eder. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Yazıcı işareti notunu temsil eden soyut sınıf. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) enumerasyonu için genişletme yöntemleri sağlar. |
| [RedactionAnnotation](./redactionannotation/) | Redact notunu temsil eder. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Bir Kayıt Mark notunu temsil eder. |
| [Rendition](./rendition/) | RenditionAnnotation'un sunum nesnesini tanımlayan sınıf. |
| [RenditionAction](./renditionaction/) | Çoklu ortam içeriğinin oynatılmasını kontrol eden bir sunum eylemi. |
| [RichMediaAnnotation](./richmediaannotation/) | PDF belgesine video/ses verilerini gömmeye izin veren RichMediaAnnotation'u tanımlayan sınıf. |
| [ScreenAnnotation](./screenannotation/) | Medya kliplerinin oynatılabileceği bir sayfa bölgesini belirten bir ekran notu. |
| [SelectorRendition](./selectorrendition/) | Seçici sunumu tanımlayan sınıf. |
| [SoundAnnotation](./soundannotation/) | Bilgisayarın mikrofonundan kaydedilen veya bir dosyadan içe aktarılan sesi içeren bir ses notunu temsil eder. |
| [SoundData](./sounddata/) | Not etkinleştirildiğinde çalınacak sesi tanımlayan ses verisini temsil eder. |
| [SoundSampleData](./soundsampledata/) | Bir ses nesnesine özgü ek girişleri temsil eder (Bölüm 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Kare notunu temsil eden sınıf. |
| [SquigglyAnnotation](./squigglyannotation/) | Bir belgedeki metin üzerinde dişli bir alt çizgi olarak görünen kıvrımlı notu temsil eder. |
| [StampAnnotation](./stampannotation/) | Kauçuk damga notunu temsil eder. Bu tür bir not, sayfada kauçuk damga ile basılmış gibi görünmesi amaçlanan metin veya grafikler gösterir. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Belgedeki metin üzerinde bir üstü çizili olarak görünen bir üstü çizili notu temsil eder. |
| [SubmitFormAction](./submitformaction/) | Form gönderme eylemini tanımlayan sınıf. |
| [TextAnnotation](./textannotation/) | PDF belgesinde bir noktaya eklenmiş bir 'yapışkan not' olan metin notunu temsil eder. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Metin işaretleme notları için soyut temel sınıf. |
| [TextStyle](./textstyle/) | Not içindeki metnin stilini temsil eden sınıf |
| [TrimMarkAnnotation](./trimmarkannotation/) | Bir Trim Mark notunu temsil eder. |
| [UnderlineAnnotation](./underlineannotation/) | Belgedeki metin üzerinde bir alt çizgi olarak görünen bir alt çizgi notunu temsil eder. |
| [WatermarkAnnotation](./watermarkannotation/) | Su işareti notu nesnesini tanımlayan sınıf. |
| [WidgetAnnotation](./widgetannotation/) | Widget notunu temsil eden sınıf. |
| [XfdfReader](./xfdfreader/) | XFDF formatını okumayı gerçekleştiren sınıf. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Sayfayı, (sol, üst) koordinatlarının pencerenin sol üst köşesine yerleştirildiği ve sayfanın içeriğinin büyütme faktörü ile büyütüldüğü açık hedefi temsil eder. Sol, üst veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. Zoom değeri 0, null değeri ile aynı anlama gelir. |
## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Farklı belge notlarını ziyaret etmek için Ziyaretçi tanımlar. |
| [IAppointment](./iappointment/) | Eylemler ve hedefler için genel arayüzü temsil eder. |
## Enumerasyon

| Enumerasyon | Açıklama |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Notun çeşitli özelliklerini belirten bir dizi bayrak. |
| [AnnotationState](./annotationstate/) | Orijinal notun ayarlanabileceği durumların enumerasyonu. |
| [AnnotationStateModel](./annotationstatemodel/) | Notun durumuna karşılık gelen durum modeli. |
| [AnnotationType](./annotationtype/) | Not türlerinin enumerasyonu. |
| [BorderEffect](./bordereffect/) | Notların sınırına uygulanacak etkiyi tanımlar. |
| [BorderStyle](./borderstyle/) | Not sınırının stilini tanımlar. |
| [CapStyle](./capstyle/) | Mürekkep notu çizgisinin uç stilini tanımlar. |
| [CaptionPosition](./captionposition/) | Notun başlık konumlandırmasının enumerasyonu. |
| [CaretSymbol](./caretsymbol/) | Caret ile ilişkilendirilecek bir sembol. |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK renk modelinde yer alan renkler. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Açık hedef türlerini enumer eder. |
| [FileIcon](./fileicon/) | Notu görüntülemek için kullanılacak bir simge. |
| [FreeTextIntent](./freetextintent/) | Serbest metin notunun niyetlerini enumer eder. |
| [HighlightingMode](./highlightingmode/) | Notun vurgulama modunu, aktif alanında fare düğmesine basıldığında veya basılı tutulduğunda kullanılacak görsel etkisini enumer eder. |
| [Justification](./justification/) | Notun metnini görüntülemede kullanılacak dörtlü (justification) biçimlerini enumer eder. |
| [LaunchActionOperation](./launchactionoperation/) | Başlatma eylemi yürütülürken belgede gerçekleştirilecek işlemleri enumer eder. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: aydınlatma şeması türlerinin seti. |
| [LineEnding](./lineending/) | Çizgiyi çizerken kullanılacak çizgi sonu stillerini enumer eder. |
| [LineIntent](./lineintent/) | Çizgi notunun niyetlerini enumer eder. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: 3D notu etkinleştirme modunun seti. |
| [PolyIntent](./polyintent/) | Çokgen veya çoklu çizgi notunun niyetlerini enumer eder. |
| [PredefinedAction](./predefinedaction/) | PDF dosyasından tetiklenebilecek farklı eylemleri tanımlar. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Bir işaretin sayfanın köşesindeki konumunu temsil eder. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Bir kayıt işaretinin sayfadaki konumunu temsil eder. |
| [PrinterMarksKind](./printermarkskind/) | Bir belgeye eklenecek yazıcı işaretlerinin türlerini belirtir. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: sunum modu türlerinin seti |
| [RenditionOperation](./renditionoperation/) | Eylem tetiklendiğinde gerçekleştirilecek işlemi tanımlar. |
| [RenditionType](./renditiontype/) | Sunumun olası türlerini tanımlayan enumerasyon. |
| [ReplyType](./replytype/) | Not ile InReplyTo tarafından belirtilen arasındaki ilişkilerin ( "cevap türü") türlerini enumer eder. |
| [SoundEncoding](./soundencoding/) | Örnek veriler için kodlama formatı. |
| [SoundIcon](./soundicon/) | Notu görüntülemek için kullanılacak simgeleri enumer eder. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Ses örnek verileri için kodlama formatı. |
| [StampIcon](./stampicon/) | Notu görüntülemek için kullanılacak simgeleri enumer eder. |
| [TextIcon](./texticon/) | Notu görüntülemek için kullanılacak simgeleri enumer eder. |