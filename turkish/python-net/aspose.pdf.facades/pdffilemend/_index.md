---
title: "PdfFileMend"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Mevcut PDF belgesinin sayfalarına metin ve görüntü eklemek için bir sınıfı temsil eder."
type: docs
weight: 280
url: /tr/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Mevcut PDF belgesinin sayfalarına metin ve görüntü eklemek için bir sınıfı temsil eder.

PdfFileMend türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileMend() | Yapıcı. |
| PdfFileMend(input_file_name, output_file_name) | PdfFileMend sınıfının yeni bir örneğini başlatır |
| PdfFileMend(input_stream, output_stream) | PdfFileMend sınıfının yeni bir örneğini başlatır |
| PdfFileMend(document) | PdfFileMend sınıfının yeni bir örneğini başlatır |
| PdfFileMend(document, output_file_name) | PdfFileMend sınıfının yeni bir örneğini başlatır |
| PdfFileMend(document, dest_stream) | PdfFileMend sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| input_stream | Giriş akışını ayarlar. |
| output_stream | Çıkış akışını ayarlar. |
| input_file | Giriş dosyasını ayarlar. |
| output_file | Çıkış dosyasını ayarlar. |
| wrap_mode | Kelime kaydırma algoritmasını ayarlar veya alır. WordWrapMode ve IsWordWrap'a bakın. |
| text_positioning_mode | Metin konumlandırma stratejisini ayarlar veya alır. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            Varsayılan mod Legacy'dir. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | PDF belgesini belirtilen dosyaya kaydeder. |
| save(dest_stream) | PDF belgesini belirtilen akışa kaydeder. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Henüz uygulanmadı. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Henüz uygulanmadı. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Henüz uygulanmadı. |
| close() | PdfFileMend nesnesini kapatır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

