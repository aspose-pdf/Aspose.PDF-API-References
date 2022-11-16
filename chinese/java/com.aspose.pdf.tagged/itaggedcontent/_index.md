---
title: ITaggedContent
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示用于处理文档的 TaggedPdf 内容的接口。
type: docs
weight: 11
url: /zh/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

表示用于处理文档的 TaggedPdf 内容的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [createAnnotElement()](#createAnnotElement--) | 创造[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement). |
| [createArtElement()](#createArtElement--) | 创造[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement). |
| [createBibEntryElement()](#createBibEntryElement--) | 创造[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement). |
| [createBlockQuoteElement()](#createBlockQuoteElement--) | 创造[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement). |
| [createCaptionElement()](#createCaptionElement--) | 创造[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement). |
| [createCodeElement()](#createCodeElement--) | 创造[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement). |
| [createDivElement()](#createDivElement--) | 创造[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement). |
| [createFigureElement()](#createFigureElement--) | 创造[FigureElement](../../com.aspose.pdf/figureelement). |
| [createFormElement()](#createFormElement--) | 创造[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement). |
| [createFormulaElement()](#createFormulaElement--) | 创造[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement). |
| [createHeaderElement()](#createHeaderElement--) | 创造[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement). |
| [createHeaderElement(int level)](#createHeaderElement-int-) | 创造[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement)与水平。 |
| [createIndexElement()](#createIndexElement--) | 创造[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement). |
| [createLinkElement()](#createLinkElement--) | 创造[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement). |
| [createListElement()](#createListElement--) | 创造[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement). |
| [createNonStructElement()](#createNonStructElement--) | 创造[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement). |
| [createNoteElement()](#createNoteElement--) | 创造[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement). |
| [createParagraphElement()](#createParagraphElement--) | 创造[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement). |
| [createPartElement()](#createPartElement--) | 创造[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement). |
| [createPrivateElement()](#createPrivateElement--) | 创造[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement). |
| [createQuoteElement()](#createQuoteElement--) | 创造[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement). |
| [createReferenceElement()](#createReferenceElement--) | 创造[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement). |
| [createRubyElement()](#createRubyElement--) | 创造[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement). |
| [createSectElement()](#createSectElement--) | 创造[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement). |
| [createSpanElement()](#createSpanElement--) | 创造[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement). |
| [createTOCElement()](#createTOCElement--) | 创造[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement). |
| [createTOCIElement()](#createTOCIElement--) | 创造[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement). |
| [createTableElement()](#createTableElement--) | 创造[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement). |
| [createTableTBodyElement()](#createTableTBodyElement--) | 创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTDElement()](#createTableTDElement--) | 创造[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement). |
| [createTableTFootElement()](#createTableTFootElement--) | 创造[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement). |
| [createTableTHElement()](#createTableTHElement--) | 创造[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement). |
| [createTableTHeadElement()](#createTableTHeadElement--) | 创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTRElement()](#createTableTRElement--) | 创造[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement). |
| [createWarichuElement()](#createWarichuElement--) | 创造[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement). |
| [getRootElement()](#getRootElement--) | 获得根[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement)PDF文档的逻辑结构。 |
| [getStructTreeRootElement()](#getStructTreeRootElement--) | 得到[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement)的PDF文件。 |
| [getStructureTextState()](#getStructureTextState--) | 得到[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate)整个文档的设置。 |
| [setLanguage(String lang)](#setLanguage-java.lang.String-) | 为 pdf 文档设置自然语言。 |
| [setTitle(String title)](#setTitle-java.lang.String-) | 设置 PDF 文档的标题。 |
### createAnnotElement() {#createAnnotElement--}
```
public abstract AnnotElement createAnnotElement()
```


创造[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement).

**退货：**
[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement) - 创建结构元素。
### createArtElement() {#createArtElement--}
```
public abstract ArtElement createArtElement()
```


创造[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement).

**退货：**
[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement) - 创建结构元素。
### createBibEntryElement() {#createBibEntryElement--}
```
public abstract BibEntryElement createBibEntryElement()
```


创造[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement).

**退货：**
[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement) - 创建结构元素。
### createBlockQuoteElement() {#createBlockQuoteElement--}
```
public abstract BlockQuoteElement createBlockQuoteElement()
```


创造[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement).

**退货：**
[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement) - 创建结构元素。
### createCaptionElement() {#createCaptionElement--}
```
public abstract CaptionElement createCaptionElement()
```


创造[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement).

**退货：**
[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement) - 创建结构元素。
### createCodeElement() {#createCodeElement--}
```
public abstract CodeElement createCodeElement()
```


创造[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement).

**退货：**
[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement) - 创建结构元素。
### createDivElement() {#createDivElement--}
```
public abstract DivElement createDivElement()
```


创造[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement).

**退货：**
[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement) - 创建结构元素。
### createFigureElement() {#createFigureElement--}
```
public abstract FigureElement createFigureElement()
```


创造[FigureElement](../../com.aspose.pdf/figureelement).

**退货：**
[FigureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/figureelement) - 创建结构元素。
### createFormElement() {#createFormElement--}
```
public abstract FormElement createFormElement()
```


创造[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement).

**退货：**
[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement) - 创建结构元素。
### createFormulaElement() {#createFormulaElement--}
```
public abstract FormulaElement createFormulaElement()
```


创造[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement).

**退货：**
[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement) - 创建结构元素。
### createHeaderElement() {#createHeaderElement--}
```
public abstract HeaderElement createHeaderElement()
```


创造[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement).

**退货：**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - 创建结构元素。
### createHeaderElement(int level) {#createHeaderElement-int-}
```
public abstract HeaderElement createHeaderElement(int level)
```


创造[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement)与水平。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| level | int | 标头的级别。必须是 1、2、3、4、5 或 6。 |

**退货：**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - 创建结构元素。
### createIndexElement() {#createIndexElement--}
```
public abstract IndexElement createIndexElement()
```


创造[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement).

**退货：**
[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement) - 创建结构元素。
### createLinkElement() {#createLinkElement--}
```
public abstract LinkElement createLinkElement()
```


创造[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement).

**退货：**
[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement) - 创建结构元素。
### createListElement() {#createListElement--}
```
public abstract ListElement createListElement()
```


创造[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement).

**退货：**
[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement) - 创建结构元素。
### createNonStructElement() {#createNonStructElement--}
```
public abstract NonStructElement createNonStructElement()
```


创造[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement).

**退货：**
[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement) - 创建结构元素。
### createNoteElement() {#createNoteElement--}
```
public abstract NoteElement createNoteElement()
```


创造[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement).

**退货：**
[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement) - 创建结构元素。
### createParagraphElement() {#createParagraphElement--}
```
public abstract ParagraphElement createParagraphElement()
```


创造[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement).

**退货：**
[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement) - 创建结构元素。
### createPartElement() {#createPartElement--}
```
public abstract PartElement createPartElement()
```


创造[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement).

**退货：**
[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement) - 创建结构元素。
### createPrivateElement() {#createPrivateElement--}
```
public abstract PrivateElement createPrivateElement()
```


创造[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement).

**退货：**
[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement) - 创建结构元素。
### createQuoteElement() {#createQuoteElement--}
```
public abstract QuoteElement createQuoteElement()
```


创造[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement).

**退货：**
[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement) - 创建结构元素。
### createReferenceElement() {#createReferenceElement--}
```
public abstract ReferenceElement createReferenceElement()
```


创造[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement).

**退货：**
[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement) - 创建结构元素。
### createRubyElement() {#createRubyElement--}
```
public abstract RubyElement createRubyElement()
```


创造[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement).

**退货：**
[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement) - 创建结构元素。
### createSectElement() {#createSectElement--}
```
public abstract SectElement createSectElement()
```


创造[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement).

**退货：**
[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement) - 创建结构元素。
### createSpanElement() {#createSpanElement--}
```
public abstract SpanElement createSpanElement()
```


创造[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement).

**退货：**
[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement) - 创建结构元素。
### createTOCElement() {#createTOCElement--}
```
public abstract TOCElement createTOCElement()
```


创造[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement).

**退货：**
[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement) - 创建结构元素。
### createTOCIElement() {#createTOCIElement--}
```
public abstract TOCIElement createTOCIElement()
```


创造[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement).

**退货：**
[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement) - 创建结构元素。
### createTableElement() {#createTableElement--}
```
public abstract TableElement createTableElement()
```


创造[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement).

**退货：**
[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement) - 创建结构元素。
### createTableTBodyElement() {#createTableTBodyElement--}
```
public abstract TableTBodyElement createTableTBodyElement()
```


创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**退货：**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - 创建结构元素。
### createTableTDElement() {#createTableTDElement--}
```
public abstract TableTDElement createTableTDElement()
```


创造[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement).

**退货：**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - 创建结构元素。
### createTableTFootElement() {#createTableTFootElement--}
```
public abstract TableTFootElement createTableTFootElement()
```


创造[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement).

**退货：**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - 创建结构元素。
### createTableTHElement() {#createTableTHElement--}
```
public abstract TableTHElement createTableTHElement()
```


创造[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement).

**退货：**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - 创建结构元素。
### createTableTHeadElement() {#createTableTHeadElement--}
```
public abstract TableTHeadElement createTableTHeadElement()
```


创造[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**退货：**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - 创建结构元素。
### createTableTRElement() {#createTableTRElement--}
```
public abstract TableTRElement createTableTRElement()
```


创造[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement).

**退货：**
[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement) - 创建结构元素。
### createWarichuElement() {#createWarichuElement--}
```
public abstract WarichuElement createWarichuElement()
```


创造[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement).

**退货：**
[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement) - 创建结构元素。
### getRootElement() {#getRootElement--}
```
public abstract StructureElement getRootElement()
```


获得根[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement)PDF文档的逻辑结构。

**退货：**
[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) - 根[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement)PDF文档的逻辑结构。
### getStructTreeRootElement() {#getStructTreeRootElement--}
```
public abstract StructTreeRootElement getStructTreeRootElement()
```


得到[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement)的PDF文件。

**退货：**
[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) PDF 文档的 StructTreeRootElement。
### getStructureTextState() {#getStructureTextState--}
```
public abstract StructureTextState getStructureTextState()
```


得到[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate)整个文档的设置。

**退货：**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - 价值：[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate)整个文档的设置。
### setLanguage(String lang) {#setLanguage-java.lang.String-}
```
public abstract void setLanguage(String lang)
```


为 pdf 文档设置自然语言。

一种语言标识符，应指定文档中所有文本的自然语言，除非被结构元素或标记内容的语言规范覆盖。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lang | java.lang.String | 语言标识符应该是空文本字符串，以指示语言未知，或者是 RFC 3066 中定义的语言标签，用于识别语言的标签。 |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String title)
```


设置 PDF 文档的标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | PDF 文档的标题。 |
