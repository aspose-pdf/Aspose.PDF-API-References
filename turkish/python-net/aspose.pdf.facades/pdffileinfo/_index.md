---
title: "PdfFileInfo"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder."
type: docs
weight: 270
url: /tr/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder.

PdfFileInfo türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileInfo() | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| PdfFileInfo(input_stream) | PdfFileInfo sınıfının yeni bir örneğini başlatır |
| PdfFileInfo(input_stream, password) | PdfFileInfo sınıfının yeni bir örneğini başlatır |
| PdfFileInfo(input_file) | PdfFileInfo sınıfının yeni bir örneğini başlatır |
| PdfFileInfo(input_file, password) | PdfFileInfo sınıfının yeni bir örneğini başlatır |
| PdfFileInfo(document) | PdfFileInfo sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| author | PDF belgesinin Author bilgisini alır veya ayarlar. |
| is_encrypted | PDF belgesinin şifrelenip şifrelenmediğini kontrol eder. |
| is_pdf_file | Kaynak girdinin geçerli bir PDF dosyası olup olmadığını kontrol eder. |
| use_strict_validation | Sıkı doğrulama kurallarını [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) özelliği aracılığıyla kullanır. |
| creation_date | PDF belgesinin CreationDate bilgisini alır veya ayarlar. |
| creator | PDF belgesinin Creator bilgisini alır veya ayarlar. |
| has_collection | Geçerli giriş dosyası, içinde PDF dosyalarının koleksiyonunu içeren bir 'Portfolio' dosyası ise true döndürür. |
| input_file | Giriş dosyasını alır veya ayarlar. |
| input_stream | Giriş akışını alır veya ayarlar. |
| keywords | PDF belgesinin Anahtar Kelimeler bilgisini alır veya ayarlar. |
| mod_date | PDF belgesinin ModDate tarih bilgisini alır veya ayarlar. |
| number_of_pages | Belge sayfalarının sayısını alır. |
| producer | PDF belgesinin Üretici bilgisini alır. |
| subject | PDF belgesinin Konu bilgisini alır veya ayarlar. |
| title | PDF belgesinin Başlık bilgisini alır veya ayarlar. |
| password_type | PdfFileInfo örneği oluşturulurken geçirilen şifre tipini döndürür. Olası değerleri [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) adresinde görebilirsiniz.<br/>            Dikkat edin ki PDF belgesi hem kullanıcı (veya açma) şifresi hem de sahip (veya izinler, düzenleme) şifresi kullanılarak açılabilir. |
| has_open_password | Parola korumalı PDF belgesini açmak için şifre gerekiyorsa true döndürür. |
| has_edit_password | İzinleri veya belge güvenlik özelliğini değiştirmek için şifre gerekiyorsa true döndürür.<br/>            Dikkat edin ki bu özellik yalnızca [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) yapıcı içinde geçerli bir şifre sağlandığında okunabilir.<br/>            PasswordType Inaccessible (geçersiz şifre sağlandığı anlamına gelir) olduğunda bu özelliği okumak [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/) hatasıyla sonuçlanır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_doc) | Facade'i başlatır. |
| bind_pdf(src_file) | Facade'i başlatır. |
| bind_pdf(src_stream) | Facade'i başlatır. |
| save(dest_stream) | Güncellenmiş PDF belgesini belirtilen akışa kaydeder. |
| save(dest_file) | Güncellenmiş PDF belgesini belirtilen dosyaya kaydeder. |
| save_new_info(output_stream) | Güncellenmiş PDF belgesini belirtilen akışa kaydeder. |
| save_new_info(output_file) | Güncellenmiş PDF belgesini belirtilen dosyaya kaydeder. |
| close() | Örneği başlatmayı kaldırır. |
| clear_info() | PDF belgesinin tüm meta bilgilerini temizler. |
| get_document_privilege() | PDF belgesinin ayrıcalık ayarlarını alır. |
| get_meta_info(name) | PDF belgesinin özelleştirilmiş bilgisini, özellik adıyla alır. Eğer adla eşleşen bir özellik yoksa boş bir dize döndürür. |
| get_page_height(page_num) | Belirtilen sayfanın yüksekliğini alır. |
| get_page_rotation(page_num) | Belirtilen sayfanın dönüşünü alır. |
| get_page_width(page_num) | Belirtilen sayfanın genişliğini alır. |
| get_page_x_offset(page_num) | Belirtilen sayfa görüntü alanının yatay offsetini alır. |
| get_page_y_offset(page_num) | Belirtilen sayfa görüntü alanının dikey offsetini alır. |
| get_pdf_version() | PDF belgesinin sürüm bilgisini alır. |
| set_meta_info(name, value) | PDF belgesinin özelleştirilmiş bilgisini ayarlar. |
| save_new_info_with_xmp(output_file_name) | Dosya bilgilerini ayarlayarak açıkça belirtilen özellikleri değiştirir, diğer özellikler aynı kalır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

