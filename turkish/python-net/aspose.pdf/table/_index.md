---
title: "Tablo"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sayfaya eklenebilen bir tabloyu temsil eder."
type: docs
weight: 1480
url: /tr/python-net/aspose.pdf/table/
---

## Table class

Sayfaya eklenebilen bir tabloyu temsil eder.

Tablo türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Tablo() | Tablo sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| vertical_alignment | Paragrafın dikey hizalamasını alır veya ayarlar. |
| horizontal_alignment | Paragrafın yatay hizalamasını alır veya ayarlar. |
| kenar boşluğu | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| is_first_paragraph_in_column | Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_kept_with_next | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_in_new_page | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_in_line_paragraph | Paragrafın satır içi olup olmadığını alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| köprü | Parçacık hiperlinkini alır veya ayarlar (pdf oluşturucu için). |
| z_index | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex <br/>            bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif <br/>            ZIndex bir grafik, sayfadaki metnin arkasına yerleştirilir. |
| background_color | Tablonun arka plan rengini alır veya ayarlar |
| break_text | Tablo için satır sonu metnini alır veya ayarlar |
| corner_style | Köşe kenar stillerini alır veya ayarlar |
| repeating_rows_style | Tekrarlanan satırlar için stili alır |
| repeating_columns_count | Tablo için maksimum sütun sayısını alır veya ayarlar |
| repeating_rows_count | Birden fazla sayfada tekrarlanan ilk satır sayısını alır |
| column_widths | Tablonun sütun genişliklerini alır. |
| broken | Tablo dikey kırılmasını alır veya ayarlar; |
| default_cell_border | Varsayılan hücre kenarlığını alır; |
| default_column_width | Varsayılan hücre kenarlığını alır; |
| satırlar | Tablonun satırlarını alır. |
| kenar | Kenarı alır veya ayarlar. |
| default_cell_padding | Varsayılan hücre dolgusu alır veya ayarlar. |
| default_cell_text_state | Varsayılan hücre metin durumunu alır veya ayarlar. |
| hizalama | Tablo hizalamasını alır veya ayarlar. |
| left | Tablonun sol koordinatını alır veya ayarlar. |
| top | Tablonun üst koordinatını alır veya ayarlar. |
| is_broken | Tablonun kırık olup olduğunu alır veya ayarlar - bir sonraki sayfada kırpılacaktır. |
| is_borders_included | Sütun genişliklerine dahil edilen kenarlığı alır veya ayarlar. |
| column_adjustment | Tablo sütun ayarlamasını alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Tabloyu klonla. |
| get_width() | Genişliği al. |
| get_height(parent_page) | Yüksekliği al. |
| set_column_text_state(col_number, text_state) | Yüksekliği ayarla. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Tek boyutlu veri dizisini tabloya aktarır. Aktarım, dizinin her öğesi için bir hücreye gider ve<br/>              parametrelerde tanımlanan satır ve sütundan başlar. Aktarım sırasında, gerekli satırların hâlâ eksik olduğu tespit edilirse (yani hedef tablo tüm verileri alacak kadar küçükse), gerekli satırlar oluşturulacaktır |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

