---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions sınıfı. Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği OptimizeResources yönteminin parametresi olarak kullanılabilir.
type: docs
weight: 7980
url: /tr/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions sınıfı

Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği OptimizeResources() yönteminin parametresi olarak kullanılabilir.

```csharp
public class OptimizationOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Eğer true ise, belge eşit sayfalar için optimize edildiğinde sayfa içerikleri yeniden kullanılacaktır. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Bu bayrak `true` olarak ayarlandığında, Pdf nesneleri Objest Akışlarına paketlenecek ve pdf dosya boyutunu azaltmak için sıkıştırılacaktır. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Belgedeki görüntülerin sıkıştırılıp sıkıştırılmayacağını ve sıkıştırma parametrelerini tanımlayan seçenekler seti. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Kullanılacak görüntü kodlayıcısı. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Bu bayrak true olarak ayarlandığında, Kaynak akışları analiz edilecektir. Eğer kopya akışlar bulunursa (yani akış içerikleri eşitse), bu akışlar bir nesne olarak saklanacaktır. Bu, bazı durumlarda belge boyutunu azaltmaya olanak tanır (örneğin, aynı belge birden fazla kez birleştirildiğinde). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Tarama seviyesi. Daha derin taramalar (daha yüksek değer) daha uzun sürer ancak daha küçük sonuç dosyaları üretebilir. Varsayılan değer: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Görüntülerin maksimum çözünürlüğünü belirtir. Eğer görüntü daha yüksek bir çözünürlüğe sahipse, ölçeklendirilecektir. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Özel bilgileri kaldırır (sayfa parça bilgisi). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Bu bayrak true olarak ayarlandığında, tüm belge nesneleri kontrol edilecek ve kullanılmayan nesneler (yani herhangi bir referansı olmayan nesneler) belgelerden kaldırılacaktır. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Bu bayrak true olarak ayarlandığında, her kaynak kullanım açısından kontrol edilecektir. Eğer kaynak hiç kullanılmadıysa, o zaman kaynak kaldırılacaktır. Bu, örneğin sayfalar belgeden çıkarıldığında belge boyutunu azaltabilir. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Yazı tipleri, true olarak ayarlandığında alt kümelere dönüştürülecektir. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Yazı tipleri, true olarak ayarlandığında gömülü olmayacaktır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Tüm seçeneklerin etkin olduğu bir optimizasyon stratejisi oluşturur. Lütfen, yalnızca belgenin herhangi bir işlevselliğini değiştirmeyen etkinleştirilen seçeneklerin olduğunu unutmayın. Yani, görüntü sıkıştırma ve yazı tiplerinin gömülmesi etkinleştirilmeyecek (ve manuel olarak gömülebilir). |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)