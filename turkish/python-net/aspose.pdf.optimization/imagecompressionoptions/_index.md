---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sınıf, görüntü sıkıştırması için bir dizi seçenek içerir."
type: docs
weight: 10
url: /tr/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Sınıf, görüntü sıkıştırması için bir dizi seçenek içerir.

ImageCompressionOptions türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| ImageCompressionOptions() | ImageCompressionOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| compress_images | Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılır. Sıkıştırma seviyesi ImageQuality özelliğiyle belirtilir. |
| resize_images | Bu bayrak true olarak ayarlanır ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılır. |
| image_quality | CompressIamges bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir. |
| max_resolution | Görüntülerin maksimum çözünürlüğünü belirtir. Görüntünün çözünürlüğü daha yüksekse ölçeklendirilir. |
| version | Sıkıştırma algoritması sürümü. Olası değerler: 1. standart sıkıştırma, 2. hızlı (standarttan daha hızlı olan geliştirilmiş sıkıştırma, ancak tüm görüntüler için geçerli olmayabilir), 3. karışık (standart sıkıştırma, daha hızlı algoritma ile sıkıştırılamayan görüntülere uygulanır; bu, en iyi sıkıştırmayı sağlayabilir ancak "fast" algoritmadan daha yavaştır. "Fast" sürümü, görüntü yeniden boyutlandırma için geçerli değildir (standart yöntem kullanılacaktır). Varsayılan "Standard"dır.) |
| kodlama | Görüntüleri depolamak için kullanılan kodlamayı alır veya ayarlar. |

### Ayrıca Bakınız

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

