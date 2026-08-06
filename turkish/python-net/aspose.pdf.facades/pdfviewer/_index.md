---
title: "PdfViewer"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF'yi görüntülemek veya yazdırmak için bir sınıfı temsil eder."
type: docs
weight: 370
url: /tr/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

PDF'yi görüntülemek veya yazdırmak için bir sınıfı temsil eder.

PdfViewer türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfViewer() | Yeni [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) nesnesini başlatır. |
| PdfViewer(document) | PdfViewer sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| show_hidden_areas | Sayfadaki gizli alanların görünürlüğünü kontrol eden bayrağı alır veya ayarlar. |
| print_status | Yazdırma işinin sonucunu alır. Başarılıysa null; aksi takdirde istisna nesnesi. |
| use_intermidiate_image | Dosya modunda yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülmesini alır/ayarlar. Çıktı dosyasının boyutu önemli olduğunda kullanın. |
| coordinate_type | Sayfa koordinat tipini (Media/Crop kutuları) alır veya ayarlar. Varsayılan olarak CropBox değeri kullanılır. |
| print_as_image | PdfViewer'ın görüntü olarak yazdırması için bir modu ayarlar veya alır. |
| page_count | Mevcut Pdf dosyasının sayfa sayısını alır. |
| password | Giriş belgesi şifresini alır veya ayarlar. |
| print_page_dialog | Yazdırma sırasında sayfa numarası iletişim kutusunun üretilip üretilmeyeceğini belirten bir bool değerini alır veya ayarlar. |
| print_as_grayscale | Sayfanın gri tonlamalı olarak yazdırılıp yazdırılmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan olarak false. |
| printer_job_name | Belge yazdırıldığında yazıcı kuyruğundaki belge adını alır veya ayarlar. Varsayılan değer dosya adıdır. |
| form_presentation_mode | Form sunum modunu alır veya ayarlar. |
| rendering_options | Renderleme seçeneklerini alır veya ayarlar. |
| vertical_alignment | Dikey hizalamayı gösteren bir değeri alır veya ayarlar |
| horizontal_alignment | Yatay hizalamayı gösteren bir değeri alır veya ayarlar |
| auto_resize | Dosyanın optimize edilmiş boyutla yazdırılıp yazdırılmayacağını gösteren bir bool değerini alır veya ayarlar. |
| auto_rotate | Dosyanın otomatik döndürme ile yazdırılıp yazdırılmayacağını gösteren bir bool değerini alır veya ayarlar. |
| auto_rotate_mode | Dönüş yönünü gösteren bir AutoRotateMode değerini alır veya ayarlar. |
| resolution | Görünüm ve yazdırma sırasında çözünürlüğü alır veya ayarlar. Çözünürlük ne kadar yüksek olursa hız o kadar yavaş olur. Varsayılan değer 150'dir. |
| scale_factor | Ölçek faktörünü gösteren bir kayan nokta değerini alır veya ayarlar. Varsayılan değer 1.0'dır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| print_large_pdf(file_path) | Büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfaya sahip ise veya boyutu <br/>             3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. |
| print_large_pdf(input_stream) | Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfaya sahip ise veya boyutu <br/>             3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. |
| print_large_pdf(file_path, printer_settings) | Belirtilen yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce <br/>             sayfaya sahip ise veya boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. |
| print_large_pdf(input_stream, printer_settings) | Belirtilen yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce <br/>             sayfaya sahip ise veya boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için önerilir. |
| print_large_pdf(file_path, page_settings, printer_settings) | Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf <br/>             dosyanız yüzlerce sayfaya sahip ise veya boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için <br/>             önerilir. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Eğer Pdf <br/> dosyanızda yüzlerce sayfa veya daha fazlaysa ya da boyutu 3 MB'den büyükse, bu yöntem daha iyi performans elde etmek için <br/> önerilir. |
| print_document_with_settings(page_settings, printer_settings) | Pdf belgesini ayarlarla yazdırır. Belge boyutu sayfa boyutuna uygun değilse, pdf.kit sayfa boyutuna sığdırmak için genişletecektir. |
| print_document_with_settings(printer_settings) | Pdf belgesini ayarlarla yazdırır. Belge boyutu sayfa boyutuna uygun değilse, pdf.kit sayfa boyutuna sığdırmak için genişletecektir. |
| open_pdf_file(file_path) | Bir Pdf dosyasını açar, ancak Pdf dosyasının sayfalarını gerçekten çözümlemez. |
| open_pdf_file(input_stream) | Bir Pdf dosya akışı açar. Ancak Pdf dosyasının sayfalarını gerçekten çözümlemez. |
| bind_pdf(src_file) | Facade'i başlatır. |
| bind_pdf(src_stream) | Facade'i başlatır. |
| bind_pdf(src_doc) | Facade'i başlatır. |
| save(dest_file) | Sonuç PDF belgesini dosyaya kaydeder. |
| save(dest_stream) | Sonuç PDF belgesini akışa kaydeder. |
| decode_all_pages() | Mevcut pdf dosyasının sayfalarını al. |
| decode_page(page_number) | Bir Pdf dosyasının bir sayfasını çözer. |
| print_document_with_setup() | Pdf belgesini bir kurulum iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin. |
| print_document() | Pdf belgesini bir kurulum iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin. |
| get_default_page_settings() | Varsayılan sayfa ayarlarını alır. |
| get_default_printer_settings() | Varsayılan yazıcı ayarlarını alır. |
| close_pdf_file() | Mevcut Pdf dosyasını kapatır. |
| close() | Mevcut Pdf dosyasını kapatır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

