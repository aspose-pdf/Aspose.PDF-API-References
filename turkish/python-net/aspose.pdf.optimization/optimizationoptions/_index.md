---
title: "OptimizationOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Belge optimizasyon algoritmasını tanımlayan sınıf.<br/>            Bu sınıfın örneği, OptimizeResources() metodunun parametresi olarak kullanılabilir."
type: docs
weight: 20
url: /tr/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Belge optimizasyon algoritmasını tanımlayan sınıf.<br/>            Bu sınıfın örneği, OptimizeResources() metodunun parametresi olarak kullanılabilir.

OptimizationOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| OptimizationOptions() | OptimizationOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| link_duplcate_streams | Bu bayrak true olarak ayarlanırsa, Kaynak akışları analiz edilecektir. Eğer yinelenen akışlar bulunursa (yani akış içeriği eşitse), bu akışlar tek bir nesne olarak saklanacaktır. <br/>            Bu, bazı durumlarda belge boyutunun azalmasını sağlar (örneğin, aynı belgenin birden çok kez birleştirildiği durumlarda). |
| allow_reuse_page_content | True ise, belge eşit sayfalar için optimize edildiğinde sayfa içerikleri yeniden kullanılacaktır. |
| remove_unused_streams | Bu bayrak true olarak ayarlanırsa, her kaynak kullanımına göre kontrol edilir. Kaynak hiç kullanılmazsa, kaynak kaldırılır.<br/>            Bu, örneğin sayfalar belgeden çıkarıldığında belge boyutunun azalmasına neden olabilir. |
| remove_unused_objects | Bu bayrak true olarak ayarlanırsa, tüm belge nesneleri kontrol edilir ve kullanılmayan nesneler (yani hiçbir referansa sahip olmayan nesneler) belgeden kaldırılır. |
| image_compression_options | Belge içindeki görüntülerin sıkıştırılıp sıkıştırılmayacağını ve sıkıştırma parametrelerini tanımlayan seçenekler kümesi. |
| compress_images | Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılır. Sıkıştırma seviyesi ImageQuality özelliğiyle belirtilir. |
| resize_images | Bu bayrak true olarak ayarlanır ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılır. |
| image_quality | CompressIamges bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir. |
| max_resoultion | Görüntülerin maksimum çözünürlüğünü belirtir. Görüntünün çözünürlüğü daha yüksekse ölçeklendirilir. |
| unembed_fonts | True olarak ayarlanırsa yazı tipleri gömülmez. |
| subset_fonts | True olarak ayarlanırsa yazı tipleri alt kümelere dönüştürülür. |
| remove_private_info | Özel bilgileri (sayfa parça bilgisi) kaldır. |
| image_encoding | Kullanılacak görüntü kodlaması. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| all() | Tüm seçenekler etkinleştirilmiş bir optimizasyon stratejisi oluşturur.<br/>            Lütfen yalnızca belgenin işlevselliğini değiştirmeyen seçeneklerin etkinleştirildiğini unutmayın.<br/>            Örneğin, görüntü sıkıştırma ve yazı tiplerinin gömülmemesi etkinleştirilmeyecek (ve manuel olarak etkinleştirilebilir). |

### Ayrıca Bakınız

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

