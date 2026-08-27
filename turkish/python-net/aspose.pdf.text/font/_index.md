---
title: "Font"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Yazı tipi nesnesini temsil eder."
type: docs
weight: 100
url: /tr/python-net/aspose.pdf.text/font/
---

## Font class

Yazı tipi nesnesini temsil eder.

Font türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| font_name | Bir [Font](/pdf/python-net/aspose.pdf.text/font/) nesnesinin yazı tipi adını alır. |
| decoded_font_name | Bazen PDF yazı tipleri (genellikle Çince/Japonca/Korece yazı tipleri) belirli bir yazı tipi adına sahip olabilir.<br/>            Bu ad, PDF yazı tipi özelliği "BaseFont" değeridir ve bazen bu özellik<br/>            onaltılık biçimde temsil edilebilir. Bu adı doğrudan okursanız okunamaz bir biçimde olabilir. Okunabilir bir biçim elde etmek için yazı tipinin adını<br/>            o yazı tipine özgü kurallara göre çözmek gerekir. <br/>            Bu özellik, çözümlenmiş yazı tipi adını döndürür; bu nedenle okunamaz bir [font_name](/pdf/python-net/aspose.pdf.text/font/) ile karşılaştığınızda kullanın.<br/>            Eğer [font_name](/pdf/python-net/aspose.pdf.text/font/) özelliği okunabilir bir biçimdeyse bu özellik aynı olacaktır<br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/) ile, bu yüzden herhangi bir durumda okunabilir bir biçimde yazı tipi adı almanız gerektiğinde bu özelliği kullanabilirsiniz. |
| base_font | PDF yazı tipi nesnesinin BaseFont değerini alır. Ayrıca yazı tipinin PostScript adı olarak da bilinir. |
| is_embedded | Yazı tipinin gömülü olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            IFont tabanlı yazı tipleri otomatik olarak alt küme oluşturulur ve gömülür. |
| is_subset | Yazı tipinin bir alt küme olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>             IFont tabanlı yazı tipleri otomatik olarak alt küme oluşturulur ve gömülür. |
| is_accessible | Yazı tipinin sistemde mevcut (kurulu) olup olmadığını gösterir. |
| font_options | Yazı tipi davranışını ayarlamak için faydalı özellikler |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| get_last_font_embedding_error() | Bu yöntemin amacı - yazı tipini gömmeye çalışırken bir hata oluşursa hatanın açıklamasını döndürmektir.<br/>            Hata durumu yoksa boş bir dize döndürür. |
| save(stream) | Yazı tipini akışa kaydeder.<br/>            Yazı tipinin yalnızca orijinal belgenin dönüştürülmüş bir kopyasında kullanılmak üzere ara TTF formatında kaydedildiğini unutmayın.<br/>            Yazı tipi dosyası, orijinal belge bağlamı dışına kullanılmak üzere tasarlanmamıştır. |
| measure_string(str, font_size) | Dizgiyi ölçer. |

### Ayrıca Bakınız

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

