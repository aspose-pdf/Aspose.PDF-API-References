---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF dosyasının yer imleriyle (oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme) çalışmak için bir sınıfı temsil eder."
type: docs
weight: 180
url: /tr/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

PDF dosyasının yer imleriyle (oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme) çalışmak için bir sınıfı temsil eder.

PdfBookmarkEditor türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfBookmarkEditor() | Yeni bir [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) nesnesi başlatır. |
| PdfBookmarkEditor(document) | PdfBookmarkEditor sınıfının yeni bir örneğini başlatır. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | PDF belgesini belirtilen dosyaya kaydeder. |
| save(dest_stream) | PDF belgesini belirtilen akışa kaydeder. |
| create_bookmarks() | Tüm sayfalar için yer imleri oluşturur. |
| create_bookmarks(bookmark) | Tüm sayfalar için yer imleri oluşturur. |
| create_bookmarks(color, bold_flag, italic_flag) | Belirtilen renk ve stil (kalın, italik) ile tüm sayfalar için yer imleri oluşturun. |
| create_bookmark_of_page(bookmark_name, page_number) | Belirtilen sayfa için yer imi oluşturur. |
| create_bookmark_of_page(bookmark_name, page_number) | Belirtilen sayfalar için yer imleri oluşturur. |
| delete_bookmarks() | PDF belgesinin tüm yer imlerini siler. |
| delete_bookmarks(title) | PDF belgesinin yer imini siler. |
| extract_bookmarks() | Belgeden tüm seviyelerdeki yer imlerini çıkarır. |
| extract_bookmarks(upper_level) | Belgeden tüm seviyelerdeki yer imlerini çıkarır. |
| extract_bookmarks(title) | Belirtilen başlıktaki yer imlerini çıkarır. |
| extract_bookmarks(bookmark) | Belgeden tüm seviyelerdeki yer imlerini çıkarır. |
| export_bookmarks_to_xml(xml_file) | Yer imlerini XML dosyasına dışa aktarır. |
| export_bookmarks_to_xml(stream) | Yer imlerini XML akışına dışa aktarır. |
| import_bookmarks_with_xml(xml_file) | Yer imlerini XML dosyasından belgeye içe aktarır. |
| import_bookmarks_with_xml(stream) | Yer imlerini XML dosyasından belgeye içe aktarır. |
| close() | Mevcut facade ile ilişkili tüm kaynakları serbest bırakır. |
| modify_bookmarks(s_title, d_title) | Belirtilen yer imi başlığına göre yer imi başlığını değiştirir. |
| extract_bookmarks_to_html(pdf_file, css_file) | Yer imlerini HTML dosyasına dışa aktarır. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Yer imlerini HTML dosyasına dışa aktarır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

