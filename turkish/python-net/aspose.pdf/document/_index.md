---
title: "Belge"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belgesini temsil eden sınıf"
type: docs
weight: 230
url: /tr/python-net/aspose.pdf/document/
---

## Document class

PDF belgesini temsil eden sınıf

Belge türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Document(input) | Document sınıfının yeni bir örneğini başlatır |
| Document(input, password, is_managed_stream) | Document sınıfının yeni bir örneğini başlatır |
| Document(input, is_managed_stream) | Document sınıfının yeni bir örneğini başlatır |
| Document(filename) | Document sınıfının yeni bir örneğini başlatır |
| Document(input, password) | Document sınıfının yeni bir örneğini başlatır |
| Document() | Boş belgeyi başlatır. |
| Document(filename, options) | Document sınıfının yeni bir örneğini başlatır |
| Document(input, options) | Document sınıfının yeni bir örneğini başlatır |
| Document(filename, password) | Document sınıfının yeni bir örneğini başlatır |
| Document(filename, password, is_managed_stream) | Document sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| java_script | Belge seviyesindeki JavaScript koleksiyonu. |
| is_licensed | Sistemin lisans durumunu alır. Sistem lisanslı modda çalışıyorsa true, aksi takdirde false döndürür. |
| page_info | Sayfa bilgilerini alır veya ayarlar. (yalnızca oluşturucu için, belge okunduğunda doldurulmaz) |
| enable_signature_sanitization | İmza alanlarının temizlenmesini yönetmek için bayrağı alır veya ayarlar. Varsayılan olarak etkindir. |
| is_pdfa_compliant | Belgenin pdfa uyumlu olup olmadığını alır. |
| is_pdf_ua_compliant | Belgenin pdfua uyumlu olup olmadığını alır. |
| is_xref_gaps_allowed | Belgenin pdfa uyumlu olup olmadığını alır veya ayarlar. |
| named_destinations | Belgedeki Adlandırılmış Hedeflerin koleksiyonu. |
| destinations | Hedeflerin koleksiyonunu alır.<br/>            Eski. Lütfen NamedDestinations kullanın. |
| pdf_format | PDF formatını alır |
| embed_standard_fonts | Belgenin tüm standart Type1 yazı tiplerini gömmesi gerektiğini belirten özellik <br/>            IsEmbedded bayrağı true olarak ayarlanmış olan. Tüm PDF yazı tipleri, IsEmbedded bayrağı true olarak ayarlandığında belgeye kolayca gömülebilir, ancak PDF standart Type1 yazı tipleri bu kuralın bir istisnasıdır.<br/>            Standart Type1 yazı tipi gömme işlemi çok zaman alır, bu yüzden bu yazı tiplerini gömmek için yalnızca belirtilen yazı tipi için IsEmbedded bayrağını true olarak ayarlamak yeterli değildir, aynı zamanda belge seviyesinde ek bir bayrak da ayarlanmalıdır - EmbedStandardFonts = true;<br/>            Bu özellik tüm yazı tipleri için yalnızca bir kez ayarlanabilir.<br/>            Varsayılan olarak false. |
| disable_font_license_verifications | Yazı tipiyle ilgili birçok işlem, bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa gerçekleştirilemez. <br/>            Örneğin, bazı yazı tipleri lisans kuralları gömmeyi devre dışı bıraktığında PDF belgesine gömülemez. <br/>            Bu bayrak, geçerli PDF belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakmak için kullanılır.<br/>            Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin, olası lisans/kanun ihlallerinin tüm sorumluluğunu üstleneceği anlamına gelir. <br/>            Bu yüzden kişi kendi riskinde hareket eder. <br/>            Bu bayrağın yalnızca telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuzda kullanılmasını şiddetle tavsiye ederiz. <br/>            Varsayılan olarak false. |
| font_utilities | IDocumentFontUtilities örneği |
| collection | Belgenin koleksiyonunu alır. |
| version | Pdf dosya başlığından Pdf sürümünü alır. |
| open_action | Belge açıldığında gerçekleştirilen eylemi alır veya ayarlar. |
| hide_tool_bar | Belge etkin olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| hide_menubar | Belge etkin olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| hide_window_ui | Belge etkin olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirten bayrağı alır veya ayarlar. |
| fit_window | Belge penceresinin ilk gösterilen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirten bayrağı alır veya ayarlar. |
| center_window | Belge penceresinin konumunun ekranda ortalanıp ortalanmayacağını belirten bayrağı alır veya ayarlar. |
| display_doc_title | Belge penceresinin başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirten bayrağı alır veya ayarlar. |
| sayfalar | Belge sayfalarının koleksiyonunu alır veya ayarlar.<br/>            Not: sayfalar koleksiyonda 1'den itibaren numaralandırılır. |
| outlines | Belge taslaklarını alır. |
| eylemler | Belge eylemlerini alır. Bu özellik, DocumentActions sınıfının bir örneğidir ve BeforClosing, BeforSaving vb. eylemleri alıp ayarlamaya izin verir. |
| form | Belgenin Acro Formunu alır. |
| embedded_files | Belgeye gömülü dosyaların koleksiyonunu alır. |
| direction | Metnin okuma sırasını alır veya ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
| page_mode | Sayfa modunu alır veya ayarlar, belgenin açıldığında nasıl görüntüleneceğini belirler. |
| non_full_screen_page_mode | Sayfa modunu alır veya ayarlar, tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirtir. |
| page_layout | Belge açıldığında kullanılacak sayfa düzenini alır veya ayarlar. |
| duplex | Yazdırma iletişim kutusundan dosyayı yazdırırken kullanılacak çift taraflı baskı modu işleme seçeneğini alır veya ayarlar. |
| file_name | Bu belgeye neden olan PDF dosyasının adı |
| info | Belge bilgilerini alır. |
| metadata | Belge meta verileri.<br/>            (Bir PDF belgesi genel bilgiler içerebilir,<br/>             örneğin belgenin başlığı, yazarı ve oluşturulma ve değiştirilme tarihleri.<br/>             Belgenin içeriği veya yapısı yerine bu tür genel bilgiler meta veri olarak adlandırılır<br/>             ve dış veri tabanlarında belgelerin kataloglanması ve aranmasına yardımcı olması amaçlanır.) |
| logical_structure | Belgenin mantıksal yapısını alır. |
| handle_signature_change | Belge değişikliklerle kaydedilecek ve imza içeriyorsa İstisna fırlat. |
| crypto_algorithm | Belge şifrelenmişse güvenlik ayarlarını alır. <br/>            Belge şifrelenmemişse .net 1.1'de ilgili istisna yükseltilecektir<br/>            veya diğer .net sürümlerinde CryptoAlgorithm null olacaktır. |
| is_linearized | Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değeri alır veya ayarlar. |
| permissions | Belgenin izinlerini alır. |
| is_encrypted | Belgenin şifrelenme durumunu alır. Belge şifreli ise True. |
| id | Kimliği alır. |
| background | Belgenin arka plan rengini alır veya ayarlar. |
| optimize_size | Optimizasyon bayrağını alır veya ayarlar. Sayfalar belgeye eklendiğinde, sonuç dosyasındaki eşit kaynak akışları<br/>            bu bayrak ayarlıysa tek bir PDF nesnesine birleştirilir. <br/>            Bu, sonuç dosya boyutunu azaltmaya olanak tanır ancak daha yavaş yürütme ve daha büyük bellek gereksinimlerine neden olabilir.<br/>            Varsayılan değer: false. |
| allow_reuse_page_content | Sayfa içeriklerini birleştirerek belge boyutunu optimize etmeyi sağlar. Kullanılırsa farklı ancak yinelenen sayfalar <br/>            aynı içerik nesnesine referans verebilir. Lütfen bu modun, bir sayfa değiştirildiğinde diğer sayfanın içeriğinin değişmesi gibi yan etkilere neden olabileceğini unutmayın. |
| ignore_corrupted_objects | Kaynak dosyalardaki hataları yoksayma bayrağını alır veya ayarlar. <br/>            Kaynak belgeden sayfalar hedef belgeye kopyalandığında, bu bayrak false olduğunda kaynak dosyalardaki bazı nesneler bozuksa kopyalama işlemi bir istisna ile durdurulur. <br/>            örnek: dest.Pages.Add(src.Pages);<br/>            Bu bayrak true olarak ayarlanırsa bozuk nesneler boş değerlerle değiştirilir.<br/>            Varsayılan: true. |
| page_labels | Belgedeki sayfa etiketlerini alır. |
| enable_object_unload | Bellekten belgenin kısmen boşaltılmasını sağlayan bayrağı alır veya ayarlar. <br/>            Bu, bellek kullanımını azaltmaya izin verir ancak performans üzerinde olumsuz etkiye sahip olabilir. |
| tagged_content | TaggedPdf içeriğine erişim sağlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| save(output) | Belgeyi akışa kaydeder. |
| save(output_file_name) | Belgeyi belirtilen dosyaya kaydeder. |
| save() | Belgeyi akışa kaydeder. |
| save(options) | Belgeyi kaydetme seçenekleriyle kaydeder. |
| save(output_file_name, format) | Belgeyi yeni bir ad ve dosya formatı ile kaydeder. |
| save(output_stream, format) | Belgeyi yeni bir ad ve dosya formatı ile kaydeder. |
| save(output_file_name, options) | Belgeyi yeni bir adla ve kaydetme seçeneklerini ayarlayarak kaydeder. |
| save(output_stream, options) | Belgeyi kaydetme seçenekleriyle bir akışa kaydeder. |
| export_annotations_to_xfdf(file_name) | Tüm belge ek açıklamalarını XFDF dosyasına dışa aktarır. |
| export_annotations_to_xfdf(stream) | Tüm belge ek açıklamalarını akışa dışa aktar. |
| send_to(device, output) | Belgenin tamamını işleme için belge cihazına gönderir. |
| send_to(device, from_page, to_page, output) | Belgenin belirli sayfalarını işleme için belge cihazına gönderir. |
| send_to(device, output_file_name) | Belgenin tamamını işleme için belge cihazına gönderir. |
| send_to(device, from_page, to_page, output_file_name) | Belgenin tamamını işleme için belge cihazına gönderir. |
| import_annotations_from_xfdf(file_name) | XFDF dosyasından belgeye ek açıklamaları içe aktarır. |
| import_annotations_from_xfdf(stream) | Akıştan belgeye ek açıklamaları içe aktarır. |
| validate(output_log_file_name, format) | Belgeyi belirtilen dosyaya doğrular. |
| validate(output_log_stream, format) | Belgeyi belirtilen dosyaya doğrular. |
| validate(options) | Belgeyi belirtilen dosyaya doğrular. |
| convert(output_log_file_name, format, action, transparency_action) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| convert(output_log_stream, format, action, transparency_action) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| convert(output_log_file_name, format, action) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| convert(options) | Belgeyi belirtilen dönüşüm seçeneklerini kullanarak dönüştür. |
| convert(output_log_stream, format, action) | Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet. |
| convert(fixup, output_log, only_validation, parameters) | Fixup uygulayarak belgeyi dönüştür. |
| convert(fixup, output_log, only_validation, parameters) | Fixup uygulayarak belgeyi dönüştür. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Kaynak formatındaki kaynak dosyayı hedef formatındaki hedef dosyaya dönüştürür. |
| convert(src_stream, load_options, dst_file_name, save_options) | Kaynak formatındaki akışı hedef formatındaki hedef dosyaya dönüştürür. |
| convert(src_file_name, load_options, dst_stream, save_options) | Kaynak formatındaki akışı hedef formatındaki hedef dosyaya dönüştürür. |
| convert(src_stream, load_options, dst_stream, save_options) | Kaynak formatındaki akışı hedef formatındaki hedef dosyaya dönüştürür. |
| flatten() | Belgedeki tüm alanları kaldırır ve yerine değerlerini yerleştirir. |
| flatten(flatten_settings) | Belgedeki tüm alanları kaldırır ve yerine değerlerini yerleştirir. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Belgeyi şifreler. Şifreli belge sürümünü elde etmek için ardından Save metodunu çağırın. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Belgeyi şifreler. Şifreli belge sürümünü elde etmek için ardından Save metodunu çağırın. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Belgeyi şifreler. Şifreli belge sürümünü elde etmek için ardından Save metodunu çağırın. |
| optimize_resources() | Belgedeki kaynakları optimize eder:<br/>            1. Belge sayfalarında kullanılmayan kaynaklar kaldırılır;<br/>            2. Aynı kaynaklar tek bir nesne içinde birleştirilir; <br/>            3. Kullanılmayan nesneler silinir. |
| optimize_resources(strategy) | Belgedeki kaynakları tanımlı optimizasyon stratejisine göre optimize eder. |
| bind_xml(file) | XML'i belgeye bağla |
| bind_xml(xml_file, xsl_file) | XML'i belgeye bağla |
| bind_xml(xml_stream, xsl_stream) | XML/XSL'i belgeye bağla |
| bind_xml(stream) | XML/XSL'i belgeye bağla |
| remove_pdfa_compliance() | Belgeden PDF/A uyumluluğunu kaldır. |
| remove_pdf_ua_compliance() | Belgeden PDF/UA uyumluluğunu kaldır. |
| set_title(title) | Pdf Belgesi için Başlık Ayarla |
| process_paragraphs() | Üreteç için paragrafları işle. |
| remove_metadata() | Belgeden meta verileri kaldırır. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Belge şifrelerini değiştirir. Bu işlem yalnızca sahibi şifresi kullanılarak yapılabilir. |
| decrypt() | Belgeyi şifre çözer. Ardından belgeyi kaydetmek için Save'i çağırın ve şifresi çözülmüş sürümü elde edin. |
| optimize() | Belgeyi lineerleştirerek<br/>            - ilk sayfayı mümkün olduğunca hızlı açmak;<br/>            - sonraki sayfayı göstermek veya sonraki sayfaya bağlantıyı mümkün olduğunca hızlı takip etmek;<br/>            - sayfa verileri yavaş bir kanaldan iletildiğinde sayfayı kademeli olarak göstermek (en faydalı verileri önce göstermek);<br/>            - bir bağlantıyı takip etmek gibi kullanıcı etkileşimine, sayfanın tamamı alınmadan ve görüntülenmeden önce bile izin vermek.<br/>            Bu yöntemi çağırmak belgeyi aslında kaydetmez. Aksine belge yalnızca optimize edilmiş bir yapıya hazırlanır,<br/>            ardından Optimize edilmiş belgeyi almak için Save'i çağırın. |
| get_catalog_value(key) | Katalog sözlüğünden öğe değerini döndürür. |
| free_memory() | Belleği temizler |
| save_xml(file) | Belgeyi XML olarak kaydet. |
| get_object_by_id(id) | Belgede belirtilen ID'ye sahip bir nesneyi alır. |
| repair() | Bozuk belgeyi onarır. |
| get_xmp_metadata(stream) | Belgeden XMP meta verilerini al. |
| set_xmp_metadata(stream) | Belgenin XMP meta verilerini ayarla. |
| check(do_repair) | Belgeyi doğrular. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Bir belgedeki sayfa ağacı düğümlerini dengeli bir ağaçta düzenler.<br/>            Yalnızca belge nodesNumInSubtrees sayısından fazla sayfa nesnesine sahipse, aksi takdirde hiçbir şey yapmaz. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

