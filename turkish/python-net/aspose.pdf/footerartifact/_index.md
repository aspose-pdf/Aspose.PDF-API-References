---
title: "FooterArtifact"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Altbilgi öğesini tanımlar. Bu, sayfanın altbilgisini ayarlamak için kullanılabilir."
type: docs
weight: 400
url: /tr/python-net/aspose.pdf/footerartifact/
---

## FooterArtifact class

Altbilgi öğesini tanımlar. Bu, sayfanın altbilgisini ayarlamak için kullanılabilir.

FooterArtifact türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| FooterArtifact() | Footer Artifact örneği oluşturur. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| custom_type | Artifact türünün adını alır. Artifact türü standart dışı ise kullanılabilir. |
| custom_subtype | Artifact alt türünün adını alır. Artifact alt türü standart bir alt tür değilse kullanılabilir. |
| type | Artifact türünü alır. |
| subtype | Artifact alt türünü alır. Artifact non-standart bir alt türe sahipse, alt türün adı CustomSubtype aracılığıyla okunabilir. |
| içerik | Artifact iç operatörlerinin koleksiyonunu alır. |
| form | Artifact'in XForm'unu alır (XForm kullanılıyorsa). |
| rectangle | Artifact'in dikdörtgenini alır. |
| position | Artifact konumunu alır veya ayarlar.<br/>            Bu özellik belirtilmişse, kenar boşlukları ve hizalamalar göz ardı edilir. |
| right_margin | Artifact'in sağ kenar boşluğu. <br/>            Konum açıkça (Position özelliğinde) belirtilmişse bu değer göz ardı edilir. |
| left_margin | Artifact'in sol kenar boşluğu. <br/>            Konum açıkça (Position özelliğinde) belirtilmişse bu değer göz ardı edilir. |
| top_margin | Artifact'in üst kenar boşluğu. <br/>            Konum açıkça (Position özelliğinde) belirtilmişse bu değer göz ardı edilir. |
| bottom_margin | Artifact'in alt kenar boşluğu. <br/>            Konum açıkça (Position özelliğinde) belirtilmişse bu değer göz ardı edilir. |
| artifact_horizontal_alignment | Artifact'in yatay hizalaması. <br/>            Konum açıkça (Position özelliğinde) belirtilmişse bu değer göz ardı edilir. |
| artifact_vertical_alignment | Artefaktın dikey hizalaması. <br/> Pozisyon açıkça (Position özelliğinde) belirtilmişse bu değer yok sayılır. |
| rotation | Artefaktın döndürme açısını alır veya ayarlar. |
| text | Artefaktın metnini alır. |
| image | Artefaktın görüntüsünü alır (varsa). |
| opaklık | Artefaktın opaklığını alır veya ayarlar. Olası değerler 0..1 aralığındadır. |
| satırlar | Çok satırlı metin artefaktının satırları. |
| text_state | Artefakt metni için metin durumu. |
| is_background | Doğru ise artefakt sayfa içeriklerinin arkasına yerleştirilir. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| set_image(image_stream) | Artefaktın görüntüsünü ayarlar. |
| set_image(image_name) | Artefaktın görüntüsünü ayarlar. |
| set_text(formatted_text) | Artefaktın metnini ayarlar. |
| set_text_and_state(text, text_state) | Artefaktın metnini ve metin özelliklerini ayarlar. |
| set_lines_and_state(text, text_state) | Artefaktın metnini ve metin özelliklerini ayarlar. Birden fazla satır belirtmeye olanak tanır. |
| set_pdf_page(page) | Belge sayfasına artefakt olarak yerleştirilen PDF sayfasını ayarlar. |
| get_value(name) | Artefaktın özel değerini alır. |
| set_value(name, value) | Artefaktın özel değerini ayarlar. |
| remove_value(name) | Artefaktın özel değerini kaldırır. |
| begin_updates() | Gecikmiş güncellemeleri başlat. Performansı artırmak için aynı artefakte birden fazla değişiklik yapmanız gerektiğinde bu özelliği kullanın. <br/>            Genellikle artefakt operatörleri, artefakt özelliği değiştiğinde her zaman değiştirilir. Bu, sayfa içeriklerinin değişmesine neden olur<br/>            artefakt değiştiğinde her seferinde. Bu etkiyi önlemek için tüm artefakt güncellemelerini StartUpdates/SaveUpdates çağrıları arasında yapın.<br/>            Bu, sayfa içeriklerini yalnızca bir kez değiştirmenizi sağlar. |
| save_updates() | BeginUpdates() çağrısından sonra yapılan artefakt içindeki tüm güncellemeleri kaydeder. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

