---
title: PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Referansı
description: Bu sınıf TrueType sembolik yazı tipinin birden fazla kodlaması olduğunda case için veri kopyalama kodlama sürecini ayarlamak için kullanılabilecek kuralları açıklar. PDF/A formatına dönüştürüldükten sonra bazı PDF belgelerinde Sembolik olarak birden fazla kodlama hatası olabilir TrueType yazı tipinin cmapi. Bu hatanın nedeni nedir Tüm TrueType sembolik yazı tiplerinin dahili verilerinde özel cmap tablosu vardır. Bu tablo karakter kodlarını glif dizinleriyle eşler. Ve bu tablo kullanılan kodlamaları tanımlayan farklı kodlama alt tabloları içerebilir. https//developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. adresinde cmap tabloları hakkında gelişmiş bilgilere bakın. PDF/A belgesinde bu yazı tipi için alt tablo 30 bırakılmalıdır. Ve buradaki kilit soru - hedef kodlama tablosuna 30 kopyalamak için başka alt tablolardan hangi veriler alınmalıdır Yazı tiplerinin çoğu iyi biçimlendirilmiş cmap tablolarına sahiptir burada her kodlama alt tablosu başka bir alt tabloyla tamamen tutarlıdır. Ancak bazı fonts nin çakışan cmap tabloları vardır - örneğin bir alt tablonun unicode 100 için glif indeksi 100e sahipken başka bir alt tablonun aynı unicode 100. için glif indeksi 200e sahiptir. Bu sorunları çözmek için özel strateji gereklidir. Varsayılan olarak şu strateji kullanılır mac alt tablosu10 aranır. Bu tablo bulunursa yalnızca bu veriler hedef tablosunu 30 doldurmak için kullanılır. mac alt tablosu bulunamazsa 30 hariç tüm alt tablolar yinelenir ve verileri hedef 30 alt tablosuna kopyalamak için kullanılır. Ayrıca her unicodeunicode glyph index için eşleme yalnızca hedef tablonun şu anda bu unicodeu yoksa hedef tabloya kopyalanır. Dolayısıyla örneğin ilk alt tablonun unicode 100 için glif indeksi 100 varsa ve sonraki alt tablonun aynı unicode 100 için glyph indeksi 200 varsa yalnızca ilk alt tablodaki veriler unicode100 glif indeksi  100 kopyalanacaktır. Böylece önceki her bir alt tablo bir sonrakine göre önceliklidir. Bu sınıfın özellikleriPdfASymbolicFontEncodingStrategy./pdfasymbolicfontencodingstrategyvarsayılan davranışı ayarlamaya yardımcı olun. Özellik isePreferredCmapEncodingTable./pdfasymbolicfontencodingstrategy/preferredcmapencodingtable tipiCMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype ayarlanırsa ilgili alt tablo mac alt tablosuna10 öncelikli olarak kullanılacaktır. numaralandırmasından MacTable değeriCMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype bu durumda hiçbir anlamı yoktur çünkü varsayılan olarak kullanılacak olan aynı mac alt tablosunu 10 işaret eder. MülkCmapEncodingTablesPriorityQueue./pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue herhangi bir alt tablo için tüm öncelikleri atar. Bu özellik ayarlanırsa belirtilen sırada yalnızca beyan edilen kuyruktaki alt tablolar kullanılacaktır. Belirtilen alt tablolar bulunamazsa tüm alt tabloların varsayılan yinelemesi ve yukarıda açıklanan kopyalama stratejisi kullanılacaktır. NesneQueueItem./pdfasymbolicfontencodingstrategy.queueitem kullanılan kodlama alt tablosunu belirtir. Bu alt tablo üye kombinasyonu PlatformID PlatformSpecificId veya aracılığıyla set olabilir.CMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype numaralandırma.
type: docs
weight: 5980
url: /tr/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy class

