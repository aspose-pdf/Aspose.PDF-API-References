---
title: "PdfFileEditor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF dosyası birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb. işlemleri uygular."
type: docs
weight: 220
url: /tr/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb.

PdfFileEditor türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileEditor() | PdfFileEditor sınıfının yeni bir örneğini başlatır. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| conversion_log | Dönüştürme sürecinin günlüğünü alır. |
| merge_duplicate_layers | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmanda birleştirilecektir. <br/>            Aksi takdirde, aynı ada sahip katmanlar sonuç belgesinde farklı katmanlar olarak kaydedilir. |
| copy_outlines | True ise, taslaklar kopyalanacaktır. |
| copy_logical_structure | True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır. |
| merge_duplicate_outlines | True ise, yinelenen taslaklar birleştirilir. |
| preserve_user_rights | True ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. Diğer tüm belgelerin kullanıcı hakları göz ardı edilir. |
| incremental_updates | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| optimize_size | Optimizasyon bayrağını alır veya ayarlar. Sonuç dosyasındaki eşit kaynak akışları bu bayrak ayarlıysa tek bir PDF nesnesine birleştirilir. <br/>            Bu, sonuç dosyasının boyutunu azaltmaya olanak tanır ancak daha yavaş yürütme ve daha büyük bellek gereksinimlerine neden olabilir.<br/>            Varsayılan değer: false. |
| corrupted_items | Birleştirme gerçekleştirildiğinde karşılaşılan sorunların dizisi. Concatenate() işlevine geçirilen her bozuk belge için <br/>            yeni bir CorruptedItem girdisi oluşturulur.<br/>            Bu özellik yalnızca CorruptedFileAction, ConcatenateIgnoringCorrupted olduğunda kullanılabilir. |
| corrupted_file_action | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar.<br/>            Olası değerler: StopWithError ve ConcatenateIgnoringCorrupted. |
| owner_password | Kaynak giriş Pdf dosyası şifrelenmişse sahibinin şifresini ayarlar.<br/>            Bu özellik henüz uygulanmadı. |
| allow_concatenate_exceptions | True olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır. Aksi takdirde istisnalar fırlatılmaz ve yöntemler başarısız olduğunda false döndürür. |
| close_concatenated_streams | True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. |
| unique_suffix | Formlar birleştirildiğinde alan adına eklenen ve onu benzersiz kılan sonek formatı.<br/>            Bu dize %NUM% alt dizisini içermelidir; bu alt dize sayılarla değiştirilecektir.<br/>            Örneğin UniqueSuffix = "ABC%NUM%" ise, "fieldName" alanı için adlar şu şekilde olur:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. |
| keep_actions | True ise eylemler kaynak belgelerden kopyalanır. Varsayılan değer : true. |
| keep_fields_unique | True ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilir.<br/>            Alan adlarına sonekler eklenir, sonek şablonu UniqueSuffix özelliğinde belirtilebilir. |
| remove_signatures | True ise, tüm imzalar alanlardan kaldırılır (alanlar kalır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| use_disk_buffer | Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilir ve sonraki birleştirme artımlı güncellemeler olarak uygulanır. |
| concatenation_packet_size | UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni bir artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | İki dosyayı birleştirir. |
| try_concatenate(src, dest) | Belgeleri birleştirir. |
| try_concatenate(input_files, output_file) | Dosyaları tek bir dosyada birleştirir. |
| try_concatenate(input_stream, output_stream) | Dosyaları birleştirir |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | İki dosyayı birleştirir. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Dosyaları birleştirir |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Sayfaları ekler, portStreams içindeki belge dizisinden seçilen.<br/>            Sonuç belge, firstInputFile ve tüm portStreams belgelerinin startPage ile endPage arasındaki sayfalarını içerir. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Sayfaları ekler, portFiles belgelerinden seçilen. <br/>            Sonuç belge, firstInputFile ve tüm portFiles belgelerinin startPage ile endPage arasındaki sayfalarını içerir. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| try_delete(input_file, page_number, output_file) | Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir PDF dosyası olarak kaydeder. |
| try_delete(input_stream, page_number, output_stream) | Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir PDF dosyası olarak kaydeder. |
| try_extract(input_file, start_page, end_page, output_file) | Giriş dosyasından sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| try_extract(input_file, page_number, output_file) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| try_extract(input_stream, page_number, output_stream) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| try_split_from_first(input_file, location, output_file) | PDF dosyasını ilk sayfadan belirtilen konuma kadar böler ve ön kısmı yeni bir dosya olarak kaydeder. |
| try_split_from_first(input_stream, location, output_stream) | Başlangıçtan belirtilen konuma kadar böler ve ön kısmı çıktı akışına kaydeder. |
| try_split_to_end(input_file, location, output_file) | Belirtilen konumdan itibaren böler ve arka kısmı yeni bir dosya olarak kaydeder. |
| try_split_to_end(input_stream, location, output_stream) | Belirtilen konumdan bölerek, arka kısmı yeni bir dosya Stream olarak kaydeder. |
| try_make_booklet(input_file, output_file) | Giriş dosyasından çıktı dosyasına bir kitapçık oluşturur. |
| try_make_booklet(input_stream, output_stream) | InputStream'den outputStream'e bir kitapçık oluşturur. |
| try_make_booklet(input_file, output_file, page_size) | inputFile'dan outputFile'a bir kitapçık oluşturur. |
| try_make_booklet(input_stream, output_stream, page_size) | Giriş akışından bir kitapçık oluşturur ve sonucu çıktı akışına kaydeder. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | firstInputFile'dan outputFile'a özelleştirilmiş bir kitapçık oluşturur. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | firstInputStream'dan outputStream'e özelleştirilmiş bir kitapçık oluşturur. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | firstInputFile'dan outputFile'a özelleştirilmiş bir kitapçık oluşturur. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | firstInputStream'dan outputStream'e bir kitapçık oluşturur. |
| try_make_n_up(input_file, output_file, x, y) | firstInputFile'dan outputFile'a N-Up belge oluşturur. |
| try_make_n_up(input_stream, output_stream, x, y) | Giriş akışından N-Up belge oluşturur ve sonucu çıktı akışına kaydeder. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | İlk giriş akışından output stream'e N-Up belge oluşturur. |
| try_make_n_up(first_input_file, second_input_file, output_file) | firstInputFile'dan outputFile'a N-Up belge oluşturur. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Giriş akışından N-Up belge oluşturur ve sonucu çıktı akışına kaydeder. |
| try_make_n_up(input_files, output_file, is_sidewise) | Çoklu giriş PDF dosyalarından outputFile dosyasına N-Up belge oluşturur. <br/>            outputFile dosyasının her sayfası, aynı sayfa numarasına sahip giriş dosyalarındaki sayfalarla kombinasyon oluşturan çoklu sayfalar içerir. Çoklu sayfalar, isSidewise doğru ise yatay olarak, isSidewise yanlış ise dikey olarak yığılır. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Çoklu giriş PDF akışlarından outputStream dosyasına N-Up belge oluşturur.<br/>            outputStream dosyasının her sayfası, aynı sayfa numarasına sahip giriş akışlarındaki sayfalarla kombinasyon oluşturan çoklu sayfalar içerir. Çoklu sayfalar, isSidewise doğru ise yatay olarak, isSidewise yanlış ise dikey olarak yığılır. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Giriş dosyasından outputFile dosyasına N-Up belge oluşturur. |
| try_resize_contents(source, destination, pages, parameters) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Belge sayfalarının içeriğini yeniden boyutlandırır. <br/>            Sayfa içeriğini küçültür ve kenar boşlukları ekler.<br/>            İçeriğin yeni boyutu varsayılan uzay birimlerinde belirtilir. |
| try_resize_contents(source, destination, pages, parameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülmüşse, sayfanın etrafına boş kenar boşlukları eklenir. |
| concatenate(first_input_file, sec_input_file, output_file) | Dosyaları birleştirir ve sonucu HttpResposnse nesnesine kaydeder. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Dosyaları birleştirir ve sonucu HttpResponse nesnesine depolar. |
| concatenate(src, dest) | Belgeleri birleştirir. |
| concatenate(input_files, output_file) | Dosyaları birleştirir ve sonucu HttpResposnse nesnesine kaydeder. |
| concatenate(input_stream, output_stream) | Dosyaları birleştirir ve sonucu HttpResponse nesnesine depolar. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Dosyaları birleştirir ve sonucu HttpResposnse nesnesine kaydeder. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Dosyaları birleştirir ve sonucu HttpResponse nesnesine depolar. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Belgeleri kaynak belgeye ekler ve sonucu response nesnesine kaydeder. |
| append(input_file, port_files, start_page, end_page, output_file) | Belgeleri kaynak belgeye ekler ve sonucu HttpResponse nesnesine kaydeder. |
| append(input_file, port_file, start_page, end_page, output_file) | Belgeleri kaynak belgeye ekler ve sonucu HttpResponse nesnesine kaydeder. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Belgeleri kaynak belgeye ekler ve sonucu response nesnesine kaydeder. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine kaydeder. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine kaydeder. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| delete(input_file, page_number, output_file) | Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder. |
| delete(input_stream, page_number, output_stream) | Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder. |
| extract(input_file, start_page, end_page, output_file) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine kaydeder. |
| extract(input_file, page_number, output_file) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine kaydeder. |
| extract(input_stream, start_page, end_page, output_stream) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine kaydeder. |
| extract(input_stream, page_number, output_stream) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine kaydeder. |
| split_from_first(input_file, location, output_file) | Belgeyi ilk sayfadan konuma kadar böler ve sonucu HttpResponse nesnelerine kaydeder. |
| split_from_first(input_stream, location, output_stream) | Belgeyi başlangıçtan belirtilen konuma kadar böler ve sonucu HttpResponse nesnesine kaydeder. |
| split_to_end(input_file, location, output_file) | Belirtilen konumdan bölerek arka kısmı HttpResponse nesnesine kaydeder. |
| split_to_end(input_stream, location, output_stream) | Belirtilen konumdan bölerek arka kısmı HttpResponse nesnesine kaydeder. |
| make_booklet(input_file, output_file) | Kaynak dosyadan kitapçık oluşturur ve sonucu HttpResponse nesnelerine kaydeder. |
| make_booklet(input_stream, output_stream) | PDF dosyasından kitapçık oluşturur ve HttpResponse içine kaydeder. |
| make_booklet(input_file, output_file, page_size) | Kaynak dosyadan kitapçık oluşturur ve sonucu HttpResponse nesnelerine kaydeder. |
| make_booklet(input_stream, output_stream, page_size) | PDF dosyasından kitapçık oluşturur ve HttpResponse içine kaydeder. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Kaynak dosyadan kitapçık oluşturur ve sonucu HttpResponse nesnelerine kaydeder. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | PDF dosyasından kitapçık oluşturur ve HttpResponse içine kaydeder. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Kaynak dosyadan kitapçık oluşturur ve sonucu HttpResponse nesnelerine kaydeder. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | PDF dosyasından kitapçık oluşturur ve HttpResponse içine kaydeder. |
| make_n_up(input_file, output_file, x, y) | N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| make_n_up(input_stream, output_stream, x, y) | N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| make_n_up(input_stream, output_stream, x, y, page_size) | N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| make_n_up(first_input_file, second_input_file, output_file) | N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| make_n_up(input_files, output_file, is_sidewise) | Çoklu giriş PDF dosyalarından outputFile dosyasına N-Up belge oluşturur. <br/>            outputFile dosyasının her sayfası, aynı sayfa numarasına sahip giriş dosyalarındaki sayfalarla kombinasyon oluşturan çoklu sayfalar içerir. Çoklu sayfalar, isSidewise doğru ise yatay olarak, isSidewise yanlış ise dikey olarak yığılır. |
| make_n_up(input_streams, output_stream, is_sidewise) | Çoklu giriş PDF akışlarından outputStream dosyasına N-Up belge oluşturur.<br/>            outputStream dosyasının her sayfası, aynı sayfa numarasına sahip giriş akışlarındaki sayfalarla kombinasyon oluşturan çoklu sayfalar içerir. Çoklu sayfalar, isSidewise doğru ise yatay olarak, isSidewise yanlış ise dikey olarak yığılır. |
| make_n_up(input_file, output_file, x, y, page_size) | N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| split_to_pages(input_file, file_name_template) | PDF dosyasını tek sayfalı belgelere ayırır. |
| split_to_pages(input_stream, file_name_template) | Pdf dosyasını tek sayfalı belgelere ayırır ve belirtilen yola kaydeder. Yol, alan adı şablonu ile belirtilir. |
| resize_contents(source, destination, pages, parameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse sayfanın etrafına boş kenarlar eklenir. Sonuç HttpResponse nesnesine kaydedilir. |
| resize_contents(source, destination, pages, new_width, new_height) | Belge sayfalarının içeriğini yeniden boyutlandırır. <br/>            Sayfa içeriğini küçültür ve kenar boşlukları ekler.<br/>            İçeriğin yeni boyutu varsayılan uzay birimlerinde belirtilir. |
| resize_contents(source, destination, pages, new_width, new_height) | Belge sayfalarının içeriğini yeniden boyutlandırır. <br/>            Sayfa içeriğini küçültür ve kenar boşlukları ekler.<br/>            İçeriğin yeni boyutu varsayılan uzay birimlerinde belirtilir. |
| resize_contents(source, destination, pages, parameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse sayfanın etrafına boş kenarlar eklenir. Sonuç HttpResponse nesnesine kaydedilir. |
| resize_contents(source, pages, parameters) | Belgenin sayfalarını yeniden boyutlandırır. Küçültülmüş sayfanın etrafına boş kenar boşlukları eklenir. |
| resize_contents(source, parameters) | Belgenin sayfalarını yeniden boyutlandırır. Küçültülmüş sayfanın etrafına boş kenar boşlukları eklenir. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Belge sayfalarının içeriğini yeniden boyutlandırır.<br/>            Sayfa içeriğini küçültür ve kenar boşlukları ekler.<br/>            Yeni içerik boyutu yüzde olarak belirtilir. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Belge sayfalarının içeriğini yeniden boyutlandırır.<br/>            Sayfa içeriğini küçültür ve kenar boşlukları ekler.<br/>            Yeni içerik boyutu yüzde olarak belirtilir. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. <br/>            Kenar boşlukları varsayılan uzay birimlerinde belirtilir. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. <br/>            Kenar boşlukları varsayılan uzay birimlerinde belirtilir. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.<br/>            Kenar boşlukları başlangıç sayfa boyutunun yüzde olarak belirtilir. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.<br/>            Kenar boşlukları başlangıç sayfa boyutunun yüzde olarak belirtilir. |
| add_page_break(src, dest, page_breaks) | Belge sayfalarına sayfa sonları ekler. |
| add_page_break(src, dest, page_breaks) | Belge sayfalarına sayfa sonları ekler. |
| add_page_break(src, dest, page_breaks) | Belge sayfalarına sayfa sonları ekler. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

