---
title: ITaggedContent
linktitle: ITaggedContent
second_title: Aspose.PDF for Java API Reference
description: Represents interface for work with TaggedPdf content of document.
type: docs
weight: 30
url: /java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Represents interface for work with TaggedPdf content of document.

## Methods

| Method | Description |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Creates {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Creates {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Creates {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Creates {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Creates {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Creates {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Creates {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Creates {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Creates {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Creates {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Creates {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Creates {@link HeaderElement} with level. |
| [createIndexElement](#createIndexElement--) | Creates {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Creates {@link LinkElement}. |
| [createListElement](#createListElement--) | Creates {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Creates {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Creates {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Creates {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Creates {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Creates {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Creates {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Creates {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Creates {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Creates {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Creates {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Creates {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Creates {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Creates {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Creates {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Creates {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Creates {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Creates {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Creates {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Creates {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Creates {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Creates {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Creates {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Creates {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Gets root {@link StructureElement} of logical structure of PDF document. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Gets {@link StructTreeRootElement} of PDF document. |
| [getStructureTextState](#getStructureTextState--) | Get {@link StructureTextState} settings for whole document. |
| [preSave](#preSave--) | Prepares the tagged content of the document for saving. This method performs necessary pre-save operations, ensuring that the structure tree and other tagged content elements are properly configured before the document is saved. |
| [save](#save--) | Saves the current state of the tagged content to the associated PDF document. This method ensures that all tagged content elements are properly updated and saved within the PDF document. It performs necessary operations such as updating MCID for MCR elements, setting BDC operators, and ensuring compliance with PDF/UA standards. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Gets natural language for pdf document. / * A language identifier that shall specify the natural language for all text in the document except where / * overridden by language specifications for structure elements or marked content. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Sets title for PDF document. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Creates {@link AnnotElement}.

**Returns:**
Created structure element.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Creates {@link ArtElement}.

**Returns:**
Created structure element.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Creates {@link BibEntryElement}.

**Returns:**
Created structure element.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Creates {@link BlockQuoteElement}.

**Returns:**
Created structure element.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Creates {@link CaptionElement}.

**Returns:**
Created structure element.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Creates {@link CodeElement}.

**Returns:**
Created structure element.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Creates {@link DivElement}.

**Returns:**
Created structure element.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Creates {@link FigureElement}.

**Returns:**
Created structure element.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Creates {@link FormElement}.

**Returns:**
Created structure element.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Creates {@link FormulaElement}.

**Returns:**
Created structure element.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Creates {@link HeaderElement}.

**Returns:**
Created structure element.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Creates {@link HeaderElement} with level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level |  | The level of Header. Must be 1, 2, 3, 4, 5 or 6. |

**Returns:**
Created structure element.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Creates {@link IndexElement}.

**Returns:**
Created structure element.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Creates {@link LinkElement}.

**Returns:**
Created structure element.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Creates {@link ListElement}.

**Returns:**
Created structure element.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Creates {@link ListLblElement}.

**Returns:**
Created structure element.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Creates {@link ListLBodyElement}.

**Returns:**
Created structure element.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Creates {@link ListLIElement}.

**Returns:**
Created structure element.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Creates {@link NonStructElement}.

**Returns:**
Created structure element.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Creates {@link NoteElement}.

**Returns:**
Created structure element.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Creates {@link ParagraphElement}.

**Returns:**
Created structure element.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Creates {@link PartElement}.

**Returns:**
Created structure element.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Creates {@link PrivateElement}.

**Returns:**
Created structure element.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Creates {@link QuoteElement}.

**Returns:**
Created structure element.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Creates {@link ReferenceElement}.

**Returns:**
Created structure element.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Creates {@link RubyElement}.

**Returns:**
Created structure element.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Creates {@link SectElement}.

**Returns:**
Created structure element.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Creates {@link SpanElement}.

**Returns:**
Created structure element.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Creates {@link TableElement}.

**Returns:**
Created structure element.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Creates {@link TableTHeadElement}.

**Returns:**
Created structure element.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Creates {@link TableTDElement}.

**Returns:**
Created structure element.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Creates {@link TableTFootElement}.

**Returns:**
Created structure element.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Creates {@link TableTHeadElement}.

**Returns:**
Created structure element.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Creates {@link TableTHElement}.

**Returns:**
Created structure element.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Creates {@link TableTRElement}.

**Returns:**
Created structure element.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Creates {@link TOCElement}.

**Returns:**
Created structure element.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Creates {@link TOCIElement}.

**Returns:**
Created structure element.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Creates {@link WarichuElement}.

**Returns:**
Created structure element.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Gets root {@link StructureElement} of logical structure of PDF document.

**Returns:**
Root {@link StructureElement} of logical structure of PDF document.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Gets {@link StructTreeRootElement} of PDF document.

**Returns:**
StructTreeRootElement of PDF document.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Get {@link StructureTextState} settings for whole document.

**Returns:**
Value: {@link StructureTextState} settings for whole document.

### preSave {#preSave--}
```
void preSave()
```

Prepares the tagged content of the document for saving. This method performs necessary pre-save operations, ensuring that the structure tree and other tagged content elements are properly configured before the document is saved.

### save {#save--}
```
void save()
```

Saves the current state of the tagged content to the associated PDF document. This method ensures that all tagged content elements are properly updated and saved within the PDF document. It performs necessary operations such as updating MCID for MCR elements, setting BDC operators, and ensuring compliance with PDF/UA standards.

### setLanguage {#setLanguage-java.lang.String-}
/ * Gets natural language for pdf document. / * A language identifier that shall specify the natural language for all text in the document except where / * overridden by language specifications for structure elements or marked content. / * / *

### setTitle {#setTitle-java.lang.String-}
Sets title for PDF document.
