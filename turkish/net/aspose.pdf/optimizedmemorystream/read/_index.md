---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: OptimizedMemoryStream metodu. Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akıştan bir dizi bayt okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.
type: docs
weight: 100
url: /tr/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read metodu

Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akıştan bir dizi bayt okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | Byte[] | Bir bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini değerlerle içerir |
| offset | Int32 | Mevcut akıştan okunan verileri depolamaya başlamak için sıfır tabanlı bayt ofseti. |
| count | Int32 | Mevcut akıştan okunacak maksimum bayt sayısı. |

### Dönüş Değeri

Tampon içine okunan toplam bayt sayısı. Bu, istenen bayt sayısından az olabilir eğer o kadar bayt mevcut değilse veya akışın sonuna ulaşıldıysa sıfır (0) olabilir.

### Ayrıca Bakınız

* sınıf [OptimizedMemoryStream](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)