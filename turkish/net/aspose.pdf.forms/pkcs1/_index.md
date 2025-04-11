---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS1 sınıfı. PKCS1 standardına göre imza nesnesini temsil eder. İmzalama için RSA şifreleme algoritması ve SHA1 özet yöntemi kullanılır.
type: docs
weight: 5170
url: /tr/net/aspose.pdf.forms/pkcs1/
---
## PKCS1 sınıfı

PKCS#1 standardına göre imza nesnesini temsil eder. İmzalama için RSA şifreleme algoritması ve SHA-1 özet yöntemi kullanılır.

```csharp
public sealed class PKCS1 : Signature
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | `PKCS1` sınıfının yeni bir örneğini başlatır. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | `PKCS1` sınıfının yeni bir örneğini başlatır. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | `PKCS1` sınıfının yeni bir örneğini başlatır. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | `PKCS1` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Belgeyi imzalayan kişi veya otoritenin adı. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | İmzanın uzunluğunu tahmin etmekten kaçınıp kaçınmayacağını belirten bir seçeneği alır ve ayarlar. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Özet hesaplaması için tam byte aralığını tanımlayan tam sayı çiftleri (başlangıç byte ofseti, byte cinsinden uzunluk) dizisi. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | İmzalayan tarafından sağlanan, alıcının imzayı doğrulamak için imzalayanla iletişim kurmasını sağlayan bilgi, örneğin bir telefon numarası. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Özel görünümü alır/ayarlar. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Belge hash'ini özel olarak imzalamak için delege. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | İmzalama zamanı. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | İmza verileri için byte cinsinden varsayılan uzunluğu alır veya ayarlar. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | İmzalama işleminin yapıldığı CPU ana bilgisayar adı veya fiziksel konumu. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ocsp ayarlarını alır/ayarlar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | İmzalama nedeni, örneğin (Kabul ediyorum, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlanmış bir görünüm formatına sahiptir (temsil etmek için dizeler): ------------------------------------------- Dijital olarak imzalanmıştır {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X} X değeri için yer tutucudur. Ayrıca imza bir resme sahip olabilir, bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak doğrudur. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Zaman damgası ayarlarını alır/ayarlar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ltv doğrulama bayrağını alır/ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | İmzada kullanılan imza algoritması hakkında bilgi alır. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |

### Ayrıca Bakınız

* sınıf [Signature](../signature/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)