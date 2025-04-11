---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table sınıfı. Sayfaya eklenebilen bir tabloyu temsil eder
type: docs
weight: 10280
url: /tr/net/aspose.pdf/table/
---
## Tablo sınıfı

Sayfaya eklenebilen bir tabloyu temsil eder.

```csharp
public sealed class Table : BaseParagraph
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Table](table/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Tablo hizalamasını alır veya ayarlar. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Tablo arka plan rengini alır veya ayarlar. |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Kenarlığı alır veya ayarlar. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Tablo için metin kırılmasını alır veya ayarlar. |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Tablo dikey kırılmasını alır veya ayarlar; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Tablo sütun ayarlamasını alır veya ayarlar. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Tablo sütun genişliklerini alır. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Kenar köşelerinin stillerini alır veya ayarlar. |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Varsayılan hücre kenarlığını alır; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Varsayılan hücre iç boşluğunu alır veya ayarlar. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Varsayılan hücre metin durumunu alır veya ayarlar. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Varsayılan hücre genişliğini alır; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Paragrafın yatay hizalamasını alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Sütun genişliklerinde kenarlığın dahil olup olmadığını alır veya ayarlar. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Tablo kırık mı - bir sonraki sayfa için kesileceğini alır veya ayarlar. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'tur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'tur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'tur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'tur. (pdf oluşturma için) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Tablo sol koordinatını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış boşluğu alır veya ayarlar (pdf oluşturma için) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Tablo için maksimum sütun sayısını alır veya ayarlar. |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Birkaç sayfa için tekrar eden ilk satır sayısını alır. |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Tekrar eden satırlar için stili alır veya ayarlar. |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Tablo satırlarını alır. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Tablo üst koordinatını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Tabloyu kopyalar. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Yüksekliği alır. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Genişliği alır. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Tek boyutlu veri dizisini tabloya aktarır. Aktarım, her dizinin öğesi için bir hücre alır ve parametrelerde tanımlanan satır ve sütundan başlar. Aktarım sırasında, gerekli satırların hala mevcut olmadığı tespit edilirse (yani hedef tablo tüm verileri almak için çok küçükse), gerekli satırlar oluşturulacaktır. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Verileri System.Data.DataTable'dan Aspose.Pdf.Table'a aktarır. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Bir DataTable nesnesini tabloya aktarır. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Bir DataTable nesnesini, ancak bütün bir varlık olarak değil, aktarır. Sadece belirtilen satırlar ve sütunlar aktarılır. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Bir DataView nesnesinin verilerini tabloya aktarır. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Yüksekliği ayarlar. |

### Ayrıca Bakınız

* sınıf [BaseParagraph](../baseparagraph/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)