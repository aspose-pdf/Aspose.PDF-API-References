---
title: ITaggedContent
second_title: Aspose.PDF для справки по Java API
описание: Представляет собой интерфейс для работы с содержимым документа TaggedPdf.
тип: документы
вес: 11
URL-адрес: /java/com.aspose.pdf.tagged/itaggedcontent/
---```
публичный интерфейс ITaggedContent
```

Represents interface for work with TaggedPdf content of document.
## Methods

| Method | Description |
| --- | --- |
| [createAnnotElement()](#createAnnotElement--) | Creates [AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement). |
| [createArtElement()](#createArtElement--) | Creates [ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement). |
| [createBibEntryElement()](#createBibEntryElement--) | Creates [BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement). |
| [createBlockQuoteElement()](#createBlockQuoteElement--) | Creates [BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement). |
| [createCaptionElement()](#createCaptionElement--) | Creates [CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement). |
| [createCodeElement()](#createCodeElement--) | Creates [CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement). |
| [createDivElement()](#createDivElement--) | Creates [DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement). |
| [createFigureElement()](#createFigureElement--) | Creates [FigureElement](../../com.aspose.pdf/figureelement). |
| [createFormElement()](#createFormElement--) | Creates [FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement). |
| [createFormulaElement()](#createFormulaElement--) | Creates [FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement). |
| [createHeaderElement()](#createHeaderElement--) | Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement). |
| [createHeaderElement(int level)](#createHeaderElement-int-) | Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) with level. |
| [createIndexElement()](#createIndexElement--) | Creates [IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement). |
| [createLinkElement()](#createLinkElement--) | Creates [LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement). |
| [createListElement()](#createListElement--) | Creates [ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement). |
| [createNonStructElement()](#createNonStructElement--) | Creates [NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement). |
| [createNoteElement()](#createNoteElement--) | Creates [NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement). |
| [createParagraphElement()](#createParagraphElement--) | Creates [ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement). |
| [createPartElement()](#createPartElement--) | Creates [PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement). |
| [createPrivateElement()](#createPrivateElement--) | Creates [PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement). |
| [createQuoteElement()](#createQuoteElement--) | Creates [QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement). |
| [createReferenceElement()](#createReferenceElement--) | Creates [ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement). |
| [createRubyElement()](#createRubyElement--) | Creates [RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement). |
| [createSectElement()](#createSectElement--) | Creates [SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement). |
| [createSpanElement()](#createSpanElement--) | Creates [SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement). |
| [createTOCElement()](#createTOCElement--) | Creates [TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement). |
| [createTOCIElement()](#createTOCIElement--) | Creates [TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement). |
| [createTableElement()](#createTableElement--) | Creates [TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement). |
| [createTableTBodyElement()](#createTableTBodyElement--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTDElement()](#createTableTDElement--) | Creates [TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement). |
| [createTableTFootElement()](#createTableTFootElement--) | Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement). |
| [createTableTHElement()](#createTableTHElement--) | Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement). |
| [createTableTHeadElement()](#createTableTHeadElement--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTRElement()](#createTableTRElement--) | Creates [TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement). |
| [createWarichuElement()](#createWarichuElement--) | Creates [WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement). |
| [getRootElement()](#getRootElement--) | Gets root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document. |
| [getStructTreeRootElement()](#getStructTreeRootElement--) | Gets [StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) of PDF document. |
| [getStructureTextState()](#getStructureTextState--) | Get [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document. |
| [setLanguage(String lang)](#setLanguage-java.lang.String-) | Sets natural language for pdf document. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Sets title for PDF document. |
### createAnnotElement() {#createAnnotElement--}
```
открытый абстрактный AnnotElement createAnnotElement()
```


Creates [AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement).

**Returns:**
[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement) - Created structure element.
### createArtElement() {#createArtElement--}
```
общедоступный абстрактный ArtElement createArtElement()
```


Creates [ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement).

**Returns:**
[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement) - Created structure element.
### createBibEntryElement() {#createBibEntryElement--}
```
общедоступный абстрактный BibEntryElement createBibEntryElement()
```


Creates [BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement).

**Returns:**
[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement) - Created structure element.
### createBlockQuoteElement() {#createBlockQuoteElement--}
```
открытый абстрактный BlockQuoteElement createBlockQuoteElement()
```


Creates [BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement).

**Returns:**
[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement) - Created structure element.
### createCaptionElement() {#createCaptionElement--}
```
общедоступный абстрактный CaptionElement createCaptionElement()
```


Creates [CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement).

**Returns:**
[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement) - Created structure element.
### createCodeElement() {#createCodeElement--}
```
общедоступный абстрактный элемент кода createCodeElement()
```


Creates [CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement).

**Returns:**
[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement) - Created structure element.
### createDivElement() {#createDivElement--}
```
общедоступный абстрактный DivElement createDivElement()
```


Creates [DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement).

**Returns:**
[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement) - Created structure element.
### createFigureElement() {#createFigureElement--}
```
общедоступный абстрактный элемент FigureElement createFigureElement()
```


Creates [FigureElement](../../com.aspose.pdf/figureelement).

**Returns:**
[FigureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/figureelement) - Created structure element.
### createFormElement() {#createFormElement--}
```
общедоступный абстрактный элемент формы createFormElement()
```


Creates [FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement).

**Returns:**
[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement) - Created structure element.
### createFormulaElement() {#createFormulaElement--}
```
общедоступный абстрактный FormulaElement createFormulaElement()
```


Creates [FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement).

**Returns:**
[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement) - Created structure element.
### createHeaderElement() {#createHeaderElement--}
```
общедоступный абстрактный элемент заголовка createHeaderElement()
```


Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement).

**Returns:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Created structure element.
### createHeaderElement(int level) {#createHeaderElement-int-}
```
открытый абстрактный HeaderElement createHeaderElement (уровень int)
```


Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) with level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | The level of Header. Must be 1, 2, 3, 4, 5 or 6. |

**Returns:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Created structure element.
### createIndexElement() {#createIndexElement--}
```
открытый абстрактный IndexElement createIndexElement()
```


Creates [IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement).

**Returns:**
[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement) - Created structure element.
### createLinkElement() {#createLinkElement--}
```
общедоступный абстрактный LinkElement createLinkElement()
```


Creates [LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement).

**Returns:**
[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement) - Created structure element.
### createListElement() {#createListElement--}
```
общедоступный абстрактный ListElement createListElement()
```


Creates [ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement).

**Returns:**
[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement) - Created structure element.
### createNonStructElement() {#createNonStructElement--}
```
общедоступный абстрактный NonStructElement createNonStructElement()
```


Creates [NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement).

**Returns:**
[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement) - Created structure element.
### createNoteElement() {#createNoteElement--}
```
общедоступный абстрактный элемент NoteElement createNoteElement()
```


Creates [NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement).

**Returns:**
[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement) - Created structure element.
### createParagraphElement() {#createParagraphElement--}
```
общедоступный абстрактный ParagraphElement createParagraphElement()
```


Creates [ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement).

**Returns:**
[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement) - Created structure element.
### createPartElement() {#createPartElement--}
```
общедоступный абстрактный PartElement createPartElement()
```


Creates [PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement).

**Returns:**
[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement) - Created structure element.
### createPrivateElement() {#createPrivateElement--}
```
открытый абстрактный PrivateElement createPrivateElement()
```


Creates [PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement).

**Returns:**
[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement) - Created structure element.
### createQuoteElement() {#createQuoteElement--}
```
общедоступный абстрактный QuoteElement createQuoteElement()
```


Creates [QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement).

**Returns:**
[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement) - Created structure element.
### createReferenceElement() {#createReferenceElement--}
```
общедоступный абстрактный ReferenceElement createReferenceElement()
```


Creates [ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement).

**Returns:**
[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement) - Created structure element.
### createRubyElement() {#createRubyElement--}
```
публичный абстрактный RubyElement createRubyElement()
```


Creates [RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement).

**Returns:**
[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement) - Created structure element.
### createSectElement() {#createSectElement--}
```
общедоступный абстрактный элемент SectElement createSectElement()
```


Creates [SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement).

**Returns:**
[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement) - Created structure element.
### createSpanElement() {#createSpanElement--}
```
общедоступный абстрактный SpanElement createSpanElement()
```


Creates [SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement).

**Returns:**
[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement) - Created structure element.
### createTOCElement() {#createTOCElement--}
```
открытый абстрактный TOCElement createTOCElement()
```


Creates [TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement).

**Returns:**
[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement) - Created structure element.
### createTOCIElement() {#createTOCIElement--}
```
общедоступный абстрактный элемент TOCIElement createTOCIElement()
```


Creates [TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement).

**Returns:**
[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement) - Created structure element.
### createTableElement() {#createTableElement--}
```
общедоступный абстрактный TableElement createTableElement()
```


Creates [TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement).

**Returns:**
[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement) - Created structure element.
### createTableTBodyElement() {#createTableTBodyElement--}
```
общедоступный абстрактный TableTBodyElement createTableTBodyElement()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Returns:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Created structure element.
### createTableTDElement() {#createTableTDElement--}
```
общедоступный абстрактный TableTDElement createTableTDElement()
```


Creates [TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement).

**Returns:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Created structure element.
### createTableTFootElement() {#createTableTFootElement--}
```
открытый абстрактный TableTFootElement createTableTFootElement()
```


Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement).

**Returns:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Created structure element.
### createTableTHElement() {#createTableTHElement--}
```
общедоступный абстрактный TableTHElement createTableTHElement()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement).

**Returns:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Created structure element.
### createTableTHeadElement() {#createTableTHeadElement--}
```
общедоступный абстрактный TableTHeadElement createTableTHeadElement()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Returns:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Created structure element.
### createTableTRElement() {#createTableTRElement--}
```
общедоступный абстрактный TableTRElement createTableTRElement()
```


Creates [TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement).

**Returns:**
[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement) - Created structure element.
### createWarichuElement() {#createWarichuElement--}
```
открытый абстрактный WarichuElement createWarichuElement()
```


Creates [WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement).

**Returns:**
[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement) - Created structure element.
### getRootElement() {#getRootElement--}
```
открытый абстрактный StructureElement getRootElement()
```


Gets root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document.

**Returns:**
[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) - Root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document.
### getStructTreeRootElement() {#getStructTreeRootElement--}
```
открытый абстрактный StructTreeRootElement getStructTreeRootElement()
```


Gets [StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) of PDF document.

**Returns:**
[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) - StructTreeRootElement of PDF document.
### getStructureTextState() {#getStructureTextState--}
```
открытый абстрактный StructureTextState getStructureTextState()
```


Get [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - Value: [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document.
### setLanguage(String lang) {#setLanguage-java.lang.String-}
```
public abstract void setLanguage (String lang)
```


Sets natural language for pdf document.

A language identifier that shall specify the natural language for all text in the document except where overridden by language specifications for structure elements or marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lang | java.lang.String | A language identifier shall either be the empty text string, to indicate that the language is unknown, or a Language-Tag as defined in RFC 3066, Tags for the Identification of Languages. |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle (заголовок строки)
```


Sets title for PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title of PDF document. |
