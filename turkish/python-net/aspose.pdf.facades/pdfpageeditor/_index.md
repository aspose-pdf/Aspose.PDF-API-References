---
title: "PdfPageEditor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder; sayfayı döndürme, sayfayı yakınlaştırma, konumu taşıma ve sayfa boyutunu değiştirme dahil."
type: docs
weight: 340
url: /tr/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder; sayfayı döndürme, sayfayı yakınlaştırma, konumu taşıma ve sayfa boyutunu değiştirme dahil.

PdfPageEditor türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfPageEditor() | PdfPageEditor sınıfı için yapıcı. |
| PdfPageEditor(document) | PdfPageEditor sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| transition_duration | Geçiş efektinin süresini alır veya ayarlar. |
| transition_type | Bir sunum sırasında bu sayfaya başka bir sayfadan geçerken kullanılacak geçiş stilini alır veya ayarlar. |
| display_duration | Sayfalar için görüntüleme süresini alır veya ayarlar. |
| process_pages | Düzenlenecek sayfa numaralarını alır veya ayarlar. Varsayılan olarak, her sayfa düzenlenir. |
| rotation | Sayfaların döndürülmesini alır veya ayarlar, döndürme 0, 90, 180 veya 270 olmalıdır.<br/>            Varsayılan değer 0'dır. |
| zoom | Yakınlaştırma katsayısını alır veya ayarlar. Değer 1.0, %100'e karşılık gelir.<br/>            Varsayılan değer 1.0'dır. |
| page_size | Çıktı dosyasının sayfa boyutunu alır veya ayarlar. |
| hizalama | Orijinal PDF içeriğinin sonuç sayfasındaki yatay hizalamasını alır veya ayarlar, varsayılan AlignmentType.Left'tir. |
| horizontal_alignment | Orijinal PDF içeriğinin sonuç sayfasındaki yatay hizalamasını alır veya ayarlar, varsayılan AlignmentType.Left'tir. |
| vertical_alignment | Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını alır veya ayarlar, varsayılan VerticalAlignmentType.Bottom'tur. |
| vertical_alignment_type | Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını alır veya ayarlar, varsayılan VerticalAlignmentType.Bottom'tur. |
| SPLITVOUT | Dış Dikey Bölme |
| SPLITHOUT | Dış Yatay Bölme |
| SPLITVIN | İç Dikey Bölme |
| SPLITHIN | IN Yatay Bölme |
| BLINDV | Dikey Storlar |
| BLINDH | Dikey Storlar |
| INBOX | İçeriye Yönelik Kutu |
| OUTBOX | Dışarıya Yönelik Kutu |
| LRWIPE | Sol-Sağ Silme |
| RLWIPE | Sağ-Sol Silme |
| BTWIPE | Alt-Üst Silme |
| TBWIPE | Üst-Alt Silme |
| DISSOLVE | Eski sayfa çözülür |
| LRGLITTER | Sol-Sağ Parıltı |
| TBGLITTER | Üst-Alt Parıltı |
| DGLITTER | Diyagonal Parıltı |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(output_file) | Değiştirilen belgeyi dosyaya kaydeder. |
| save(output_stream) | Değiştirilen belgeyi akışa kaydeder. |
| close() | Mevcut facade ile ilişkili tüm kaynakları serbest bırakır. |
| move_position(move_x, move_y) | Kökeni (0, 0) noktasından belirtilen noktaya taşır. <br/>            Köken sol-alt konumdadır ve birim point'tir (1 inç = 72 point). |
| get_pages() | Toplam sayfa sayısını döndürür. |
| get_page_size(page) | Belirtilen sayfanın sayfa boyutunu döndürür. |
| get_page_rotation(page) | Belirtilen sayfanın dönüşünü döndürür. |
| get_page_box_size(page, page_box_name) | Belirtilen kutunun belge içindeki boyutunu döndürür. |
| apply_changes() | Belge sayfalarında yapılan değişiklikleri uygula. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

