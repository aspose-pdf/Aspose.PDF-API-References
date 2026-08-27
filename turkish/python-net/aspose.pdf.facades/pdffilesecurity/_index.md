---
title: "PdfFileSecurity"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Bir PDF dosyasını sahibi veya kullanıcı parolasıyla şifreleme veya şifre çözmeyi, güvenlik ayarını ve parolayı değiştirmeyi temsil eder."
type: docs
weight: 300
url: /tr/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Bir PDF dosyasını sahibi veya kullanıcı parolasıyla şifreleme veya şifre çözmeyi, güvenlik ayarını ve parolayı değiştirmeyi temsil eder.

PdfFileSecurity türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | PdfFileSecurity sınıfının yeni bir örneğini başlatır |
| PdfFileSecurity(input_file, output_file) | PdfFileSecurity sınıfının yeni bir örneğini başlatır |
| PdfFileSecurity() | PdfFileSecurity nesnesini başlat. |
| PdfFileSecurity(document) | PdfFileSecurity sınıfının yeni bir örneğini başlatır |
| PdfFileSecurity(document, output_file) | PdfFileSecurity sınıfının yeni bir örneğini başlatır |
| PdfFileSecurity(document, output_stream) | PdfFileSecurity sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| allow_exceptions | Bu değer true olarak ayarlanırsa, işlem hatasında bir istisna fırlatılır. Aksi takdirde, yöntem başarısızlıkta false döner ve son istisna LastException özelliğiyle kontrol edilebilir. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | Facade'i başlatır. |
| bind_pdf(src_stream) | Facade'i başlatır. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | PDF belgesini belirtilen dosyaya kaydeder. |
| save(dest_stream) | PDF belgesini belirtilen akışa kaydeder. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Pdf dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar.<br/>            Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Giriş sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilir.<br/>            İşlem başarısız olursa istisna fırlatır. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Pdf dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar.<br/>            Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Giriş sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilir.<br/>            KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır.<br/>            Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaştığında ilgili istisna yükseltilir.<br/>            İşlem başarısız olursa bir istisna fırlatır. |
| set_privilege(privilege) | Pdf dosyası güvenliğini boş kullanıcı/sahibi şifreleriyle ayarlar.<br/>            Sahibi şifresi rastgele bir dizeyle eklenir.<br/>            İşlem başarısız olursa bir istisna fırlatır. |
| set_privilege(user_password, owner_password, privilege) | Pdf dosyası güvenliğini orijinal şifreyle ayarlar.<br/>            İşlem başarısız olursa bir istisna fırlatır. |
| change_password(owner_password, new_user_password, new_owner_password) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, orijinal güvenlik ayarlarını korur.<br/>             Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilir.<br/>             İşlem başarısız olursa bir istisna fırlatır. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Kullanıcı şifresini ve şifreyi, sahibi şifresiyle değiştirir, Pdf belgesi güvenliğini sıfırlamaya izin verir.<br/>            Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilir.<br/>            İşlem başarısız olursa bir istisna fırlatır. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, PDF belge güvenliğini sıfırlamaya izin verir.<br/>            Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Sahibi şifresi, yeni sahibi şifresi null veya boş ise rastgele bir dizeyle değiştirilir.<br/>            KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. <br/>            Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve ilgili <br/>            istisna, kit bu kombinasyonla karşılaştığında yükseltilir.<br/>            İşlem başarısız olursa bir istisna fırlatır. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, orijinal güvenlik ayarlarını korur.<br/>             Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Sahibi şifresi, <br/>             yeni sahibi şifresi null veya boş ise rastgele bir dizeyle değiştirilir.<br/>             İşlem başarısız olsa da bir istisna fırlatmaz. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, PDF belge güvenliğini sıfırlamaya izin verir.<br/>            Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Sahibi şifresi, yeni sahibi şifresi null veya boş ise rastgele bir dizeyle değiştirilir.<br/>            İşlem başarısız olsa da bir istisna fırlatmaz. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, PDF belge güvenliğini sıfırlamaya izin verir.<br/>            Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Sahibi şifresi, yeni sahibi şifresi null veya boş ise rastgele bir dizeyle değiştirilir.<br/>            KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. <br/>            Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve ilgili <br/>            istisna, kit bu kombinasyonla karşılaştığında yükseltilir.<br/>            İşlem başarısız olsa da bir istisna fırlatmaz. |
| close() | Facade'i kapatır. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | PDF dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim izinlerini ayarlar.<br/>            Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Sahibi şifresi, girilen sahibi şifresi null veya boş ise rastgele bir dizeyle değiştirilir.<br/>            İşlem başarısız olsa da bir istisna fırlatmaz. |
| decrypt_file(owner_password) | Şifrelenmiş bir PDF belgesini sahibi şifresiyle çözer. <br/>            Belgenin sahibi şifresi yoksa, kullanıcı şifresi kullanılmasına izin verilir.<br/>            İşlem başarısız olursa bir istisna fırlatır. |
| try_decrypt_file(owner_password) | Şifrelenmiş bir PDF belgesini sahibi şifresiyle çözer. <br/>            Belgenin sahibi şifresi yoksa, kullanıcı şifresi kullanılmasına izin verilir.<br/>            İşlem başarısız olsa da bir istisna fırlatmaz. |
| try_set_privilege(user_password, owner_password, privilege) | PDF dosyasının güvenliğini orijinal şifreyle ayarlar.<br/>            İşlem başarısız olsa da bir istisna fırlatmaz. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

