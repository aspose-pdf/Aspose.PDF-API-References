---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Aspose.PDF for Java API Referansı"
description: "Standart Yapı Türlerini temsil eder."
type: docs
weight: 130
url: /tr/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Standart Yapı Türlerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) ILSE içeriğinin bir bölümü ile ilgili PDF ek açıklaması arasındaki ilişki. Annot, bağlantı ek açıklamaları ve widget ek açıklamaları dışındaki tüm PDF ek açıklamaları için kullanılmalıdır. |
| [Art](#Art) | (Article) Göreceli olarak kendi içinde tutarlı bir metin bloğu olup tek bir anlatı ya da açıklama oluşturur. Makaleler birbirinden ayrı olmalıdır; yani diğer makaleleri bileşen öğe olarak içermemelidir. |
| [BibEntry](#BibEntry) | (Bibliography entry) Bazı alıntılanan içeriğin dış kaynağını tanımlayan bir referans. Bir etiket (yapı türü Lbl) çocuk olarak içerebilir. Bibliyografi girişi, alıntılanan içeriğin yazarını, eserini, yayıncısını vb. tanımlayan bileşen parçaları içerebilir, ancak bu düzeyde ayrıntılı standart yapı türleri tanımlanmamıştır. |
| [BlockQuote](#BlockQuote) | (Block quotation) Bir veya daha fazla paragraftan oluşan ve çevrenin yazarından farklı birine atfedilen bir metin bölümü. |
| [Caption](#Caption) | (Caption) Bir tabloyu veya şekli tanımlayan kısa bir metin bölümü. |
| [Code](#Code) | (Code) Bilgisayar programı metninin bir bölümü. |
| [Div](#Div) | (Division) Genel bir blok düzeyinde öğe ya da öğe grubu. |
| [Document](#Document) | (Document) Tam bir belge. Bu, birden fazla bölüm veya birden fazla makale içeren herhangi bir yapı ağacının kök öğesidir. |
| [Figure](#Figure) | (Figure) Grafik içerikli bir öğe. Yerleşimi Placement düzen özniteliği ile belirtilebilir. |
| [Form](#Form) | (Form) Etkileşimli bir form alanını temsil eden bir widget ek açıklaması. |
| [Formula](#Formula) | (Formula) Matematiksel bir formül. Bu yapı türü yalnızca tüm bir içerik öğesini formül olarak tanımlamak için kullanışlıdır. Formül içindeki bireysel bileşenleri tanımlamak için standart bir yapı türü tanımlanmamıştır. Biçimlendirme açısından, formül bir şekil (yapı türü Figure) gibi ele alınmalıdır. |
| [H](#H) | (Heading) Bir belgenin içeriğinin alt bölümü için bir etiket. Başlık verdiği bölümün ilk çocuğu olmalıdır. |
| [H1](#H1) | Seviye 1 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| [H2](#H2) | Seviye 2 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| [H3](#H3) | Seviye 3 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| [H4](#H4) | Seviye 4 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| [H5](#H5) | Seviye 5 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| [H6](#H6) | Seviye 6 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| [Index](#Index) | (Index) Belirli metni belge ana gövdesinde gösteren referans öğeleriyle birlikte tanımlayıcı metin içeren girişlerin bir dizisi. |
| [L](#L) | (List) Anlam ve önemde benzer öğelerin bir dizisi. Doğrudan alt öğeleri isteğe bağlı bir başlık (yapı türü Caption) ve ardından bir veya daha fazla liste öğesi (yapı türü LI) olmalıdır. |
| [Lbl](#Lbl) | (Label) Aynı listedeki veya benzer öğeler grubundaki diğerlerinden bir öğeyi ayıran ad veya numara. |
| [LBody](#LBody) | (List body) Bir liste öğesinin açıklayıcı içeriği. Örneğin bir sözlük listesinde, terimin tanımını içerir. İçeriği doğrudan içerebilir veya alt öğe olarak diğer BLSE'leri, belki iç içe listeleri de içerebilir. |
| [LI](#LI) | (List item) Bir listenin bireysel üyesi. Alt öğeleri bir veya daha fazla etiket, liste gövdesi veya her ikisi (yapı türleri Lbl veya LBody) olabilir. |
| [Link](#Link) | (Link) ILSE içeriğinin bir bölümü ile ilgili bağlantı açıklaması veya açıklamaları arasındaki ilişki. Alt öğeleri bir veya daha fazla içerik öğesi veya alt ILSE ve ilişkili bağlantı açıklamalarını tanımlayan bir veya daha fazla nesne referansı olmalıdır. |
| [NonStruct](#NonStruct) | (Nonstructural element) İçsel bir yapısal önemi olmayan bir gruplama öğesi; yalnızca gruplama amacıyla hizmet eder. Bu öğe türü, bir bölüme (yapı türü Div) farklıdır; yorumlanmamalı veya diğer belge formatlarına dışa aktarılmamalıdır; ancak, alt öğeleri normal şekilde işlenmelidir. |
| [Note](#Note) | (Note) Belge gövdesinden başvurulan açıklayıcı bir metin öğesi, örneğin bir dipnot veya sonnot. Alt öğe olarak bir etiket (yapı türü Lbl) içerebilir. Not, ona başvuran gövde metnindeki yapı öğesinin alt öğesi olarak eklenebilir veya başka bir yerde (örneğin sonnotlar bölümünde) eklenip bir referans (yapı türü Reference) aracılığıyla erişilebilir. Etiketli PDF, dipnotların sayfa içeriği sırasındaki yerleşimini belirlemez. Dipnotlar, uyumlu yazarın takdirine bağlı olarak satır içinde ya da sayfanın sonunda bulunabilir. |
| [P](#P) | (Paragraph) Metnin düşük seviyeli bir bölümü. |
| [Part](#Part) | (Part) Bir belgenin büyük ölçekli bölümü. Bu öğe türü, makaleleri veya bölümleri gruplamak için uygundur. |
| [Private](#Private) | (Private element) Üreten uygulamaya ait özel içeriği içeren bir gruplama öğesi. Bu öğe türünün yapısal önemi belirtilmemiştir ve tamamen uyumlu yazar tarafından belirlenmelidir. Ne Private öğesi ne de onun alt öğeleri yorumlanmamalı veya diğer belge formatlarına dışa aktarılmamalıdır. |
| [Quote](#Quote) | (Quotation) Çevresindeki metnin yazarından farklı birine atfedilen satır içi bir metin bölümü. Alıntılanan metin tek bir paragraf içinde satır içi olarak bulunmalıdır. Bu, bir veya daha fazla tam paragraftan (veya tam paragraf gibi sunulan diğer öğelerden) oluşan blok düzeyindeki BlockQuote öğesinden farklıdır. |
| [RB](#RB) | (Ruby base text) Ruby açıklamasının uygulandığı tam boyutlu metin. RB metin, diğer satır içi öğeler veya her ikisinin bir karışımını içerebilir. RubyAlign özelliğine sahip olabilir. |
| [Reference](#Reference) | (Reference) Belgenin başka bir yerindeki içeriğe atıf. |
| [RP](#RP) | (Ruby punctuation) Ruby açıklama metnini çevreleyen noktalama işaretleri. Ruby açıklaması uygun bir ruby stiliyle biçimlendirilemediğinde ve normal bir yorum olarak ya da warichu olarak biçimlendirildiğinde kullanılır. Metin içerir (genellikle tek bir SOL veya SAĞ PARANTEZ veya benzeri bir ayraç karakteri). |
| [RT](#RT) | (Ruby annotation text) Ruby temel metnine bitişik olarak yerleştirilecek daha küçük boyutlu metin. Metin, diğer satır içi öğeler veya her ikisinin bir karışımını içerebilir. RubyAlign ve RubyPosition özelliklerine sahip olabilir. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) Daha küçük bir metin boyutunda yazılmış ve referans aldığı temel metnin yanına yerleştirilmiş bir yan-not (annotasyon). Bir Ruby öğesi ayrıca RB, RT ve RP öğelerini içerebilir. (Ruby) Tüm ruby montajının etrafındaki sarmalayıcı. Bir RB öğesi ve ardından bir RT öğesi ya da RP, RT ve RP'den oluşan üç öğeli bir grup içermelidir. Ruby öğeleri ve içerik öğeleri birden fazla satıra bölünmemelidir. |
| [Sect](#Sect) | (Section) İlgili içerik öğelerini gruplamak için bir kapsayıcı. |
| [Span](#Span) | (Span) Belirli bir içsel özelliği olmayan, genel bir satır içi metin bölümü. Örneğin, belirli bir stil özelliği setiyle bir metin aralığını sınırlamak için kullanılabilir. |
| [Table](#Table) | (Table) Dikdörtgen veri hücrelerinden oluşan iki boyutlu bir düzen, olası karmaşık bir alt yapıya sahip olabilir. Çocuk olarak bir veya daha fazla tablo satırı (yapı tipi TR) içerir; ya da isteğe bağlı bir tablo başlığı (yapı tipi THead) ardından bir veya daha fazla tablo gövde öğesi (yapı tipi TBody) ve isteğe bağlı bir tablo altbilgisi (yapı tipi TFoot). Ayrıca, bir tablo ilk ya da son çocuğu olarak bir başlık (yapı tipi Caption) içerebilir. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) Bir tablonun ana gövde kısmını oluşturan satır grubudur. Tablo birden fazla sayfaya bölünürse, gövde alanı bir satır sınırında bölünebilir. Bir tablo, bir satır kümesi için kenarlık veya arka plan çizmeye izin vermek amacıyla birden fazla TBody öğesine sahip olabilir. |
| [TD](#TD) | (Table data cell) Tablo içeriğinin bir parçası olan veri içeren bir tablo hücresi. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) Bir tablonun altbilgisini oluşturan satır grubudur. Tablo birden fazla sayfaya bölünürse, bu satırlar her tablo parçasının altına yeniden çizilebilir (tek bir TFoot öğesi olsa bile). |
| [TH](#TH) | (Table header cell) Tablonun bir veya daha fazla satır veya sütununu tanımlayan başlık metni içeren bir tablo hücresi. |
| [THead](#THead) | (Table header row group; PDF 1.5) Bir tablonun başlığını oluşturan satır grubudur. Tablo birden fazla sayfaya bölünürse, bu satırlar her tablo parçasının üstüne yeniden çizilebilir (tek bir THead öğesi olsa bile). |
| [TOC](#TOC) | (Table of contents) İçindekiler tablosu öğesi girişlerinden (yapı tipi TOCI) ve/veya diğer iç içe geçmiş içindekiler tablosu girişlerinden (TOC) oluşan bir listedir. Yalnızca TOCI girişlerini içeren bir TOC girişi düz bir hiyerarşi temsil eder. Diğer iç içe TOC girişlerini (ve muhtemelen TOCI girişlerini) içeren bir TOC girişi daha karmaşık bir hiyerarşi temsil eder. İdeal olarak, üst düzey bir TOC girişinin hiyerarşisi belgenin ana gövdesinin yapısını yansıtır. |
| [TOCI](#TOCI) | (Table of contents item) İçindekiler tablosunun bireysel bir üyesidir. Bu girişin çocukları aşağıdaki yapı tiplerinden herhangi biri olabilir: Lbl - Bir etiket Reference - Başlığa ve sayfa numarasına referans NonStruct - Lider artefaktı sarmak için kullanılan yapı dışı öğeler P - Açıklayıcı metin TOC - Hiyerarşik içindekiler tabloları için içindekiler tablosu öğeleri, TOC girişi için açıklandığı gibi |
| [TR](#TR) | (Table row) Bir tablodaki başlık veya veri satırı. Tablo başlık hücreleri ve tablo veri hücreleri (yapı tipleri TH ve TD) içerebilir. |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) Daha küçük bir metin boyutunda ve temel metnin yüksekliği içinde iki daha küçük satıra biçimlendirilmiş bir yorum veya anotasyon; referans aldığı temel metnin ardından (satır içi) yer alır. Bir Warichu öğesi ayrıca WT ve WP öğelerini içerebilir. (Warichu) Tüm warichu montajının etrafındaki sarmalayıcı. WP, WT ve WP'den oluşan üç öğeli bir grup içerebilir. Warichu öğeleri (ve içerik öğeleri) Japon Endüstri Standardı (JIS) X 4051-1995'te tanımlanan warichu kırılma kurallarına göre birden fazla satıra sarılabilir. |
| [WP](#WP) | (Warichu punctuation) WT metnini çevreleyen noktalama işaretleri. Genellikle tek bir SOL veya SAĞ PARANTEZ ya da benzeri bir ayraç karakteri içeren metin içerir. JIS X 4051-1995'e göre, warichu'yu çevreleyen parantezler biçimlendiricinin takdirine bağlı olarak bir BOŞLUK (genişliği nominal olarak 1/4 EM) ile değiştirilebilir. |
| [WT](#WT) | (Warichu metni) Çevreleyen WP öğeleri arasında iki satıra biçimlendirilmiş ve yerleştirilmiş daha küçük boyutlu warichu yorum metni. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Standart Yapı Tipinin kategorisini alır. |
| [getTag](#getTag--) | {@code StructureElement} etiket adını alır. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | {@link String} tipinden {@link StructureTypeStandard} tipine açık dönüşüm gerçekleştirir. |
| [toString](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) ILSE içeriğinin bir bölümü ile ilgili PDF ek açıklaması arasındaki ilişki. Annot, bağlantı ek açıklamaları ve widget ek açıklamaları dışındaki tüm PDF ek açıklamaları için kullanılmalıdır.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) Göreceli olarak kendi içinde tutarlı bir metin bloğu olup tek bir anlatı ya da açıklama oluşturur. Makaleler birbirinden ayrı olmalıdır; yani diğer makaleleri bileşen öğe olarak içermemelidir.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Bibliography entry) Bazı alıntılanan içeriğin dış kaynağını tanımlayan bir referans. Bir etiket (yapı türü Lbl) çocuk olarak içerebilir. Bibliyografi girişi, alıntılanan içeriğin yazarını, eserini, yayıncısını vb. tanımlayan bileşen parçaları içerebilir, ancak bu düzeyde ayrıntılı standart yapı türleri tanımlanmamıştır.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Block quotation) Bir veya daha fazla paragraftan oluşan ve çevrenin yazarından farklı birine atfedilen bir metin bölümü.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Caption) Bir tabloyu veya şekli tanımlayan kısa bir metin bölümü.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) Bilgisayar programı metninin bir bölümü.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) Genel bir blok düzeyinde öğe ya da öğe grubu.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) Tam bir belge. Bu, birden fazla bölüm veya birden fazla makale içeren herhangi bir yapı ağacının kök öğesidir.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) Grafik içerikli bir öğe. Yerleşimi Placement düzen özniteliği ile belirtilebilir.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) Etkileşimli bir form alanını temsil eden bir widget ek açıklaması.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Matematiksel bir formül. Bu yapı türü yalnızca tüm bir içerik öğesini formül olarak tanımlamak için kullanışlıdır. Formül içindeki bireysel bileşenleri tanımlamak için standart bir yapı türü tanımlanmamıştır. Biçimlendirme açısından, formül bir şekil (yapı türü Figure) gibi ele alınmalıdır.

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) Bir belgenin içeriğinin alt bölümü için bir etiket. Başlık verdiği bölümün ilk çocuğu olmalıdır.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Seviye 1 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Seviye 2 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Seviye 3 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Seviye 4 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Seviye 5 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Seviye 6 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Index) Belirli metni belge ana gövdesinde gösteren referans öğeleriyle birlikte tanımlayıcı metin içeren girişlerin bir dizisi.

### L {#L}
```
public static final StructureTypeStandard L
```

(List) Anlam ve önemde benzer öğelerin bir dizisi. Doğrudan alt öğeleri isteğe bağlı bir başlık (yapı türü Caption) ve ardından bir veya daha fazla liste öğesi (yapı türü LI) olmalıdır.

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Label) Aynı listedeki veya benzer öğeler grubundaki diğerlerinden bir öğeyi ayıran ad veya numara.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(List body) Bir liste öğesinin açıklayıcı içeriği. Örneğin bir sözlük listesinde, terimin tanımını içerir. İçeriği doğrudan içerebilir veya alt öğe olarak diğer BLSE'leri, belki iç içe listeleri de içerebilir.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(List item) Bir listenin bireysel üyesi. Alt öğeleri bir veya daha fazla etiket, liste gövdesi veya her ikisi (yapı türleri Lbl veya LBody) olabilir.

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Link) ILSE içeriğinin bir bölümü ile ilgili bağlantı açıklaması veya açıklamaları arasındaki ilişki. Alt öğeleri bir veya daha fazla içerik öğesi veya alt ILSE ve ilişkili bağlantı açıklamalarını tanımlayan bir veya daha fazla nesne referansı olmalıdır.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Nonstructural element) İçsel bir yapısal önemi olmayan bir gruplama öğesi; yalnızca gruplama amacıyla hizmet eder. Bu öğe türü, bir bölüme (yapı türü Div) farklıdır; yorumlanmamalı veya diğer belge formatlarına dışa aktarılmamalıdır; ancak, alt öğeleri normal şekilde işlenmelidir.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Note) Belge gövdesinden başvurulan açıklayıcı bir metin öğesi, örneğin bir dipnot veya sonnot. Alt öğe olarak bir etiket (yapı türü Lbl) içerebilir. Not, ona başvuran gövde metnindeki yapı öğesinin alt öğesi olarak eklenebilir veya başka bir yerde (örneğin sonnotlar bölümünde) eklenip bir referans (yapı türü Reference) aracılığıyla erişilebilir. Etiketli PDF, dipnotların sayfa içeriği sırasındaki yerleşimini belirlemez. Dipnotlar, uyumlu yazarın takdirine bağlı olarak satır içinde ya da sayfanın sonunda bulunabilir.

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraph) Metnin düşük seviyeli bir bölümü.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Part) Bir belgenin büyük ölçekli bölümü. Bu öğe türü, makaleleri veya bölümleri gruplamak için uygundur.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Private element) Üreten uygulamaya ait özel içeriği içeren bir gruplama öğesi. Bu öğe türünün yapısal önemi belirtilmemiştir ve tamamen uyumlu yazar tarafından belirlenmelidir. Ne Private öğesi ne de onun alt öğeleri yorumlanmamalı veya diğer belge formatlarına dışa aktarılmamalıdır.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Quotation) Çevresindeki metnin yazarından farklı birine atfedilen satır içi bir metin bölümü. Alıntılanan metin tek bir paragraf içinde satır içi olarak bulunmalıdır. Bu, bir veya daha fazla tam paragraftan (veya tam paragraf gibi sunulan diğer öğelerden) oluşan blok düzeyindeki BlockQuote öğesinden farklıdır.

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Ruby base text) Ruby açıklamasının uygulandığı tam boyutlu metin. RB metin, diğer satır içi öğeler veya her ikisinin bir karışımını içerebilir. RubyAlign özelliğine sahip olabilir.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Reference) Belgenin başka bir yerindeki içeriğe atıf.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Ruby punctuation) Ruby açıklama metnini çevreleyen noktalama işaretleri. Ruby açıklaması uygun bir ruby stiliyle biçimlendirilemediğinde ve normal bir yorum olarak ya da warichu olarak biçimlendirildiğinde kullanılır. Metin içerir (genellikle tek bir SOL veya SAĞ PARANTEZ veya benzeri bir ayraç karakteri).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Ruby annotation text) Ruby temel metnine bitişik olarak yerleştirilecek daha küçük boyutlu metin. Metin, diğer satır içi öğeler veya her ikisinin bir karışımını içerebilir. RubyAlign ve RubyPosition özelliklerine sahip olabilir.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) Daha küçük bir metin boyutunda yazılmış ve referans aldığı temel metnin yanına yerleştirilmiş bir yan-not (annotasyon). Bir Ruby öğesi ayrıca RB, RT ve RP öğelerini içerebilir. (Ruby) Tüm ruby montajının etrafındaki sarmalayıcı. Bir RB öğesi ve ardından bir RT öğesi ya da RP, RT ve RP'den oluşan üç öğeli bir grup içermelidir. Ruby öğeleri ve içerik öğeleri birden fazla satıra bölünmemelidir.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) İlgili içerik öğelerini gruplamak için bir kapsayıcı.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Belirli bir içsel özelliği olmayan, genel bir satır içi metin bölümü. Örneğin, belirli bir stil özelliği setiyle bir metin aralığını sınırlamak için kullanılabilir.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Dikdörtgen veri hücrelerinden oluşan iki boyutlu bir düzen, olası karmaşık bir alt yapıya sahip olabilir. Çocuk olarak bir veya daha fazla tablo satırı (yapı tipi TR) içerir; ya da isteğe bağlı bir tablo başlığı (yapı tipi THead) ardından bir veya daha fazla tablo gövde öğesi (yapı tipi TBody) ve isteğe bağlı bir tablo altbilgisi (yapı tipi TFoot). Ayrıca, bir tablo ilk ya da son çocuğu olarak bir başlık (yapı tipi Caption) içerebilir.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) Bir tablonun ana gövde kısmını oluşturan satır grubudur. Tablo birden fazla sayfaya bölünürse, gövde alanı bir satır sınırında bölünebilir. Bir tablo, bir satır kümesi için kenarlık veya arka plan çizmeye izin vermek amacıyla birden fazla TBody öğesine sahip olabilir.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Tablo içeriğinin bir parçası olan veri içeren bir tablo hücresi.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) Bir tablonun altbilgisini oluşturan satır grubudur. Tablo birden fazla sayfaya bölünürse, bu satırlar her tablo parçasının altına yeniden çizilebilir (tek bir TFoot öğesi olsa bile).

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Tablonun bir veya daha fazla satır veya sütununu tanımlayan başlık metni içeren bir tablo hücresi.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) Bir tablonun başlığını oluşturan satır grubudur. Tablo birden fazla sayfaya bölünürse, bu satırlar her tablo parçasının üstüne yeniden çizilebilir (tek bir THead öğesi olsa bile).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) İçindekiler tablosu öğesi girişlerinden (yapı tipi TOCI) ve/veya diğer iç içe geçmiş içindekiler tablosu girişlerinden (TOC) oluşan bir listedir. Yalnızca TOCI girişlerini içeren bir TOC girişi düz bir hiyerarşi temsil eder. Diğer iç içe TOC girişlerini (ve muhtemelen TOCI girişlerini) içeren bir TOC girişi daha karmaşık bir hiyerarşi temsil eder. İdeal olarak, üst düzey bir TOC girişinin hiyerarşisi belgenin ana gövdesinin yapısını yansıtır.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) İçindekiler tablosunun bireysel bir üyesidir. Bu girişin çocukları aşağıdaki yapı tiplerinden herhangi biri olabilir: Lbl - Bir etiket Reference - Başlığa ve sayfa numarasına referans NonStruct - Lider artefaktı sarmak için kullanılan yapı dışı öğeler P - Açıklayıcı metin TOC - Hiyerarşik içindekiler tabloları için içindekiler tablosu öğeleri, TOC girişi için açıklandığı gibi

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Bir tablodaki başlık veya veri satırı. Tablo başlık hücreleri ve tablo veri hücreleri (yapı tipleri TH ve TD) içerebilir.

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) Daha küçük bir metin boyutunda ve temel metnin yüksekliği içinde iki daha küçük satıra biçimlendirilmiş bir yorum veya anotasyon; referans aldığı temel metnin ardından (satır içi) yer alır. Bir Warichu öğesi ayrıca WT ve WP öğelerini içerebilir. (Warichu) Tüm warichu montajının etrafındaki sarmalayıcı. WP, WT ve WP'den oluşan üç öğeli bir grup içerebilir. Warichu öğeleri (ve içerik öğeleri) Japon Endüstri Standardı (JIS) X 4051-1995'te tanımlanan warichu kırılma kurallarına göre birden fazla satıra sarılabilir.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) WT metnini çevreleyen noktalama işaretleri. Genellikle tek bir SOL veya SAĞ PARANTEZ ya da benzeri bir ayraç karakteri içeren metin içerir. JIS X 4051-1995'e göre, warichu'yu çevreleyen parantezler biçimlendiricinin takdirine bağlı olarak bir BOŞLUK (genişliği nominal olarak 1/4 EM) ile değiştirilebilir.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu metni) Çevreleyen WP öğeleri arasında iki satıra biçimlendirilmiş ve yerleştirilmiş daha küçük boyutlu warichu yorum metni.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Standart Yapı Tipinin kategorisini alır.

**Returns:**
Değer: Standart Yapı Tipinin Kategorisi.

### getTag {#getTag--}
```
public final String getTag()
```

{@code StructureElement} etiket adını alır.

**Returns:**
{@code StructureElement} etiket adı.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
{@link String} tipinden {@link StructureTypeStandard} tipine açık dönüşüm gerçekleştirir.

### toString {#toString--}
```
public String toString()
```

Geçerli nesneyi temsil eden bir dize döndürür.

**Returns:**
Geçerli nesneyi temsil eden String.
