---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptions sınıfı. Html formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 5560
url: /tr/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions Sınıfı

Html formatına dışa aktarma için kaydetme seçenekleri

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | `HtmlSaveOptions` sınıfının yeni bir örneğini başlatır. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | `HtmlSaveOptions` sınıfının yeni bir örneğini başlatır. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | `HtmlSaveOptions` sınıfının yeni bir örneğini başlatır. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | `HtmlSaveOptions` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Kaynak ve hedef format çiftine uygulanabilirse, toplu dönüşüm için toplu boyutunu tanımlar. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken font gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'den diğer formatlara dönüşümün performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belgenin yanıt içine kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Bulunan SVG grafiklerinin (varsa) kaydedilirken SVGZ formatında sıkıştırılıp sıkıştırılmayacağını belirten bayrağı alır veya ayarlar. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | ConvertMarkedContentToLayers özelliği true olarak ayarlandığında, PDF işaretli içeriğindeki tüm öğeler "data-pdflayer" niteliği ile bir HTML div içine yerleştirilecektir. Bu katman adı, PDF işaretli içeriğinin isteğe bağlı özelliklerinden çıkarılacaktır. Bu özellik false (varsayılan olarak) ise, PDF işaretli içeriğinden herhangi bir katman oluşturulmayacaktır. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Sistem içinde gömülü olmayan ve yüklenmemiş herhangi bir belge fontunu ikame etmek için kullanılan yüklü bir fontun adını belirtir. Null ise varsayılan ikame fontu kullanılır. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | [`HtmlDocumentType`](../htmldocumenttype/) alır veya ayarlar. |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır. Bu listedeki sayfaların görünüm sırası, sonuç HTML sayfasındaki sıralarını etkilemez - sonuç sayfaları her zaman kaynak PDF'de mevcut oldukları sırada gidecektir. Bu liste null ise (varsayılan olarak olduğu gibi), tüm sayfalar dönüştürülecektir. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların aralığının dışına çıkarsa (1-[amountOfPagesInDocument]) bir istisna fırlatılacaktır. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için görüntü veya metin çıkarma işlevselliğini etkinleştirir. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | HTML'nin sabit düzen olarak oluşturulup oluşturulmayacağını belirten bir değer alır veya ayarlar. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Bu özellik, Akış modunda tam genişlikte paragraf metnini belirtir, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Önceden kaydedilmiş fontların font kaynakları. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Belirtilen boyutta veya daha küçük olan metin, dönüşüm sırasında göz ardı edilecektir. Bu metni kaldırmıyoruz, göz ardı ediyoruz ve çıktı dosyasına aktarmıyoruz. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Font yokluğuna ilişkin hataların göz ardı edilip edilmeyeceğini belirten bir değer alır veya ayarlar. true - font yokluğu hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara atıfta bulunan metin segmentleri işleme sırasında atlanacaktır. varsayılan olarak false |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Görüntü işleme için çözünürlüğü alır veya ayarlar. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Bu özellik, grafik yolunun minimal kalınlığını ayarlar. Eğer çizgi kalınlığı 1px'den az ise Adobe Acrobat bunu bu değere yuvarlar. Bu nedenle, bu özellik HTML tarayıcıları için bu davranışı taklit etmek için kullanılabilir. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Bu özellik, metin gliflerinin kelimeler ve dizeler halinde gruplanmayacağı modu açar. Bu mod, sayfadaki gliflerin konumlandırılması sırasında maksimum hassasiyeti korumaya olanak tanır ve müzik notaları veya ayrı yerleştirilmesi gereken glifler içeren belgelerin dönüşümü için kullanılabilir. Bu parametre, FixedLayout niteliğinin değeri true olduğunda belgeye uygulanacaktır. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | RenderTextAsImage niteliği true olarak ayarlandığında, kaynak metin HTML'de bir görüntü haline gelir. Metni seçilemez hale getirmek veya HTML metni düzgün bir şekilde işlenmediğinde faydalı olabilir. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Tam fontun kaydedileceğini belirtir, yalnızca True Type Fonts'u destekler. Varsayılan olarak SaveFullFont = false'dır ve dönüştürücü, belgenin metnini görüntülemek için gereken başlangıç fontunun alt kümesini kaydeder. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Bu özellik, gliflerin ve kelimelerin dizeler halinde ardışık gruplamasını belirtir. Örneğin, etiketler ve kelimeler dönüştürülmüş HTML'de farklı bir sıraya sahipse ve bunların eşleşmesini istiyorsanız. Bu parametre, FixedLayout niteliğinin değeri true olduğunda belgeye uygulanacaktır. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Çok sayfalı mod seçildiğinde (yani 'SplitIntoPages' true ise), bu özellik, her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını tanımlar. Varsayılan olarak bu özellik false'dur, bu nedenle, oluşturulan tüm sayfalar için bir büyük ortak CSS oluşturulacaktır. Bu modda üretilen tüm CSS'lerin toplam boyutu (sayfa başına bir CSS) genellikle bir büyük CSS dosyasının boyutundan çok daha fazladır, çünkü önceki durumda CSS sınıfları, her sayfa için birkaç CSS dosyasında tekrar eder. Bu nedenle, bu ayar yalnızca her HTML sayfasının bağımsız olarak gelecekteki işlenmesiyle ilgileniyorsanız kullanılmalıdır ve bu nedenle her bir sayfanın CSS'sinin ayrı ayrı boyutu en kritik konudur. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Kaynak belgenin her sayfasının kendi hedef HTML belgesine dönüştürülüp dönüştürülmeyeceğini belirten bayrağı alır veya ayarlar, yani sonuç HTML'nin birkaç HTML sayfasına bölünüp bölünmeyeceğini. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | HTML sayfa başlığını alır veya ayarlar. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Görüntü parçalarını bir resim haline getirmek için bayrak. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | UseZOrder niteliği true olarak ayarlandığında, grafikler ve metin, orijinal PDF belgesindeki Z sırasına göre sonuç HTML belgesine eklenir. Bu özellik false ise, tüm grafikler tek bir katman olarak yerleştirilir, bu da üst üste binen nesneler için bazı gereksiz etkiler yaratabilir. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir, bu durumda Kaydetme işlemi durmalıdır. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Bu parametre, PDF'den HTML'ye dönüşüm sırasında bileşik arka plan görüntüleri için gerekli kenar yumuşatma önlemlerini tanımlar. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | PDFtoHTML dönüştürücüsü sonuç CSS'leri oluşturduğunda, CSS sınıf adları (".stl_01 {}" ... ".stl_NN {}" gibi) oluşturulur ve sonuç CSS'de kullanılır. Bu özellik, sınıf adı ön ekini zorla ayarlamaya olanak tanır. Örneğin, tüm sınıf adlarının 'my_prefix_' ile başlamasını istiyorsanız (yani 'my_prefix_1' ... 'my_prefix_NNN' gibi), dönüşümden önce bu özelliğe 'my_prefix_' atamanız yeterlidir. Bu özellik dokunulmazsa (yani null değeri bırakılırsa), dönüştürücü sınıf adlarını kendisi oluşturacaktır (bu ".stl_01 {}" ... ".stl_NN {}" gibi olacaktır). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Bu alan, PDF'den HTML'ye dönüşüm sırasında oluşturulan HTML belgesinin tamamı veya sayfaları ile ilgili CSS'lerin kaydedilmesi için kullanılacak kaydetme stratejisini içerebilir (varsa). CSS dosyasını belirli bir şekilde işlemek istiyorsanız, lütfen ilgili yöntemi oluşturun ve bu özelliğe oluşturulan delegasyonu atayın. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Dönüşüm sonucu bir veya birden fazla HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının işlenmesini uygulayan özel bir yöntemden oluşturulan delegasyonu atayabilirsiniz (doğru bir şekilde - harici bağlı dosyalar olmadan işaretleme-HTML). Bu durumda, sayfanın HTML'sinin akışta veya diskte kaydedilmesi gibi işlemler, o özel kodda yapılabilir. Bu durumda, HTML sayfasının kaydedilmesi için gerekli tüm işlemler, sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuç kaydı dönüştürücünün kodunda kullanılmayacaktır. Bu veya diğer durumlar için bir nedenle dönüştürücünün kodu tarafından yapılması gereken işlemler varsa, lütfen özel kodda 'htmlSavingInfo' parametresinin değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini sinyal eder, sanki o kaynağın işlenmesi için herhangi bir harici özel kod yokmuş gibi. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Bu işleyici, dönüşüm ilerleme olaylarını işlemek için kullanılabilir, örneğin, işlenen sayfaların mevcut miktarı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir. İşleyicinin konsolda ilerlemeyi gösteren kod örneği: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Bu alan, oluşturulan referans kaynak dosyalarının (görüntüler ve fontlar gibi) kaydedilmesi için kullanılacak kaydetme stratejisini içerebilir (varsa). Bu strateji, kaynakları işleyecek ve oluşturulan HTML'deki kaydedilen kaynak için istenen URL'yi temsil eden bir dize döndürecektir. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Bu alan, oluşturulan sonuç HTML'de yer alması gereken CSS'nin URL'sini (veya çok sayfalı üretim açık olduğunda URL şablonunu) döndüren özel bir yöntemi içerebilir. Örneğin, dönüştürücünün oluşturulan CSS'de standart CSS dosyası adı yerine belirli bir URL koymasını istiyorsanız, o zaman bu özelliğe istenen URL'yi üreten bir yöntem oluşturmalısınız. 'SplitCssIntoPages' bayrağı ayarlandığında, bu özel strateji (varsa) CSS'nin tam URL'sini değil, daha ziyade yer tutucunun sayfa numarası ile yer değiştirilmesi gereken bir şablon dizesini döndürmelidir. Bu durumda beklenen dönüş dizesi örnekleri: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | HTML'de gömülmeyecek PDF gömülü font adlarının listesi. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Mevcut belgenin PDF çözümlemesini ayarlamak için özel kodlama kuralını tanımlar. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | PDF'yi istenen formata kaydederken kullanılacak font kaydetme modunu tanımlar. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Bazen HTML işaretleme oluşturma için özel gereksinimler vardır. Bu parametre, PDF'den HTML'ye dönüşüm sırasında bu özel gereksinimleri karşılamak için kullanılabilecek HTML hazırlama modlarını tanımlar. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleyin. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Sonuç HTML'deki kelimelerde harflerin konumlandırma modunu ayarlar. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Bu özellik, kaynak PDF sayfasını temsil eden alan etrafında sonuç HTML belgesinde (varsa) kenar çizgisi çizmek için kullanılan ayarların bir kümesini temsil eder. Temelde, sayfanın kağıt kenarlarının gösterilmesi ile ilgilidir, PDF sayfasında atıfta bulunulan sayfa kenarları ile değil. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Bu özellik, kaynak PDF sayfasını temsil eden alan etrafında sonuç HTML belgesinde (varsa) ek sayfa marjını temsil eder. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | 'SplitOnPages=false' niteliği ayarlandığında, tüm HTML, tüm giriş PDF sayfalarını temsil eden tek bir büyük sonuç HTML dosyasına yerleştirilecektir. Bu bayrak, sonuç HTML'nin, sonuç HTML'deki PDF sayfalarını temsil eden alanların akışının görüntüleyicinin ekran çözünürlüğüne bağlı olarak oluşturulup oluşturulmayacağını tanımlar. Görüntüleyici tarafındaki ekranın genişliği, 2 veya daha fazla sayfayı yatay yönde yan yana yerleştirmek için yeterince büyükse. Bu bayrak true olarak ayarlandığında, bu fırsat kullanılacaktır (mümkün olduğunca çok sayfa yatay yönde yan yana gösterilecektir, ardından sonraki yatay sayfa grubu ilkinin altına gösterilecektir). Aksi takdirde, sayfalar şu şekilde akacaktır: sonraki sayfa her zaman önceki sayfanın altına gider. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Referans dosyaların (HTML, Fontlar, Görüntüler, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak mı oluşturulacağını tanımlar. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Dönüştürülen PDF, raster görüntüler içerebilir. Bu parametre, PDF'den HTML'ye dönüşüm sırasında nasıl işleneceklerini tanımlar. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Oluşturulan HTML'de, herhangi bir içerik olmadan (varsa) üst ve alt boş alanların kaldırılıp kaldırılmayacağını tanımlar. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF, başka öğeler (örneğin, görüntüler) tarafından gölgelenmiş metinler içerebilir, ancak Acrobat Reader'da panoya seçilebilir (genellikle bu, belge görüntüler ve OCR ile çıkarılan metinler içerdiğinde olur). Bu ayar, dönüştürücüye, bu metinlerin sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedilip kaydedilmeyeceğini söyler, böylece Acrobat Reader'ın davranışını taklit eder (aksi takdirde, bu metinler genellikle gizli olarak kaydedilir, panoya kopyalamak için mevcut değildir). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF, panoya seçilebilen şeffaf metinler içerebilir (genellikle bu, belge görüntüler ve OCR ile çıkarılan metinler içerdiğinde olur). Bu ayar, dönüştürücüye, bu metinlerin sonuç HTML'de şeffaf seçilebilir metinler olarak kaydedilip kaydedilmeyeceğini söyler. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Herhangi bir görüntü ile karşılaşıldığında kaydedilmesi gereken dizinin yolunu alır veya ayarlar. Parametre boş veya null ise, görüntü dosyaları (varsa) HTML ile bağlantılı diğer dosyalarla birlikte kaydedilecektir. ÖzelImageSavingStrategy özelliği ilgili görüntü dosyasını işlemek için başarıyla kullanıldıysa, bu durum hiçbir şeyi etkilemez. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Herhangi bir SVG görüntüsü ile karşılaşıldığında kaydedilmesi gereken dizinin yolunu alır veya ayarlar. Parametre boş veya null ise, SVG dosyaları (varsa) diğer görüntü dosyalarıyla (çıktı dosyasının yanına) veya görüntüler için özel bir klasörde (eğer SpecialImagesFolderIfAny seçeneğinde belirtilmişse) kaydedilecektir. ÖzelImageSavingStrategy özelliği ilgili görüntü dosyasını işlemek için başarıyla kullanıldıysa, bu durum hiçbir şeyi etkilemez. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir. Bu durumda, hedef formatların renderlayıcıları (örneğin, DOCS formatı için MsWord), arka plan görüntülerinin parçaları arasında görünür sınırlar oluşturabilir, çünkü görüntü kenar yumuşatma teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgenin, aynı arka plan görüntülerinin parçaları arasında görünür sınırlar içerdiği görünüyorsa, lütfen bu ayarı kullanarak o istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF kendisi metinler için alt çizgi işaretleyicileri içermez. Bu, metnin altında bulunan bir çizgi ile taklit edilir. Bu seçenek, dönüştürücünün bu veya o çizginin bir metnin alt çizgisi olduğunu tahmin etmesine ve bu bilgiyi CSS'ye koymasına olanak tanır. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını HTML dosyasına nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* arayüz [IPageSetOptions](../ipagesetoptions/)
* arayüz [IPipelineOptions](../ipipelineoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)