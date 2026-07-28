---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "HTML formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 1990
url: /tr/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

HTML formatına dışa aktarma için kaydetme seçenekleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | HtmlSaveOptions sınıfının yeni bir örneğini başlatır. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | {@code HtmlSaveOptions} sınıfının yeni bir örneğini başlatır. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | HtmlSaveOptions sınıfının yeni bir örneğini başlatır. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | HtmlSaveOptions sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Eğer 'SplitOnPages=false' özniteliği belirtilmişse, tüm giriş PDF sayfalarını temsil eden HTML, farklı HTML sayfalarına bölünmez, tek büyük bir sonuç HTML dosyasına yerleştirilir. Ancak her kaynak PDF sayfası, HTML içinde kendi dikdörtgen alanı ile temsil edilir (gerekirse bu alanlar, 'PageBorderIfAny' adlı özel öznitelik ile sayfa kağıdı kenarlarını gösterecek şekilde kenarlıklandırılabilir). Bu parametre, çıktı HTML alanlarının etrafında zorunlu olarak bırakılacak kenar boşluğunun genişliğini tanımlar; bu alanlar kaynak PDF belgesinin sayfalarını temsil eder. Esasen, PDF \"paper\" sayfalarının HTML temsilleri arasındaki garantili aralığı tanımlar. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Bu parametre, PDF'ten HTML'e bileşik arka plan görüntülerinin dönüşümü sırasında gerekli anti-aliasing önlemlerini tanımlar. |
| [getBatchSize](#getBatchSize--) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | PDFtoHTML dönüştürücüsü sonuç CSS'leri oluşturduğunda, CSS sınıf adları (örneğin \".stl_01 {}\" ... \".stl_NN {}\") üretilir ve sonuç CSS içinde kullanılır. Bu özellik, sınıf adı önekini zorunlu olarak ayarlamayı sağlar. Örneğin, tüm sınıf adlarının 'my_prefix_' ile başlamasını istiyorsanız (yani 'my_prefix_1' ... 'my_prefix_NNN' gibi), dönüştürmeden önce bu özelliğe 'my_prefix_' değerini atayın. Bu özellik dokunulmaz bırakılırsa (yani değer olarak null bırakılırsa), dönüştürücü sınıf adlarını kendisi oluşturur (örneğin \".stl_01 {}\" ... \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Bu alan, PDF'ten HTML'e dönüşüm sırasında (varsa) oluşturulan HTML belgesinin tamamına ya da sayfalarına ilişkin CSS dosyalarının kaydedilmesi için kullanılacak kaydetme stratejisini içerebilir (birden fazla HTML sayfası oluşturuluyorsa). CSS dosyasını belirli bir şekilde işlemek istiyorsanız, lütfen ilgili yöntemi oluşturun ve ondan oluşturulan temsilciyi bu özelliğe atayın. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Dönüşüm sonucu bir veya birkaç HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının (tam olarak - işaretleme-HTML, varsa dışa bağlı dosyalar olmadan) işlenmesini sağlayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Bu durumda, işleme (örneğin sayfanın HTML'inin akışa veya diske kaydedilmesi) bu özel kod içinde yapılabilir. Bu durumda, HTML sayfasının kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü dönüştürücünün kodundaki kaydetme kullanılmayacaktır. Bu ya da o durum için işleme bir sebeple dönüştürücünün kodu tarafından, özel kod yerine yapılması gerekiyorsa, lütfen özel kod içinde 'htmlSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye kaynağın işlenmesi için gerekli tüm adımların, dışarıda herhangi bir özel kod bulunmuyormuş gibi, dönüştürücü içinde yapılması gerektiğini bildirecektir. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir; örneğin işlenen sayfaların mevcut miktarı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir. Konsolda ilerlemeyi gösteren işleyici kodunun örneği şu şekildedir: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Bu alan, dönüşüm sırasında (varsa) oluşturulan referanslı kaynak dosyalarının (örneğin görüntüler ve yazı tipleri) kaydedilmiş HTML düğümleriyle ilgili özelleştirilmiş işlenmesi için kullanılacak kaydetme stratejisini içerebilir. Bu strateji, kaynakları işleyecek ve oluşturulan HTML'de kaydedilen kaynağın istenen URL'sini temsil eden bir dize döndürecektir. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Bu alan, oluşturulan sonuç HTML'ye yerleştirilecek konu CSS'nin URL'sini (veya çok sayfalı oluşturma açıksa URL şablonunu - aşağıdaki detaylara bakınız) döndüren özel bir yöntemi içerebilir. Örneğin, dönüştürücünün oluşturulan CSS içinde standart CSS dosya adı yerine belirli bir URL koymasını istiyorsanız, bu özelliğe istenen URL'yi üreten bir yöntem oluşturup atamanız yeterlidir. 'SplitCssIntoPages' bayrağı ayarlıysa, bu özel strateji (varsa) CSS'nin kesin URL'si yerine, (dönüştürücü içinde String.Format() işleviyle sayfa numarası yer tutucusunun değiştirilmesinden sonra) bu veya o sayfanın CSS URL'sine çözülebilecek bir şablon dizesi döndürmelidir. Bu durumda beklenen dönüş dizesine örnekler: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' |
| [getDefaultFontName](#getDefaultFontName--) | Sistemde yüklü olmayan ve belgeye gömülmemiş herhangi bir yazı tipinin yerine kullanılacak yüklü bir yazı tipinin adını belirtir. Null ise varsayılan yedek yazı tipi kullanılır. |
| [getDocumentType](#getDocumentType--) | Alır {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | HTML'de gömülemeyecek PDF gömülü yazı tipi adlarının listesi. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır. Listedeki sayfaların görünüm sırası, sonuç HTML sayfalarındaki sıralarını etkilemez – sonuç sayfalar her zaman kaynak PDF'de bulundukları sırayla görüntülenir. Bu liste null ise (varsayılan olarak olduğu gibi), tüm sayfalar dönüştürülür. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların (1-[amountOfPagesInDocument]) aralığının dışına çıkarsa bir istisna fırlatılır. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Bu öznitelik, Akış modu için tam genişlikte paragraf metnini belirtir, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Mevcut belge için PDF kod çözümlemesini ayarlamak amacıyla kodlama özel kuralını tanımlar |
| [getFontSavingMode](#getFontSavingMode--) | PDF'nin istenen formata kaydedilmesi sırasında kullanılacak yazı tipi kaydetme modunu tanımlar |
| [getFontSources](#getFontSources--) | <p> Önceden kaydedilmiş yazı tiplerinin kaynakları. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Bazen HTML işaretlemesinin oluşturulması için özel gereksinimler bulunur. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bu tür özel gereksinimlere uyacak şekilde kullanılabilecek HTML hazırlama modlarını tanımlar. |
| [getImageResolution](#getImageResolution--) | Görüntü işleme çözünürlüğünü alır veya ayarlar. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Sonuç HTML'de kelimeler içindeki harflerin konumlandırma modunu ayarlar. |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Bu öznitelik, grafik yol çizgisinin minimum genişliğini ayarlar. Çizgi kalınlığı 1px'den az ise Adobe Acrobat bu değere yuvarlar. Bu nedenle bu öznitelik, HTML tarayıcıları için bu davranışı taklit etmek amacıyla kullanılabilir. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafına (varsa) kenarlık çizmek için kullanılan ayar kümesini temsil eder. Esas olarak, PDF sayfasında tanımlı sayfa kenarı değil, sayfanın kağıt kenarlarının gösterilmesiyle ilgilidir. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafındaki ek sayfa kenar boşluklarını (varsa) temsil eder. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Referans verilen dosyaların (HTML, Yazı Tipleri, Görseller, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak oluşturulup oluşturulmayacağını tanımlar |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Dönüştürülen PDF raster görüntüler içerebilir. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bunların nasıl işleneceğini tanımlar. |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Belge HTML olarak kaydedilirken karşılaşılan tüm görüntülerin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise görüntü dosyaları (varsa) HTML'ye bağlı diğer dosyalarla birlikte kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Belge HTML olarak kaydedilirken karşılaşılan yalnızca SVG görüntülerinin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise SVG dosyaları (varsa) diğer görüntü dosyalarıyla birlikte (çıkış dosyasının yakınında) veya SpecialImagesFolderIfAny seçeneğinde belirtilmişse özel bir görüntü klasöründe kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez. |
| [getTitle](#getTitle--) | HTML sayfa başlığını alır veya ayarlar. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Bulunan SVG grafiklerinin (varsa) kaydetme sırasında SVGZ formatına sıkıştırılıp (ziplenip) yapılacağını gösteren bayrağı alır. Değer: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | ConvertMarkedContentToLayers özniteliği true olarak ayarlanırsa, PDF işaretli içeriği (katman) içindeki tüm öğeler, katman adını belirten \"data-pdflayer\" özniteliğine sahip bir HTML div'ine yerleştirilecektir. Bu katman adı, PDF işaretli içeriğinin isteğe bağlı özelliklerinden çıkarılacaktır. Bu öznitelik false (varsayılan) ise PDF işaretli içeriğinden hiçbir katman oluşturulmaz. |
| [isFixedLayout](#isFixedLayout--) | HTML'nin sabit düzen olarak oluşturulup oluşturulmadığını gösteren bir değeri alır. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false. |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Eğer 'SplitOnPages=false' özniteliği kullanılırsa, tüm giriş PDF sayfalarını temsil eden HTML tek büyük sonuç HTML dosyasına yerleştirilecektir. Bu bayrak, sonuç HTML'nin, PDF sayfalarını temsil eden alanların akışının görüntüleyicinin ekran çözünürlüğüne bağlı olacak şekilde oluşturulup oluşturulmayacağını tanımlar. Görüntüleyicideki ekran genişliğinin, yatay yönde 2 veya daha fazla sayfayı yan yana koymaya yeterli olduğunu varsayalım. Bu bayrak true olarak ayarlanırsa, bu fırsat kullanılacaktır (mümkün olduğu kadar çok sayfa yatay yönde yan yana gösterilecek, ardından bir sonraki yatay sayfa grubu ilk grubun altında gösterilecektir). Aksi takdirde sayfalar şu şekilde akacaktır: sonraki sayfa her zaman öncekinin altında yer alır. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Bu öznitelik, metin gliflerinin kelimeler ve dizeler halinde gruplanmayacağı bir modu etkinleştirir. Bu mod, sayfadaki gliflerin konumlandırılmasında en yüksek hassasiyeti korumayı sağlar ve müzik notaları veya birbirinden ayrı ayrı yerleştirilmesi gereken glifler içeren belgelerin dönüştürülmesinde kullanılabilir. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Oluşturulan HTML'de herhangi bir içerik bulunmayan üst ve alt boş alanların kaldırılıp kaldırılmayacağını tanımlar (varsa). |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Eğer RenderTextAsImage özniteliği true olarak ayarlanırsa, kaynaktaki metin HTML'de bir görüntü haline gelir. Metni seçilemez kılmak veya HTML metni düzgün render edilmediğinde faydalı olabilir. |
| [isSaveFullFont](#isSaveFullFont--) | Tam fontun kaydedileceğini gösterir, yalnızca True Type Fontları destekler. Varsayılan olarak SaveFullFont = false ve dönüştürücü, belgenin metnini görüntülemek için gereken başlangıç fontunun alt kümesini kaydeder. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Pdf, başka öğeler (ör. görüntüler) tarafından gölgelenmiş metinler içerebilir ancak Acrobat Reader'da panoya seçilebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip Acrobat Reader davranışını taklit edip etmeyeceğimizi söyler (aksi takdirde bu metinler genellikle gizli olarak kaydedilir ve panoya kopyalanamaz). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Pdf, panoya seçilebilen şeffaf metinler içerebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip kaydetmeyeceğimizi belirtir. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Bu öznitelik, gliflerin ve kelimelerin dize halinde sıralı gruplandırılmasını belirtir. Örneğin, etiketler ve kelimeler dönüştürülmüş HTML'de farklı sıraya sahiptir ve bunların eşleşmesini isteyebilirsiniz. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Çok sayfalı mod seçildiğinde (yani 'SplitIntoPages' true olduğunda), bu öznitelik her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını tanımlar. Varsayılan olarak bu öznitelik false olduğundan, oluşturulan tüm sayfalar için tek büyük ortak CSS oluşturulur. Bu modda (sayfa başına bir CSS) üretilen tüm CSS'lerin toplam boyutu genellikle tek büyük CSS dosyasının boyutundan çok daha fazladır, çünkü önceki durumda CSS sınıfları her sayfa için birkaç CSS dosyasında tekrar eder. Bu nedenle bu ayar, yalnızca her HTML sayfasını bağımsız olarak ileride işlemek istediğinizde ve dolayısıyla her bir sayfanın ayrı CSS boyutunun en kritik konu olduğu durumlarda kullanılmalıdır. |
| [isSplitIntoPages](#isSplitIntoPages--) | Kaynak belgenin her sayfasının kendi hedef HTML belgesine dönüştürülüp dönüştürülmeyeceğini gösteren bayrağı alır, yani sonuç HTML'nin birkaç HTML sayfasına bölünüp bölünmeyeceğini belirtir. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF kendisi metinler için alt çizgi işaretleri içermez. Altına yerleştirilen bir çizgiyle taklit edilir. Bu seçenek, dönüştürücünün bu ya da o çizginin metnin alt çizgisi olduğunu tahmin etmeye çalışmasını ve alt çizgiyi grafik olarak çizmeye yerine bu bilgiyi CSS'e yerleştirmesini sağlar. |
| [isUseZOrder](#isUseZOrder--) | Eğer UseZORder özniteliği true olarak ayarlanırsa, grafikler ve metinler orijinal PDF belgesindeki Z-sırasına göre sonuç HTML belgesine eklenir. Bu öznitelik false ise, tüm grafikler tek bir katmana konur ve üst üste binen nesneler için bazı gereksiz etkiler oluşabilir. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Eğer 'SplitOnPages=false' özniteliği belirtilmişse, tüm giriş PDF sayfalarını temsil eden HTML, farklı HTML sayfalarına bölünmez, tek büyük bir sonuç HTML dosyasına yerleştirilir. Ancak her kaynak PDF sayfası, HTML içinde kendi dikdörtgen alanı ile temsil edilir (gerekirse bu alanlar, 'PageBorderIfAny' adlı özel öznitelik ile sayfa kağıdı kenarlarını gösterecek şekilde kenarlıklandırılabilir). Bu parametre, çıktı HTML alanlarının etrafında zorunlu olarak bırakılacak kenar boşluğunun genişliğini tanımlar; bu alanlar kaynak PDF belgesinin sayfalarını temsil eder. Esasen, PDF \"paper\" sayfalarının HTML temsilleri arasındaki garantili aralığı tanımlar. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Bu parametre, PDF'ten HTML'e bileşik arka plan görüntülerinin dönüşümü sırasında gerekli anti-aliasing önlemlerini tanımlar. |
| [setBatchSize](#setBatchSize-int-) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Kaydetme sırasında bulunan SVG grafiklerinin (varsa) SVGZ formatına sıkıştırılıp (zipped) yapılacağını gösteren bayrağı ayarlar. Değer: {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | ConvertMarkedContentToLayers özniteliği true olarak ayarlanırsa, PDF işaretli içeriği (katman) içindeki tüm öğeler, katman adını belirten \"data-pdflayer\" özniteliğine sahip bir HTML div'ine yerleştirilecektir. Bu katman adı, PDF işaretli içeriğinin isteğe bağlı özelliklerinden çıkarılacaktır. Bu öznitelik false (varsayılan) ise PDF işaretli içeriğinden hiçbir katman oluşturulmaz. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | PDFtoHTML dönüştürücüsü sonuç CSS'leri oluşturduğunda, CSS sınıf adları (örneğin \".stl_01 {}\" ... \".stl_NN {}\") üretilir ve sonuç CSS içinde kullanılır. Bu özellik, sınıf adı önekini zorunlu olarak ayarlamayı sağlar. Örneğin, tüm sınıf adlarının 'my_prefix_' ile başlamasını istiyorsanız (yani 'my_prefix_1' ... 'my_prefix_NNN' gibi), dönüştürmeden önce bu özelliğe 'my_prefix_' değerini atayın. Bu özellik dokunulmaz bırakılırsa (yani değer olarak null bırakılırsa), dönüştürücü sınıf adlarını kendisi oluşturur (örneğin \".stl_01 {}\" ... \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Bu alan, PDF'ten HTML'e dönüşüm sırasında (varsa) oluşturulan HTML belgesinin tamamına ya da sayfalarına ilişkin CSS dosyalarının kaydedilmesi için kullanılacak kaydetme stratejisini içerebilir (birden fazla HTML sayfası oluşturuluyorsa). CSS dosyasını belirli bir şekilde işlemek istiyorsanız, lütfen ilgili yöntemi oluşturun ve ondan oluşturulan temsilciyi bu özelliğe atayın. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Dönüşüm sonucu bir veya birden fazla HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının (doğru bir ifadeyle - işaretleme-HTML, varsa dış bağlantılı dosyalar olmadan) işlenmesini sağlayan özel bir yöntemden oluşturulan delegeyi atayabilirsiniz. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir, örn. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Bu alan, kaydedilen HTML'nin düğümleriyle ilişkili oluşturulan başvurulu kaynak dosyalarının (örneğin görüntüler ve yazı tipleri) özelleştirilmiş işlenmesi için dönüşüm sırasında (varsa) kullanılacak kaydetme stratejisini içerebilir. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Bu alan, konu CSS'nin oluşturulan sonuç HTML'sine yerleştirilmesi gereken URL'yi (veya çok sayfalı oluşturma açıksa URL şablonunu - ayrıntılar aşağıda) döndüren özel bir yöntemi içerebilir. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Sistemde yüklü olmayan ve belgeye gömülmemiş herhangi bir yazı tipinin yerine kullanılacak yüklü bir yazı tipinin adını belirtir. Null ise varsayılan yedek yazı tipi kullanılır. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | {@code HtmlDocumentType} ayarlar. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | HTML'de gömülemeyecek PDF gömülü yazı tipi adlarının listesi. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır. Listedeki sayfaların görünüm sırası, sonuç HTML sayfalarındaki sıralarını etkilemez – sonuç sayfalar her zaman kaynak PDF'de bulundukları sırayla görüntülenir. Bu liste null ise (varsayılan olarak olduğu gibi), tüm sayfalar dönüştürülür. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların (1-[amountOfPagesInDocument]) aralığının dışına çıkarsa bir istisna fırlatılır. |
| [setFixedLayout](#setFixedLayout-boolean-) | HTML'nin sabit düzen olarak oluşturulup oluşturulmadığını gösteren bir değeri ayarlar. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Bu öznitelik, Akış modu için tam genişlikte paragraf metnini belirtir, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Mevcut belge için PDF kod çözümlemesini ayarlamak amacıyla kodlama özel kuralını tanımlar |
| [setFontSavingMode](#setFontSavingMode-int-) | PDF'nin istenen formata kaydedilmesi sırasında kullanılacak yazı tipi kaydetme modunu tanımlar |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Bazen HTML işaretlemesinin oluşturulması için özel gereksinimler bulunur. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bu tür özel gereksinimlere uyacak şekilde kullanılabilecek HTML hazırlama modlarını tanımlar. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false. |
| [setImageResolution](#setImageResolution-int-) | Görüntü işleme çözünürlüğünü alır veya ayarlar. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Sonuç HTML'de kelimeler içindeki harflerin konumlandırma modunu ayarlar. |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Bu öznitelik, grafik yol çizgisinin minimum genişliğini ayarlar. Çizgi kalınlığı 1px'den az ise Adobe Acrobat bu değere yuvarlar. Bu nedenle bu öznitelik, HTML tarayıcıları için bu davranışı taklit etmek amacıyla kullanılabilir. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Bu öznitelik, kaynak PDF sayfasını temsil eden alanın etrafında sonuç HTML belgesinde (varsa) kenarlık çizmek için kullanılan ayar kümesini temsil eder. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafındaki ek sayfa kenar boşluklarını (varsa) temsil eder. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Eğer 'SplitOnPages=false' özniteliği kullanılırsa, tüm giriş PDF sayfalarını temsil eden HTML tek büyük sonuç HTML dosyasına yerleştirilecektir. Bu bayrak, sonuç HTML'nin, PDF sayfalarını temsil eden alanların akışının görüntüleyicinin ekran çözünürlüğüne bağlı olacak şekilde oluşturulup oluşturulmayacağını tanımlar. Görüntüleyicideki ekran genişliğinin, yatay yönde 2 veya daha fazla sayfayı yan yana koymaya yeterli olduğunu varsayalım. Bu bayrak true olarak ayarlanırsa, bu fırsat kullanılacaktır (mümkün olduğu kadar çok sayfa yatay yönde yan yana gösterilecek, ardından bir sonraki yatay sayfa grubu ilk grubun altında gösterilecektir). Aksi takdirde sayfalar şu şekilde akacaktır: sonraki sayfa her zaman öncekinin altında yer alır. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Referans verilen dosyaların (HTML, Yazı Tipleri, Görseller, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak oluşturulup oluşturulmayacağını tanımlar |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Bu öznitelik, metin gliflerinin kelimeler ve dizeler halinde gruplanmayacağı bir modu etkinleştirir. Bu mod, sayfadaki gliflerin konumlandırılmasında en yüksek hassasiyeti korumayı sağlar ve müzik notaları veya birbirinden ayrı ayrı yerleştirilmesi gereken glifler içeren belgelerin dönüştürülmesinde kullanılabilir. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Dönüştürülen PDF raster görüntüler içerebilir. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bunların nasıl işleneceğini tanımlar. |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Oluşturulan HTML'de herhangi bir içerik bulunmayan üst ve alt boş alanların kaldırılıp kaldırılmayacağını tanımlar (varsa). |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Eğer RenderTextAsImage özniteliği true olarak ayarlanırsa, kaynaktaki metin HTML'de bir görüntü haline gelir. Metni seçilemez kılmak veya HTML metni düzgün render edilmediğinde faydalı olabilir. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Tam fontun kaydedileceğini gösterir, yalnızca True Type Fontları destekler. Varsayılan olarak SaveFullFont = false ve dönüştürücü, belgenin metnini görüntülemek için gereken başlangıç fontunun alt kümesini kaydeder. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf, başka öğeler (ör. görüntüler) tarafından gölgelenmiş metinler içerebilir ancak Acrobat Reader'da panoya seçilebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip Acrobat Reader davranışını taklit edip etmeyeceğimizi söyler (aksi takdirde bu metinler genellikle gizli olarak kaydedilir ve panoya kopyalanamaz). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Pdf, panoya seçilebilen şeffaf metinler içerebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip kaydetmeyeceğimizi belirtir. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Bu öznitelik, gliflerin ve kelimelerin dize halinde sıralı gruplandırılmasını belirtir. Örneğin, etiketler ve kelimeler dönüştürülmüş HTML'de farklı sıraya sahiptir ve bunların eşleşmesini isteyebilirsiniz. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Belge HTML olarak kaydedilirken karşılaşılan tüm görüntülerin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise görüntü dosyaları (varsa) HTML'ye bağlı diğer dosyalarla birlikte kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Belge HTML olarak kaydedilirken karşılaşılan yalnızca SVG görüntülerinin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise SVG dosyaları (varsa) diğer görüntü dosyalarıyla birlikte (çıkış dosyasının yakınında) veya SpecialImagesFolderIfAny seçeneğinde belirtilmişse özel bir görüntü klasöründe kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Çok sayfalı mod seçildiğinde (yani 'SplitIntoPages' true olduğunda), bu öznitelik her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını tanımlar. Varsayılan olarak bu öznitelik false olduğundan, oluşturulan tüm sayfalar için tek büyük ortak CSS oluşturulur. Bu modda (sayfa başına bir CSS) üretilen tüm CSS'lerin toplam boyutu genellikle tek büyük CSS dosyasının boyutundan çok daha fazladır, çünkü önceki durumda CSS sınıfları her sayfa için birkaç CSS dosyasında tekrar eder. Bu nedenle bu ayar, yalnızca her HTML sayfasını bağımsız olarak ileride işlemek istediğinizde ve dolayısıyla her bir sayfanın ayrı CSS boyutunun en kritik konu olduğu durumlarda kullanılmalıdır. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Kaynak belgenin her sayfasının kendi hedef HTML belgesine dönüştürülüp dönüştürülmeyeceğini gösteren bayrağı ayarlar, yani sonuç HTML'nin birden fazla HTML sayfasına bölünüp bölünmeyeceğini belirler. |
| [setTitle](#setTitle-java.lang.String-) | HTML sayfa başlığını alır veya ayarlar. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF kendisi metinler için alt çizgi işaretleri içermez. Altına yerleştirilen bir çizgiyle taklit edilir. Bu seçenek, dönüştürücünün bu ya da o çizginin metnin alt çizgisi olduğunu tahmin etmeye çalışmasını ve alt çizgiyi grafik olarak çizmeye yerine bu bilgiyi CSS'e yerleştirmesini sağlar. |
| [setUseZOrder](#setUseZOrder-boolean-) | Eğer UseZORder özniteliği true olarak ayarlanırsa, grafikler ve metinler orijinal PDF belgesindeki Z-sırasına göre sonuç HTML belgesine eklenir. Bu öznitelik false ise, tüm grafikler tek bir katmana konur ve üst üste binen nesneler için bazı gereksiz etkiler oluşabilir. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

HtmlSaveOptions sınıfının yeni bir örneğini başlatır.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

{@code HtmlSaveOptions} sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fixedLayout |  | boolean değer |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
HtmlSaveOptions sınıfının yeni bir örneğini başlatır.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
HtmlSaveOptions sınıfının yeni bir örneğini başlatır.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Eğer 'SplitOnPages=false' özniteliği belirtilmişse, tüm giriş PDF sayfalarını temsil eden HTML, farklı HTML sayfalarına bölünmez, tek büyük bir sonuç HTML dosyasına yerleştirilir. Ancak her kaynak PDF sayfası, HTML içinde kendi dikdörtgen alanı ile temsil edilir (gerekirse bu alanlar, 'PageBorderIfAny' adlı özel öznitelik ile sayfa kağıdı kenarlarını gösterecek şekilde kenarlıklandırılabilir). Bu parametre, çıktı HTML alanlarının etrafında zorunlu olarak bırakılacak kenar boşluğunun genişliğini tanımlar; bu alanlar kaynak PDF belgesinin sayfalarını temsil eder. Esasen, PDF \"paper\" sayfalarının HTML temsilleri arasındaki garantili aralığı tanımlar.

**Returns:**
int değer @deprecated AdditionalMarginWidthInPoints kullanımdan kaldırıldı, lütfen yerine PageMarginIfAny kullanın.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Bu parametre, PDF'ten HTML'e bileşik arka plan görüntülerinin dönüşümü sırasında gerekli anti-aliasing önlemlerini tanımlar.

**Returns:**
AntialiasingProcessingType öğesi @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Returns:**
int değer

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

PDFtoHTML dönüştürücüsü sonuç CSS'leri oluşturduğunda, CSS sınıf adları (örneğin \".stl_01 {}\" ... \".stl_NN {}\") üretilir ve sonuç CSS içinde kullanılır. Bu özellik, sınıf adı önekini zorunlu olarak ayarlamayı sağlar. Örneğin, tüm sınıf adlarının 'my_prefix_' ile başlamasını istiyorsanız (yani 'my_prefix_1' ... 'my_prefix_NNN' gibi), dönüştürmeden önce bu özelliğe 'my_prefix_' değerini atayın. Bu özellik dokunulmaz bırakılırsa (yani değer olarak null bırakılırsa), dönüştürücü sınıf adlarını kendisi oluşturur (örneğin \".stl_01 {}\" ... \".stl_NN {}\").

**Returns:**
String değeri

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Bu alan, PDF'ten HTML'e dönüşüm sırasında (varsa) oluşturulan HTML belgesinin tamamına ya da sayfalarına ilişkin CSS dosyalarının kaydedilmesi için kullanılacak kaydetme stratejisini içerebilir (birden fazla HTML sayfası oluşturuluyorsa). CSS dosyasını belirli bir şekilde işlemek istiyorsanız, lütfen ilgili yöntemi oluşturun ve ondan oluşturulan temsilciyi bu özelliğe atayın.

**Returns:**
CssSavingStrategy örneği

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Dönüşüm sonucu bir veya birkaç HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının (tam olarak - işaretleme-HTML, varsa dışa bağlı dosyalar olmadan) işlenmesini sağlayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Bu durumda, işleme (örneğin sayfanın HTML'inin akışa veya diske kaydedilmesi) bu özel kod içinde yapılabilir. Bu durumda, HTML sayfasının kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü dönüştürücünün kodundaki kaydetme kullanılmayacaktır. Bu ya da o durum için işleme bir sebeple dönüştürücünün kodu tarafından, özel kod yerine yapılması gerekiyorsa, lütfen özel kod içinde 'htmlSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye kaynağın işlenmesi için gerekli tüm adımların, dışarıda herhangi bir özel kod bulunmuyormuş gibi, dönüştürücü içinde yapılması gerektiğini bildirecektir.

**Returns:**
HtmlPageMarkupSavingStrategy örneği

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir; örneğin işlenen sayfaların mevcut miktarı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir. Konsolda ilerlemeyi gösteren işleyici kodunun örneği şu şekildedir: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler örneği

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Bu alan, dönüşüm sırasında (varsa) oluşturulan referanslı kaynak dosyalarının (örneğin görüntüler ve yazı tipleri) kaydedilmiş HTML düğümleriyle ilgili özelleştirilmiş işlenmesi için kullanılacak kaydetme stratejisini içerebilir. Bu strateji, kaynakları işleyecek ve oluşturulan HTML'de kaydedilen kaynağın istenen URL'sini temsil eden bir dize döndürecektir.

**Returns:**
ResourceSavingStrategy örneği

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Bu alan, oluşturulan sonuç HTML'ye yerleştirilecek konu CSS'nin URL'sini (veya çok sayfalı oluşturma açıksa URL şablonunu - aşağıdaki detaylara bakınız) döndüren özel bir yöntemi içerebilir. Örneğin, dönüştürücünün oluşturulan CSS içinde standart CSS dosya adı yerine belirli bir URL koymasını istiyorsanız, bu özelliğe istenen URL'yi üreten bir yöntem oluşturup atamanız yeterlidir. 'SplitCssIntoPages' bayrağı ayarlıysa, bu özel strateji (varsa) CSS'nin kesin URL'si yerine, (dönüştürücü içinde String.Format() işleviyle sayfa numarası yer tutucusunun değiştirilmesinden sonra) bu veya o sayfanın CSS URL'sine çözülebilecek bir şablon dizesi döndürmelidir. Bu durumda beklenen dönüş dizesine örnekler: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }'

**Returns:**
CssUrlMakingStrategy örneği

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Sistemde yüklü olmayan ve belgeye gömülmemiş herhangi bir yazı tipinin yerine kullanılacak yüklü bir yazı tipinin adını belirtir. Null ise varsayılan yedek yazı tipi kullanılır.

**Returns:**
String değer: Yazı tipi adı

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Alır {@code HtmlDocumentTypeInternal}.

**Returns:**
Bu {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

HTML'de gömülemeyecek PDF gömülü yazı tipi adlarının listesi.

**Returns:**
String öğelerinden oluşan dizi

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır. Listedeki sayfaların görünüm sırası, sonuç HTML sayfalarındaki sıralarını etkilemez – sonuç sayfalar her zaman kaynak PDF'de bulundukları sırayla görüntülenir. Bu liste null ise (varsayılan olarak olduğu gibi), tüm sayfalar dönüştürülür. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların (1-[amountOfPagesInDocument]) aralığının dışına çıkarsa bir istisna fırlatılır.

**Returns:**
int dizisi

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Bu öznitelik, Akış modu için tam genişlikte paragraf metnini belirtir, FixedLayout = false

**Returns:**
boolean değer

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Mevcut belge için PDF kod çözümlemesini ayarlamak amacıyla kodlama özel kuralını tanımlar

**Returns:**
FontEncodingRules öğesi @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

PDF'nin istenen formata kaydedilmesi sırasında kullanılacak yazı tipi kaydetme modunu tanımlar

**Returns:**
FontSavingModes öğesi @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Önceden kaydedilmiş yazı tiplerinin kaynakları. </p>

**Returns:**
FontSourceCollection nesnesi <hr> <p> Yazı tipleri önceden önbellek amacıyla kaydedilebilir ve ardından Html dönüşüm sürecine aktarılabilir. Örneğin, belge bölme senaryosunda ve birden çok iş parçacığında tek bir yazı tipi setiyle belge sayfalarını işlemek için faydalı olabilir. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Bazen HTML işaretlemesinin oluşturulması için özel gereksinimler bulunur. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bu tür özel gereksinimlere uyacak şekilde kullanılabilecek HTML hazırlama modlarını tanımlar.

**Returns:**
HtmlMarkupGenerationModes öğesi @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Görüntü işleme çözünürlüğünü alır veya ayarlar.

**Returns:**
Değer: Çözünürlük

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Sonuç HTML'de kelimeler içindeki harflerin konumlandırma modunu ayarlar.

**Returns:**
LettersPositioningMethods öğesi @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Bu öznitelik, grafik yol çizgisinin minimum genişliğini ayarlar. Çizgi kalınlığı 1px'den az ise Adobe Acrobat bu değere yuvarlar. Bu nedenle bu öznitelik, HTML tarayıcıları için bu davranışı taklit etmek amacıyla kullanılabilir.

**Returns:**
float değer

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafına (varsa) kenarlık çizmek için kullanılan ayar kümesini temsil eder. Esas olarak, PDF sayfasında tanımlı sayfa kenarı değil, sayfanın kağıt kenarlarının gösterilmesiyle ilgilidir.

**Returns:**
BorderInfo örneği

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafındaki ek sayfa kenar boşluklarını (varsa) temsil eder.

**Returns:**
MarginInfo örneği

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Referans verilen dosyaların (HTML, Yazı Tipleri, Görseller, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak oluşturulup oluşturulmayacağını tanımlar

**Returns:**
PartsEmbeddingModes öğesi @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Dönüştürülen PDF raster görüntüler içerebilir. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bunların nasıl işleneceğini tanımlar.

**Returns:**
RasterImagesSavingModes öğesi @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Belge HTML olarak kaydedilirken karşılaşılan tüm görüntülerin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise görüntü dosyaları (varsa) HTML'ye bağlı diğer dosyalarla birlikte kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez.

**Returns:**
String değeri

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Belge HTML olarak kaydedilirken karşılaşılan yalnızca SVG görüntülerinin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise SVG dosyaları (varsa) diğer görüntü dosyalarıyla birlikte (çıkış dosyasının yakınında) veya SpecialImagesFolderIfAny seçeneğinde belirtilmişse özel bir görüntü klasöründe kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez.

**Returns:**
String değeri

### getTitle {#getTitle--}
```
public final String getTitle()
```

HTML sayfa başlığını alır veya ayarlar.

**Returns:**
String değeri

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Bulunan SVG grafiklerinin (varsa) kaydetme sırasında SVGZ formatına sıkıştırılıp (ziplenip) yapılacağını gösteren bayrağı alır. Değer: {@code HtmlDocumentType}.

**Returns:**
boolean değer

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

ConvertMarkedContentToLayers özniteliği true olarak ayarlanırsa, PDF işaretli içeriği (katman) içindeki tüm öğeler, katman adını belirten \"data-pdflayer\" özniteliğine sahip bir HTML div'ine yerleştirilecektir. Bu katman adı, PDF işaretli içeriğinin isteğe bağlı özelliklerinden çıkarılacaktır. Bu öznitelik false (varsayılan) ise PDF işaretli içeriğinden hiçbir katman oluşturulmaz.

**Returns:**
boolean değer

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

HTML'nin sabit düzen olarak oluşturulup oluşturulmadığını gösteren bir değeri alır.

**Returns:**
değer: {@code true} eğer [fixed layout]; aksi takdirde {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false.

**Returns:**
boolean değer

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Eğer 'SplitOnPages=false' özniteliği kullanılırsa, tüm giriş PDF sayfalarını temsil eden HTML tek büyük sonuç HTML dosyasına yerleştirilecektir. Bu bayrak, sonuç HTML'nin, PDF sayfalarını temsil eden alanların akışının görüntüleyicinin ekran çözünürlüğüne bağlı olacak şekilde oluşturulup oluşturulmayacağını tanımlar. Görüntüleyicideki ekran genişliğinin, yatay yönde 2 veya daha fazla sayfayı yan yana koymaya yeterli olduğunu varsayalım. Bu bayrak true olarak ayarlanırsa, bu fırsat kullanılacaktır (mümkün olduğu kadar çok sayfa yatay yönde yan yana gösterilecek, ardından bir sonraki yatay sayfa grubu ilk grubun altında gösterilecektir). Aksi takdirde sayfalar şu şekilde akacaktır: sonraki sayfa her zaman öncekinin altında yer alır.

**Returns:**
boolean değer

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Bu öznitelik, metin gliflerinin kelimeler ve dizeler halinde gruplanmayacağı bir modu etkinleştirir. Bu mod, sayfadaki gliflerin konumlandırılmasında en yüksek hassasiyeti korumayı sağlar ve müzik notaları veya birbirinden ayrı ayrı yerleştirilmesi gereken glifler içeren belgelerin dönüştürülmesinde kullanılabilir. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır.

**Returns:**
boolean değer

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Oluşturulan HTML'de herhangi bir içerik bulunmayan üst ve alt boş alanların kaldırılıp kaldırılmayacağını tanımlar (varsa).

**Returns:**
boolean değer

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Eğer RenderTextAsImage özniteliği true olarak ayarlanırsa, kaynaktaki metin HTML'de bir görüntü haline gelir. Metni seçilemez kılmak veya HTML metni düzgün render edilmediğinde faydalı olabilir.

**Returns:**
boolean değer

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Tam fontun kaydedileceğini gösterir, yalnızca True Type Fontları destekler. Varsayılan olarak SaveFullFont = false ve dönüştürücü, belgenin metnini görüntülemek için gereken başlangıç fontunun alt kümesini kaydeder.

**Returns:**
boolean değer

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Pdf, başka öğeler (ör. görüntüler) tarafından gölgelenmiş metinler içerebilir ancak Acrobat Reader'da panoya seçilebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip Acrobat Reader davranışını taklit edip etmeyeceğimizi söyler (aksi takdirde bu metinler genellikle gizli olarak kaydedilir ve panoya kopyalanamaz).

**Returns:**
boolean değer

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Pdf, panoya seçilebilen şeffaf metinler içerebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip kaydetmeyeceğimizi belirtir.

**Returns:**
boolean değer

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Bu öznitelik, gliflerin ve kelimelerin dize halinde sıralı gruplandırılmasını belirtir. Örneğin, etiketler ve kelimeler dönüştürülmüş HTML'de farklı sıraya sahiptir ve bunların eşleşmesini isteyebilirsiniz. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır.

**Returns:**
boolean değer

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Çok sayfalı mod seçildiğinde (yani 'SplitIntoPages' true olduğunda), bu öznitelik her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını tanımlar. Varsayılan olarak bu öznitelik false olduğundan, oluşturulan tüm sayfalar için tek büyük ortak CSS oluşturulur. Bu modda (sayfa başına bir CSS) üretilen tüm CSS'lerin toplam boyutu genellikle tek büyük CSS dosyasının boyutundan çok daha fazladır, çünkü önceki durumda CSS sınıfları her sayfa için birkaç CSS dosyasında tekrar eder. Bu nedenle bu ayar, yalnızca her HTML sayfasını bağımsız olarak ileride işlemek istediğinizde ve dolayısıyla her bir sayfanın ayrı CSS boyutunun en kritik konu olduğu durumlarda kullanılmalıdır.

**Returns:**
boolean değer

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Kaynak belgenin her sayfasının kendi hedef HTML belgesine dönüştürülüp dönüştürülmeyeceğini gösteren bayrağı alır, yani sonuç HTML'nin birkaç HTML sayfasına bölünüp bölünmeyeceğini belirtir.

**Returns:**
boolean değer

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF kendisi metinler için alt çizgi işaretleri içermez. Altına yerleştirilen bir çizgiyle taklit edilir. Bu seçenek, dönüştürücünün bu ya da o çizginin metnin alt çizgisi olduğunu tahmin etmeye çalışmasını ve alt çizgiyi grafik olarak çizmeye yerine bu bilgiyi CSS'e yerleştirmesini sağlar.

**Returns:**
boolean değer

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Eğer UseZORder özniteliği true olarak ayarlanırsa, grafikler ve metinler orijinal PDF belgesindeki Z-sırasına göre sonuç HTML belgesine eklenir. Bu öznitelik false ise, tüm grafikler tek bir katmana konur ve üst üste binen nesneler için bazı gereksiz etkiler oluşabilir.

**Returns:**
boolean değer

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Eğer 'SplitOnPages=false' özniteliği belirtilmişse, tüm giriş PDF sayfalarını temsil eden HTML, farklı HTML sayfalarına bölünmez, tek büyük bir sonuç HTML dosyasına yerleştirilir. Ancak her kaynak PDF sayfası, HTML içinde kendi dikdörtgen alanı ile temsil edilir (gerekirse bu alanlar, 'PageBorderIfAny' adlı özel öznitelik ile sayfa kağıdı kenarlarını gösterecek şekilde kenarlıklandırılabilir). Bu parametre, çıktı HTML alanlarının etrafında zorunlu olarak bırakılacak kenar boşluğunun genişliğini tanımlar; bu alanlar kaynak PDF belgesinin sayfalarını temsil eder. Esasen, PDF \"paper\" sayfalarının HTML temsilleri arasındaki garantili aralığı tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer @deprecated AdditionalMarginWidthInPoints kullanımdan kaldırıldı, lütfen yerine PageMarginIfAny kullanın. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Bu parametre, PDF'ten HTML'e bileşik arka plan görüntülerinin dönüşümü sırasında gerekli anti-aliasing önlemlerini tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| antialiasingProcessing |  | AntialiasingProcessingType öğesi @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Kaydetme sırasında bulunan SVG grafiklerinin (varsa) SVGZ formatına sıkıştırılıp (zipped) yapılacağını gösteren bayrağı ayarlar. Değer: {@code HtmlDocumentType}.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

ConvertMarkedContentToLayers özniteliği true olarak ayarlanırsa, PDF işaretli içeriği (katman) içindeki tüm öğeler, katman adını belirten \"data-pdflayer\" özniteliğine sahip bir HTML div'ine yerleştirilecektir. Bu katman adı, PDF işaretli içeriğinin isteğe bağlı özelliklerinden çıkarılacaktır. Bu öznitelik false (varsayılan) ise PDF işaretli içeriğinden hiçbir katman oluşturulmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
PDFtoHTML dönüştürücüsü sonuç CSS'leri oluşturduğunda, CSS sınıf adları (örneğin \".stl_01 {}\" ... \".stl_NN {}\") üretilir ve sonuç CSS içinde kullanılır. Bu özellik, sınıf adı önekini zorunlu olarak ayarlamayı sağlar. Örneğin, tüm sınıf adlarının 'my_prefix_' ile başlamasını istiyorsanız (yani 'my_prefix_1' ... 'my_prefix_NNN' gibi), dönüştürmeden önce bu özelliğe 'my_prefix_' değerini atayın. Bu özellik dokunulmaz bırakılırsa (yani değer olarak null bırakılırsa), dönüştürücü sınıf adlarını kendisi oluşturur (örneğin \".stl_01 {}\" ... \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Bu alan, PDF'ten HTML'e dönüşüm sırasında (varsa) oluşturulan HTML belgesinin tamamına ya da sayfalarına ilişkin CSS dosyalarının kaydedilmesi için kullanılacak kaydetme stratejisini içerebilir (birden fazla HTML sayfası oluşturuluyorsa). CSS dosyasını belirli bir şekilde işlemek istiyorsanız, lütfen ilgili yöntemi oluşturun ve ondan oluşturulan temsilciyi bu özelliğe atayın.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Dönüşüm sonucu bir veya birden fazla HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının (doğru bir ifadeyle - işaretleme-HTML, varsa dış bağlantılı dosyalar olmadan) işlenmesini sağlayan özel bir yöntemden oluşturulan delegeyi atayabilirsiniz.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir, örn.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Bu alan, kaydedilen HTML'nin düğümleriyle ilişkili oluşturulan başvurulu kaynak dosyalarının (örneğin görüntüler ve yazı tipleri) özelleştirilmiş işlenmesi için dönüşüm sırasında (varsa) kullanılacak kaydetme stratejisini içerebilir.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Bu alan, konu CSS'nin oluşturulan sonuç HTML'sine yerleştirilmesi gereken URL'yi (veya çok sayfalı oluşturma açıksa URL şablonunu - ayrıntılar aşağıda) döndüren özel bir yöntemi içerebilir.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Sistemde yüklü olmayan ve belgeye gömülmemiş herhangi bir yazı tipinin yerine kullanılacak yüklü bir yazı tipinin adını belirtir. Null ise varsayılan yedek yazı tipi kullanılır.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
{@code HtmlDocumentType} ayarlar.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
HTML'de gömülemeyecek PDF gömülü yazı tipi adlarının listesi.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır. Listedeki sayfaların görünüm sırası, sonuç HTML sayfalarındaki sıralarını etkilemez – sonuç sayfalar her zaman kaynak PDF'de bulundukları sırayla görüntülenir. Bu liste null ise (varsayılan olarak olduğu gibi), tüm sayfalar dönüştürülür. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların (1-[amountOfPagesInDocument]) aralığının dışına çıkarsa bir istisna fırlatılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

HTML'nin sabit düzen olarak oluşturulup oluşturulmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | : {@code true} eğer [fixed layout]; aksi takdirde {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Bu öznitelik, Akış modu için tam genişlikte paragraf metnini belirtir, FixedLayout = false

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Mevcut belge için PDF kod çözümlemesini ayarlamak amacıyla kodlama özel kuralını tanımlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontEncodingStrategy |  | FontEncodingRules öğesi @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

PDF'nin istenen formata kaydedilmesi sırasında kullanılacak yazı tipi kaydetme modunu tanımlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSavingMode |  | FontSavingModes öğesi @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Bazen HTML işaretlemesinin oluşturulması için özel gereksinimler bulunur. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bu tür özel gereksinimlere uyacak şekilde kullanılabilecek HTML hazırlama modlarını tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | HtmlMarkupGenerationModes öğesi @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Görüntü işleme çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Değer: Çözünürlük |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Sonuç HTML'de kelimeler içindeki harflerin konumlandırma modunu ayarlar.

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Bu öznitelik, grafik yol çizgisinin minimum genişliğini ayarlar. Çizgi kalınlığı 1px'den az ise Adobe Acrobat bu değere yuvarlar. Bu nedenle bu öznitelik, HTML tarayıcıları için bu davranışı taklit etmek amacıyla kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Bu öznitelik, kaynak PDF sayfasını temsil eden alanın etrafında sonuç HTML belgesinde (varsa) kenarlık çizmek için kullanılan ayar kümesini temsil eder.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafındaki ek sayfa kenar boşluklarını (varsa) temsil eder.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Eğer 'SplitOnPages=false' özniteliği kullanılırsa, tüm giriş PDF sayfalarını temsil eden HTML tek büyük sonuç HTML dosyasına yerleştirilecektir. Bu bayrak, sonuç HTML'nin, PDF sayfalarını temsil eden alanların akışının görüntüleyicinin ekran çözünürlüğüne bağlı olacak şekilde oluşturulup oluşturulmayacağını tanımlar. Görüntüleyicideki ekran genişliğinin, yatay yönde 2 veya daha fazla sayfayı yan yana koymaya yeterli olduğunu varsayalım. Bu bayrak true olarak ayarlanırsa, bu fırsat kullanılacaktır (mümkün olduğu kadar çok sayfa yatay yönde yan yana gösterilecek, ardından bir sonraki yatay sayfa grubu ilk grubun altında gösterilecektir). Aksi takdirde sayfalar şu şekilde akacaktır: sonraki sayfa her zaman öncekinin altında yer alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | boolean değer |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Referans verilen dosyaların (HTML, Yazı Tipleri, Görseller, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak oluşturulup oluşturulmayacağını tanımlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| partsEmbeddingMode |  | PartsEmbeddingModes öğesi @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Bu öznitelik, metin gliflerinin kelimeler ve dizeler halinde gruplanmayacağı bir modu etkinleştirir. Bu mod, sayfadaki gliflerin konumlandırılmasında en yüksek hassasiyeti korumayı sağlar ve müzik notaları veya birbirinden ayrı ayrı yerleştirilmesi gereken glifler içeren belgelerin dönüştürülmesinde kullanılabilir. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Dönüştürülen PDF raster görüntüler içerebilir. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bunların nasıl işleneceğini tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImagesSavingMode |  | RasterImagesSavingModes öğesi @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Oluşturulan HTML'de herhangi bir içerik bulunmayan üst ve alt boş alanların kaldırılıp kaldırılmayacağını tanımlar (varsa).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | boolean değer |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Eğer RenderTextAsImage özniteliği true olarak ayarlanırsa, kaynaktaki metin HTML'de bir görüntü haline gelir. Metni seçilemez kılmak veya HTML metni düzgün render edilmediğinde faydalı olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Tam fontun kaydedileceğini gösterir, yalnızca True Type Fontları destekler. Varsayılan olarak SaveFullFont = false ve dönüştürücü, belgenin metnini görüntülemek için gereken başlangıç fontunun alt kümesini kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Pdf, başka öğeler (ör. görüntüler) tarafından gölgelenmiş metinler içerebilir ancak Acrobat Reader'da panoya seçilebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip Acrobat Reader davranışını taklit edip etmeyeceğimizi söyler (aksi takdirde bu metinler genellikle gizli olarak kaydedilir ve panoya kopyalanamaz).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | boolean değer |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Pdf, panoya seçilebilen şeffaf metinler içerebilir (genellikle belge görüntüler ve ondan çıkarılan OCR metinleri içerdiğinde olur). Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedip kaydetmeyeceğimizi belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| saveTransparentTexts |  | boolean değer |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Bu öznitelik, gliflerin ve kelimelerin dize halinde sıralı gruplandırılmasını belirtir. Örneğin, etiketler ve kelimeler dönüştürülmüş HTML'de farklı sıraya sahiptir ve bunların eşleşmesini isteyebilirsiniz. Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Belge HTML olarak kaydedilirken karşılaşılan tüm görüntülerin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise görüntü dosyaları (varsa) HTML'ye bağlı diğer dosyalarla birlikte kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Belge HTML olarak kaydedilirken karşılaşılan yalnızca SVG görüntülerinin kaydedileceği dizin yolunu alır veya ayarlar. Parametre boş veya null ise SVG dosyaları (varsa) diğer görüntü dosyalarıyla birlikte (çıkış dosyasının yakınında) veya SpecialImagesFolderIfAny seçeneğinde belirtilmişse özel bir görüntü klasöründe kaydedilir. İlgili görüntü dosyasını işlemek için CustomImageSavingStrategy özelliği başarıyla kullanıldıysa bu durum hiçbir şeyi etkilemez.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Çok sayfalı mod seçildiğinde (yani 'SplitIntoPages' true olduğunda), bu öznitelik her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını tanımlar. Varsayılan olarak bu öznitelik false olduğundan, oluşturulan tüm sayfalar için tek büyük ortak CSS oluşturulur. Bu modda (sayfa başına bir CSS) üretilen tüm CSS'lerin toplam boyutu genellikle tek büyük CSS dosyasının boyutundan çok daha fazladır, çünkü önceki durumda CSS sınıfları her sayfa için birkaç CSS dosyasında tekrar eder. Bu nedenle bu ayar, yalnızca her HTML sayfasını bağımsız olarak ileride işlemek istediğinizde ve dolayısıyla her bir sayfanın ayrı CSS boyutunun en kritik konu olduğu durumlarda kullanılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Kaynak belgenin her sayfasının kendi hedef HTML belgesine dönüştürülüp dönüştürülmeyeceğini gösteren bayrağı ayarlar, yani sonuç HTML'nin birden fazla HTML sayfasına bölünüp bölünmeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTitle {#setTitle-java.lang.String-}
HTML sayfa başlığını alır veya ayarlar.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF kendisi metinler için alt çizgi işaretleri içermez. Altına yerleştirilen bir çizgiyle taklit edilir. Bu seçenek, dönüştürücünün bu ya da o çizginin metnin alt çizgisi olduğunu tahmin etmeye çalışmasını ve alt çizgiyi grafik olarak çizmeye yerine bu bilgiyi CSS'e yerleştirmesini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | boolean değer |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Eğer UseZORder özniteliği true olarak ayarlanırsa, grafikler ve metinler orijinal PDF belgesindeki Z-sırasına göre sonuç HTML belgesine eklenir. Bu öznitelik false ise, tüm grafikler tek bir katmana konur ve üst üste binen nesneler için bazı gereksiz etkiler oluşabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
