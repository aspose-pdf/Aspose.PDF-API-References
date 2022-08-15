---
title: PdfFileSignature
second_title: Aspose.PDF for .NET API Referansı
description: Bir pdf dosyasını bir sertifika ile imzalamak için bir sınıfı temsil eder.
type: docs
weight: 2570
url: /tr/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Bir pdf dosyasını bir sertifika ile imzalamak için bir sınıfı temsil eder.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | PdfFileSignature sınıfının yapıcısı. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Yeniyi başlatır[`PdfFileSignature`](../pdffilesignature) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Bir belgenin sertifikalı olup olmadığını belirleyen bayrağı alır. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | LTV etkin bayrağını alır. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | İmza için grafik bir görünüm ayarlar veya alır. Özellik değeri, resim dosyası adını temsil eder. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | İmza için grafik bir görünüm ayarlar veya alır. Özellik değeri, görüntü akışını temsil eder. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Düzenleme için bir Pdf akışını bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Düzenleme için bir Pdf dosyası bağlar. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Mevcut imza alanına yerleştirilmiş MDP imzalı belgeyi onaylayın. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten imza alanı var, yeri belirtmemelisiniz. imzayı damgala, karşılık gelen sayfa ve dikdörtgen, imza adıyla bulunan imza alanından alınır (bkz. sigName parametresi). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Belgeyi MDP imzasıyla onaylayın. İmza nedeni, iletişim ve konum gibi veriler Signature nesnesinin karşılık gelen özellikleri tarafından sağlanmalıdır sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Cepheyi kapatır. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | PDF'nin dijital imzası olup olmadığını kontrol eder. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | PDF'nin kullanım haklarına sahip olup olmadığını kontrol eder. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | İmzanın tüm belgeyi kapsayıp kapsamadığını kontrol eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | İmzanın tek X.509 sertifikasını akış olarak çıkarır. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | İmzanın görüntüsünü çıkarır. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | MDP imza türüne göre onaylı belgenin erişim izinleri değerini döndürür. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Tüm boş imza alanlarının adlarını alır. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Bir imzanın iletişim bilgilerini alır. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | İmzanın tarih saatini alır. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Bir imzanın konumunu alır. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | İmzanın nedenini alır. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Bir imzanın revizyonunu alır. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | PDF belgesini imzalayan kişi veya kuruluşun adını alır. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Boş olmayan tüm imzaların adlarını alır. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Toplam revizyonu alır. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | İmzanın adına göre imzayı kaldırın. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | İmzanın adına göre imzayı kaldırır. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Kullanım hakları girişini kaldırır. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Sonuç PDF'sini akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Sonuç PDF'sini dosyaya kaydeder. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | İmzalama rutini için sertifika dosyası ve parola ayarlayın. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Halihazırda sunulan imza alanına yerleştirilen belgeyi verilen tip imza ile imzalayın. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten imza alanı var, yeri belirtmemelisiniz. imzayı damgalamak için, imza adıyla bulunan imza alanından ilgili sayfa ve dikdörtgen alınır (bkz. SigName parametresi). İmza nedeni, iletişim ve konum gibi veriler Signature nesnesinin karşılık gelen özellikleri tarafından sağlanmalıdır sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Belgeyi verilen tür imzasıyla imzalayın. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Halihazırda sunulan imza alanına yerleştirilen belgeyi verilen tip imza ile imzalayın. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten imza alanı var, yeri belirtmemelisiniz. imzayı damgalamak için, imza adıyla bulunan imza alanından ilgili sayfa ve dikdörtgen alınır (bkz. SigName parametresi). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | PDF belgesine bir imza atın. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Belgeyi verilen tür imzasıyla imzalayın. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Belgeyi, zaten sunulan imza alanına yerleştirilmiş olan imza türüyle imzalayın. İmzalamadan önce pdf belgesinin imza alanı olmalıdır, ilgili sayfa ve dikdörtgen, imza adıyla bulunan imza alanından alınır (bkz. SigName parametresi) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Bir imzanın geçerliliğini kontrol eder. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Bir imzanın geçerliliğini kontrol eder. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
