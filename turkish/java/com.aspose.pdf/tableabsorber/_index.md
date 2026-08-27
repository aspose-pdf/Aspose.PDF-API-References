---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Tablo öğelerinin bir emici nesnesini temsil eder. Arama yapar ve {@code TableAbsorber.TableList} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> The."
type: docs
weight: 4800
url: /tr/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Tablo öğelerinin bir emici nesnesini temsil eder. Arama yapar ve {@code TableAbsorber.TableList} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> Bu örnek, ilk PDF belge sayfasında tablo bulmayı ve bir tablo hücresindeki metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Yeni bir {@code TableAbsorber} örneği başlatır. </p> <hr> Tabloları arar ve {@code TableList} nesnesi aracılığıyla tablolara erişim sağlar. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Yeni bir {@code TableAbsorber} örneği başlatır. </p> <hr> Tabloları arar ve {@code TableList} nesnesi aracılığıyla tablolara erişim sağlar. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTableList](#getTableList--) | <p> Bulunan tabloları içeren salt okunur IList döndürür </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Metin arama seçeneklerini alır. </p> <hr> Tablolarda bulunan metin araması sırasında kullanılacak birkaç seçenek tanımlamaya izin verir. |
| [isUseFlowEngine](#isUseFlowEngine--) | Birçok senaryoda üstün olan ve kenarlığı olmayan tabloları tanıyabilen alternatif bir tablo tanıma motorunu etkinleştirin. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Sayfadan bir {@code AbsorbedTable} kaldırır. </p> <hr> <p> Lütfen bunun TableList koleksiyonunu değiştirdiğini unutmayın. Döngü içinde tabloları kaldırırken/değiştirirken lütfen TableList koleksiyonunun bir kopyasını kullanın. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Sayfada bir {@code AbsorbedTable}'ı {@code Table} ile değiştirir. </p> <hr> <p> Lütfen bunun TableList koleksiyonunu değiştirdiğini unutmayın. Döngü içinde tabloları kaldırırken/değiştirirken lütfen TableList koleksiyonunun bir kopyasını kullanın. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Metin arama seçeneklerini alır veya ayarlar. </p> <hr> Tablolarda bulunan metin araması sırasında kullanılacak birkaç seçenek tanımlamaya izin verir. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Birçok senaryoda üstün olan ve kenarlığı olmayan tabloları tanıyabilen alternatif bir tablo tanıma motorunu etkinleştirin. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Belirtilen belgede tabloları çıkarır. </p> <hr> <pre> Bu örnek, ilk PDF belge sayfasında tablo çıkarmayı gösterir. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Belirtilen sayfada tabloları çıkarır </p> <hr> <pre> Bu örnek, ilk PDF belge sayfasında tablo çıkarmayı gösterir. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Yeni bir {@code TableAbsorber} örneği başlatır. </p> <hr> Tabloları arar ve {@code TableList} nesnesi aracılığıyla tablolara erişim sağlar.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Yeni bir {@code TableAbsorber} örneği başlatır. </p> <hr> Tabloları arar ve {@code TableList} nesnesi aracılığıyla tablolara erişim sağlar.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Bulunan tabloları içeren salt okunur IList döndürür </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Metin arama seçeneklerini alır. </p> <hr> Tablolarda bulunan metin araması sırasında kullanılacak birkaç seçenek tanımlamaya izin verir.

**Returns:**
TextSearchOptions nesnesi

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Birçok senaryoda üstün olan ve kenarlığı olmayan tabloları tanıyabilen alternatif bir tablo tanıma motorunu etkinleştirin.

**Returns:**
boolean değer

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Sayfadan bir {@code AbsorbedTable} kaldırır. </p> <hr> <p> Lütfen bunun TableList koleksiyonunu değiştirdiğini unutmayın. Döngü içinde tabloları kaldırırken/değiştirirken lütfen TableList koleksiyonunun bir kopyasını kullanın. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Sayfada bir {@code AbsorbedTable}'ı {@code Table} ile değiştirir. </p> <hr> <p> Lütfen bunun TableList koleksiyonunu değiştirdiğini unutmayın. Döngü içinde tabloları kaldırırken/değiştirirken lütfen TableList koleksiyonunun bir kopyasını kullanın. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Metin arama seçeneklerini alır veya ayarlar. </p> <hr> Tablolarda bulunan metin araması sırasında kullanılacak birkaç seçenek tanımlamaya izin verir.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Birçok senaryoda üstün olan ve kenarlığı olmayan tabloları tanıyabilen alternatif bir tablo tanıma motorunu etkinleştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useFlowEngine |  | boolean değer |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Belirtilen belgede tabloları çıkarır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında tablo nasıl çıkarılacağını gösterir. // Belgeyi aç Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Tabloları bulmak için TableAbsorber nesnesi oluştur TableAbsorber absorber = new TableAbsorber(); // İlk sayfayı absorber ile ziyaret et absorber.visit(pdfDocument); // Sayfadaki ilk tabloya, onun ilk hücresine ve içindeki metin parçalarına eriş TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Hücredeki ilk metin parçasının metnini değiştir fragment.setText (\"hi world\"); // Belgeyi kaydet doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Belirtilen sayfada tabloları çıkarır </p> <hr> <pre> Örnek, ilk PDF belge sayfasında tablo nasıl çıkarılacağını gösterir. // Belgeyi aç Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Tabloları bulmak için TableAbsorber nesnesi oluştur TableAbsorber absorber = new TableAbsorber(); // Absorber ile ilk sayfayı ziyaret et absorber.visit(doc.getPages.get_item(1)); // Sayfadaki ilk tabloya, onun ilk hücresine ve içindeki metin parçalarına eriş TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Hücredeki ilk metin parçasının metnini değiştir fragment.setText (\"hi world\"); // Belgeyi kaydet doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
