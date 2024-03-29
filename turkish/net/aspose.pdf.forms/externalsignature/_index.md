---
title: ExternalSignature
second_title: Aspose.PDF for .NET API Referansı
description: Bir X509Certificate2 kullanarak ayrılmış bir PKCS7Ayrık imza oluşturur. Dışa aktarılabilir özel anahtarlar olmadan usb akıllı kartları belirteçleri destekler.
type: docs
weight: 2990
url: /tr/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

Bir X509Certificate2 kullanarak ayrılmış bir PKCS#7Ayrık imza oluşturur. Dışa aktarılabilir özel anahtarlar olmadan usb akıllı kartları, belirteçleri destekler.

```csharp
public class ExternalSignature : Signature
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ExternalSignature](externalsignature)(X509Certificate2) | Bir X509Certificate2 kullanarak ayrılmış bir PKCS#7Ayrık imza oluşturur. Dışa aktarılabilir özel anahtarlar olmadan usb akıllı kartları, belirteçleri destekler. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority) { get; set; } | Belgeyi imzalayan kişi veya yetkilinin adı. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange) { get; } | Özet hesaplaması için tam bayt aralığını tanımlaması gereken bir tam sayı çiftleri dizisi (başlangıç bayt ofseti, bayt cinsinden uzunluk) . |
| [Certificate](../../aspose.pdf.forms/externalsignature/certificate) { get; } | Özel anahtara sahip sertifika. |
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
