---
title: "İzinler"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Bu enum, bir pdf için kullanıcının izinlerini temsil eder."
type: docs
weight: 6560
url: /tr/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Bu enum, bir pdf için kullanıcının izinlerini temsil eder.

## Members
| Üye adı | Açıklama |
| :- | :- |
| PRINT_DOCUMENT | (Revision 2 güvenlik işleyicileri) Belgeyi yazdır.<br/>            (Revision 3 veya daha yüksek güvenlik işleyicileri) Belgeyi yazdır <br/>            (muhtemelen en yüksek kalite seviyesinde olmayabilir, <br/>            [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) ayarlıysa buna bağlı olarak). |
| MODIFY_CONTENT | Belgenin içeriğini, [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) ve [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/) tarafından kontrol edilen işlemler dışındaki işlemlerle değiştirin ve 11. |
| EXTRACT_CONTENT | (Revision 2 güvenlik işleyicileri) Belgeden metin ve grafikleri kopyalayın veya başka şekilde çıkarın, engelli kullanıcıların erişilebilirliğini desteklemek veya diğer amaçlar için metin ve grafikleri çıkarmayı da içerecek şekilde.<br/>            (Revision 3 veya daha yüksek güvenlik işleyicileri) Belgeden metin ve grafikleri, [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/) tarafından kontrol edilmeyen işlemlerle kopyalayın veya başka şekilde çıkarın. |
| MODIFY_TEXT_ANNOTATIONS | Metin açıklamaları ekleyin veya değiştirin, etkileşimli form alanlarını doldurun, <br/>            ve [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) ayarlıysa, etkileşimli form alanlarını (imza alanları dahil) oluşturun veya değiştirin. |
| FILL_FORM | (Revision 3 veya daha yüksek güvenlik işleyicileri) Mevcut etkileşimli form alanlarını (imza alanları dahil) doldurun, [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) temiz olsa bile. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Revision 3 veya daha yüksek güvenlik işleyicileri) Metin ve grafikleri çıkarın (engelli kullanıcıların erişilebilirliğini desteklemek veya diğer amaçlar için). |
| ASSEMBLE_DOCUMENT | (Revision 3 veya daha yüksek güvenlik işleyicileri) Belgeyi birleştirin (sayfaları ekleyin, döndürün veya silin ve yer imleri veya küçük resim görüntüleri oluşturun), [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) temiz olsa bile. |
| PRINTING_QUALITY | (Revision 3 veya daha yüksek güvenlik işleyicileri) Belgeyi, PDF içeriğinin doğru bir dijital kopyasının oluşturulabileceği bir temsile yazdırın. Bu bit temiz olduğunda (ve bit 3 ayarlıysa), <br/>            yazdırma, görünümün düşük seviyeli bir temsiliyle sınırlıdır, muhtemelen kalitesi düşmüş şekilde. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

