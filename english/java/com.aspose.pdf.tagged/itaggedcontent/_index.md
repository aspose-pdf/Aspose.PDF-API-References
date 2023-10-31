---
title: ITaggedContent
second_title: Aspose.PDF for Java API Reference
description: Represents interface for work with TaggedPdf content of document.
type: docs
weight: 12
url: /java/com.aspose.pdf.tagged/itaggedcontent/
---```
public interface ITaggedContent
```

Represents interface for work with TaggedPdf content of document.
## Methods

| Method | Description |
| --- | --- |
| [getStructureTextState()](#getStructureTextState--) | Get [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document. |
| [getStructTreeRootElement()](#getStructTreeRootElement--) | Gets [StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) of PDF document. |
| [getRootElement()](#getRootElement--) | Gets root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document. |
| [setLanguage(String lang)](#setLanguage-java.lang.String-) | Sets natural language for pdf document. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Sets title for PDF document. |
| [createPartElement()](#createPartElement--) | Creates [PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement). |
| [createArtElement()](#createArtElement--) | Creates [ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement). |
| [createSectElement()](#createSectElement--) | Creates [SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement). |
| [createDivElement()](#createDivElement--) | Creates [DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement). |
| [createBlockQuoteElement()](#createBlockQuoteElement--) | Creates [BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement). |
| [createCaptionElement()](#createCaptionElement--) | Creates [CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement). |
| [createTOCElement()](#createTOCElement--) | Creates [TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement). |
| [createTOCIElement()](#createTOCIElement--) | Creates [TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement). |
| [createIndexElement()](#createIndexElement--) | Creates [IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement). |
| [createNonStructElement()](#createNonStructElement--) | Creates [NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement). |
| [createPrivateElement()](#createPrivateElement--) | Creates [PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement). |
| [createParagraphElement()](#createParagraphElement--) | Creates [ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement). |
| [createHeaderElement()](#createHeaderElement--) | Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement). |
| [createHeaderElement(int level)](#createHeaderElement-int-) | Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) with level. |
| [createListElement()](#createListElement--) | Creates [ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement). |
| [createTableElement()](#createTableElement--) | Creates [TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement). |
| [createTableTHeadElement()](#createTableTHeadElement--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTBodyElement()](#createTableTBodyElement--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTFootElement()](#createTableTFootElement--) | Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement). |
| [createTableTRElement()](#createTableTRElement--) | Creates [TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement). |
| [createTableTHElement()](#createTableTHElement--) | Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement). |
| [createTableTDElement()](#createTableTDElement--) | Creates [TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement). |
| [createSpanElement()](#createSpanElement--) | Creates [SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement). |
| [createQuoteElement()](#createQuoteElement--) | Creates [QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement). |
| [createNoteElement()](#createNoteElement--) | Creates [NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement). |
| [createReferenceElement()](#createReferenceElement--) | Creates [ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement). |
| [createBibEntryElement()](#createBibEntryElement--) | Creates [BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement). |
| [createCodeElement()](#createCodeElement--) | Creates [CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement). |
| [createLinkElement()](#createLinkElement--) | Creates [LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement). |
| [createAnnotElement()](#createAnnotElement--) | Creates [AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement). |
| [createRubyElement()](#createRubyElement--) | Creates [RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement). |
| [createWarichuElement()](#createWarichuElement--) | Creates [WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement). |
| [createFigureElement()](#createFigureElement--) | Creates [FigureElement](../../com.aspose.pdf/figureelement). |
| [createFormulaElement()](#createFormulaElement--) | Creates [FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement). |
| [createFormElement()](#createFormElement--) | Creates [FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement). |
### getStructureTextState() {#getStructureTextState--}
```
public abstract StructureTextState getStructureTextState()
```


Get [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - Value: [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document.
### getStructTreeRootElement() {#getStructTreeRootElement--}
```
public abstract StructTreeRootElement getStructTreeRootElement()
```


Gets [StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) of PDF document.

**Returns:**
[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) - StructTreeRootElement of PDF document.
### getRootElement() {#getRootElement--}
```
public abstract StructureElement getRootElement()
```


Gets root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document.

**Returns:**
[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) - Root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document.
### setLanguage(String lang) {#setLanguage-java.lang.String-}
```
public abstract void setLanguage(String lang)
```


Sets natural language for pdf document.

A language identifier that shall specify the natural language for all text in the document except where overridden by language specifications for structure elements or marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lang | java.lang.String | A language identifier shall either be the empty text string, to indicate that the language is unknown, or a Language-Tag as defined in RFC 3066, Tags for the Identification of Languages. |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String title)
```


Sets title for PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title of PDF document. |

### createPartElement() {#createPartElement--}
```
public abstract PartElement createPartElement()
```


Creates [PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement).

**Returns:**
[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement) - Created structure element.
### createArtElement() {#createArtElement--}
```
public abstract ArtElement createArtElement()
```


Creates [ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement).

**Returns:**
[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement) - Created structure element.
### createSectElement() {#createSectElement--}
```
public abstract SectElement createSectElement()
```


Creates [SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement).

**Returns:**
[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement) - Created structure element.
### createDivElement() {#createDivElement--}
```
public abstract DivElement createDivElement()
```


Creates [DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement).

**Returns:**
[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement) - Created structure element.
### createBlockQuoteElement() {#createBlockQuoteElement--}
```
public abstract BlockQuoteElement createBlockQuoteElement()
```


Creates [BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement).

**Returns:**
[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement) - Created structure element.
### createCaptionElement() {#createCaptionElement--}
```
public abstract CaptionElement createCaptionElement()
```


Creates [CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement).

**Returns:**
[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement) - Created structure element.
### createTOCElement() {#createTOCElement--}
```
public abstract TOCElement createTOCElement()
```


Creates [TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement).

**Returns:**
[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement) - Created structure element.
### createTOCIElement() {#createTOCIElement--}
```
public abstract TOCIElement createTOCIElement()
```


Creates [TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement).

**Returns:**
[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement) - Created structure element.
### createIndexElement() {#createIndexElement--}
```
public abstract IndexElement createIndexElement()
```


Creates [IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement).

**Returns:**
[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement) - Created structure element.
### createNonStructElement() {#createNonStructElement--}
```
public abstract NonStructElement createNonStructElement()
```


Creates [NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement).

**Returns:**
[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement) - Created structure element.
### createPrivateElement() {#createPrivateElement--}
```
public abstract PrivateElement createPrivateElement()
```


Creates [PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement).

**Returns:**
[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement) - Created structure element.
### createParagraphElement() {#createParagraphElement--}
```
public abstract ParagraphElement createParagraphElement()
```


Creates [ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement).

**Returns:**
[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement) - Created structure element.
### createHeaderElement() {#createHeaderElement--}
```
public abstract HeaderElement createHeaderElement()
```


Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement).

**Returns:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Created structure element.
### createHeaderElement(int level) {#createHeaderElement-int-}
```
public abstract HeaderElement createHeaderElement(int level)
```


Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) with level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | The level of Header. Must be 1, 2, 3, 4, 5 or 6. |

**Returns:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Created structure element.
### createListElement() {#createListElement--}
```
public abstract ListElement createListElement()
```


Creates [ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement).

**Returns:**
[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement) - Created structure element.
### createTableElement() {#createTableElement--}
```
public abstract TableElement createTableElement()
```


Creates [TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement).

**Returns:**
[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement) - Created structure element.
### createTableTHeadElement() {#createTableTHeadElement--}
```
public abstract TableTHeadElement createTableTHeadElement()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Returns:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Created structure element.
### createTableTBodyElement() {#createTableTBodyElement--}
```
public abstract TableTBodyElement createTableTBodyElement()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Returns:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Created structure element.
### createTableTFootElement() {#createTableTFootElement--}
```
public abstract TableTFootElement createTableTFootElement()
```


Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement).

**Returns:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Created structure element.
### createTableTRElement() {#createTableTRElement--}
```
public abstract TableTRElement createTableTRElement()
```


Creates [TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement).

**Returns:**
[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement) - Created structure element.
### createTableTHElement() {#createTableTHElement--}
```
public abstract TableTHElement createTableTHElement()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement).

**Returns:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Created structure element.
### createTableTDElement() {#createTableTDElement--}
```
public abstract TableTDElement createTableTDElement()
```


Creates [TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement).

**Returns:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Created structure element.
### createSpanElement() {#createSpanElement--}
```
public abstract SpanElement createSpanElement()
```


Creates [SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement).

**Returns:**
[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement) - Created structure element.
### createQuoteElement() {#createQuoteElement--}
```
public abstract QuoteElement createQuoteElement()
```


Creates [QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement).

**Returns:**
[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement) - Created structure element.
### createNoteElement() {#createNoteElement--}
```
public abstract NoteElement createNoteElement()
```


Creates [NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement).

**Returns:**
[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement) - Created structure element.
### createReferenceElement() {#createReferenceElement--}
```
public abstract ReferenceElement createReferenceElement()
```


Creates [ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement).

**Returns:**
[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement) - Created structure element.
### createBibEntryElement() {#createBibEntryElement--}
```
public abstract BibEntryElement createBibEntryElement()
```


Creates [BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement).

**Returns:**
[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement) - Created structure element.
### createCodeElement() {#createCodeElement--}
```
public abstract CodeElement createCodeElement()
```


Creates [CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement).

**Returns:**
[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement) - Created structure element.
### createLinkElement() {#createLinkElement--}
```
public abstract LinkElement createLinkElement()
```


Creates [LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement).

**Returns:**
[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement) - Created structure element.
### createAnnotElement() {#createAnnotElement--}
```
public abstract AnnotElement createAnnotElement()
```


Creates [AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement).

**Returns:**
[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement) - Created structure element.
### createRubyElement() {#createRubyElement--}
```
public abstract RubyElement createRubyElement()
```


Creates [RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement).

**Returns:**
[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement) - Created structure element.
### createWarichuElement() {#createWarichuElement--}
```
public abstract WarichuElement createWarichuElement()
```


Creates [WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement).

**Returns:**
[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement) - Created structure element.
### createFigureElement() {#createFigureElement--}
```
public abstract FigureElement createFigureElement()
```


Creates [FigureElement](../../com.aspose.pdf/figureelement).

**Returns:**
[FigureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/figureelement) - Created structure element.
### createFormulaElement() {#createFormulaElement--}
```
public abstract FormulaElement createFormulaElement()
```


Creates [FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement).

**Returns:**
[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement) - Created structure element.
### createFormElement() {#createFormElement--}
```
public abstract FormElement createFormElement()
```


Creates [FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement).

**Returns:**
[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement) - Created structure element.
