---
title: "PdfFileSignature"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Bir PDF dosyasını sertifika ile imzalamak için bir sınıfı temsil eder."
type: docs
weight: 310
url: /tr/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Bir PDF dosyasını sertifika ile imzalamak için bir sınıfı temsil eder.

PdfFileSignature türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileSignature() | PdfFileSignature sınıfının yapıcı metodu. |
| PdfFileSignature(input_file) | PdfFileSignature sınıfının yeni bir örneğini başlatır |
| PdfFileSignature(input_file, output_file) | PdfFileSignature sınıfının yeni bir örneğini başlatır |
| PdfFileSignature(document) | PdfFileSignature sınıfının yeni bir örneğini başlatır |
| PdfFileSignature(document, output_file) | PdfFileSignature sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| signature_appearance | İmza için grafik görünümünü ayarlar veya alır. Özellik değeri resim dosya adını temsil eder. |
| is_ltv_enabled | LTV etkin bayrağını alır. |
| is_certified | Belgenin onaylı olup olmadığını belirleyen bayrağı alır. |
| signature_appearance_stream | İmza için grafik görünümünü ayarlar veya alır. Özellik değeri resim akışını temsil eder. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(input_file) | Düzenleme için bir Pdf dosyasını bağlar. |
| bind_pdf(input_stream) | Düzenleme için bir Pdf akışını bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(output_file) | Sonuç PDF'i dosyaya kaydeder. |
| save(output_stream) | Sonuç PDF'i akışa kaydeder. |
| save() | Sonuç PDF'i dosyaya kaydeder. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Pdf belgesine bir imza ekleyin. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Belgeyi verilen tip imzası ile imzalayın. |
| sign(page, visible, annot_rect, sig) | Belgeyi verilen tip imzası ile imzalayın. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Belgeyi verilen tip imzası ile imzalayın. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Belgeyi verilen tip imzası ile imzalayın. |
| sign(sig_name, sig) | Belgeyi verilen tip imzası ile imzalayın. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Belgeyi MDP imzası ile onaylayın.<br/>            İmza nedeni, iletişim ve konum gibi veriler, Signature nesnesi sig'in ilgili özellikleriyle sağlanmalıdır. |
| certify(sig_name, doc_mdp_signature) | Belgeyi MDP imzası ile onaylayın.<br/>            İmza nedeni, iletişim ve konum gibi veriler, Signature nesnesi sig'in ilgili özellikleriyle sağlanmalıdır. |
| remove_signature(sign_name) | İmzanın adına göre imzayı kaldırın. |
| remove_signature(sign_name, remove_field) | İmzanın adına göre imzayı kaldırır. |
| close() | Facade'i kapatır. |
| get_access_permissions() | MDP imza türüyle onaylanmış belgenin erişim izinleri değerini döndürür. |
| get_sign_names(only_active) | Boş olmayan tüm imzaların adlarını alır. |
| get_blank_sign_names() | Tüm boş imza alanlarının adlarını alır. |
| is_contain_signature() | Pdf'nin dijital bir imzası olup olmadığını kontrol eder. |
| contains_signature() | Pdf'nin dijital bir imzası olup olmadığını kontrol eder. |
| contains_usage_rights() | PDF'nin kullanım haklarına sahip olup olmadığını kontrol eder. |
| is_covers_whole_document(sign_name) | İmzanın tüm belgeyi kapsayıp kapsamadığını kontrol eder. |
| covers_whole_document(sign_name) | İmzanın tüm belgeyi kapsayıp kapsamadığını kontrol eder. |
| get_revision(sign_name) | İmzanın revizyonunu alır. |
| get_total_revision() | Toplam revizyonu alır. |
| remove_usage_rights() | Kullanım hakları girişini kaldırır. |
| verify_signed(sign_name) | İmzanın geçerliliğini kontrol eder. |
| get_signer_name(sign_name) | PDF belgesini imzalayan kişi veya kuruluşun adını alır. |
| get_date_time(sign_name) | İmzanın tarih ve saatini alır. |
| get_reason(sign_name) | İmzanın nedenini alır. |
| get_location(sign_name) | İmzanın konumunu alır. |
| get_contact_info(sign_name) | İmzanın iletişim bilgilerini alır. |
| verify_signature(sign_name) | İmzanın geçerliliğini kontrol eder. |
| extract_image(sign_name) | İmzanın görüntüsünü çıkarır. |
| extract_certificate(sign_name) | İmzanın tek X.509 sertifikasını akış olarak çıkarır. |
| set_certificate(pfx, pass) | İmzalama rutini için sertifika dosyasını ve şifreyi ayarla. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

