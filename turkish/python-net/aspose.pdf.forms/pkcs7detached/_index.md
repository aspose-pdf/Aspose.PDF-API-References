---
title: "PKCS7Detached"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Internet RFC 2315'teki PKCS#7 spesifikasyonuna uyan PKCS#7 nesnesini temsil eder, <br/>            PKCS #7: Kriptografik Mesaj Söz Dizimi, Versiyon 1.5.<br/>            Belgenin bayt aralığının orijinal imzalı mesaj özeti, normal PKCS#7 SignedData alanı olarak eklenir. <br/>            PKCS#7 SignedData alanına hiçbir veri kapsüllenmez."
type: docs
weight: 200
url: /tr/python-net/aspose.pdf.forms/pkcs7detached/
---

## PKCS7Detached class

Internet RFC 2315'teki PKCS#7 spesifikasyonuna uyan PKCS#7 nesnesini temsil eder, <br/>            PKCS #7: Kriptografik Mesaj Söz Dizimi, Versiyon 1.5.<br/>            Belgenin bayt aralığının orijinal imzalı mesaj özeti, normal PKCS#7 SignedData alanı olarak eklenir. <br/>            PKCS#7 SignedData alanına hiçbir veri kapsüllenmez.

PKCS7Detached türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PKCS7Detached(image) | PKCS7Detached sınıfının yeni bir örneğini başlatır |
| PKCS7Detached() | [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) sınıfının yeni bir örneğini başlatır. |
| PKCS7Detached(pfx, password) | PKCS7Detached sınıfının yeni bir örneğini başlatır |
| PKCS7Detached(pfx, password) | PKCS7Detached sınıfının yeni bir örneğini başlatır |
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

