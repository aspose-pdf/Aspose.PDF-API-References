---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileInfo sınıfı. PDF belgesinin meta bilgilerine erişim sağlayan bir sınıfı temsil eder.
type: docs
weight: 4520
url: /tr/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo Sınıfı

PDF belgesinin meta bilgilerine erişim sağlayan bir sınıfı temsil eder.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Varsayılan değerlerle Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | *belge* temelinde yeni bir `PdfFileInfo` nesnesi başlatır. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Aspose.Pdf.Facades.PdfFileInfo sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | PDF belgesinin Yazar bilgilerini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | PDF belgesinin Oluşturulma Tarihi bilgilerini alır veya ayarlar. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | PDF belgesinin Oluşturucu bilgilerini alır veya ayarlar. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Mevcut giriş dosyasının içinde PDF dosyaları koleksiyonu içeren bir 'Portföy' dosyası olup olmadığını kontrol eder. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | İzinleri veya belge güvenlik özelliğini değiştirmek için şifre gerektiğinde true döner. Bu özelliğin yalnızca geçerli bir şifre `PdfFileInfo` yapıcısında sağlandığında okunabileceğine dikkat edin. PasswordType erişilemez olduğunda (geçersiz şifre sağlandığında) bu özelliği okumak [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/) ile başarısız olacaktır. |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Şifre korumalı PDF belgesini açmak için şifre gerektiğinde true döner. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | PDF belgesinin özelleştirilmiş bilgilerini alır veya ayarlar. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | PDF belgesinin şifreli olup olmadığını kontrol eder. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Kaynak girişin geçerli bir PDF dosyası olup olmadığını kontrol eder. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | PDF belgesinin Anahtar Kelimeler bilgilerini alır veya ayarlar. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | PDF belgesinin Değiştirilme Tarihi bilgilerini alır veya ayarlar. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Belge sayfa sayısını alır. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | PdfFileInfo örneğini oluşturmak için geçirilen şifre türünü döner. Olası değerleri [`PasswordType`](./passwordtype/) içinde görebilirsiniz. PDF belgesinin hem kullanıcı (veya açma) şifresi hem de sahip (veya izinler, düzenleme) şifresi kullanılarak açılabileceğine dikkat edin. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | PDF belgesinin Üretici bilgilerini alır. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | PDF belgesinin Konu bilgilerini alır veya ayarlar. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | PDF belgesinin Başlık bilgilerini alır veya ayarlar. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | [`IsPdfFile`](./ispdffile/) özelliğini kullanarak katı doğrulama kurallarını kullanır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | PDF belgesinin tüm meta bilgilerini temizler. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Örneği deinitializes eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | PDF belgesi ayrıcalık ayarlarını alır. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Özellik adı ile PDF belgesinin özelleştirilmiş bilgilerini alır. Eğer isimle eşleşen bir özellik yoksa boş bir dize döner. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Belirtilen sayfanın yüksekliğini alır. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Belirtilen sayfanın dönüşünü alır. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Belirtilen sayfanın genişliğini alır. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Belirtilen sayfanın görüntüleme alanının yatay kaymasını alır. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Belirtilen sayfanın görüntüleme alanının dikey kaymasını alır. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | PDF belgesinin sürüm bilgilerini alır. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | PDF belgesini belirtilen dosyaya kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Güncellenmiş PDF belgesini belirtilen dosyaya kaydeder. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Dosya bilgilerini ayarlayarak açıkça belirtilen özellikleri değiştirir, diğer özellikler kalır. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | PDF belgesinin özelleştirilmiş bilgilerini ayarlar. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)