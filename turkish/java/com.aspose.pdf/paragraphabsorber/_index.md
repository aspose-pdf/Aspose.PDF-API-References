---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Bölümler ve paragraflar gibi sayfa yapı nesnelerinin bir emici nesnesini temsil eder. Metnin bölümler ve paragraflarını arar ve erişim sağlar."
type: docs
weight: 3470
url: /tr/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Bölümler ve paragraflar gibi sayfa yapı nesnelerinin bir absorber nesnesini temsil eder. Metin bölümleri ve paragrafları arar ve metin koordinat uzayında tanımlayan dikdörtgenler ve çokgenlere erişim sağlar. Ayrıca metin segmentleri araması yapar ve yapı öğeleriyle gruplanmış {@code TextFragments} koleksiyonları aracılığıyla arama sonuçlarına erişim sunar. </p> Örnek, ilk PDF belge sayfasındaki her paragrafın ilk metin segmentini bulup vurgulamayı gösterir. <p> // Belgeyi aç Document doc = new Document("input.pdf"); // ParagraphAbsorber nesnesi oluştur ParagraphAbsorber absorber = new ParagraphAbsorber(); // İlk sayfa için absorber'ı kabul et absorber.visit(doc.getPages.get_Item(1)); // İlk sayfanın işaretleme nesnesini al PageMarkup markup = absorber.getPageMarkups().get(0); // Sayfa metninin yapı öğeleri arasında döngü yaparak her paragrafın ilk metin fragmentini bul for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Metin özelliklerini güncelle fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Belgeyi kaydet doc.save(GetOutputPath("output.pdf")); </p> <hr> Arama tamamlandığında {@code ParagraphAbsorber.PageMarkups} koleksiyonu {@code MarkupSection} ve {@code MarkupParagraph} koleksiyonlarıyla sayfa yapısını temsil eden {@code PageMarkup} nesnelerini içerir. {@code TextFragment} nesnesi arama gerçekleşen metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Emilen {@code PageMarkup} koleksiyonunu alır. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | ParagraphAbsorberOptions nesnesini alır. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Yapısal daha ince öğeler için kaç kez ardışık arama yapılacağını belirten değeri alır veya ayarlar. Varsayılan arama derinliği 3'tür. Bu, yatay olarak bölünmüş bölümler (başlıklar, paragraflar vb.) için üç arama ve dikey olarak bölünmüş bölümler (sütunlar) için üç arama anlamına gelir. </p><hr> Bu değerin artırılması, arama sonuçlarında görünür bir değişiklik olmadan performansta hafif bir düşüşe yol açabilir. Bu değerin azaltılması, bölümlerdeki paragrafların yanlış belirlenmesine neden olabilir. Varsayılan değerden daha düşük bir değer ayarlamanız önerilmez, eğer sayfa yapısının yalnızca 'kabaca' öğelerini elde etmek istemiyorsanız. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | TextReplaceOptions nesnesini alır veya ayarlar. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | ParagraphAbsorberOptions nesnesini ayarlar. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Yapısal daha ince öğeler için kaç kez ardışık arama yapılacağını belirten değeri alır veya ayarlar. Varsayılan arama derinliği 3'tür. Bu, yatay olarak bölünmüş bölümler (başlıklar, paragraflar vb.) için üç arama ve dikey olarak bölünmüş bölümler (sütunlar) için üç arama anlamına gelir. </p><hr> Bu değerin artırılması, arama sonuçlarında görünür bir değişiklik olmadan performansta hafif bir düşüşe yol açabilir. Bu değerin azaltılması, bölümlerdeki paragrafların yanlış belirlenmesine neden olabilir. Varsayılan değerden daha düşük bir değer ayarlamanız önerilmez, eğer sayfa yapısının yalnızca 'kabaca' öğelerini elde etmek istemiyorsanız. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | TextReplaceOptions nesnesini alır veya ayarlar. |
| [visit](#visit-com.aspose.pdf.Document-) | Belirtilen {@link Document} üzerinde bölümler ve paragraflar için arama gerçekleştirir. |
| [visit](#visit-com.aspose.pdf.Page-) | Belirtilen {@code Page} üzerinde arama gerçekleştirir. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sectionsSearchDepth |  | Yapılacak daha ince yapı elemanları için ardışık arama sayısı. <hr> Parametre hakkında daha fazla ipucu için {@code ParagraphAbsorber.SectionsSearchDepth} özelliğine bakın. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Belge veya sayfanın bölümlerini/paragraflarını arayan {@code ParagraphAbsorber} sınıfının yeni bir örneğini başlatır.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Emilen {@code PageMarkup} koleksiyonunu alır.

**Returns:**
PageMarkup örneklerinin listesi

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

ParagraphAbsorberOptions nesnesini alır.

**Returns:**
ParagraphAbsorberOptions örneği

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Yapısal daha ince öğeler için kaç kez ardışık arama yapılacağını belirten değeri alır veya ayarlar. Varsayılan arama derinliği 3'tür. Bu, yatay olarak bölünmüş bölümler (başlıklar, paragraflar vb.) için üç arama ve dikey olarak bölünmüş bölümler (sütunlar) için üç arama anlamına gelir. </p><hr> Bu değerin artırılması, arama sonuçlarında görünür bir değişiklik olmadan performansta hafif bir düşüşe yol açabilir. Bu değerin azaltılması, bölümlerdeki paragrafların yanlış belirlenmesine neden olabilir. Varsayılan değerden daha düşük bir değer ayarlamanız önerilmez, eğer sayfa yapısının yalnızca 'kabaca' öğelerini elde etmek istemiyorsanız.

**Returns:**
int değer

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

TextReplaceOptions nesnesini alır veya ayarlar.

**Returns:**
TextReplaceOptions örneği

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar.

**Returns:**
boolean değer

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
ParagraphAbsorberOptions nesnesini ayarlar.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Yapısal daha ince öğeler için kaç kez ardışık arama yapılacağını belirten değeri alır veya ayarlar. Varsayılan arama derinliği 3'tür. Bu, yatay olarak bölünmüş bölümler (başlıklar, paragraflar vb.) için üç arama ve dikey olarak bölünmüş bölümler (sütunlar) için üç arama anlamına gelir. </p><hr> Bu değerin artırılması, arama sonuçlarında görünür bir değişiklik olmadan performansta hafif bir düşüşe yol açabilir. Bu değerin azaltılması, bölümlerdeki paragrafların yanlış belirlenmesine neden olabilir. Varsayılan değerden daha düşük bir değer ayarlamanız önerilmez, eğer sayfa yapısının yalnızca 'kabaca' öğelerini elde etmek istemiyorsanız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
TextReplaceOptions nesnesini alır veya ayarlar.

### visit {#visit-com.aspose.pdf.Document-}
Belirtilen {@link Document} üzerinde bölümler ve paragraflar için arama gerçekleştirir.

### visit {#visit-com.aspose.pdf.Page-}
Belirtilen {@code Page} üzerinde arama gerçekleştirir.
