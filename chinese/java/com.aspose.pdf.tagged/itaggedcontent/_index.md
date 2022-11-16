---
标题：ITaggedContent
second_title: Aspose.PDF for Java API 参考
描述：表示处理文档的 TaggedPdf 内容的接口。
类型：文档
体重：11
网址：/java/com.aspose.pdf.tagged/itaggedcontent/
---```
公共接口 ITaggedContent
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
公共抽象 AnnotElement createAnnotElement()
```


Creates [AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement).

**Returns:**
[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement) - Created structure element.
### createArtElement() {#createArtElement--}
```
公共抽象 ArtElement createArtElement()
```


Creates [ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement).

**Returns:**
[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement) - Created structure element.
### createBibEntryElement() {#createBibEntryElement--}
```
公共抽象 BibEntryElement createBibEntryElement()
```


Creates [BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement).

**Returns:**
[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement) - Created structure element.
### createBlockQuoteElement() {#createBlockQuoteElement--}
```
公共抽象 BlockQuoteElement createBlockQuoteElement()
```


Creates [BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement).

**Returns:**
[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement) - Created structure element.
### createCaptionElement() {#createCaptionElement--}
```
公共抽象标题元素 createCaptionElement()
```


Creates [CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement).

**Returns:**
[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement) - Created structure element.
### createCodeElement() {#createCodeElement--}
```
公共抽象 CodeElement createCodeElement()
```


Creates [CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement).

**Returns:**
[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement) - Created structure element.
### createDivElement() {#createDivElement--}
```
公共抽象 DivElement createDivElement()
```


Creates [DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement).

**Returns:**
[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement) - Created structure element.
### createFigureElement() {#createFigureElement--}
```
公共抽象 FigureElement createFigureElement()
```


Creates [FigureElement](../../com.aspose.pdf/figureelement).

**Returns:**
[FigureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/figureelement) - Created structure element.
### createFormElement() {#createFormElement--}
```
公共抽象 FormElement createFormElement()
```


Creates [FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement).

**Returns:**
[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement) - Created structure element.
### createFormulaElement() {#createFormulaElement--}
```
公共抽象 FormulaElement createFormulaElement()
```


Creates [FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement).

**Returns:**
[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement) - Created structure element.
### createHeaderElement() {#createHeaderElement--}
```
公共抽象 HeaderElement createHeaderElement()
```


Creates [HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement).

**Returns:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Created structure element.
### createHeaderElement(int level) {#createHeaderElement-int-}
```
公共抽象 HeaderElement createHeaderElement(int level)
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
公共抽象索引元素 createIndexElement()
```


Creates [IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement).

**Returns:**
[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement) - Created structure element.
### createLinkElement() {#createLinkElement--}
```
公共抽象 LinkElement createLinkElement()
```


Creates [LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement).

**Returns:**
[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement) - Created structure element.
### createListElement() {#createListElement--}
```
公共抽象 ListElement createListElement()
```


Creates [ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement).

**Returns:**
[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement) - Created structure element.
### createNonStructElement() {#createNonStructElement--}
```
公共抽象 NonStructElement createNonStructElement()
```


Creates [NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement).

**Returns:**
[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement) - Created structure element.
### createNoteElement() {#createNoteElement--}
```
公共抽象 NoteElement createNoteElement()
```


Creates [NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement).

**Returns:**
[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement) - Created structure element.
### createParagraphElement() {#createParagraphElement--}
```
公共抽象段落元素 createParagraphElement()
```


Creates [ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement).

**Returns:**
[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement) - Created structure element.
### createPartElement() {#createPartElement--}
```
公共抽象 PartElement createPartElement()
```


Creates [PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement).

**Returns:**
[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement) - Created structure element.
### createPrivateElement() {#createPrivateElement--}
```
公共抽象 PrivateElement createPrivateElement()
```


Creates [PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement).

**Returns:**
[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement) - Created structure element.
### createQuoteElement() {#createQuoteElement--}
```
公共抽象 QuoteElement createQuoteElement()
```


Creates [QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement).

**Returns:**
[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement) - Created structure element.
### createReferenceElement() {#createReferenceElement--}
```
公共抽象 ReferenceElement createReferenceElement()
```


Creates [ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement).

**Returns:**
[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement) - Created structure element.
### createRubyElement() {#createRubyElement--}
```
公共抽象 RubyElement createRubyElement()
```


Creates [RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement).

**Returns:**
[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement) - Created structure element.
### createSectElement() {#createSectElement--}
```
公共抽象 SectElement createSectElement()
```


Creates [SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement).

**Returns:**
[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement) - Created structure element.
### createSpanElement() {#createSpanElement--}
```
公共抽象 SpanElement createSpanElement()
```


Creates [SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement).

**Returns:**
[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement) - Created structure element.
### createTOCElement() {#createTOCElement--}
```
公共抽象 TOCElement createTOCElement()
```


Creates [TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement).

**Returns:**
[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement) - Created structure element.
### createTOCIElement() {#createTOCIElement--}
```
公共抽象 TOCIElement createTOCIElement()
```


Creates [TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement).

**Returns:**
[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement) - Created structure element.
### createTableElement() {#createTableElement--}
```
公共抽象 TableElement createTableElement()
```


Creates [TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement).

**Returns:**
[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement) - Created structure element.
### createTableTBodyElement() {#createTableTBodyElement--}
```
公共抽象 TableTBodyElement createTableTBodyElement()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Returns:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Created structure element.
### createTableTDElement() {#createTableTDElement--}
```
公共抽象 TableTDElement createTableTDElement()
```


Creates [TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement).

**Returns:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Created structure element.
### createTableTFootElement() {#createTableTFootElement--}
```
公共抽象 TableTFootElement createTableTFootElement()
```


Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement).

**Returns:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Created structure element.
### createTableTHElement() {#createTableTHElement--}
```
公共抽象 TableTHElement createTableTHElement()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement).

**Returns:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Created structure element.
### createTableTHeadElement() {#createTableTHeadElement--}
```
公共抽象 TableTHeadElement createTableTHeadElement()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Returns:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Created structure element.
### createTableTRElement() {#createTableTRElement--}
```
公共抽象 TableTRElement createTableTRElement()
```


Creates [TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement).

**Returns:**
[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement) - Created structure element.
### createWarichuElement() {#createWarichuElement--}
```
公共抽象 WarichuElement createWarichuElement()
```


Creates [WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement).

**Returns:**
[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement) - Created structure element.
### getRootElement() {#getRootElement--}
```
公共抽象结构元素 getRootElement()
```


Gets root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document.

**Returns:**
[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) - Root [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) of logical structure of PDF document.
### getStructTreeRootElement() {#getStructTreeRootElement--}
```
公共抽象 StructTreeRootElement getStructTreeRootElement()
```


Gets [StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) of PDF document.

**Returns:**
[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) - StructTreeRootElement of PDF document.
### getStructureTextState() {#getStructureTextState--}
```
公共抽象 StructureTextState getStructureTextState()
```


Get [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - Value: [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) settings for whole document.
### setLanguage(String lang) {#setLanguage-java.lang.String-}
```
public abstract void setLanguage(字符串语言)
```


Sets natural language for pdf document.

A language identifier that shall specify the natural language for all text in the document except where overridden by language specifications for structure elements or marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lang | java.lang.String | A language identifier shall either be the empty text string, to indicate that the language is unknown, or a Language-Tag as defined in RFC 3066, Tags for the Identification of Languages. |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(字符串标题)
```


Sets title for PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title of PDF document. |
