---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Collection sınıfı. Collection12.3.5 Koleksiyonları için sınıfı temsil eder.
type: docs
weight: 3020
url: /tr/net/aspose.pdf/collection/
---
## Koleksiyon sınıfı

Collection(12.3.5 Koleksiyonları) için sınıfı temsil eder.

```csharp
public class Collection : EmbeddedFileCollection
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Collection](collection/)() | Yeni bir Koleksiyon nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Koleksiyondaki gömülü dosya sayısını alır. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Varsayılan gömülü dosya adı. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Bu koleksiyona erişimin senkronize olup olmadığını (iş parçacığı güvenli) belirten bir değer alır. |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Gömülü dosyayı indeksine göre alır. (2 indeksleyici) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Dosya ekleme anahtarlarının listesini döndürür. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Bir belge koleksiyonunun "Şemasını" alır. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Bu koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Gömülü dosya spesifikasyonunu koleksiyona ekler. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Belirtilen anahtar ile gömülü dosyalara dosya ekler. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | FileSpecification nesnesinin dizisini koleksiyona kopyalar. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Belgeden tüm gömülü dosyaları kaldırır. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Adına göre gömülü dosyayı siler. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Koleksiyondaki anahtarına göre dosyayı siler. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Adına göre gömülü dosyayı döndürür. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Koleksiyon enumeratörünü döndürür. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Spesifikasyona göre sıralanmış dosyalar koleksiyonunu alır. |

### Ayrıca Bakınız

* sınıf [EmbeddedFileCollection](../embeddedfilecollection/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)