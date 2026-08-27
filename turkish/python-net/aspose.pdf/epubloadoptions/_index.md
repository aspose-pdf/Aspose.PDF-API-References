---
title: "EpubLoadOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "EPUB dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini içerir."
type: docs
weight: 310
url: /tr/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

EPUB dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini içerir.

EpubLoadOptions türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| EpubLoadOptions() | EPUB dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. <br/>            Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | EpubLoadOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Load işlemi devam eder, ancak kullanıcı Abort döndürürse Load işlemi durmalıdır. |
| load_format | Dosya formatını temsil eder ki [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) bunu tanımlar. |
| page_size | İçe aktarma için çıktı sayfa boyutunu alır veya ayarlar. |
| kenar boşluğu | Marjin bilgilerini temsil eden nesneye referansı alır. |
| margins_area_usage_mode | Marjin alanının kullanım modunu temsil eder - içe aktarılan belgenin CSS talimatlarının (varsa) marjin kullanımına ilişkin işlenmesini tanımlar. <br/> |
| page_size_adjustment_mode | DİKKAT! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici sorun nedeniyle henüz genel API'ye eklenmemiştir.<br/>              <br/>             <br/>              Dönüştürme sırasında sayfa boyutunun kullanım modunu temsil eder.<br/>             HTML, EPUB vb. formatlar genellikle akış tasarımına sahiptir, bu nedenle gerekli sayfa boyutuna sığdırmaya izin verir. Ancak bazen içerik, belirtilen yatay konumlar veya boyutlar nedeniyle gerekli sayfa boyutuna yerleştirilemez.<br/>               Bu durumda ne yapılması gerektiğini tanımlayabiliriz (örneğin içerik boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında). |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

