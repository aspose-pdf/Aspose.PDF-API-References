---
title: "ITaggedContent Interface"
linktitle: "ITaggedContent"
articleTitle: "ITaggedContent"
second_title: "Aspose.PDF for .NET"
description: "Represents interface for work with TaggedPdf content of document."
type: docs
weight: 30
url: "/net/aspose.pdf.tagged/itaggedcontent/"
product_version: "26.9.0"
---
## ITaggedContent interface

Represents interface for work with TaggedPdf content of document.

```csharp
public interface ITaggedContent
```

## Properties

| Name | Description |
| --- | --- |
| [RootElement](./rootelement/) { get; } | Gets root [`StructureElement`](../../aspose.pdf.logicalstructure/structureelement/) of logical structure of PDF document. |
| [StructTreeRootElement](./structtreerootelement/) { get; } | Gets [`StructTreeRootElement`](../../aspose.pdf.logicalstructure/structtreerootelement/) of PDF document. |
| [StructureTextState](./structuretextstate/) { get; } | Get [`StructureTextState`](../../aspose.pdf.logicalstructure/structuretextstate/) settings for whole document. |

## Methods

| Name | Description |
| --- | --- |
| [CreateAnnotElement](./createannotelement/)() | Creates [`AnnotElement`](../../aspose.pdf.logicalstructure/annotelement/). |
| [CreateArtElement](./createartelement/)() | Creates [`ArtElement`](../../aspose.pdf.logicalstructure/artelement/). |
| [CreateBibEntryElement](./createbibentryelement/)() | Creates [`BibEntryElement`](../../aspose.pdf.logicalstructure/bibentryelement/). |
| [CreateBlockQuoteElement](./createblockquoteelement/)() | Creates [`BlockQuoteElement`](../../aspose.pdf.logicalstructure/blockquoteelement/). |
| [CreateCaptionElement](./createcaptionelement/)() | Creates [`CaptionElement`](../../aspose.pdf.logicalstructure/captionelement/). |
| [CreateCodeElement](./createcodeelement/)() | Creates [`CodeElement`](../../aspose.pdf.logicalstructure/codeelement/). |
| [CreateDivElement](./createdivelement/)() | Creates [`DivElement`](../../aspose.pdf.logicalstructure/divelement/). |
| [CreateFigureElement](./createfigureelement/)() | Creates [`FigureElement`](../../aspose.pdf.structure/figureelement/). |
| [CreateFormElement](./createformelement/)() | Creates [`FormElement`](../../aspose.pdf.logicalstructure/formelement/). |
| [CreateFormulaElement](./createformulaelement/)() | Creates [`FormulaElement`](../../aspose.pdf.logicalstructure/formulaelement/). |
| [CreateHeaderElement](./createheaderelement/)() | Creates [`HeaderElement`](../../aspose.pdf.logicalstructure/headerelement/). |
| [CreateHeaderElement](./createheaderelement/)(*int*) | Creates [`HeaderElement`](../../aspose.pdf.logicalstructure/headerelement/) with level. |
| [CreateIndexElement](./createindexelement/)() | Creates [`IndexElement`](../../aspose.pdf.logicalstructure/indexelement/). |
| [CreateLinkElement](./createlinkelement/)() | Creates [`LinkElement`](../../aspose.pdf.logicalstructure/linkelement/). |
| [CreateListElement](./createlistelement/)() | Creates [`ListElement`](../../aspose.pdf.logicalstructure/listelement/). |
| [CreateListLBodyElement](./createlistlbodyelement/)() | Creates [`ListLBodyElement`](../../aspose.pdf.logicalstructure/listlbodyelement/). |
| [CreateListLIElement](./createlistlielement/)() | Creates [`ListLIElement`](../../aspose.pdf.logicalstructure/listlielement/). |
| [CreateListLblElement](./createlistlblelement/)() | Creates [`ListLblElement`](../../aspose.pdf.logicalstructure/listlblelement/). |
| [CreateNonStructElement](./createnonstructelement/)() | Creates [`NonStructElement`](../../aspose.pdf.logicalstructure/nonstructelement/). |
| [CreateNoteElement](./createnoteelement/)() | Creates [`NoteElement`](../../aspose.pdf.logicalstructure/noteelement/). |
| [CreateParagraphElement](./createparagraphelement/)() | Creates [`ParagraphElement`](../../aspose.pdf.logicalstructure/paragraphelement/). |
| [CreatePartElement](./createpartelement/)() | Creates [`PartElement`](../../aspose.pdf.logicalstructure/partelement/). |
| [CreatePrivateElement](./createprivateelement/)() | Creates [`PrivateElement`](../../aspose.pdf.logicalstructure/privateelement/). |
| [CreateQuoteElement](./createquoteelement/)() | Creates [`QuoteElement`](../../aspose.pdf.logicalstructure/quoteelement/). |
| [CreateReferenceElement](./createreferenceelement/)() | Creates [`ReferenceElement`](../../aspose.pdf.logicalstructure/referenceelement/). |
| [CreateRubyElement](./createrubyelement/)() | Creates [`RubyElement`](../../aspose.pdf.logicalstructure/rubyelement/). |
| [CreateSectElement](./createsectelement/)() | Creates [`SectElement`](../../aspose.pdf.logicalstructure/sectelement/). |
| [CreateSpanElement](./createspanelement/)() | Creates [`SpanElement`](../../aspose.pdf.logicalstructure/spanelement/). |
| [CreateTOCElement](./createtocelement/)() | Creates [`TOCElement`](../../aspose.pdf.logicalstructure/tocelement/). |
| [CreateTOCIElement](./createtocielement/)() | Creates [`TOCIElement`](../../aspose.pdf.logicalstructure/tocielement/). |
| [CreateTableElement](./createtableelement/)() | Creates [`TableElement`](../../aspose.pdf.logicalstructure/tableelement/). |
| [CreateTableTBodyElement](./createtabletbodyelement/)() | Creates [`TableTHeadElement`](../../aspose.pdf.logicalstructure/tabletheadelement/). |
| [CreateTableTDElement](./createtabletdelement/)() | Creates [`TableTDElement`](../../aspose.pdf.logicalstructure/tabletdelement/). |
| [CreateTableTFootElement](./createtabletfootelement/)() | Creates [`TableTFootElement`](../../aspose.pdf.logicalstructure/tabletfootelement/). |
| [CreateTableTHElement](./createtablethelement/)() | Creates [`TableTHElement`](../../aspose.pdf.logicalstructure/tablethelement/). |
| [CreateTableTHeadElement](./createtabletheadelement/)() | Creates [`TableTHeadElement`](../../aspose.pdf.logicalstructure/tabletheadelement/). |
| [CreateTableTRElement](./createtabletrelement/)() | Creates [`TableTRElement`](../../aspose.pdf.logicalstructure/tabletrelement/). |
| [CreateWarichuElement](./createwarichuelement/)() | Creates [`WarichuElement`](../../aspose.pdf.logicalstructure/warichuelement/). |
| [PreSave](./presave/)() | Prepares the tagged content of the document for saving. |
| [Save](./save/)() | Saves the current state of the tagged content to the associated PDF document. |
| [SetLanguage](./setlanguage/)(*string*) | Sets natural language for pdf document. |
| [SetTitle](./settitle/)(*string*) | Sets title for PDF document. |

### See Also

* namespace [Aspose.Pdf.Tagged](../../aspose.pdf.tagged/)
* assembly [Aspose.PDF](../../)

