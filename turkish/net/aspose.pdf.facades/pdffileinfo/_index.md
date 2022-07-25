---
title: PdfFileInfo
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder.
type: docs
weight: 2530
url: /tr/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | Yeniyi başlatır[`PdfFileInfo`](../pdffileinfo) temelinde nesne*document* . |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | PDF belgesinin Yazar bilgilerini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | PDF belgesinin CreationDate bilgilerini alır veya ayarlar. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | PDF belgesinin Oluşturucu bilgilerini alır veya ayarlar. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | Geçerli girdi dosyası, içinde PDF dosyalarının koleksiyonunu içeren bir 'Portföy' dosyasıysa true değerini döndürür. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | İzinleri değiştirmek veya güvenlik özelliğini belgelemek için parola gerekiyorsa doğru döndürür. Bu özelliğin yalnızca şurada geçerli parola sağlanmışsa okunabileceğine dikkat edin.[`PdfFileInfo`](../pdffileinfo) yapıcı. PasswordType'ın Erişilememesi durumunda (geçersiz parola sağlandığı anlamına gelir) bu özelliğin okunması ile başarısız olur[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception) . |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | Parola korumalı pdf belgesini açmak için parola gerekiyorsa doğru döndürür. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | PDF belgesinin özelleştirilmiş bilgilerini alır veya ayarlar. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | PDF belgesinin şifrelenip şifrelenmediğini kontrol eder. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | Kaynak girişinin geçerli bir PDF dosyası olup olmadığını kontrol eder. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | PDF belgesinin Anahtar Sözcük bilgilerini alır veya ayarlar. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | PDF belgesinin ModDate tarih bilgilerini alır veya ayarlar. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | Belge sayfalarının sayısını alır. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | PdfFileInfo örneği oluşturmak için geçirilen parola türünü döndürür. içindeki olası değerleri görün[`PasswordType`](./passwordtype) . PDF belgesinin hem kullanıcı (veya açık) şifresi hem de sahip (veya izinler, düzenleme) şifresi kullanılarak açılabileceğine dikkat edin. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | PDF belgesinin Üretici bilgilerini alır. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | PDF belgesinin Konu bilgilerini alır veya ayarlar. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | PDF belgesinin Başlık bilgilerini alır veya ayarlar. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | kullanarak katı doğrulama kuralları kullanır[`IsPdfFile`](./ispdffile) özellik. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | PDF belgesinin tüm meta bilgilerini temizler. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | Örneği sıfırlar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | PDF belgesi ayrıcalık ayarlarını alır. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | Özellik adıyla PDF belgesinin özelleştirilmiş bilgilerini alır. Adla eşleşen bir özellik yoksa, boş bir dize döndürür. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | Belirtilen sayfanın yüksekliğini alır. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | Belirtilen sayfanın dönüşünü alır. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | Belirtilen sayfanın genişliğini alır. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | Belirtilen sayfa görüntüleme alanının yatay uzaklığını alır. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | Belirtilen sayfa görüntüleme alanının dikey uzaklığını alır. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | PDF belgesinin sürüm bilgisini alır. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | PDF belgesini belirtilen dosyaya kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | Güncellenen PDF belgesini belirtilen dosyaya kaydedin. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | Dosya bilgilerini ayarlayarak açıkça belirtilen özellikleri değiştirir, diğer özellikler kalır. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | PDF belgesinin özelleştirilmiş bilgilerini ayarlar. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
