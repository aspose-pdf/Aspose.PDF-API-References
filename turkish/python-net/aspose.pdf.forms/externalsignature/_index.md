---
title: "ExternalSignature"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Bir X509Certificate2 kullanarak ayrık PKCS#7Detached imzası oluşturur. USB akıllı kartları, dışa aktarılabilir özel anahtarı olmayan tokenları destekler."
type: docs
weight: 80
url: /tr/python-net/aspose.pdf.forms/externalsignature/
---

## ExternalSignature class

Bir X509Certificate2 kullanarak ayrık PKCS#7Detached imzası oluşturur. USB akıllı kartları, dışa aktarılabilir özel anahtarı olmayan tokenları destekler.

ExternalSignature türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| custom_appearance | Özel görünümü alır/ayarlar. |
| authority | Belgeyi imzalayan kişi veya otoritenin adı. |
| date | İmzalama zamanı. |
| location | İmzalamanın CPU ana bilgisayar adı veya fiziksel konumu. |
| reason | İmzalamanın nedeni, örneğin (I agreeРІР‚В¦). |
| contact_info | İmzalayan tarafından alıcının imzalayan ile iletişime geçmesini sağlamak için sağlanan bilgi <br/>            imzayı doğrulamak amacıyla, ör. bir telefon numarası. |
| byte_range | Tam sayı çiftlerinden oluşan bir dizi (başlangıç bayt ofseti, bayt cinsinden uzunluk) <br/>             özet hesaplaması için kesin bayt aralığını tanımlamalıdır. |
| timestamp_settings | Zaman damgası ayarlarını alır/ayarlar. |
| ocsp_settings | OCSP ayarlarını alır/ayarlar. |
| use_ltv | LTV doğrulama bayrağını alır/ayarlar. |
| show_properties | İmza özelliklerini gösterme/gizleme zorunluluğu.<br/>            ShowProperties true olduğunda imza alanı önceden tanımlı bir görünüm formatına sahiptir (temsil eden dizeler):<br/>            -------------------------------------------<br/>            Dijital olarak imzalayan {certificate subject}<br/>            Tarih: {signature.Date}<br/>            Sebep: {signature.Reason}<br/>            Konum: {signature.Location}<br/>            -------------------------------------------<br/>            burada {X}, X değerinin yer tutucusudur. Ayrıca imza bir görüntü içerebilir; bu durumda listelenen dizeler görüntünün üzerine yerleştirilir.<br/>            ShowProperties varsayılan olarak true'tur. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| verify() | Bu imzayla ilgili belgeyi doğrular ve belge geçerli ise true, aksi takdirde false döndürür.<br/>             |

### Ayrıca Bakınız

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

