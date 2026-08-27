---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, TrueType sembolik yazı tipinin birden fazla kodlaması olduğunda kodlama verilerini kopyalama sürecini ayarlamak için kullanılabilecek kuralları tanımlar. Bazı PDF belgeleri sonrasında."
type: docs
weight: 3690
url: /tr/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Bu sınıf, TrueType sembolik yazı tipinin birden fazla kodlamaya sahip olduğu durumlarda kodlama verilerinin kopyalanma sürecini ayarlamak için kullanılabilecek kuralları açıklar. Bazı PDF belgeleri PDF/A formatına dönüştürüldükten sonra "Sembolik TrueType yazı tipinin cmap'inde birden fazla kodlama" hatasını verebilir. Bu hatanın nedeni nedir? Tüm TrueType sembolik yazı tiplerinin dahili verilerinde özel bir "cmap" tablosu bulunur. Bu tablo karakter kodlarını glif indekslerine eşler. Ve bu tablo, kullanılan kodlamaları tanımlayan farklı kodlama alt tablolarını içerebilir. cmap tabloları hakkında ileri düzey bilgiyi https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html adresinde görebilirsiniz. Genellikle cmap tablosu birden fazla kodlama alt tablosu içerir, ancak PDF/A standardı, bu yazı tipi için PDF/A belgesinde yalnızca bir kodlama alt tablosunun bırakılmasını ya da bu yazı tipinin alt tabloları arasında bir (3,0) kodlama alt tablosunun bulunmasını şart koşar. Ve burada kilit soru - başka alt tablolardan hangi veriler alınarak hedef kodlama tablosu (3,0)'a kopyalanmalıdır? Çoğu yazı tipinde, her kodlama alt tablosunun diğer alt tabloyla tamamen tutarlı olduğu 'iyi yapılandırılmış' cmap tabloları bulunur. Ancak bazı yazı tiplerinde çakışmalar içeren cmap tabloları vardır - örneğin bir alt tablo unicode 100 için glif indeksi 100'ü, diğer alt tablo ise aynı unicode 100 için glif indeksi 200'ü içerir. Bu sorunları çözmek için özel bir strateji gereklidir. Varsayılan olarak aşağıdaki strateji kullanılır: mac alt tablosu (1,0) aranır. Bu tablo bulunursa, yalnızca bu veri hedef tablo (3,0)'ı doldurmak için kullanılır. Mac alt tablosu bulunamazsa, (3,0) dışındaki tüm alt tablolar döngüye alınır ve verileri hedef (3,0) alt tablosuna kopyalamak için kullanılır. Ayrıca her unicode (unicode, glif indeksi) eşlemesi, hedef tablo şu anda bu unicode'ı içermiyorsa hedef tabloya kopyalanır. Dolayısıyla, örneğin ilk alt tablo unicode 100 için glif indeksi 100'ü, sonraki alt tablo aynı unicode 100 için glif indeksi 200'ü içeriyorsa, yalnızca ilk alt tablodan (unicode=100, glif indeksi = 100) gelen veri kopyalanır. Bu yüzden her önceki alt tablo, sonraki alt tabloya göre öncelik kazanır. Bu sınıfın { PdfASymbolicFontEncodingStrategy} özellikleri, varsayılan davranışı ayarlamaya yardımcı olur. Eğer {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) özelliği { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} tipinde ayarlanmışsa, ilgili alt tablo mac alt tablosu (1,0)'a göre öncelikli olarak kullanılacaktır. Bu durumda {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} enumarasyonundaki 'MacTable' değeri bir anlam ifade etmez, çünkü varsayılan olarak kullanılacak aynı mac alt tablosuna (1,0) işaret eder. {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) özelliği, herhangi bir alt tablo için tüm öncelikleri göz ardı eder. Bu özellik ayarlanırsa, yalnızca bildirilen kuyruktaki alt tablolar belirtilen sırayla kullanılacaktır. Belirtilen alt tablolar bulunamazsa, tüm alt tabloların varsayılan iterasyonu ve yukarıda açıklanan kopyalama stratejisi kullanılacaktır. { PdfASymbolicFontEncodingStrategy.QueueItem} nesnesi kullanılan kodlama alt tablosunu belirtir. Bu alt tablo, üyeler (PlatformID, PlatformSpecificId) kombinasyonu ile ya da { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} enumarasyonu aracılığıyla ayarlanabilir. Yazı tipinde (3,0) alt tablosu bulunmadığında, PDF/A uyumluluğunu sürdürmek için başka bir alt tablo kullanılacaktır. Kullanılacak alt tablonun seçimi, daha önce açıklanan aynı kurallar çerçevesinde yapılır; böylece {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) ve {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) özellikleri sonuç alt tabloyu belirlemek için kullanılır ve yazı tipi istenen alt tablo(ları)na sahip değilse, mevcut herhangi bir alt tablo kullanılacaktır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Yapıcı. Varsayılan alt tabloyu (mac 1,0) ayarlar |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Yapıcı. Varsayılan alt tabloyu (mac 1,0) ayarlar |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | İşlenecek kodlama alt tablolarının kuyruğunu belirtir. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | mac alt tablosuna (1,0) öncelik vermek için kullanılacak alt tabloyu belirtir. Bu durumda {@code QueueItem.CMapEncodingTableType} enum'undan 'MacTable' değeri bir anlam taşımaz. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | İşlenecek kodlama alt tablolarının kuyruğunu belirtir. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | mac alt tablosuna (1,0) öncelik vermek için kullanılacak alt tabloyu belirtir. Bu durumda {@code QueueItem.CMapEncodingTableType} enum'undan 'MacTable' değeri bir anlam taşımaz. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Yapıcı. Varsayılan alt tabloyu (mac 1,0) ayarlar

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Yapıcı. Varsayılan alt tabloyu (mac 1,0) ayarlar

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Yapıcı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| preferredEncodingTable |  | mac alt tablosuna (1,0) öncelik vermek için kullanılacak kodlama alt tablosu @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

İşlenecek kodlama alt tablolarının kuyruğunu belirtir.

**Returns:**
QueueItem kuyruğu

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

mac alt tablosuna (1,0) öncelik vermek için kullanılacak alt tabloyu belirtir. Bu durumda {@code QueueItem.CMapEncodingTableType} enum'undan 'MacTable' değeri bir anlam taşımaz.

**Returns:**
CMapEncodingTableType öğesi @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
İşlenecek kodlama alt tablolarının kuyruğunu belirtir.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

mac alt tablosuna (1,0) öncelik vermek için kullanılacak alt tabloyu belirtir. Bu durumda {@code QueueItem.CMapEncodingTableType} enum'undan 'MacTable' değeri bir anlam taşımaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | preferredEncodingTable kodlama alt tablosu, mac alt tablosuna (1,0) öncelik verilerek kullanılacak @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
