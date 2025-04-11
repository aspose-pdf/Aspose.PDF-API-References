---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ExternalSignature sınıfı. X509Certificate2 kullanarak ayrık bir PKCS7 imzası oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kart token'larını destekler.
type: docs
weight: 5040
url: /tr/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature sınıfı

X509Certificate2 kullanarak ayrık bir PKCS#7 imzası oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler.

```csharp
public class ExternalSignature : Signature
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | X509Certificate2 kullanarak ayrık bir PKCS#7 `(detached)` imzası oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | X509Certificate2'yi base64 dizesi olarak kullanarak bir PKCS#7 imzası oluşturur. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | X509Certificate2'yi base64 dizesi olarak kullanarak bir PKCS#7 `(detached)` imzası oluşturur. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | X509Certificate2 kullanarak ayrık bir PKCS#7 imzası oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | X509Certificate2 kullanarak ayrık bir PKCS#7 `(detached)` imzası oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Belgeyi imzalayan kişi veya otoritenin adı. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Bir imzanın uzunluğunu tahmin etmekten kaçınıp kaçınmayacağını belirten bir seçeneği alır ve ayarlar. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Özüt hesaplaması için tam byte aralığını tanımlayan tam sayı çiftleri (başlangıç byte ofseti, byte cinsinden uzunluk) dizisi. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | İmzalayan tarafından sağlanan, alıcının imzalayanla iletişim kurarak imzayı doğrulamasını sağlamak için gereken bilgi, örneğin bir telefon numarası. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Özel görünümü alır/ayarlar. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Belge hash'ini özel olarak imzalamak için delege. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | İmza zamanı. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | İmza verisi için byte cinsinden varsayılan uzunluğu alır veya ayarlar. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | İmzanın yapıldığı CPU ana bilgisayar adı veya fiziksel konumu. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ocsp ayarlarını alır/ayarlar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | İmzanın nedeni, örneğin (Kabul ediyorum, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlanmış bir görünüm formatına sahiptir (temsil etmek için dizeler): ------------------------------------------- Dijital olarak imzalanmıştır {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X} X değeri için yer tutucudur. Ayrıca imza bir resme sahip olabilir, bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'dur. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Zaman damgası ayarlarını alır/ayarlar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ltv doğrulama bayrağını alır/ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | İmzada kullanılan imza algoritması hakkında bilgi alır. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | Özel anahtara sahip sertifika. |

### Ayrıca Bakınız

* sınıf [Signature](../signature/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)