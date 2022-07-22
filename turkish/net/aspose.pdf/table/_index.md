---
title: Table
second_title: Aspose.PDF for .NET API Referansı
description: Sayfaya eklenebilecek bir tabloyu temsil eder.
type: docs
weight: 6500
url: /tr/net/aspose.pdf/table/
---
## Table class

Sayfaya eklenebilecek bir tabloyu temsil eder.

```csharp
public sealed class Table : BaseParagraph
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Table](table)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Tablo hizalamasını alır veya ayarlar. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Tablo arka plan rengini alır veya ayarlar |
| [Border](../../aspose.pdf/table/border) { get; set; } | Sınırı alır veya ayarlar. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | table için kesme metnini alır veya ayarlar |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Tablo dikeyini bozuk alır veya ayarlar; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Tablo sütunu ayarını alır veya ayarlar. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Tablonun sütun genişliklerini alır. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Kenarlık köşelerinin stillerini alır veya ayarlar |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Varsayılan hücre kenarlığını alır; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Varsayılan hücre dolgusunu alır veya ayarlar. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Varsayılan hücre metni durumunu alır veya ayarlar. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Varsayılan hücre kenarlığını alır; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | paragrafının yatay hizalamasını alır veya ayarlar |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Sütun genişliklerinde bulunan kenarlığı alır veya ayarlar. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Tablonun bozuk olduğunu alır veya ayarlar - sonraki sayfa için kesilecektir. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Tablonun sol koordinatını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | table için maksimum sütun sayısını alır veya ayarlar |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Birkaç sayfa için tekrarlanan ilk satır sayısını alır |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Yinelenen satırların stilini alır |
| [Rows](../../aspose.pdf/table/rows) { get; } | Tablonun satırlarını alır. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Masa üstü koordinatını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Tabloyu klonlayın. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Yüksekliği alın. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Genişliği alın. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Tek boyutlu veri dizisini tabloya aktarır. İçe aktarma, her dizinin öğesi başına bir hücreye gider ve , parametrelerde tanımlanan satır ve sütundan başlar. İçe aktarma sırasında, gerekli satırların hala mevcut olmadığı (yani hedef tablonun tüm verileri ememeyecek kadar küçük olduğu) tespit edilirse, gerekli satırlar oluşturulur |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | System.Data.DataTable'dan Aspose.Pdf.Table 'ye veri aktarır |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | BirDataTable tabloya nesne. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | BirDataTable nesnedir, ancak bütün olarak değil. Yalnızca belirtilen satırlar ve sütunlar içe aktarılır. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | BirDataView nesnenin verilerini tabloya aktarın. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Yüksekliği ayarla. |

### Ayrıca bakınız

* class [BaseParagraph](../baseparagraph)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
