---
title: "PdfExtractor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belgesinden görüntü ve metin çıkarmak için sınıf."
type: docs
weight: 210
url: /tr/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

PDF belgesinden görüntü ve metin çıkarmak için sınıf.

PdfExtractor türü aşağıdaki üyeleri ortaya çıkar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfExtractor() | Yeni bir [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) nesnesi başlatır. |
| PdfExtractor(document) | PdfExtractor sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| start_page | Çıkarma işleminin gerçekleştirileceği sayfa aralığında başlangıç sayfasını alır veya ayarlar. |
| end_page | Çıkarma işleminin gerçekleştirileceği sayfa aralığında bitiş sayfasını alır veya ayarlar. |
| extract_text_mode | Metin çıkarma sonucunun modunu ayarlar. |
| text_search_options | Metin arama seçeneklerini alır veya ayarlar. |
| extract_image_mode | Görsel çıkarma sürecinin modunu ayarlar. |
| is_bidi | Metinde İbranice veya Arapça semboller olduğunda doğru olur. Bu durum özel olarak dikkate alınmalıdır çünkü<br/>            string fonksiyonları davranışlarını değiştirir ve metni sağdan sola doğru işler (sayılar <br/>            ve diğer metin dışı karakterler hariç). |
| resolution | Çıkarılan görseller için çözünürlüğü ayarlar veya alır.<br/>            Varsayılan değer 150'dir.<br/>            Daha yüksek çözünürlük değerine sahip görseller daha nettir.<br/>            Ancak çözünürlük değerini artırmak, görselleri çıkarmak için gereken zaman ve belleği artırır.<br/>            Genellikle net bir görüntü elde etmek için çözünürlüğü 150 veya 300 olarak ayarlamak yeterlidir. |
| password | Giriş dosyasının şifresini alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(input_file) | Giriş PDF dosyasını bağlar. |
| bind_pdf(input_stream) | PDF belgesini akıştan bağlar. |
| bind_pdf(src_doc) | Facade'i başlatır. |
| extract_text() | Unicode kodlamasını kullanarak bir PDF belgesinden metin çıkarır. |
| extract_text(encoding) | Belirtilen kodlamayı kullanarak bir PDF belgesinden metin çıkarır. |
| get_text(output_file) | Metni dosyaya kaydeder. ayrıca bakınız:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Metni akışa kaydeder. ayrıca bakınız:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Metni akışa kaydeder. ayrıca bakınız:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | PDF belgesinden bir sonraki görseli alır. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır. |
| get_next_image(output_file, format) | Verilen görsel formatı ile PDF belgesinden bir sonraki görseli alır. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır. |
| get_next_image(output_stream, format) | PDF dosyasından bir sonraki görseli alır ve verilen görsel formatı ile akışa kaydeder. |
| get_next_image(output_stream) | PDF dosyasından bir sonraki görseli alır ve verilen görsel formatı ile akışa kaydeder. |
| extract_attachment() | Bir PDF belgesinden ekleri çıkarır. |
| extract_attachment(attachment_file_name) | Ek adını kullanarak bir PDF dosyasına eki çıkarır. |
| get_next_page_text(output_file) | Bir sayfanın metnini dosyaya kaydeder. |
| get_next_page_text(output_stream) | Bir sayfanın metnini akışa kaydeder. |
| close() | Bir facade ile bağlanan Aspose.Pdf.Document nesnesini serbest bırakır. |
| extract_image() | PDF dosyasından görüntüleri çıkar. |
| has_next_image() | PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır. |
| get_attach_names() | PDF dosyasındaki eklerin listesini döndürür. Not: Bu yöntemi kullanmadan önce ExtractAttachments çağrılmalıdır. |
| get_attachment(output_path) | Ek'i dosyaya kaydeder. |
| has_next_page_text() | Daha fazla metin alınıp alınamayacağını gösterir. |
| get_attachment_info() | Eklerin listesini alır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

