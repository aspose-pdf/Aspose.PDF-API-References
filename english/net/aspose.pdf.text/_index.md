---
title: "Aspose.Pdf.Text"
linktitle: "Aspose.Pdf.Text"
articleTitle: "Aspose.Pdf.Text"
second_title: "Aspose.PDF for .NET API Reference"
description: "The Aspose.Pdf.Text namespace provides classes."
type: docs
weight: 10
url: "/net/aspose.pdf.text/"
keywords: "Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Overview

The **Aspose.Pdf.Text** namespace provides classes.

Part of the [Aspose.PDF for .NET](../) API reference.

## Classes

| Class | Description |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Represents cell of table that exist on the page. |
| [AbsorbedRow](./absorbedrow/) | Represents row of table that exist on the page. |
| [AbsorbedTable](./absorbedtable/) | Represents table that exist on the page. |
| [CharInfo](./charinfo/) | Represents a character info object. |
| [CharInfoCollection](./charinfocollection/) | Represents CharInfo objects collection. |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase/) | Represents a base class for custom font substitution strategy. |
| [CustomFontSubstitutionBase.OriginalFontSpecification](./customfontsubstitutionbase.originalfontspecification/) | Represents original font specification. |
| [FileFontSource](./filefontsource/) | Represents single font file source. |
| [FolderFontSource](./folderfontsource/) | Represents the folder that contains font files. |
| [Font](./font/) | Represents font object. |
| [FontAbsorber](./fontabsorber/) | Represents an absorber object of fonts. |
| [FontCollection](./fontcollection/) | Represents font collection. |
| [FontRepository](./fontrepository/) | Performs font search. Searches in system installed fonts and standard Pdf fonts. |
| [FontSource](./fontsource/) | Represents a base class fot font source. |
| [FontSourceCollection](./fontsourcecollection/) | Represents font sources collection. |
| [FontSubstitution](./fontsubstitution/) | Represents a base class fot font substitution strategies. |
| [FontSubstitutionCollection](./fontsubstitutioncollection/) | Represents font substitution strategies collection. |
| [MarkupParagraph](./markupparagraph/) | Represents a paragraph. |
| [MarkupSection](./markupsection/) | Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks. |
| [MemoryFontSource](./memoryfontsource/) | Represents single font file source. |
| [PageMarkup](./pagemarkup/) | Page markup represented by collections of [`MarkupSection`](../aspose.pdf.text/markupsection/) and [`MarkupParagraph`](../aspose.pdf.text/markupparagraph/). |
| [ParagraphAbsorber](./paragraphabsorber/) | Represents an absorber object of page structure objects such as sections and paragraphs. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Represents options for the [`ParagraphAbsorber`](../aspose.pdf.text/paragraphabsorber/). |
| [Position](./position/) | Represents a position object. |
| [RegexManager](./regexmanager/) | Provides a wrapper for regular expression operations with configurable timeout settings. |
| [SimpleFontSubstitution](./simplefontsubstitution/) | Represents a class for simple font substitution strategy. |
| [SystemFontSource](./systemfontsource/) | Represents all fonts installed to the system. |
| [SystemFontsSubstitution](./systemfontssubstitution/) | Represents a class for font substitution strategy that substitutes fonts with system fonts. |
| [TabStop](./tabstop/) | Represents a custom Tab stop position in a paragraph. |
| [TabStops](./tabstops/) | Represents a collection of [`TabStop`](../aspose.pdf.text/tabstop/) objects. |
| [TableAbsorber](./tableabsorber/) | Represents an absorber object of table elements. |
| [TextAbsorber](./textabsorber/) | Represents an absorber object of a text. |
| [TextBuilder](./textbuilder/) | Appends text object to Pdf page. |
| [TextEditOptions](./texteditoptions/) | Descubes options of text edit operations. |
| [TextExtractionError](./textextractionerror/) | Describes the text extraction error has appeared in the PDF document. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Represents the location in the PDF document where text extraction error has appeared. |
| [TextExtractionOptions](./textextractionoptions/) | Represents text extraction options. |
| [TextFormattingOptions](./textformattingoptions/) | Represents text formatting options. |
| [TextFragment](./textfragment/) | Represents fragment of Pdf text. |
| [TextFragmentAbsorber](./textfragmentabsorber/) | Represents an absorber object of text fragments. |
| [TextFragmentCollection](./textfragmentcollection/) | Represents a text fragments collection. |
| [TextFragmentState](./textfragmentstate/) | Represents a text state of a text fragment. |
| [TextOptions](./textoptions/) | Represents text processing options. |
| [TextParagraph](./textparagraph/) | Represents text paragraphs as multiline text object. |
| [TextReplaceOptions](./textreplaceoptions/) | Represents text replace options. |
| [TextSearchOptions](./textsearchoptions/) | Represents text search options. |
| [TextSegment](./textsegment/) | Represents segment of Pdf text. |
| [TextSegmentCollection](./textsegmentcollection/) | Represents a text segments collection. |
| [TextState](./textstate/) | Represents a text state of a text. |

## Interfaces

| Interface | Description |
| --- | --- |
| [IFontOptions](./ifontoptions/) | Useful properties to tune Font behaviour. |
| [ITableElement](./itableelement/) | This interface represents an element of existing table extracted by TableAbsorber. |

## Enumeration

| Enumeration | Description |
| --- | --- |
| [CoordinateOrigin](./coordinateorigin/) | Text CoordinateOrigin enumeration. |
| [FontStyles](./fontstyles/) | Specifies style information applied to text. |
| [FontTypes](./fonttypes/) | Supported font types enumeration. |
| [SubstitutionFontCategories](./substitutionfontcategories/) | Represents font categories that can be substituted. |
| [TabAlignmentType](./tabalignmenttype/) | Enumerates the tab alignment types. |
| [TabLeaderType](./tableadertype/) | Enumerates the tab leader types. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Clipping path processing modes. |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Font replacement behavior. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Language transformation modes. |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Action to perform if font does not contain required character. |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Defines different modes which can be used while converting pdf document into text. See `!:TextDevice` class. |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Defines line spacing specifics. |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Defines word wrapping strategies. |
| [TextRenderingMode](./textrenderingmode/) | The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Specifies a policy for how the font size of text should be adjusted to fit within a containing area. |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Determines action that will be done after replace of text fragment to more short. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Scope where replace text operation is applied. |

## FAQ

### What classes does the Aspose.Pdf.Text namespace contain?

[AbsorbedCell](./absorbedcell/), [AbsorbedRow](./absorbedrow/), [AbsorbedTable](./absorbedtable/), [CharInfo](./charinfo/), [CharInfoCollection](./charinfocollection/), and 44 more.

### How many types are in the Aspose.Pdf.Text namespace?

The Aspose.Pdf.Text namespace contains 68 types, listed above.

