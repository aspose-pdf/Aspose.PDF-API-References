---
title: PKCS7
second_title: Aspose.PDF for .NET API Referansı
description: Internet RFC 2315 PKCS 7deki PKCS7 belirtimine uyan PKCS7 nesnesini temsil eder Şifreli İleti Sözdizimi Sürüm 1.5. Belgenin bayt aralığının SHA1 özeti PKCS7 SignedData alanında kapsüllenir .
type: docs
weight: 3130
url: /tr/net/aspose.pdf.forms/pkcs7/
---
## PKCS7 class

Internet RFC 2315, PKCS #7'deki PKCS#7 belirtimine uyan PKCS#7 nesnesini temsil eder: Şifreli İleti Sözdizimi, Sürüm 1.5. Belgenin bayt aralığının SHA1 özeti, PKCS#7 SignedData alanında kapsüllenir .

```csharp
public sealed class PKCS7 : Signature
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PKCS7](pkcs7#constructor)() | Yeni örneğini başlatır[`PKCS7`](../pkcs7) sınıf. |
| [PKCS7](pkcs7#constructor_1)(Stream, string) | Yeni örneğini başlatır[`PKCS7`](../pkcs7) sınıf. |
| [PKCS7](pkcs7#constructor_2)(string, string) | Yeni örneğini başlatır[`PKCS7`](../pkcs7) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority) { get; set; } | Belgeyi imzalayan kişi veya yetkilinin adı. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange) { get; } | Özet hesaplaması için tam bayt aralığını tanımlaması gereken bir tam sayı çiftleri dizisi (başlangıç bayt ofseti, bayt cinsinden uzunluk) . |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo) { get; set; } | Bir alıcının imzayı doğrulamak için imzalayanla iletişim kurmasını sağlamak için imzalayan tarafından sağlanan bilgiler, örneğin bir telefon numarası. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance) { get; set; } | Özel görünümü alır/ayarlar. |
| [Date](../../aspose.pdf.forms/signature/date) { get; set; } | İmzalama zamanı. |
| [Location](../../aspose.pdf.forms/signature/location) { get; set; } | İmzalamanın CPU ana bilgisayar adı veya fiziksel konumu. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings) { get; set; } | ocsp ayarlarını alır/ayarlar. |
| [Reason](../../aspose.pdf.forms/signature/reason) { get; set; } | İmzalamanın nedeni, örneğin (Kabul ediyorumРІР‚В¦). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties) { get; set; } | İmza özelliklerini göstermeye/gizlemeye zorla. ShowProperties'in doğru olması durumunda, imza alanının önceden tanımlanmış bir görünüm biçimi vardır (temsil edilecek dizeler): --------------------- ---------------------- {sertifika konusu} tarafından dijital olarak imzalandı Tarih: {signature.Date} Neden: {signature.Reason} Konum: { imza.Konum} ------------------------------------------- burada {X}, X değeri için yer tutucudur. Ayrıca imzanın resmi olabilir, bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'dur. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings) { get; set; } | Zaman damgası ayarlarını alır/ayarlar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv) { get; set; } | ltv doğrulama bayrağını alır/ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Verify](../../aspose.pdf.forms/signature/verify)() | Bu imzayla ilgili belgeyi doğrulayın ve belge geçerliyse veya yanlışsa true değerini döndürün. |

### Ayrıca bakınız

* class [Signature](../signature)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->