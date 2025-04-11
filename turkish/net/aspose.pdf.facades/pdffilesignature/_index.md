---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature sınıfı. Bir pdf dosyasını bir sertifika ile imzalamak için bir sınıfı temsil eder.
type: docs
weight: 4560
url: /tr/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature sınıfı

Bir pdf dosyasını bir sertifika ile imzalamak için bir sınıfı temsil eder.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | PdfFileSignature sınıfının yapıcısı. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | *document* temelinde yeni bir `PdfFileSignature` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Bir belgenin sertifikalı olup olmadığını belirleyen bayrağı alır. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | LTV etkin bayrağını alır. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | İmza için grafik görünümünü ayarlar veya alır. Özellik değeri resim dosyası adını temsil eder. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | İmza için grafik görünümünü ayarlar veya alır. Özellik değeri resim akışını temsil eder. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Düzenleme için bir Pdf akışını bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Düzenleme için bir Pdf dosyasını bağlar. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Belgeyi, zaten mevcut olan imza alanında yer alan MDP imzası ile sertifikalandırır. İmza atılmadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Böylece pdf belgesi zaten bir imza alanına sahiptir, imzayı damgalamak için yeri sağlamanız gerekmez, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. sigName parametresi). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Belgeyi MDP imzası ile sertifikalandırır. İmza nedeni, iletişim ve konum gibi veriler, imza nesnesinin sig ile ilgili özellikleri tarafından sağlanmalıdır. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Yüzeyi kapatır. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Pdf'nin dijital bir imza içerip içermediğini kontrol eder. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Pdf'nin kullanım haklarına sahip olup olmadığını kontrol eder. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | İmzanın tüm belgeyi kapsayıp kapsamadığını kontrol eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | İmzanın tek X.509 sertifikasını bir akış olarak çıkarır. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | İmzanın resmini çıkarır. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | MDP imza türü ile sertifikalı belgenin erişim izinleri değerini döndürür. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Tüm boş imza alanlarının adlarını alır. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Bir imzanın iletişim bilgilerini alır. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | İmzanın tarih saatini alır. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Bir imzanın konumunu alır. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Bir imzanın nedenini alır. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Bir imzanın revizyonunu alır. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Tüm boş olmayan imzaların adlarını alır. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | PDF belgesinde mevcut olan tüm imza algoritmaları hakkında bilgi alır. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Pdf belgesini imzalayan kişi veya kuruluşun adını alır. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Toplam revizyonu alır. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | İmza adını kullanarak imzayı kaldırır. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | İmza adını kullanarak imzayı kaldırır. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Tüm imzaları kaldırır. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Kullanım hakları girişini kaldırır. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Sonuç PDF'sini akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Sonuç PDF'sini dosyaya kaydeder. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | İmzalama işlemi için sertifika dosyası ve şifre ayarlar. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Belgeyi, zaten mevcut olan imza alanında yer alan belirtilen türdeki imza ile imzalar. İmza atılmadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Böylece pdf belgesi zaten bir imza alanına sahiptir, imzayı damgalamak için yeri sağlamanız gerekmez, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. SigName parametresi). İmza nedeni, iletişim ve konum gibi veriler, imza nesnesinin sig ile ilgili özellikleri tarafından sağlanmalıdır. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Belgeyi belirtilen türdeki imza ile imzalar. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Belgeyi, zaten mevcut olan imza alanında yer alan belirtilen türdeki imza ile imzalar. İmza atılmadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Böylece pdf belgesi zaten bir imza alanına sahiptir, imzayı damgalamak için yeri sağlamanız gerekmez, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. SigName parametresi). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Pdf belgesinde bir imza yapar. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Belgeyi belirtilen türdeki imza ile imzalar. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Belgeyi, zaten mevcut olan imza alanında yer alan belirtilen türdeki imza ile imzalar. İmza atılmadan önce pdf belgesi zaten bir imza alanına sahip olmalıdır, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. SigName parametresi). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Bir imzanın geçerliliğini kontrol eder. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Bir imzanın geçerliliğini kontrol eder. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)