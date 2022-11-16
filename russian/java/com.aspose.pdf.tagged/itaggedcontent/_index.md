---
title: ITaggedContent
second_title: Aspose.PDF для справки по Java API
description: Представляет собой интерфейс для работы с содержимым документа TaggedPdf.
type: docs
weight: 11
url: /ru/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Представляет собой интерфейс для работы с содержимым документа TaggedPdf.
## Методы

| Метод | Описание |
| --- | --- |
| [createAnnotElement()](#createAnnotElement--) |  Создает[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement). |
| [createArtElement()](#createArtElement--) |  Создает[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement). |
| [createBibEntryElement()](#createBibEntryElement--) |  Создает[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement). |
| [createBlockQuoteElement()](#createBlockQuoteElement--) |  Создает[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement). |
| [createCaptionElement()](#createCaptionElement--) |  Создает[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement). |
| [createCodeElement()](#createCodeElement--) |  Создает[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement). |
| [createDivElement()](#createDivElement--) |  Создает[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement). |
| [createFigureElement()](#createFigureElement--) |  Создает[FigureElement](../../com.aspose.pdf/figureelement). |
| [createFormElement()](#createFormElement--) |  Создает[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement). |
| [createFormulaElement()](#createFormulaElement--) |  Создает[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement). |
| [createHeaderElement()](#createHeaderElement--) |  Создает[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement). |
| [createHeaderElement(int level)](#createHeaderElement-int-) |  Создает[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) с уровнем. |
| [createIndexElement()](#createIndexElement--) |  Создает[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement). |
| [createLinkElement()](#createLinkElement--) |  Создает[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement). |
| [createListElement()](#createListElement--) |  Создает[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement). |
| [createNonStructElement()](#createNonStructElement--) |  Создает[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement). |
| [createNoteElement()](#createNoteElement--) |  Создает[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement). |
| [createParagraphElement()](#createParagraphElement--) |  Создает[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement). |
| [createPartElement()](#createPartElement--) |  Создает[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement). |
| [createPrivateElement()](#createPrivateElement--) |  Создает[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement). |
| [createQuoteElement()](#createQuoteElement--) |  Создает[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement). |
| [createReferenceElement()](#createReferenceElement--) |  Создает[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement). |
| [createRubyElement()](#createRubyElement--) |  Создает[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement). |
| [createSectElement()](#createSectElement--) |  Создает[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement). |
| [createSpanElement()](#createSpanElement--) |  Создает[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement). |
| [createTOCElement()](#createTOCElement--) |  Создает[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement). |
| [createTOCIElement()](#createTOCIElement--) |  Создает[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement). |
| [createTableElement()](#createTableElement--) |  Создает[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement). |
| [createTableTBodyElement()](#createTableTBodyElement--) |  Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTDElement()](#createTableTDElement--) |  Создает[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement). |
| [createTableTFootElement()](#createTableTFootElement--) |  Создает[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement). |
| [createTableTHElement()](#createTableTHElement--) |  Создает[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement). |
| [createTableTHeadElement()](#createTableTHeadElement--) |  Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement). |
| [createTableTRElement()](#createTableTRElement--) |  Создает[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement). |
| [createWarichuElement()](#createWarichuElement--) |  Создает[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement). |
| [getRootElement()](#getRootElement--) |  Получает root[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) логической структуры документа PDF. |
| [getStructTreeRootElement()](#getStructTreeRootElement--) |  Получает[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) документа PDF. |
| [getStructureTextState()](#getStructureTextState--) |  Получить[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) настройки для всего документа. |
| [setLanguage(String lang)](#setLanguage-java.lang.String-) | Устанавливает естественный язык для документа PDF. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Устанавливает заголовок для PDF-документа. |
### createAnnotElement() {#createAnnotElement--}
```
public abstract AnnotElement createAnnotElement()
```


 Создает[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement).

**Возвращает:**
[AnnotElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotelement) - Создан элемент структуры.
### createArtElement() {#createArtElement--}
```
public abstract ArtElement createArtElement()
```


 Создает[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement).

**Возвращает:**
[ArtElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/artelement) - Создан элемент структуры.
### createBibEntryElement() {#createBibEntryElement--}
```
public abstract BibEntryElement createBibEntryElement()
```


 Создает[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement).

**Возвращает:**
[BibEntryElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/bibentryelement) - Создан элемент структуры.
### createBlockQuoteElement() {#createBlockQuoteElement--}
```
public abstract BlockQuoteElement createBlockQuoteElement()
```


 Создает[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement).

**Возвращает:**
[BlockQuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/blockquoteelement) - Создан элемент структуры.
### createCaptionElement() {#createCaptionElement--}
```
public abstract CaptionElement createCaptionElement()
```


 Создает[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement).

**Возвращает:**
[CaptionElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/captionelement) - Создан элемент структуры.
### createCodeElement() {#createCodeElement--}
```
public abstract CodeElement createCodeElement()
```


 Создает[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement).

**Возвращает:**
[CodeElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/codeelement) - Создан элемент структуры.
### createDivElement() {#createDivElement--}
```
public abstract DivElement createDivElement()
```


 Создает[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement).

**Возвращает:**
[DivElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/divelement) - Создан элемент структуры.
### createFigureElement() {#createFigureElement--}
```
public abstract FigureElement createFigureElement()
```


 Создает[FigureElement](../../com.aspose.pdf/figureelement).

**Возвращает:**
[FigureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/figureelement) - Создан элемент структуры.
### createFormElement() {#createFormElement--}
```
public abstract FormElement createFormElement()
```


 Создает[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement).

**Возвращает:**
[FormElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formelement) - Создан элемент структуры.
### createFormulaElement() {#createFormulaElement--}
```
public abstract FormulaElement createFormulaElement()
```


 Создает[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement).

**Возвращает:**
[FormulaElement](../../com.aspose.pdf.tagged.logicalstructure.elements/formulaelement) - Создан элемент структуры.
### createHeaderElement() {#createHeaderElement--}
```
public abstract HeaderElement createHeaderElement()
```


 Создает[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement).

**Возвращает:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Создан элемент структуры.
### createHeaderElement(int level) {#createHeaderElement-int-}
```
public abstract HeaderElement createHeaderElement(int level)
```


 Создает[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) с уровнем.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int | Уровень заголовка. Должно быть 1, 2, 3, 4, 5 или 6. |

**Возвращает:**
[HeaderElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/headerelement) - Создан элемент структуры.
### createIndexElement() {#createIndexElement--}
```
public abstract IndexElement createIndexElement()
```


 Создает[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement).

**Возвращает:**
[IndexElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/indexelement) - Создан элемент структуры.
### createLinkElement() {#createLinkElement--}
```
public abstract LinkElement createLinkElement()
```


 Создает[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement).

**Возвращает:**
[LinkElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement) - Создан элемент структуры.
### createListElement() {#createListElement--}
```
public abstract ListElement createListElement()
```


 Создает[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement).

**Возвращает:**
[ListElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/listelement) - Создан элемент структуры.
### createNonStructElement() {#createNonStructElement--}
```
public abstract NonStructElement createNonStructElement()
```


 Создает[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement).

**Возвращает:**
[NonStructElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/nonstructelement) - Создан элемент структуры.
### createNoteElement() {#createNoteElement--}
```
public abstract NoteElement createNoteElement()
```


 Создает[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement).

**Возвращает:**
[NoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/noteelement) - Создан элемент структуры.
### createParagraphElement() {#createParagraphElement--}
```
public abstract ParagraphElement createParagraphElement()
```


 Создает[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement).

**Возвращает:**
[ParagraphElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/paragraphelement) - Создан элемент структуры.
### createPartElement() {#createPartElement--}
```
public abstract PartElement createPartElement()
```


 Создает[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement).

**Возвращает:**
[PartElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/partelement) - Создан элемент структуры.
### createPrivateElement() {#createPrivateElement--}
```
public abstract PrivateElement createPrivateElement()
```


 Создает[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement).

**Возвращает:**
[PrivateElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/privateelement) - Создан элемент структуры.
### createQuoteElement() {#createQuoteElement--}
```
public abstract QuoteElement createQuoteElement()
```


 Создает[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement).

**Возвращает:**
[QuoteElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/quoteelement) - Создан элемент структуры.
### createReferenceElement() {#createReferenceElement--}
```
public abstract ReferenceElement createReferenceElement()
```


 Создает[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement).

**Возвращает:**
[ReferenceElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/referenceelement) - Создан элемент структуры.
### createRubyElement() {#createRubyElement--}
```
public abstract RubyElement createRubyElement()
```


 Создает[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement).

**Возвращает:**
[RubyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/rubyelement) - Создан элемент структуры.
### createSectElement() {#createSectElement--}
```
public abstract SectElement createSectElement()
```


 Создает[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement).

**Возвращает:**
[SectElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/sectelement) - Создан элемент структуры.
### createSpanElement() {#createSpanElement--}
```
public abstract SpanElement createSpanElement()
```


 Создает[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement).

**Возвращает:**
[SpanElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/spanelement) - Создан элемент структуры.
### createTOCElement() {#createTOCElement--}
```
public abstract TOCElement createTOCElement()
```


 Создает[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement).

**Возвращает:**
[TOCElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocelement) - Создан элемент структуры.
### createTOCIElement() {#createTOCIElement--}
```
public abstract TOCIElement createTOCIElement()
```


 Создает[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement).

**Возвращает:**
[TOCIElement](../../com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement) - Создан элемент структуры.
### createTableElement() {#createTableElement--}
```
public abstract TableElement createTableElement()
```


 Создает[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement).

**Возвращает:**
[TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement) - Создан элемент структуры.
### createTableTBodyElement() {#createTableTBodyElement--}
```
public abstract TableTBodyElement createTableTBodyElement()
```


 Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Возвращает:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Создан элемент структуры.
### createTableTDElement() {#createTableTDElement--}
```
public abstract TableTDElement createTableTDElement()
```


 Создает[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement).

**Возвращает:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Создан элемент структуры.
### createTableTFootElement() {#createTableTFootElement--}
```
public abstract TableTFootElement createTableTFootElement()
```


 Создает[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement).

**Возвращает:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Создан элемент структуры.
### createTableTHElement() {#createTableTHElement--}
```
public abstract TableTHElement createTableTHElement()
```


 Создает[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement).

**Возвращает:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Создан элемент структуры.
### createTableTHeadElement() {#createTableTHeadElement--}
```
public abstract TableTHeadElement createTableTHeadElement()
```


 Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement).

**Возвращает:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Создан элемент структуры.
### createTableTRElement() {#createTableTRElement--}
```
public abstract TableTRElement createTableTRElement()
```


 Создает[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement).

**Возвращает:**
[TableTRElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement) - Создан элемент структуры.
### createWarichuElement() {#createWarichuElement--}
```
public abstract WarichuElement createWarichuElement()
```


 Создает[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement).

**Возвращает:**
[WarichuElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/warichuelement) - Создан элемент структуры.
### getRootElement() {#getRootElement--}
```
public abstract StructureElement getRootElement()
```


 Получает root[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) логической структуры документа PDF.

**Возвращает:**
[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) - Корень[StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) логической структуры документа PDF.
### getStructTreeRootElement() {#getStructTreeRootElement--}
```
public abstract StructTreeRootElement getStructTreeRootElement()
```


 Получает[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) документа PDF.

**Возвращает:**
[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement) - StructTreeRootElement документа PDF.
### getStructureTextState() {#getStructureTextState--}
```
public abstract StructureTextState getStructureTextState()
```


 Получить[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) настройки для всего документа.

**Возвращает:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - Ценность:[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) настройки для всего документа.
### setLanguage(String lang) {#setLanguage-java.lang.String-}
```
public abstract void setLanguage(String lang)
```


Устанавливает естественный язык для документа PDF.

Идентификатор языка, который должен указывать естественный язык для всего текста в документе, за исключением случаев, когда он перекрывается спецификациями языка для элементов структуры или маркированного содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| lang | java.lang.String | Идентификатор языка должен быть либо пустой текстовой строкой, чтобы указать, что язык неизвестен, либо тегом языка, как определено в RFC 3066, Теги для идентификации языков. |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String title)
```


Устанавливает заголовок для PDF-документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | java.lang.String | Название PDF-документа. |
