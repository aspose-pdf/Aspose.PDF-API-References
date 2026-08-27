---
title: "FileSpecification"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Gömülü dosyayı temsil eden sınıf."
type: docs
weight: 360
url: /tr/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Gömülü dosyayı temsil eden sınıf.

FileSpecification türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| FileSpecification(file) | FileSpecification sınıfının yeni bir örneğini başlatır |
| FileSpecification(stream, name) | FileSpecification sınıfının yeni bir örneğini başlatır |
| FileSpecification(file, description) | FileSpecification sınıfının yeni bir örneğini başlatır |
| FileSpecification(stream, name, description) | FileSpecification sınıfının yeni bir örneğini başlatır |
| FileSpecification(file_name, annot) | FileSpecification sınıfının yeni bir örneğini başlatır |
| FileSpecification() | Yeni boş dosya spesifikasyonu oluştur. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| kodlama | Kodlama biçimini alır veya ayarlar.<br/>            Olası değerler: Zip - dosya ZIP ile sıkıştırılmıştır, <br/>            None - dosya sıkıştırılmamıştır. |
| include_contents | Doğru ise, dosyanın içeriği dosya spesifikasyonuna dahil edilecektir. |
| encrypted_payload | Şifrelenmiş yükü alır. |
| açıklama | Dosya tanımıyla ilişkili metni alır veya ayarlar. |
| af_relationship | İlişkili dosya ilişkisi. |
| stream_contents | Dosyanın içeriğini akış olarak alır. <br/>            İçerik belleğe yüklenmez, bu da bellek kullanımını azaltmayı sağlar.<br/>            Ancak bu akış konumlandırmayı ve Length özelliğini desteklemez. Eğer bu özelliklere ihtiyacınız varsa, lütfen bunun yerine Contents özelliğini kullanın. |
| içerik | İçerik dosyasını alır veya ayarlar. <br/>            Bu özellik, belleğe yüklenen verileri döndürür; büyük veri için bellek yetersizliği hatasına neden olabilir.<br/>            Bellek kullanımını azaltmak için lütfen StreamContents'ı kullanın. |
| params | Dosya parametrelerini alır. |
| mime_type | Gömülü dosyanın alt türünü alır. |
| name | Dosya tanımı adını alır veya ayarlar. |
| unicode_name | Dosya tanımı Unicode adını alır veya ayarlar. |
| file_system | Dosya sisteminin adını alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| get_value(key) | Uygulamaya özgü parametreyi alır. |
| set_value(key, value) | Uygulamaya özgü parametreyi ayarlar. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

