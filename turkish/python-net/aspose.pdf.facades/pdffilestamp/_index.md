---
title: "PdfFileStamp"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF dosyalarına damga (filigran veya arka plan) eklemek için sınıf."
type: docs
weight: 320
url: /tr/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

PDF dosyalarına damga (filigran veya arka plan) eklemek için sınıf.

PdfFileStamp türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileStamp(input_file, output_file) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
| PdfFileStamp(input_stream, output_stream) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
| PdfFileStamp(input_file, output_file, keep_security) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
| PdfFileStamp(input_stream, output_stream, keep_security) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
| PdfFileStamp() | PdfFileStamp yapıcısı.<br/>            Giriş dosyası ve çıkış dosyası ilgili özellikler aracılığıyla belirtilebilir. |
| PdfFileStamp(document) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
| PdfFileStamp(document, output_file) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
| PdfFileStamp(document, output_stream) | PdfFileStamp sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| optimize_size | Optimizasyon bayrağını alır veya ayarlar. Sonuç dosyasındaki eşit kaynak akışları bu bayrak ayarlıysa tek bir PDF nesnesine birleştirilir. <br/>            Bu, sonuç dosyasının boyutunu azaltmaya olanak tanır ancak daha yavaş yürütme ve daha büyük bellek gereksinimlerine neden olabilir.<br/>            Varsayılan değer: false. |
| keep_security | Doğru ise güvenliği korur. (Bu özellik sonraki sürümlerde uygulanacaktır). |
| input_file | Giriş dosyasının adını ve yolunu alır veya ayarlar. |
| input_stream | Giriş akışını alır veya ayarlar. |
| output_file | Çıkış dosyasının adını ve yolunu alır veya ayarlar. |
| output_stream | Çıkış akışını alır veya ayarlar. |
| page_number_rotation | Sayfa numarasının dönüşünü alır veya ayarlar. Dönüş derece cinsindendir. Varsayılan 0'dır. |
| page_height | Kaynak dosyadaki ilk sayfanın yüksekliğini alır. |
| page_width | Giriş dosyasındaki ilk sayfanın genişliğini alır. |
| starting_number | Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır. <br/>            Örneğin StartingNumber 100 olarak ayarlanırsa, belge sayfaları 100, 101, 102... numaralarına sahip olur. |
| numbering_style | Sayfa numaralandırma stilini alır veya ayarlar. Olası değerler: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | Son eklenen damganın Damga Kimliği (sayfa başlıkları/altbilgileri/sayfa numaraları dahil). |
| POS_BOTTOM_MIDDLE | Alt orta konum. |
| POS_BOTTOM_RIGHT | Alt sağ konum. |
| POS_UPPER_RIGHT | Sağ üst konum. |
| POS_SIDES_RIGHT | Sağ konum. |
| POS_UPPER_MIDDLE | Üst orta konum. |
| POS_BOTTOM_LEFT | Alt sol konum. |
| POS_SIDES_LEFT | Sol konum. |
| POS_UPPER_LEFT | Üst sol konum. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | Sonucu belirtilen dosyaya kaydeder. |
| save(dest_stream) | Belgeyi belirtilen akışa kaydeder. |
| add_page_number(format_string) | Dosyaya sayfa numarası ekle. Sayfa numarası metni # işareti içerebilir ve bu işaret sayfanın numarasıyla değiştirilecektir. <br/>            Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanmış şekilde yerleştirilir. |
| add_page_number(formatted_text) | Sayfaya sayfa numarası ekler. Sayfa numarası # işareti içerebilir ve bu işaret sayfa numarasıyla değiştirilecektir.<br/>            Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanmış şekilde yerleştirilir. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Belgenin sayfalarına sayfa numarası ekler. |
| add_page_number(format_string, x, y) | Belgenin sayfalarına sayfa numarası ekler. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Belgenin sayfalarına sayfa numarası ekler. |
| add_page_number(formatted_text, x, y) | Belgenin sayfalarına sayfa numarası ekler. |
| add_page_number(format_string, position) | Belgenin sayfalarına sayfa numarası ekler. |
| add_page_number(formatted_text, position) | Belgenin sayfalarına sayfa numarası ekler. |
| add_header(formatted_text, top_margin) | Sayfaya başlık ekler. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Sayfaya başlık ekler. |
| add_header(image_file, top_margin) | Görüntüyü dosyanın sayfalarına başlık olarak ekler. |
| add_header(image_file, top_margin, left_margin, right_margin) | Görüntüyü dosyanın sayfalarına başlık olarak ekler. |
| add_header(image_stream, top_margin) | Görüntüyü sayfalara başlık olarak ekler. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Görüntüyü sayfalara başlık olarak ekler. |
| add_footer(formatted_text, bottom_margin) | Altbilgiyi belgenin sayfalarına ekler. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Altbilgiyi belgenin sayfalarına ekler. |
| add_footer(image_file, bottom_margin) | Görüntüyü belgenin sayfalarına altbilgi olarak ekler. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Görüntüyü belgenin sayfalarına altbilgi olarak ekler. |
| add_footer(image_stream, bottom_margin) | Görüntüyü sayfanın altbilgisi olarak ekler. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Görüntüyü sayfanın altbilgisi olarak ekler. |
| close() | Açık dosyaları kapatır ve değişiklikleri kaydeder. <br/>            Uyarı. Giriş veya çıkış akışları belirtilmişse, Close() yöntemiyle kapatılmaz. |
| add_stamp(stamp) | Dosyaya damga ekler. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

