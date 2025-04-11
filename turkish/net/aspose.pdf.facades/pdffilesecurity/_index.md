---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSecurity sınıfı. Bir Pdf dosyasını sahip veya kullanıcı parolası ile şifreleme veya şifre çözme, güvenlik ayarlarını ve parolayı değiştirme işlemini temsil eder.
type: docs
weight: 4550
url: /tr/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity Sınıfı

Bir Pdf dosyasını sahip veya kullanıcı parolası ile şifreleme veya şifre çözme, güvenlik ayarlarını ve parolayı değiştirme işlemini temsil eder.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | PdfFileSecurity nesnesini başlatır. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | *document* temelinde yeni bir `PdfFileSecurity` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Son işlem tarafından fırlatılan istisnayı döndürür. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Yüzeyi başlatır. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Kullanıcı parolasını ve sahip parolasını değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı parolası ve yeni sahip parolası null veya boş olabilir. Yeni sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatır. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Kullanıcı parolasını ve sahip parolasını değiştirir, Pdf belgesinin güvenliğini sıfırlamaya izin verir. Yeni kullanıcı parolası ve yeni sahip parolası null veya boş olabilir. Yeni sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatır. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Kullanıcı parolasını ve sahip parolasını değiştirir, Pdf belgesinin güvenliğini sıfırlamaya izin verir. Yeni kullanıcı parolası ve yeni sahip parolası null veya boş olabilir. Yeni sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. 6 olası KeySize ve Algorithm kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve bu kombinasyonla karşılaşılırsa ilgili bir istisna fırlatılacaktır. İşlem başarısız olursa bir istisna fırlatır. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Yüzeyi kapatır. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Sahip parolası ile şifrelenmiş bir Pdf belgesinin şifresini çözer. Belgenin sahip parolası yoksa, kullanıcı parolasının kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Pdf dosyasını kullanıcı parolası ve sahip parolası ile şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı parolası ve sahip parolası null veya boş olabilir. Girdi sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatır. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Pdf dosyasını kullanıcı parolası ve sahip parolası ile şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı parolası ve sahip parolası null veya boş olabilir. Girdi sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. 6 olası KeySize ve Algorithm kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve bu kombinasyonla karşılaşılırsa ilgili bir istisna fırlatılacaktır. İşlem başarısız olursa bir istisna fırlatır. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Boş kullanıcı/sahip parolaları ile Pdf dosyası güvenliğini ayarlar. Sahip parolası rastgele bir dize ile eklenecektir. İşlem başarısız olursa bir istisna fırlatır. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Orijinal parolayla Pdf dosyası güvenliğini ayarlar. İşlem başarısız olursa bir istisna fırlatır. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Kullanıcı parolasını ve sahip parolasını değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı parolası ve yeni sahip parolası null veya boş olabilir. Yeni sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Kullanıcı parolasını ve sahip parolasını değiştirir, Pdf belgesinin güvenliğini sıfırlamaya izin verir. Yeni kullanıcı parolası ve yeni sahip parolası null veya boş olabilir. Yeni sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Kullanıcı parolasını ve sahip parolasını değiştirir, Pdf belgesinin güvenliğini sıfırlamaya izin verir. Yeni kullanıcı parolası ve yeni sahip parolası null veya boş olabilir. Yeni sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. 6 olası KeySize ve Algorithm kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve bu kombinasyonla karşılaşılırsa ilgili bir istisna fırlatılacaktır. İşlem başarısız olursa bir istisna fırlatmaz. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Sahip parolası ile şifrelenmiş bir Pdf belgesinin şifresini çözer. Belgenin sahip parolası yoksa, kullanıcı parolasının kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatmaz. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Pdf dosyasını kullanıcı parolası ve sahip parolası ile şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı parolası ve sahip parolası null veya boş olabilir. Girdi sahip parolası null veya boşsa, sahip parolası rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Orijinal parolayla Pdf dosyası güvenliğini ayarlar. İşlem başarısız olursa bir istisna fırlatmaz. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)