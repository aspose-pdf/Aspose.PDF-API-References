---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageListQueryParameters sınıfı. Thread mesajlarını listelemek için sorgu parametreleri nesnesi
type: docs
weight: 1130
url: /tr/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters sınıfı

Thread mesajlarını listelemek için sorgu parametreleri nesnesi.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Sayfalamada kullanılmak üzere bir imleç alır veya ayarlar. after, listedeki yerinizi tanımlayan bir nesne kimliğidir. Örneğin, bir liste isteği yapıp 100 nesne alırsanız ve bunlar obj_foo ile bitiyorsa, sonraki çağrınız after=obj_foo içerebilir, böylece listenin bir sonraki sayfasını alabilirsiniz. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Sayfalamada kullanılmak üzere bir imleç alır veya ayarlar. before, listedeki yerinizi tanımlayan bir nesne kimliğidir. Örneğin, bir liste isteği yapıp 100 nesne alırsanız ve bunlar obj_foo ile bitiyorsa, sonraki çağrınız before=obj_foo içerebilir, böylece listenin bir önceki sayfasını alabilirsiniz. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Döndürülecek nesne sayısı için bir sınır alır veya ayarlar. Limit 1 ile 100 arasında olabilir ve varsayılan 20'dir. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Nesnelerin created_at zaman damgasına göre sıralama düzenini alır veya ayarlar. artan sıralama için asc ve azalan sıralama için desc. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Mesajları üreten çalışma kimliğine göre filtreler. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Thread mesajlarını listelemek için sorgu parametrelerini alır. |

### Ayrıca Bakınız

* sınıf [BaseListQueryParameters](../baselistqueryparameters/)
* arayüz [IQueryParameters](../iqueryparameters/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)