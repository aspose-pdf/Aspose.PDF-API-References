---
title: "PdfContentEditor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder."
type: docs
weight: 190
url: /tr/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder.

PdfContentEditor türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfContentEditor() | PdfContentEditor nesnesinin yapıcısı. |
| PdfContentEditor(document) | PdfContentEditor sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| text_search_options | Metin arama seçeneklerini alır veya ayarlar. |
| text_edit_options | Metin düzenleme seçeneklerini alır veya ayarlar. |
| text_replace_options | Metin değiştirme seçeneklerini alır veya ayarlar. |
| replace_text_strategy | Metin değiştirme işlemi için bir dizi parametre. |
| DOCUMENT_OPEN | Bir belge olayı türü. Bir belge açar. |
| DOCUMENT_CLOSE | Bir belge olayı türü. Bir belge kapatır. |
| DOCUMENT_WILL_SAVE | Bir belge olayı türü. Kaydetmeden önce bir eylemi gerçekleştirir. |
| DOCUMENT_SAVED | Bir belge olayı türü. Kaydettikten sonra bir eylemi gerçekleştirir. |
| DOCUMENT_WILL_PRINT | Bir belge olayı türü. Yazdırmadan önce bir eylemi gerçekleştirir. |
| DOCUMENT_PRINTED | Bir belge olayı türü. Yazdırdıktan sonra bir eylemi yürütür. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(input_file) | Düzenleme için bir PDF dosyasını bağlar. |
| bind_pdf(input_stream) | Düzenleme için bir PDF akışını bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | PDF belgesini belirtilen dosyaya kaydeder. |
| save(dest_stream) | PDF belgesini belirtilen akışa kaydeder. |
| create_web_link(rect, url, original_page, clr) | PDF belgesinde bir web bağlantısı oluşturur. |
| create_web_link(rect, url, original_page) | PDF belgesinde bir web bağlantısı oluşturur. |
| create_local_link(rect, des_page, original_page, clr) | PDF belgesinde yerel bir bağlantı oluşturur. |
| create_local_link(rect, des_page, original_page) | PDF belgesinde yerel bir bağlantı oluşturur. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Başka bir PDF belge sayfasına bir bağlantı oluşturur. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Başka bir PDF belge sayfasına bir bağlantı oluşturur. |
| create_application_link(rect, application, page, clr) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| create_application_link(rect, application, page) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| create_file_attachment(rect, contents, file_path, page, name) | Dosya eki açıklaması oluşturur. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Dosya eki açıklaması oluşturur. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Dosya eki açıklaması oluşturur. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Dosya eki açıklaması oluşturur. |
| add_document_attachment(file_attachment_path, description) | Açıklama olmadan belge eki ekler. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Açıklama olmadan belge eki ekler. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Bir kauçuk damga açıklaması oluşturur. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Bir kauçuk damga açıklaması oluşturur. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Bir kauçuk damga açıklaması oluşturur. |
| delete_image(page_number, index) | Belirtilen sayfadaki belirtilen görüntüleri siler. |
| delete_image() | Belirtilen sayfadaki belirtilen görüntüleri siler. |
| replace_text(src_string, the_page, dest_string, text_state) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) değiştirilecek metin için belirtilebilir. |
| replace_text(src_string, dest_string) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) değiştirilecek metin için belirtilebilir. |
| replace_text(src_string, the_page, dest_string) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) değiştirilecek metin için belirtilebilir. |
| replace_text(src_string, dest_string, text_state) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) değiştirilecek metin için belirtilebilir. |
| replace_text(src_string, dest_string, font_size) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) değiştirilecek metin için belirtilebilir. |
| delete_stamp_by_ids(stamp_ids) | Belirtilen kimliklere sahip damgaları belgenin tüm sayfalarından siler. |
| delete_stamp_by_ids(page_number, stamp_ids) | Belirtilen kimliklere sahip damgaları belgenin tüm sayfalarından siler. |
| delete_stamp_by_id(page_number, stamp_id) | Belirtilen kimliklere sahip damgaları belgenin tüm sayfalarından siler. |
| delete_stamp_by_id(stamp_id) | Belirtilen kimliklere sahip damgaları belgenin tüm sayfalarından siler. |
| close() | Açık belgeyi kapatır. |
| extract_link() | PDF belgesinde bulunan Link örneklerinin koleksiyonunu çıkarır. |
| create_java_script_link(code, rect, original_page, color) | PDF belgesinde JavaScript'e bir bağlantı oluşturur. |
| create_text(rect, title, contents, open, icon, page) | PDF belgesinde metin açıklaması oluşturur. |
| create_free_text(rect, contents, page) | PDF belgesinde serbest metin açıklaması oluşturur. |
| create_markup(rect, contents, type, page, clr) | PDF belgesinde işaretleme açıklaması oluşturur. |
| create_popup(rect, contents, open, page) | PDF belgesinde açılır pencere açıklaması oluşturur. |
| delete_attachments() | PDF belgesindeki tüm ekleri siler. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Çizgi açıklaması oluşturur. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Kare-daire açıklaması oluşturur. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Eğri açıklaması oluşturur. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Poligon açıklaması oluşturur. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Çoklu çizgi açıklaması oluşturur. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | İmleç açıklaması oluşturur. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Belirtilen eyleme sahip bir yer imi oluşturur. |
| add_document_additional_action(event_type, code) | Belge olayı için ek eylem ekler. |
| remove_document_open_action() | Belgeden açma eylemini kaldırır. Bu işlem, başlangıçta açıkça 'GoTo' eylemi kullanan birden fazla belgeyi birleştirirken faydalıdır. |
| change_viewer_preference(viewer_attribution) | Görünüm tercihini değiştirir. |
| get_viewer_preference() | Görünüm tercihini döndürür. |
| replace_image(page_number, index, image_file) | PDF belgesinin belirtilen sayfasındaki belirtilen resmi başka bir resimle değiştirir. |
| create_movie(rect, file_path, page) | Film Açıklamaları Oluşturur. |
| create_sound(rect, file_path, name, page, rate) | Ses Açıklamaları Oluşturur. |
| delete_stamp(page_number, index) | Belirtilen sayfada birden fazla damgayı damga indeksleriyle siler. |
| hide_stamp_by_id(page_number, stamp_id) | Damgayı gizler. Gizlendikten sonra, damga görünürlüğü ShowStampById yöntemiyle geri getirilebilir. |
| show_stamp_by_id(page_number, stamp_id) | HiddenStampById ile gizlenen damgayı gösterir. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Damganın sayfadaki konumunu değiştirir. |
| move_stamp(page_number, stamp_index, x, y) | Damganın sayfadaki konumunu değiştirir. |
| get_stamps(page_number) | Sayfadaki damgaların dizisini döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

