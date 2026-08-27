---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Aspose.PDF for Java API Referansı"
description: "Belgenin TaggedPdf içeriğiyle çalışmak için arabirimi temsil eder."
type: docs
weight: 30
url: /tr/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Belgenin TaggedPdf içeriğiyle çalışmak için arabirimi temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Oluşturur {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Oluşturur {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Oluşturur {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Oluşturur {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Oluşturur {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Oluşturur {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Oluşturur {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Oluşturur {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Oluşturur {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Oluşturur {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Oluşturur {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Oluşturur {@link HeaderElement} seviye ile. |
| [createIndexElement](#createIndexElement--) | Oluşturur {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Oluşturur {@link LinkElement}. |
| [createListElement](#createListElement--) | Oluşturur {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Oluşturur {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Oluşturur {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Oluşturur {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Oluşturur {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Oluşturur {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Oluşturur {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Oluşturur {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Oluşturur {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Oluşturur {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Oluşturur {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Oluşturur {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Oluşturur {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Oluşturur {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Oluşturur {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Oluşturur {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Oluşturur {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Oluşturur {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Oluşturur {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Oluşturur {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Oluşturur {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Oluşturur {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Oluşturur {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Oluşturur {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | PDF belgesinin mantıksal yapısının kök {@link StructureElement} öğesini alır. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | PDF belgesinin {@link StructTreeRootElement} öğesini alır. |
| [getStructureTextState](#getStructureTextState--) | {@link StructureTextState} ayarlarını tüm belge için alır. |
| [preSave](#preSave--) | Belgenin etiketli içeriğini kaydetmek için hazırlar. Bu yöntem, yapı ağacının ve diğer etiketli içerik öğelerinin belge kaydedilmeden önce doğru şekilde yapılandırılmasını sağlayarak gerekli ön kaydetme işlemlerini gerçekleştirir. |
| [save](#save--) | Etiketli içeriğin mevcut durumunu ilişkili PDF belgesine kaydeder. Bu yöntem, tüm etiketli içerik öğelerinin PDF belgesi içinde doğru şekilde güncellenip kaydedildiğinden emin olur. MCID'yi MCR öğeleri için güncelleme, BDC operatörlerini ayarlama ve PDF/UA standartlarına uyumu sağlama gibi gerekli işlemleri gerçekleştirir. |
| [setLanguage](#setLanguage-java.lang.String-) | / * PDF belgesi için doğal dili alır. / * Tüm belgedeki metin için doğal dili belirleyecek bir dil tanımlayıcısıdır, ancak yapı öğeleri veya işaretli içerik için dil tanımlamalarıyla geçersiz kılınmadıkça. / * / * |
| [setTitle](#setTitle-java.lang.String-) | PDF belgesi için başlık ayarlar. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Oluşturur {@link AnnotElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Oluşturur {@link ArtElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Oluşturur {@link BibEntryElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Oluşturur {@link BlockQuoteElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Oluşturur {@link CaptionElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Oluşturur {@link CodeElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Oluşturur {@link DivElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Oluşturur {@link FigureElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Oluşturur {@link FormElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Oluşturur {@link FormulaElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Oluşturur {@link HeaderElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Oluşturur {@link HeaderElement} seviye ile.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seviye |  | Başlık seviyesi. 1, 2, 3, 4, 5 veya 6 olmalıdır. |

**Returns:**
Yapı öğesi oluşturuldu.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Oluşturur {@link IndexElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Oluşturur {@link LinkElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Oluşturur {@link ListElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Oluşturur {@link ListLblElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Oluşturur {@link ListLBodyElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Oluşturur {@link ListLIElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Oluşturur {@link NonStructElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Oluşturur {@link NoteElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Oluşturur {@link ParagraphElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Oluşturur {@link PartElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Oluşturur {@link PrivateElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Oluşturur {@link QuoteElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Oluşturur {@link ReferenceElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Oluşturur {@link RubyElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Oluşturur {@link SectElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Oluşturur {@link SpanElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Oluşturur {@link TableElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Oluşturur {@link TableTHeadElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Oluşturur {@link TableTDElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Oluşturur {@link TableTFootElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Oluşturur {@link TableTHeadElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Oluşturur {@link TableTHElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Oluşturur {@link TableTRElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Oluşturur {@link TOCElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Oluşturur {@link TOCIElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Oluşturur {@link WarichuElement}.

**Returns:**
Yapı öğesi oluşturuldu.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

PDF belgesinin mantıksal yapısının kök {@link StructureElement} öğesini alır.

**Returns:**
PDF belgesinin mantıksal yapısının kök {@link StructureElement} öğesi.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

PDF belgesinin {@link StructTreeRootElement} öğesini alır.

**Returns:**
PDF belgesinin StructTreeRootElement öğesi.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

{@link StructureTextState} ayarlarını tüm belge için alır.

**Returns:**
Değer: Tüm belge için {@link StructureTextState} ayarları.

### preSave {#preSave--}
```
void preSave()
```

Belgenin etiketli içeriğini kaydetmek için hazırlar. Bu yöntem, yapı ağacının ve diğer etiketli içerik öğelerinin belge kaydedilmeden önce doğru şekilde yapılandırılmasını sağlayarak gerekli ön kaydetme işlemlerini gerçekleştirir.

### save {#save--}
```
void save()
```

Etiketli içeriğin mevcut durumunu ilişkili PDF belgesine kaydeder. Bu yöntem, tüm etiketli içerik öğelerinin PDF belgesi içinde doğru şekilde güncellenip kaydedildiğinden emin olur. MCID'yi MCR öğeleri için güncelleme, BDC operatörlerini ayarlama ve PDF/UA standartlarına uyumu sağlama gibi gerekli işlemleri gerçekleştirir.

### setLanguage {#setLanguage-java.lang.String-}
/ * PDF belgesi için doğal dili alır. / * Tüm belgedeki metin için doğal dili belirleyecek bir dil tanımlayıcısıdır, ancak yapı öğeleri veya işaretli içerik için dil tanımlamalarıyla geçersiz kılınmadıkça. / * / *

### setTitle {#setTitle-java.lang.String-}
PDF belgesi için başlık ayarlar.