Bu sınıf, TrueType sembolik yazı tipinin birden fazla kodlaması olduğunda case için veri kopyalama kodlama sürecini ayarlamak için kullanılabilecek kuralları açıklar. PDF/A formatına dönüştürüldükten sonra bazı PDF belgelerinde "Sembolik olarak birden fazla kodlama hatası olabilir" TrueType yazı tipinin cmap'i". Bu hatanın nedeni nedir? Tüm TrueType sembolik yazı tiplerinin dahili verilerinde özel "cmap" tablosu vardır. Bu tablo karakter kodlarını glif dizinleriyle eşler. Ve bu tablo, kullanılan kodlamaları tanımlayan farklı kodlama alt tabloları içerebilir. https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. adresinde cmap tabloları hakkında gelişmiş bilgilere bakın. PDF/A belgesinde bu yazı tipi için alt tablo (3,0) bırakılmalıdır. Ve buradaki kilit soru - hedef kodlama tablosuna (3,0) kopyalamak için başka alt tablolardan hangi veriler alınmalıdır? Yazı tiplerinin çoğu, 'iyi biçimlendirilmiş' cmap tablolarına sahiptir, burada her kodlama alt tablosu başka bir alt tabloyla tamamen tutarlıdır. Ancak bazı fonts 'nin çakışan cmap tabloları vardır - örneğin, bir alt tablonun unicode 100 için glif indeksi 100'e sahipken, başka bir alt tablonun aynı unicode 100. için glif indeksi 200'e sahiptir. Bu sorunları çözmek için özel strateji gereklidir. Varsayılan olarak şu strateji kullanılır: mac alt tablosu(1,0) aranır. Bu tablo bulunursa, yalnızca bu veriler hedef tablosunu (3,0) doldurmak için kullanılır. mac alt tablosu bulunamazsa, (3,0) hariç tüm alt tablolar yinelenir ve verileri hedef (3,0) alt tablosuna kopyalamak için kullanılır. Ayrıca her unicode(unicode, glyph index) için eşleme, yalnızca hedef tablonun şu anda bu unicode'u yoksa hedef tabloya kopyalanır. Dolayısıyla, örneğin, ilk alt tablonun unicode 100 için glif indeksi 100 varsa ve sonraki alt tablonun aynı unicode 100 için glyph indeksi 200 varsa, yalnızca ilk alt tablodaki veriler (unicode=100, glif indeksi = 100) kopyalanacaktır. Böylece önceki her bir alt tablo bir sonrakine göre önceliklidir. Bu sınıfın özellikleri[`PdfASymbolicFontEncodingStrategy`](../pdfasymbolicfontencodingstrategy)varsayılan davranışı ayarlamaya yardımcı olun. Özellik ise[`PreferredCmapEncodingTable`](./preferredcmapencodingtable) tipi[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) ayarlanırsa, ilgili alt tablo, mac alt tablosuna(1,0) öncelikli olarak kullanılacaktır. numaralandırmasından 'MacTable' değeri[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) bu durumda hiçbir anlamı yoktur, çünkü varsayılan olarak kullanılacak olan aynı mac alt tablosunu (1,0) işaret eder. Mülk[`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue) herhangi bir alt tablo için tüm öncelikleri atar. Bu özellik ayarlanırsa, belirtilen sırada yalnızca beyan edilen kuyruktaki alt tablolar kullanılacaktır. Belirtilen alt tablolar bulunamazsa, tüm alt tabloların varsayılan yinelemesi ve yukarıda açıklanan kopyalama stratejisi kullanılacaktır. Nesne[`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem) kullanılan kodlama alt tablosunu belirtir. Bu alt tablo, üye kombinasyonu (PlatformID, PlatformSpecificId) veya aracılığıyla set olabilir.[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) numaralandırma.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy#constructor)() | Oluşturucu. Varsayılan alt tabloyu ayarlar (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy#constructor_1)(CMapEncodingTableType) | Yapıcı |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy#constructor_2)(Queue&lt;QueueItem&gt;) | Yapıcı |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue) { get; set; } | İşlenecek kodlama alt tablolarının kuyruğunu belirtir. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable) { get; set; } | mac alt tablosundan(1,0) önce kullanılacak olan alt tabloyu belirtir. numaralandırmasından 'MacTable' değeri[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) bu durumda hiçbir anlamı yok. |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->