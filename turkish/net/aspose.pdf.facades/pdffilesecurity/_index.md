---
title: PdfFileSecurity
second_title: Aspose.PDF for .NET API Referansı
description: Bir Pdf dosyasının sahip veya kullanıcı şifresi ile şifrelenmesini veya şifresinin çözülmesini güvenlik ayarının ve şifrenin değiştirilmesini temsil eder.
type: docs
weight: 2560
url: /tr/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Bir Pdf dosyasının sahip veya kullanıcı şifresi ile şifrelenmesini veya şifresinin çözülmesini, güvenlik ayarının ve şifrenin değiştirilmesini temsil eder.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | PdfFileSecurity nesnesini başlatın. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Yeniyi başlatır[`PdfFileSecurity`](../pdffilesecurity) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Son işlem tarafından oluşturulan istisnayı döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Cepheyi başlatır. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Kullanıcı parolasını ve sahip parolasını sahip parolasıyla değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa sahip parolası rastgele bir dizeyle değiştirilir. İşlem başarısız olursa bir istisna atar. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Kullanıcı parolasını ve parolayı sahip parolasıyla değiştirir, Pdf belge güvenliğinin sıfırlanmasına olanak tanır. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa sahip parolası rastgele bir dizeyle değiştirilir. İşlem başarısız olursa bir istisna atar. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Kullanıcı parolasını ve parolayı sahip parolasıyla değiştirir, Pdf belge güvenliğinin sıfırlanmasına olanak tanır. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa, sahip parolası rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisnası ortaya çıkar. İşlem başarısız olursa bir istisna atar. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Cepheyi kapatır. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Şifrelenmiş bir Pdf belgesinin şifresini sahip parolasıyla çözer. Belgenin sahip parolası yoksa, kullanıcı parolasını kullanmasına izin verilir. İşlem başarısız olursa bir istisna atar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Pdf dosyasını kullanıcı parolası ve sahip parolasıyla şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı parolası ve sahip parolası boş veya boş olabilir. Girilen sahip parolası boşsa veya boşsa sahip parolası rastgele bir dizeyle değiştirilir. İşlem başarısız olursa istisna atar. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Pdf dosyasını kullanıcı parolası ve sahip parolasıyla şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı parolası ve sahip parolası boş veya boş olabilir. Girilen sahip parolası boş veya boşsa, sahip parolası rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisnası ortaya çıkar. İşlem başarısız olursa bir istisna atar. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Boş kullanıcı/sahip parolalarıyla Pdf dosyası güvenliğini ayarlar. Sahip parolası rastgele bir dizeyle eklenecektir. İşlem başarısız olursa bir istisna atar. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Orijinal parola ile Pdf dosyası güvenliğini ayarlar. İşlem başarısız olursa bir istisna atar. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Kullanıcı parolasını ve sahip parolasını sahip parolasıyla değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Sahip parolası değiştirilecek İşlem başarısız olursa bir istisna oluşturmaz. Yeni sahip parolası boş veya boşsa rastgele bir dizeyle. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Kullanıcı parolasını ve parolayı sahip parolasıyla değiştirir, Pdf belge güvenliğinin sıfırlanmasına olanak tanır. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa sahip parolası rastgele bir dizeyle değiştirilir. İşlem başarısız olursa bir istisna oluşturmaz. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Kullanıcı parolasını ve parolayı sahip parolasıyla değiştirir, Pdf belge güvenliğinin sıfırlanmasına olanak tanır. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa, sahip parolası rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisnası ortaya çıkar. İşlem başarısız olursa bir istisna oluşturmaz. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Şifrelenmiş bir Pdf belgesinin şifresini sahip parolasıyla çözer. Belgenin sahip parolası yoksa, kullanıcı parolasını kullanmasına izin verilir. İşlem başarısız olursa bir istisna oluşturmaz. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Pdf dosyasını kullanıcı parolası ve sahip parolasıyla şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı parolası ve sahip parolası boş veya boş olabilir. Girilen sahip parolası boşsa veya boşsa sahip parolası rastgele bir dizeyle değiştirilir. İşlem başarısız olursa bir istisna oluşturmaz. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Orijinal parola ile Pdf dosyası güvenliğini ayarlar. İşlem başarısız olursa bir istisna oluşturmaz. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
