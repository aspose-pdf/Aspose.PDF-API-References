---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar gränssnitt för arbete med TaggedPdf-innehåll i dokumentet."
type: docs
weight: 30
url: /sv/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Representerar gränssnitt för arbete med TaggedPdf-innehåll i dokumentet.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Skapar {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Skapar {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Skapar {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Skapar {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Skapar {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Skapar {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Skapar {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Skapar {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Skapar {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Skapar {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Skapar {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Skapar {@link HeaderElement} med nivå. |
| [createIndexElement](#createIndexElement--) | Skapar {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Skapar {@link LinkElement}. |
| [createListElement](#createListElement--) | Skapar {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Skapar {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Skapar {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Skapar {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Skapar {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Skapar {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Skapar {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Skapar {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Skapar {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Skapar {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Skapar {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Skapar {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Skapar {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Skapar {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Skapar {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Skapar {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Skapar {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Skapar {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Skapar {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Skapar {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Skapar {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Skapar {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Skapar {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Skapar {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Hämtar rot {@link StructureElement} av den logiska strukturen i PDF-dokumentet. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Hämtar {@link StructTreeRootElement} i PDF-dokumentet. |
| [getStructureTextState](#getStructureTextState--) | Hämta {@link StructureTextState}-inställningar för hela dokumentet. |
| [preSave](#preSave--) | Förbereder det taggade innehållet i dokumentet för sparande. Denna metod utför nödvändiga förhandsoperationer, och säkerställer att strukturträdet och andra taggade innehållselement är korrekt konfigurerade innan dokumentet sparas. |
| [save](#save--) | Sparar det aktuella tillståndet för det taggade innehållet till det associerade PDF-dokumentet. Denna metod säkerställer att alla taggade innehållselement är korrekt uppdaterade och sparade i PDF-dokumentet. Den utför nödvändiga operationer såsom att uppdatera MCID för MCR-element, ställa in BDC-operatorer och säkerställa efterlevnad av PDF/UA-standarder. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Hämtar naturligt språk för pdf-dokumentet. / * En språkidentifierare som ska specificera det naturliga språket för all text i dokumentet förutom där / * det åsidosätts av språksspecifikationer för strukturelement eller markerat innehåll. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Ställer in titel för PDF-dokumentet. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Skapar {@link AnnotElement}.

**Returns:**
Skapat strukturelement.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Skapar {@link ArtElement}.

**Returns:**
Skapat strukturelement.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Skapar {@link BibEntryElement}.

**Returns:**
Skapat strukturelement.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Skapar {@link BlockQuoteElement}.

**Returns:**
Skapat strukturelement.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Skapar {@link CaptionElement}.

**Returns:**
Skapat strukturelement.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Skapar {@link CodeElement}.

**Returns:**
Skapat strukturelement.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Skapar {@link DivElement}.

**Returns:**
Skapat strukturelement.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Skapar {@link FigureElement}.

**Returns:**
Skapat strukturelement.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Skapar {@link FormElement}.

**Returns:**
Skapat strukturelement.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Skapar {@link FormulaElement}.

**Returns:**
Skapat strukturelement.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Skapar {@link HeaderElement}.

**Returns:**
Skapat strukturelement.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Skapar {@link HeaderElement} med nivå.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nivå |  | Nivån för rubrik. Måste vara 1, 2, 3, 4, 5 eller 6. |

**Returns:**
Skapat strukturelement.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Skapar {@link IndexElement}.

**Returns:**
Skapat strukturelement.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Skapar {@link LinkElement}.

**Returns:**
Skapat strukturelement.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Skapar {@link ListElement}.

**Returns:**
Skapat strukturelement.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Skapar {@link ListLblElement}.

**Returns:**
Skapat strukturelement.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Skapar {@link ListLBodyElement}.

**Returns:**
Skapat strukturelement.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Skapar {@link ListLIElement}.

**Returns:**
Skapat strukturelement.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Skapar {@link NonStructElement}.

**Returns:**
Skapat strukturelement.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Skapar {@link NoteElement}.

**Returns:**
Skapat strukturelement.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Skapar {@link ParagraphElement}.

**Returns:**
Skapat strukturelement.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Skapar {@link PartElement}.

**Returns:**
Skapat strukturelement.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Skapar {@link PrivateElement}.

**Returns:**
Skapat strukturelement.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Skapar {@link QuoteElement}.

**Returns:**
Skapat strukturelement.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Skapar {@link ReferenceElement}.

**Returns:**
Skapat strukturelement.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Skapar {@link RubyElement}.

**Returns:**
Skapat strukturelement.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Skapar {@link SectElement}.

**Returns:**
Skapat strukturelement.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Skapar {@link SpanElement}.

**Returns:**
Skapat strukturelement.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Skapar {@link TableElement}.

**Returns:**
Skapat strukturelement.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Skapar {@link TableTHeadElement}.

**Returns:**
Skapat strukturelement.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Skapar {@link TableTDElement}.

**Returns:**
Skapat strukturelement.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Skapar {@link TableTFootElement}.

**Returns:**
Skapat strukturelement.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Skapar {@link TableTHeadElement}.

**Returns:**
Skapat strukturelement.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Skapar {@link TableTHElement}.

**Returns:**
Skapat strukturelement.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Skapar {@link TableTRElement}.

**Returns:**
Skapat strukturelement.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Skapar {@link TOCElement}.

**Returns:**
Skapat strukturelement.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Skapar {@link TOCIElement}.

**Returns:**
Skapat strukturelement.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Skapar {@link WarichuElement}.

**Returns:**
Skapat strukturelement.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Hämtar rot {@link StructureElement} av den logiska strukturen i PDF-dokumentet.

**Returns:**
Rot {@link StructureElement} av den logiska strukturen i PDF-dokumentet.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Hämtar {@link StructTreeRootElement} i PDF-dokumentet.

**Returns:**
StructTreeRootElement i PDF-dokumentet.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Hämta {@link StructureTextState}-inställningar för hela dokumentet.

**Returns:**
Värde: {@link StructureTextState}-inställningar för hela dokumentet.

### preSave {#preSave--}
```
void preSave()
```

Förbereder det taggade innehållet i dokumentet för sparande. Denna metod utför nödvändiga förhandsoperationer, och säkerställer att strukturträdet och andra taggade innehållselement är korrekt konfigurerade innan dokumentet sparas.

### save {#save--}
```
void save()
```

Sparar det aktuella tillståndet för det taggade innehållet till det associerade PDF-dokumentet. Denna metod säkerställer att alla taggade innehållselement är korrekt uppdaterade och sparade i PDF-dokumentet. Den utför nödvändiga operationer såsom att uppdatera MCID för MCR-element, ställa in BDC-operatorer och säkerställa efterlevnad av PDF/UA-standarder.

### setLanguage {#setLanguage-java.lang.String-}
/ * Hämtar naturligt språk för pdf-dokumentet. / * En språkidentifierare som ska specificera det naturliga språket för all text i dokumentet förutom där / * det åsidosätts av språksspecifikationer för strukturelement eller markerat innehåll. / * / *

### setTitle {#setTitle-java.lang.String-}
Ställer in titel för PDF-dokumentet.
