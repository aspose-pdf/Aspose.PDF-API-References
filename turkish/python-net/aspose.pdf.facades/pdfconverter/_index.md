---
title: "PdfConverter"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF dosyasının her sayfasını görüntülere dönüştüren bir sınıfı temsil eder, şu anda BMP, JPEG, PNG ve TIFF desteklenmektedir.<br/>            PDF'lerde desteklenen içerik: resimler, form, yorum."
type: docs
weight: 200
url: /tr/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Bir pdf dosyasının her sayfasını görüntülere dönüştürmek için bir sınıfı temsil eder, şu anda BMP, JPEG, PNG ve TIFF desteklenmektedir.<br/>            pdf'lerde desteklenen içerik: resimler, form, yorum.

PdfConverter türü aşağıdaki üyeleri ortaya çıkar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfConverter() | Yeni bir [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) nesnesi başlatır. |
| PdfConverter(document) | PdfConverter sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| coordinate_type | Sayfa koordinat tipini (Media/Crop kutuları) alır veya ayarlar. Varsayılan olarak CropBox değeri kullanılır. |
| show_hidden_areas | Sayfadaki gizli alanların görünürlüğünü kontrol eden bayrağı alır veya ayarlar. |
| rendering_options | Renderleme seçeneklerini alır veya ayarlar. |
| form_presentation_mode | Form sunum modunu alır veya ayarlar. |
| resolution | Dönüştürme sırasında çözünürlüğü alır veya ayarlar. Çözünürlük ne kadar yüksek olursa, dönüştürme hızı o kadar yavaş olur. Varsayılan değer 150'tir. |
| start_page | Dönüştürmek istediğiniz başlangıç konumunu alır veya ayarlar. Minimum değer 1'dir. |
| end_page | Dönüştürmek istediğiniz bitiş konumunu alır veya ayarlar. |
| password | Belgenin OwnerPassword değerini alır veya ayarlar. |
| user_password | Belgenin UserPassword değerini alır veya ayarlar. |
| page_count | Sayfa sayısını alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(input_file) | Dönüştürme için bir Pdf dosyasını bağlar. |
| bind_pdf(input_stream) | Dönüştürme için bir Pdf akışını bağlar. |
| bind_pdf(src_doc) | Facade'i başlatır. |
| save_as_tiff(output_file) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, compression_type) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, image_width, image_height) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, page_size) | Bir pdf belgesinin her sayfasını sayfa boyutunda görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, page_size, settings) | Bir pdf belgesinin her sayfasını sayfa boyutunda görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, image_width, image_height, settings) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_stream) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| save_as_tiff(output_stream, compression_type) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_stream, page_size) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| save_as_tiff(output_stream, page_size, settings) | PDF belgesinin her sayfasını sayfa boyutunda görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| save_as_tiff(output_stream, image_width, image_height) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| save_as_tiff(output_stream, image_width, image_height, settings) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| save_as_tiff(output_file, settings) | Bir pdf belgesinin her sayfasını sayfa boyutunda görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_file, settings, converter) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| save_as_tiff(output_stream, settings) | PDF belgesinin her sayfasını sayfa boyutunda görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| save_as_tiff(output_stream, settings, converter) | PDF belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| save_as_tiff_class_f(output_file, image_width, image_height) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| save_as_tiff_class_f(output_file, page_size) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| save_as_tiff_class_f(output_stream, page_size) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| save_as_tiff_class_f(output_file) | PDF belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| save_as_tiff_class_f(output_stream) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| get_next_image(output_file) | Görüntüyü varsayılan görüntü formatı - jpeg ile dosyaya kaydeder. |
| get_next_image(output_file, page_size) | Görüntüyü verilen i. sayfa boyutu ve varsayılan görüntü formatı - jpeg ile dosyaya kaydeder. |
| get_next_image(output_file, format) | Görüntüyü verilen görüntü formatı ile dosyaya kaydeder. |
| get_next_image(output_file, page_size, format) | Görüntüyü verilen sayfa boyutu ve görüntü formatı ile dosyaya kaydeder. |
| get_next_image(output_stream) | Görüntüyü varsayılan görüntü formatı - jpeg ile akışa kaydeder. |
| get_next_image(output_stream, page_size) | Görüntüyü verilen sayfa boyutuyla akışa kaydeder. |
| get_next_image(output_stream, format) | Görüntüyü verilen görüntü formatıyla akışa kaydeder. |
| get_next_image(output_stream, page_size, format) | Görüntüyü verilen sayfa boyutuyla akışa kaydeder. |
| get_next_image(output_file, format, image_width, image_height, quality) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile dosyaya kaydeder. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile akışa kaydeder. |
| get_next_image(output_file, format, image_width, image_height, quality) | Görüntüyü verilen görüntü formatı, görüntü boyutu ve kalite ile dosyaya kaydeder. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Görüntüyü verilen görüntü formatı, boyut ve kalite ile akışa kaydeder. |
| get_next_image(output_file, format, image_width, image_height) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile dosyaya kaydeder. |
| get_next_image(output_stream, format, image_width, image_height) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile akışa kaydeder. |
| get_next_image(output_stream, format, quality) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile akışa kaydeder. |
| get_next_image(output_stream, page_size, format, quality) | Görüntüyü verilen sayfa boyutu, görüntü formatı ve kalite ile akışa kaydeder. |
| get_next_image(output_file, format, quality) | Görüntüyü verilen görüntü formatı, boyutlar ve kalite ile dosyaya kaydeder. |
| get_next_image(output_file, page_size, format, quality) | Görüntüyü verilen sayfa boyutu, görüntü formatı ve kalite ile dosyaya kaydeder. |
| close() | PdfConverter örneğini kapatın ve kaynakları serbest bırakın. |
| do_convert() | Bir PDF belgesini görüntülere dönüştürmek için bazı başlangıç işlemleri yapın. |
| has_next_image() | PDF dosyasının daha fazla görüntüsü olup olmadığını gösterir. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Yok |
| merge_images_as_tiff(input_images_streams) | Tiff akışlarının listesini tek bir çok çerçeveli tiff akışı olarak birleştirir. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

