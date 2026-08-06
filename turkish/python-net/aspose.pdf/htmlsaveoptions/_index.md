---
title: "HtmlSaveOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "HTML formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 490
url: /tr/python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

HTML formatına dışa aktarma için kaydetme seçenekleri

HtmlSaveOptions türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| HtmlSaveOptions() | Yeni bir [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/) sınıf örneği başlatır. |
| HtmlSaveOptions(document_type) | HtmlSaveOptions sınıfının yeni bir örneğini başlatır |
| HtmlSaveOptions(fixed_layout) | HtmlSaveOptions sınıfının yeni bir örneğini başlatır |
| HtmlSaveOptions(document_type, fixed_layout) | HtmlSaveOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı Abort döndürürse Kaydetme işlemi durmalıdır. |
| save_format | Veri kaydetme biçimi. |
| close_response | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır veya ayarlar. |
| extract_ocr_sublayer_only | Yok |
| try_merge_adjacent_same_background_images | Yok |
| document_type | [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/) öğesini alır veya ayarlar. |
| compress_svg_graphics_if_any | Kaydetme sırasında bulunan SVG grafiklerinin (varsa) sıkıştırılıp (ziplenerek) <br/>            SVGZ formatına aktarılacağını gösteren bayrağı alır veya ayarlar. |
| split_css_into_pages | Çok sayfalı mod seçildiğinde (ör. 'SplitIntoPages' 'true' ise), <br/>            bu öznitelik her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını tanımlar.<br/>            Varsayılan olarak bu öznitelik false'dur, bu yüzden oluşturulan tüm sayfalar için tek büyük ortak bir CSS oluşturulur. Bu modda üretilen tüm CSS'lerin (sayfa başına bir CSS) toplam boyutu genellikle tek büyük bir CSS dosyasının boyutundan çok daha fazladır, çünkü önceki durumda CSS sınıfları her sayfa için birkaç CSS dosyasında yinelenir.<br/>            Bu ayar yalnızca her HTML sayfasını bağımsız olarak gelecekte işlemek istediğinizde ve bu yüzden her bir sayfanın ayrı ayrı CSS boyutu en kritik konu olduğunda kullanılmalıdır. |
| split_into_pages | Kaynak belgenin her sayfasının kendi hedef HTML belgesine dönüştürülüp dönüştürülmeyeceğini gösteren bayrağı alır veya ayarlar, <br/>            yani sonuç HTML'nin birkaç HTML sayfasına bölünüp bölünmeyeceğini. |
| explicit_list_of_saved_pages | Bu özellik ile belgede hangi sayfaların dönüştürüleceğini açıkça tanımlayabilirsiniz.<br/>            Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani <br/>            geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır.<br/>            Bu listedeki sayfaların görünüm sırası, sonuç HTML sayfalarının <br/>            sırasını etkilemez - sonuç sayfaları her zaman kaynak PDF'de bulundukları sırayla gider.<br/>            Bu liste null ise (varsayılan olarak), tüm sayfalar dönüştürülür.<br/>            Eğer bu listedeki herhangi bir sayfa numarası mevcut sayfaların (1-[amountOfPagesInDocument]) aralığının dışına çıkarsa, bir istisna fırlatılır. |
| fixed_layout | HTML'nin sabit düzen olarak oluşturulup oluşturulmayacağını gösteren bir değeri alır veya ayarlar. |
| image_resolution | Görüntü işleme için çözünürlüğü alır veya ayarlar. |
| default_font_name | Yerleşik olmayan ve sistemde yüklü olmayan herhangi bir belge yazı tipinin yerine kullanılacak yüklü bir yazı tipinin adını belirtir.<br/>            Eğer null ise varsayılan yedek yazı tipi kullanılır. |
| batch_size | Toplu dönüşüm uygulanabilir olduğunda toplu boyutunu tanımlar<br/>            kaynak ve hedef format çiftine. |
| font_sources | Önceden kaydedilmiş yazı tiplerinin font kaynakları. |
| additional_margin_width_in_points | Eğer öznitelik 'SplitOnPages=false' ise, tüm giriş PDF sayfalarını temsil eden tek HTML, farklı HTML sayfalarına bölünmez, bunun yerine tek büyük sonuç HTML dosyasına yerleştirilir.<br/>            Ancak her kaynak PDF sayfası, HTML içinde kendi <br/>            dikdörtgen alanı ile temsil edilir (gerekirse bu alanlar, özel öznitelik 'PageBorderIfAny' ile sayfa kağıdı kenarlarını göstermek için kenarlıklandırılabilir).<br/>            Bu parametre, çıktı HTML‑alanlarının etrafında zorunlu olarak bırakılacak kenar boşluğunun genişliğini tanımlar; bu alanlar kaynak PDF belgesinin sayfalarını temsil eder. Esasen, PDF \"kağıt\" sayfalarının HTML temsilleri arasındaki garantili aralığı tanımlar. |
| use_z_order | Eğer öznitelik UseZORder true olarak ayarlanmışsa, grafikler ve metinler sonuç HTML belgesine, orijinal PDF belgesindeki Z-sırasına göre eklenir.<br/>            Bu öznitelik false ise, tüm grafikler tek bir katmana konur ve üst üste binen nesneler için gereksiz etkiler oluşabilir. |
| convert_marked_content_to_layers | Eğer öznitelik ConvertMarkedContentToLayers true olarak ayarlanmışsa, PDF işaretli içeriği (katman) içindeki tüm öğeler, katman adını belirten \"data-pdflayer\" özniteliğine sahip bir HTML div'ine yerleştirilir.<br/>            Bu katman adı, PDF işaretli içeriğinin isteğe bağlı özelliklerinden çıkarılır.<br/>            Bu öznitelik false (varsayılan) ise, PDF işaretli içeriğinden hiçbir katman oluşturulmaz. |
| minimal_line_width | Bu öznitelik grafik yol çizgisinin minimum genişliğini ayarlar.<br/>            Çizgi kalınlığı 1px'den az ise Adobe Acrobat bunu bu değere yuvarlar. Bu nedenle bu öznitelik, HTML tarayıcıları için bu davranışı taklit etmekte kullanılabilir. |
| prevent_glyphs_grouping | Bu öznitelik, metin gliflerinin kelimeler ve dizeler halinde gruplanmayacağı modu etkinleştirir.<br/>            Bu mod, sayfa üzerindeki gliflerin konumlandırılmasında en yüksek hassasiyeti korur ve müzik notaları veya birbirinden ayrı yerleştirilmesi gereken glifler içeren belgelerin dönüştürülmesinde kullanılabilir.<br/>            Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanır. |
| simple_textbox_mode_grouping | Bu öznitelik, gliflerin ve kelimelerin dizelere sıralı olarak gruplanmasını belirtir.<br/>            Örneğin, dönüştürülmüş HTML'de etiketler ve kelimeler farklı bir sırada olabilir ve bunların eşleşmesini isteyebilirsiniz.<br/>            Bu parametre, yalnızca FixedLayout özniteliğinin değeri true olduğunda belgeye uygulanır. |
| flow_layout_paragraph_full_width | Bu öznitelik, Akış modunda tam genişlik paragraf metnini belirtir, FixedLayout = false |
| render_text_as_image | Eğer öznitelik RenderTextAsImage true olarak ayarlanırsa, kaynaktan gelen metin HTML içinde bir görüntü haline gelir.<br/>            Metni seçilemez hâle getirmek veya HTML metni düzgün render edilmiyorsa faydalı olabilir. |
| save_full_font | Tam fontun kaydedileceğini gösterir, yalnızca True Type Fontları destekler.<br/>            Varsayılan olarak SaveFullFont = false ve dönüştürücü, belgenin metnini görüntülemek için gereken başlangıç fontunun alt kümesini kaydeder. |
| antialiasing_processing | Bu parametre, PDF'den HTML'ye karmaşık arka plan görüntülerinin dönüştürülmesi sırasında gerekli antialiasing önlemlerini tanımlar. |
| save_transparent_texts | Pdf, panoya seçilebilen şeffaf metinler içerebilir (genellikle belge resimler ve ondan çıkarılan OCR'lenmiş metinler içerdiğinde olur).<br/>            Bu ayar, dönüştürücüye bu tür metinleri sonuç HTML'de şeffaf, seçilebilir metinler olarak kaydetmemiz gerekip gerekmediğini bildirir. |
| save_shadowed_texts_as_transparent_texts | Pdf, başka öğeler (ör. görüntüler) tarafından gölgelenen metinler içerebilir ancak <br/> Acrobat Reader'da panoya seçilebilir (genellikle belge görüntüler ve ondan çıkarılan OCR'lenmiş metinler içerdiğinde olur).<br/> Bu ayar, dönüştürücüye bu metinleri sonuç HTML'de şeffaf<br/> seçilebilir metinler olarak kaydetmemiz gerekip gerekmediğini söyler, böylece Acrobat Reader davranışını taklit eder (aksi takdirde bu metinler genellikle gizli olarak kaydedilir, panoya kopyalanamaz). |
| font_saving_mode | PDF'nin istenen biçime kaydedilmesi sırasında kullanılacak yazı tipi kaydetme modunu tanımlar |
| page_border_if_any | Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafında (varsa) kenarlık çizmeye kullanılan ayar kümesini temsil eder.<br/> Esas olarak sayfanın kağıt kenarlarının gösterilmesiyle ilgilidir,<br/> PDF sayfasının kendisinde referans verilen sayfa kenarıyla değil. |
| page_margin_if_any | Bu öznitelik, sonuç HTML belgesinde kaynak PDF sayfasını temsil eden alanın etrafında (varsa) ek sayfa kenar boşluğunu temsil eden ayar kümesini içerir. |
| letters_positioning_method | Sonuç HTML'de kelimelerdeki harflerin konumlandırma modunu ayarlar |
| exclude_font_name_list | HTML'de gömülmeyecek PDF gömülü yazı tipi adlarının listesidir. |
| special_folder_for_svg_images | Belge HTML olarak kaydedilirken karşılaşılan SVG-görüntülerin yalnızca kaydedileceği dizine giden yolu alır veya ayarlar.<br/> Parametre boş veya null ise SVG dosyaları (varsa) diğer görüntü dosyalarıyla birlikte (çıktı dosyasının yanına) kaydedilir<br/> veya SpecialImagesFolderIfAny seçeneğinde belirtilmişse görüntüler için özel bir klasöre.<br/> Bu, CustomImageSavingStrategy özelliği ilgili görüntü dosyasını işlemek için başarıyla kullanıldıysa hiçbir şeyi etkilemez. |
| special_folder_for_all_images | Belge HTML olarak kaydedilirken karşılaşılan tüm görüntülerin kaydedileceği dizine giden yolu alır veya ayarlar.<br/> Parametre boş veya null ise görüntü dosyaları (varsa) HTML'ye bağlanan diğer dosyalarla birlikte kaydedilir<br/> Bu, CustomImageSavingStrategy özelliği ilgili görüntü dosyasını işlemek için başarıyla kullanıldıysa hiçbir şeyi etkilemez. |
| css_class_names_prefix | PDFtoHTML dönüştürücüsü sonuç CSS'leri oluşturduğunda, CSS sınıf adları (ör. ".stl_01 {}" ... ".stl_NN {}") üretilir ve sonuç CSS'de kullanılır.<br/> Bu özellik, sınıf adı önekini zorunlu olarak ayarlamayı sağlar.<br/> Örneğin, tüm sınıf adlarının 'my_prefix_' ile başlamasını istiyorsanız (yani 'my_prefix_1' ... 'my_prefix_NNN' gibi), <br/> dönüşümden önce bu özelliğe 'my_prefix_' atayın.<br/> Bu özellik değeri değiştirilmezse (yani null bırakılırsa), <br/> dönüştürücü sınıf adlarını kendisi oluşturur <br/> (ör. ".stl_01 {}" ... ".stl_NN {}"). |
| parts_embedding_mode | Referans verilen dosyaların (HTML, Yazı Tipleri, Görüntüler, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini tanımlar<br/> ya da ayrı ikili varlıklar olarak oluşturulacağını belirler. |
| html_markup_generation_mode | HTML işaretlemesinin oluşturulmasıyla ilgili belirli gereksinimler bazen bulunur.<br/> Bu parametre, PDF'den HTML'ye dönüşüm sırasında bu tür özel gereksinimlere uyacak şekilde kullanılabilecek HTML hazırlama modlarını tanımlar. |
| raster_images_saving_mode | Dönüştürülen PDF raster görüntüler içerebilir<br/> Bu parametre, PDF'den HTML'ye dönüşüm sırasında bunların nasıl işleneceğini tanımlar. |
| remove_empty_areas_on_top_and_bottom | Oluşturulan HTML'de içerik olmayan üst ve alt boş alanların (varsa) kaldırılıp kaldırılmayacağını tanımlar. |
| font_encoding_strategy | Mevcut belge için PDF çözümlemesini ayarlamak amacıyla kodlama özel kuralını tanımlar. |
| pages_flow_type_depends_on_viewers_screen_size | Eğer 'SplitOnPages=false' özniteliği varsa, tüm giriş PDF sayfalarını temsil eden HTML bir <br/>            büyük sonuç HTML dosyasına yerleştirilecektir. <br/>            Bu bayrak, sonuç HTML'nin şu şekilde üretilip üretilmeyeceğini tanımlar<br/>            ki sonuç HTML'de PDF sayfalarını temsil eden alanların akışı<br/>            izleyicinin ekran çözünürlüğüne bağlı olsun. <br/>            İzleyicinin ekran genişliği, yatay yönde 2 veya daha fazla sayfayı yan yana koymaya yeterli olduğunu varsayalım. Bu bayrak true olarak ayarlanırsa, bu fırsat<br/>            kullanılacaktır (mümkün olduğunca çok sayfa yatay yönde yan yana gösterilecek, ardından bir sonraki yatay sayfa grubu ilk grubun altında gösterilecektir).<br/>            Aksi takdirde sayfalar şu şekilde akacaktır: sonraki sayfa her zaman bir öncekinin altında yer alır. |
| try_save_text_underlining_and_strikeouting_in_css | PDF kendisi metinler için alt çizgi işaretleri içermez. Alt çizgi, metnin altında bulunan bir çizgiyle taklit edilir.<br/>            Bu seçenek, dönüştürücünün bu ya da o çizginin bir metnin alt çizgisi olduğunu tahmin etmesine izin verir<br/>            ve bu bilgiyi alt çizgiyi grafik olarak çizmeye yerine CSS'e yerleştirir. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

