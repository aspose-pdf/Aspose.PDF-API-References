---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belgesini dönüştürmek için seçenekler kümesini temsil eder"
type: docs
weight: 1220
url: /tr/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

PDF belgesini dönüştürmek için seçenekler kümesini temsil eder

PdfFormatConversionOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | PdfFormatConversionOptions sınıfının yeni bir örneğini başlatır |
| PdfFormatConversionOptions(output_log_file_name, format) | PdfFormatConversionOptions sınıfının yeni bir örneğini başlatır |
| PdfFormatConversionOptions(format) | PdfFormatConversionOptions sınıfının yeni bir örneğini başlatır |
| PdfFormatConversionOptions(format, action) | PdfFormatConversionOptions sınıfının yeni bir örneğini başlatır |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | PdfFormatConversionOptions sınıfının yeni bir örneğini başlatır |
| PdfFormatConversionOptions(output_log_stream, format, action) | PdfFormatConversionOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_async_image_streams_conversion_mode | Asenkron modda görüntü akışlarının çalıştırılmasını alır/ayarlar. |
| is_low_memory_mode | Düşük bellek dönüşüm modu etkin mi |
| format | PDF formatı. |
| log_file_name | Yorumların saklanacağı dosyanın yolu. |
| log_stream | Yorumların saklanacağı akış. |
| error_action | Dönüştürülemeyen nesneler için eylem |
| transparency_action | Maskeleme uygulanmış görüntü nesneleri için eylem |
| convert_soft_mask_action | Yumuşak maske içeren görüntüler için eylem. |
| varsayılan | Varsayılan parametrelerle PdfFormatConversionOptions nesnesini alır |
| non_specification_cases | Kaynak belge<br/>            PDF/A spesifikasyonuna uymadığında durumlar için PDF/A dönüşüm sürecini kontrol eden bayrakları tutar. |
| symbolic_font_encoding_strategy | Sembolik TrueType fontunun birden fazla kodlama alt tablosu varsa, sembolik fontlar için kodlama verilerini kopyalama stratejisi.<br/>             |
| align_text | Bu bayrak, dönüştürülmüş belgede metin hizalamasını kontrol eder. Varsayılan olarak belge dönüşümü <br/>            metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda yazı tipi ikamesi<br/>            dönüştürülmüş belgede metin çakışmasına veya ekstra boşluklara neden olur. Bu bayrak ayarlandığında<br/>            özel hizalama işlemleri gerçekleştirilir. Bu bayrak yalnızca metin çakışması veya ekstra boşluk sorunları olan belgeler için ayarlanmalıdır<br/>            çünkü bu bayrağın kullanılması performansı düşürür ve bazı durumlarda metin içeriğini bozabilir. |
| pua_text_processing_strategy | Unicode Özel Kullanım Alanı (PUA) içindeki sembolleri işlemek için strateji. |
| optimize_file_size | PDF/A belgesinin dosya boyutunu azaltmak için özel dönüşüm modunu etkinleştiren/devre dışı bırakan bir bayrağı alır veya ayarlar.<br/>            Şimdi bu bayrak, PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler, muhtemelen gelecekte bu bayrak <br/>            ayrıca grafik gibi diğer veri yapılarına optimizasyonu açmak için kullanılacaktır.  <br/>            Bu bayrak ve modun ayarlanması dosya boyutunu önemli ölçüde azaltabilir, ancak aynı zamanda dönüşüm performansını <br/>            önemli ölçüde düşürebilir. |
| exclude_fonts_strategy | Gereksiz yazı tiplerini dışlamak ve belge dosya boyutunu azaltmak için strateji(ler). <br/>            Bu parametre yalnızca [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) bayrağı true olarak ayarlandığında anlamlıdır.<br/>            Varsayılan olarak [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) ve <br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) stratejilerinin kombinasyonu kullanılır. |
| font_embedding_options | Bazı yazı tiplerinin PDF belgesine gömülmesinin mümkün olmadığı durumlar için seçenekler. |
| unicode_processing_rules | Unicode eşlemesiyle ilgili sorunları çözmek için kurallar. Null olabilir. |
| icc_profile_file_name | ICC profil adının dosya adını alır veya ayarlar. Null durumunda varsayılan ICC profil kullanılır. |
| not_accessible_fonts | Bu özellik dışarıya yönlendirilmiş bir özelliktir. Bilgisayarda bulunamayan tüm yazı tiplerini (yazı tipi adları) tutar <br/>            son PDF/A dönüşümünde. |
| is_transfer_info | PDF 2.0'a dönüştürüldüğünde Bilgi'den Üstveri'ye veri aktarılıp aktarılmayacağını alır veya ayarlar. Varsayılan olarak true. |
| align_strategy | Metni hizalamak için strateji. Bu parametre yalnızca [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) bayrağı true olarak ayarlandığında anlamlıdır. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

