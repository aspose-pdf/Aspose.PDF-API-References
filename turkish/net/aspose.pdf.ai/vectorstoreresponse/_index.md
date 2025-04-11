---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse sınıfı. Vektör mağaza nesnesi
type: docs
weight: 1390
url: /tr/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse sınıfı

Vektör mağaza nesnesi.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Vektör mağazasının oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Bir vektör mağazası için sona erme politikasını alır veya ayarlar. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Vektör mağazasının ne zaman sona ereceği için Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | İşlenen dosya sayısını alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek kimlik numarasını alır veya ayarlar. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Vektör mağazasının en son ne zaman aktif olduğunu gösteren Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi depolamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Vektör mağazasının adını alır veya ayarlar. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Nesne türünü alır veya ayarlar, bu her zaman vector_store'dur. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata nedenini gösteren ifadeyi alır. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Vektör mağazasının durumunu alır veya ayarlar, bu durum ya süresi dolmuş, devam eden ya da tamamlanmış olabilir. Tamamlanmış durumu, vektör mağazasının kullanıma hazır olduğunu gösterir. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Vektör mağazasındaki dosyalar tarafından kullanılan toplam byte sayısını alır veya ayarlar. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* arayüz [IEntityId](../ientityid/)
* arayüz [IStatus](../istatus/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)