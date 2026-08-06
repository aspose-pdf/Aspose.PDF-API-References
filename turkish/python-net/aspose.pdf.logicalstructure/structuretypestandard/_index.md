---
title: "StructureTypeStandard"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Standart Yapı Türlerini temsil eder."
type: docs
weight: 560
url: /tr/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Standart Yapı Türlerini temsil eder.

StructureTypeStandard türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| tag | [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/) etiket adını alır. |
| category | Standart Yapı Türünün kategorisini alır. |
| DOCUMENT | (Document) Tam bir belge. Bu, birden çok bölüm veya birden çok makale içeren herhangi bir yapı ağacının kök öğesidir. |
| BÖLÜM | (Part) Bir belgenin büyük ölçekli bölümü. Bu öğe türü, makaleleri veya bölümleri gruplamak için uygundur. |
| MAK | (Article) Tek bir anlatı ya da açıklama oluşturan nispeten bağımsız bir metin gövdesi. Makaleler birbirinden ayrı olmalıdır; yani, diğer makaleleri bileşen öğe olarak içermemelidir. |
| BÖL | (Section) İlgili içerik öğelerini gruplamak için bir kapsayıcı. |
| DIV | (Division) Genel bir blok düzeyinde öğe ya da öğe grubu. |
| BLOCK_QUOTE | (Block quotation) Çevresindeki metnin yazarından farklı birine atfedilen bir veya daha fazla paragraftan oluşan bir metin bölümü. |
| CAPTION | (Caption) Bir tabloyu ya da şekli tanımlayan kısa bir metin bölümü. |
| İÇİNDEKİLER | (Table of contents) İçindekiler öğesi girişlerinden (yapı türü TOCI) ve/veya diğer iç içe geçmiş içindekiler girişlerinden (TOC) oluşan bir liste. |
| TOCI | (Table of contents item) İçindekiler'in bireysel bir üyesi. Bu girişin alt öğeleri aşağıdaki yapı türlerinden herhangi biri olabilir: |
| DİZİN | (Index) Belirtilen metnin belge ana gövdesindeki oluşumlarını gösteren referans öğeleriyle birlikte tanımlayıcı metin içeren bir dizi giriş. |
| NON_STRUCT | (Nonstructural element) İçsel bir yapısal öneme sahip olmayan bir gruplama öğesi; yalnızca gruplama amacıyla hizmet eder. Bu öğe türü, bir bölümden (yapı türü Div) farklı olarak diğer belge formatlarına yorumlanmaz veya dışa aktarılmaz; ancak, alt öğeleri normal şekilde işlenir. |
| ÖZEL | (Private element) Onu üreten uygulamaya ait özel içeriği barındıran bir gruplama öğesi. Bu öğe türünün yapısal önemi belirtilmemiştir ve tamamen uyumlu yazar tarafından belirlenir. Ne Özel öğe ne de onun alt öğeleri diğer belge formatlarına yorumlanmaz veya dışa aktarılmaz. |
| P | (Paragraph) Metnin düşük seviyeli bir bölümü. |
| H | (Heading) Belgenin içeriğinin bir alt bölümüne verilen bir etiket. Başlık verdiği bölmenin ilk çocuğu olmalıdır. |
| H1 | Seviye 1 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe yerleştirme seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| H2 | Seviye 2 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe yerleştirme seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| H3 | Seviye 3 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe yerleştirme seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| H4 | Seviye 4 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe yerleştirme seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| H5 | Seviye 5 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe yerleştirme seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| H6 | Seviye 6 Başlık, bölümlerini hiyerarşik olarak iç içe yerleştiremeyen ve bu nedenle bir başlığın seviyesini iç içe yerleştirme seviyesinden belirleyemeyen uyumlu yazarlar için kullanılır. |
| L | (List) Benzer anlam ve öneme sahip öğelerin bir dizisi. Doğrudan alt öğeleri isteğe bağlı bir başlık (yapı türü Caption) ve ardından bir veya daha fazla liste öğesi (yapı türü LI) olmalıdır. |
| LI | (List item) Bir listenin bireysel üyesi. Alt öğeleri bir veya daha fazla etiket, liste gövdesi veya her ikisi (yapı türleri Lbl veya LBody) olabilir. |
| LBL | (Label) Aynı listedeki veya benzer öğeler grubundaki diğerlerinden belirli bir öğeyi ayıran bir ad veya numara. |
| L_BODY | (List body) Bir liste öğesinin açıklayıcı içeriği. Örneğin bir sözlük listesinde, terimin tanımını içerir. İçeriği doğrudan içerebilir ya da diğer BLSE'leri, belki iç içe listeleri, alt öğe olarak barındırabilir. |
| TABLE | (Table) Dikdörtgen veri hücrelerinden oluşan iki boyutlu bir düzen, olası karmaşık bir alt yapıya sahip olabilir. Çocukları olarak bir veya daha fazla tablo satırı (yapı türü TR) ya da isteğe bağlı bir tablo başlığı (yapı türü THead) ardından bir veya daha fazla tablo gövdesi öğesi (yapı türü TBody) ve isteğe bağlı bir tablo altbilgisi (yapı türü TFoot) içerir. Ayrıca, bir tablonun ilk veya son çocuğu olarak bir başlık (yapı türü Caption) olabilir. |
| T_HEAD | (Table header row group; PDF 1.5) Bir tablonun başlığını oluşturan satır grubudur. Tablo birden fazla sayfaya bölünmüşse, bu satırlar her tablo parçasının üst kısmında yeniden çizilebilir (ancak yalnızca bir THead öğesi vardır). |
| T_BODY | (Table body row group; PDF 1.5) Bir tablonun ana gövde kısmını oluşturan satır grubudur. Tablo birden fazla sayfaya bölünmüşse, gövde alanı satır sınırında bölünebilir. Bir tablo, bir satır kümesi için kenarlık veya arka plan çizmeye izin vermek amacıyla birden çok TBody öğesine sahip olabilir. |
| T_FOOT | (Table footer row group; PDF 1.5) Bir tablonun altbilgisini oluşturan satır grubudur. Tablo birden fazla sayfaya bölünmüşse, bu satırlar her tablo parçasının alt kısmında yeniden çizilebilir (her ne kadar yalnızca bir TFoot öğesi olsa da). |
| TR | (Table row) Bir tabloda başlık veya veri satırıdır. Tablo başlık hücreleri ve tablo veri hücreleri (yapı türleri TH ve TD) içerebilir. |
| TH | (Table header cell) Tablo içinde bir veya daha fazla satır ya da sütunu tanımlayan başlık metni içeren bir tablo hücresidir. |
| TD | (Table data cell) Tablo içeriğinin bir parçası olan veriyi içeren bir tablo hücresidir. |
| SPAN | (Span) Belirli bir özelliği olmayan genel bir satır içi metin bölümüdür. Örneğin, belirli bir stil özniteliği kümesiyle bir metin aralığını sınırlamak için kullanılabilir. |
| QUOTE | (Quotation) Çevre metnin yazarından farklı birine atfedilen satır içi bir metin bölümüdür. |
| NOT | (Note) Belgenin gövdesinden referans verilen, dipnot ya da sonnot gibi açıklayıcı bir metin öğesidir. Çocuk olarak bir etiket (yapı türü Lbl) içerebilir. Not, ona başvuran gövde metnindeki yapı öğesinin çocuğu olarak eklenebilir ya da başka bir yerde (örneğin sonnotlar bölümünde) bulunabilir ve bir referans (yapı türü Reference) aracılığıyla erişilebilir. |
| REFERENCE | (Reference) Belgenin başka bir yerindeki içeriğe yapılan bir atıftır. |
| BIB_ENTRY | (Bibliography entry) Atıfta bulunulan içeriğin dış kaynağını belirten bir referanstır. Çocuk olarak bir etiket (yapı türü Lbl) içerebilir. |
| CODE | (Code) Bir bilgisayar programı metni parçasıdır. |
| LINK | (Link) ILSE içeriğinin bir bölümü ile ilgili bağlantı açıklaması veya açıklamaları arasındaki ilişkidir. Çocukları bir veya daha fazla içerik öğesi ya da alt ILSE ve ilişkili bağlantı açıklamalarını tanımlayan bir veya daha fazla nesne referansı olmalıdır. |
| ANNOT | (Annotation; PDF 1.5) ILSE içeriğinin bir bölümü ile ilgili PDF açıklaması arasındaki ilişkidir. Annot, bağlantı açıklamaları ve widget açıklamaları dışındaki tüm PDF açıklamaları için kullanılmalıdır. |
| RUBY | (Ruby; PDF 1.5) Başvurduğu temel metnin yanına yerleştirilen, daha küçük bir metin boyutunda yazılmış bir yan not (açıklama)dır. Bir Ruby öğesi ayrıca RB, RT ve RP öğelerini de içerebilir. |
| RB | (Ruby base text) Ruby açıklamasının uygulandığı tam boyutlu metin. RB metin, diğer satır içi öğeler veya her ikisinin bir karışımını içerebilir. RubyAlignattribute özelliğine sahip olabilir. |
| RT | (Ruby annotation text) Ruby temel metnine bitişik olarak yerleştirilecek daha küçük boyutlu metin. Metin, diğer satır içi öğeler veya her ikisinin bir karışımını içerebilir. RubyAlign ve RubyPosition özelliklerine sahip olabilir. |
| RP | (Ruby punctuation) Ruby açıklama metnini çevreleyen noktalama işaretleri. Yalnızca bir ruby açıklaması ruby stilinde düzgün biçimlendirilemediğinde ve bunun yerine normal bir yorum olarak biçimlendirildiğinde veya warichu olarak biçimlendirildiğinde kullanılır. Genellikle tek bir SOL veya SAĞ PARANTEZ veya benzeri ayraç karakteri içeren metin içerir. |
| WARICHU | (Warichu; PDF 1.5) Daha küçük bir metin boyutunda ve içeren metin satırının yüksekliği içinde iki daha küçük satıra biçimlendirilmiş bir yorum veya açıklama ve başvurduğu temel metnin ardından (satır içi) yer alır. Bir Warichu öğesi ayrıca WT ve WP öğelerini içerebilir. |
| WT | (Warichu text) İki satıra biçimlendirilmiş ve çevreleyen WP öğeleri arasına yerleştirilmiş bir warichu yorumunun daha küçük boyutlu metni. |
| WP | (Warichu punctuation) WT metnini çevreleyen noktalama işaretleri. Genellikle tek bir SOL veya SAĞ PARANTEZ veya benzeri ayraç karakteri içeren metin içerir. JIS X 4051-1995 standardına göre, bir warichu'yu çevreleyen parantezler biçimlendiricinin takdirine bağlı olarak BİR BOŞLUK (genişlik olarak nominal 1/4 EM) ile değiştirilebilir. |
| FIGURE | (Figure) Grafik içerikli bir öğe. Yerleşimi Placement düzen özniteliği ile belirtilebilir. |
| FORMULA | (Formula) Matematiksel bir formül. |
| FORM | (Form) Etkileşimli bir form alanını temsil eden bir widget açıklaması. |

### Ayrıca Bakınız

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

