---
title: "Heading"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Başlığı temsil eder."
type: docs
weight: 460
url: /tr/python-net/aspose.pdf/heading/
---

## Heading class

Başlığı temsil eder.

Heading türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Heading(level) | Heading sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| vertical_alignment | Metin parçacığının dikey hizalamasını alır veya ayarlar. |
| horizontal_alignment | Metin parçacığının yatay hizalamasını alır veya ayarlar. |
| kenar boşluğu | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| is_first_paragraph_in_column | Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_kept_with_next | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_in_new_page | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_in_line_paragraph | Paragrafın satır içi olup olmadığını alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| köprü | Parçacığın bağlantısını ayarlar |
| z_index | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex <br/>            bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif <br/>            ZIndex bir grafik, sayfadaki metnin arkasına yerleştirilir. |
| replace_options | Metin değiştirme seçeneklerini alır. Seçenekler, parçacık metni daha kısa/uzun olarak değiştirildiğinde davranışı tanımlar. |
| text | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) nesnesinin temsil ettiği dize metin nesnesini alır veya ayarlar. |
| text_state | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar. |
| segments | Mevcut [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) için metin segmentlerini alır. |
| position | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) nesnesiyle temsil edilen metnin konumunu alır veya ayarlar. |
| baseline_position | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) nesnesiyle temsil edilen metnin konumunu alır.<br/>            Position yapısının YIndent özelliği, metin parçacığının temel çizgi koordinatını temsil eder. |
| rectangle | TextFragment'in dikdörtgenini alır |
| sayfa | MetinParçasını içeren sayfayı alır |
| form | MetinParçasını içeren form nesnesini alır |
| wrap_lines_count | Bu paragraf için wrap lines count değerini alır veya ayarlar (yalnızca pdf oluşturma için) |
| end_note | Paragraf son notunu alır veya ayarlar (yalnızca pdf oluşturma için) |
| foot_note | Paragraf dipnotunu alır veya ayarlar (yalnızca pdf oluşturma için) |
| toc_page | Bu başlığı içeren sayfayı alır. |
| top | Bu başlıkların üst Y değerini alır. |
| start_number | Başlığın başlangıç numarasını alır. |
| is_auto_sequence | Başlığın otomatik olarak numaralandırılması gerektiğini alır. |
| is_in_list | Başlığın içindekiler listesinde olması gerektiğini alır. |
| destination_page | Hedef sayfayı alır. |
| seviye | Seviyeyi alır. |
| style | Stili alır veya ayarlar. |
| user_label | Kullanıcı etiketini alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Başlığı kopyalar. |
| isolate_text_segments(start_index, length) | Belirtilen [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) metninin belirli bir kısmını temsil eden [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(leri) alır. |
| clone_with_segments() | Başlığı tüm bölümleriyle kopyalar. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

