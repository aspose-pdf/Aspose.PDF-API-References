---
title: "İmza"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. <br/>            İmzalar, imza nesnelerinin değerlerine sahip alanlardır; sonuncusu belge geçerliliğini doğrulamak için kullanılan verileri içerir.<br/>            "
type: docs
weight: 250
url: /tr/python-net/aspose.pdf.forms/signature/
---

## Signature class

PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. <br/>            İmzalar, imza nesnelerinin değerlerine sahip alanlardır; sonuncusu belge geçerliliğini doğrulamak için kullanılan verileri içerir.<br/>            

İmza türü aşağıdaki üyeleri sunar:
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

