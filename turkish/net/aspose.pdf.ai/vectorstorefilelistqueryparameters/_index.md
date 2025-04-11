---
title: Class VectorStoreFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileListQueryParameters sınıfı. Vektör depolama dosyalarını listelemek için sorgu parametreleri nesnesi
type: docs
weight: 1330
url: /tr/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters sınıfı

Vektör depolama dosyalarını listelemek için sorgu parametreleri nesnesi.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Sayfalamada kullanılmak üzere bir imleç alır veya ayarlar. after, listedeki yerinizi tanımlayan bir nesne kimliğidir. Örneğin, bir liste isteği yapıp 100 nesne alırsanız ve bu nesneler obj_foo ile bitiyorsa, sonraki çağrınızda after=obj_foo ekleyerek listenin bir sonraki sayfasını alabilirsiniz. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Sayfalamada kullanılmak üzere bir imleç alır veya ayarlar. before, listedeki yerinizi tanımlayan bir nesne kimliğidir. Örneğin, bir liste isteği yapıp 100 nesne alırsanız ve bu nesneler obj_foo ile bitiyorsa, sonraki çağrınızda before=obj_foo ekleyerek listenin bir önceki sayfasını alabilirsiniz. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | Dosya durumu ile bir filtre alır veya ayarlar. in_progress, completed, failed, cancelled seçeneklerinden biri. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Döndürülecek nesne sayısı için bir sınır alır veya ayarlar. Limit 1 ile 100 arasında olabilir ve varsayılan 20'dir. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Nesnelerin created_at zaman damgasına göre sıralama düzenini alır veya ayarlar. artan sıralama için asc ve azalan sıralama için desc. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | Vektör depolama dosyalarını listelemek için sorgu parametrelerini alır. |

### Ayrıca Bakınız

* sınıf [BaseListQueryParameters](../baselistqueryparameters/)
* arayüz [IQueryParameters](../iqueryparameters/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)