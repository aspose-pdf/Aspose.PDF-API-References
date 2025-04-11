---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber sınıfı. Tablo öğelerinin bir emici nesnesini temsil eder. Arama yapar ve arama sonuçlarına [`TableList`](./tablelist/) koleksiyonu aracılığıyla erişim sağlar.
type: docs
weight: 10790
url: /tr/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber sınıfı

Tablo öğelerinin bir emici nesnesini temsil eder. Arama yapar ve arama sonuçlarına [`TableList`](./tablelist/) koleksiyonu aracılığıyla erişim sağlar.

```csharp
public class TableAbsorber
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | `TableAbsorber`'ın yeni bir örneğini başlatır. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Metin arama seçenekleri ile `TableAbsorber`'ın yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Bulunan tabloları içeren readonly IList döner |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Metin arama seçeneklerini alır veya ayarlar. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Birçok senaryoda üstün olan ve kenarlara sahip olmayan tabloları tanıyabilen alternatif bir tablo tanıma motorunu etkinleştirir. Henüz tabloları düzenleme ve metin stillerini alma desteği yoktur. Varsayılan değer false; |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Sayfadan bir [`AbsorbedTable`](../absorbedtable/) kaldırır. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Sayfadaki bir [`AbsorbedTable`](../absorbedtable/) ile [`Table`](../../aspose.pdf/table/) değiştirir. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Belirtilen belgede tabloları çıkarır. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Belirtilen sayfadaki tabloları çıkarır |

## Örnekler

Örnek, ilk PDF belgesi sayfasında tablo bulmayı ve bir tablo hücresindeki metni değiştirmeyi gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)