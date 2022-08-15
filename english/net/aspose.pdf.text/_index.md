---
title: Aspose.Pdf.Text
second_title: Aspose.PDF for .NET API Reference
description: The Aspose.Pdf.Text namespace provides classes that allow to extract text add text manipulate existing text of a document. It also contain classes that allow to extract replace substitute fonts of a document.
type: docs
weight: 160
url: /net/aspose.pdf.text/
---
The **Aspose.Pdf.Text** namespace provides classes that allow to extract text, add text, manipulate existing text of a document. It also contain classes that allow to extract, replace, substitute fonts of a document.

## Classes

| Class | Description |
| --- | --- |
| [AbsorbedCell](./absorbedcell) | Represents cell of table that exist on the page |
| [AbsorbedRow](./absorbedrow) | Represents row of table that exist on the page |
| [AbsorbedTable](./absorbedtable) | Represents table that exist on the page |
| [CharInfo](./charinfo) | Represents a character info object. Provides character positioning information. |
| [CharInfoCollection](./charinfocollection) | Represents CharInfo objects collection. |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase) | Represents a base class for custom font substitution strategy. |
| [FileFontSource](./filefontsource) | Represents single font file source. |
| [FolderFontSource](./folderfontsource) | Represents the folder that contains font files. |
| [Font](./font) | Represents font object. |
| [FontAbsorber](./fontabsorber) | Represents an absorber object of fonts. Performs search for fonts and provides access to search results via [`Fonts`](../aspose.pdf.text/fontabsorber/fonts) collection. |
| [FontCollection](./fontcollection) | Represents font collection. |
| [FontRepository](./fontrepository) | Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts. |
| [FontSource](./fontsource) | Represents a base class fot font source. |
| [FontSourceCollection](./fontsourcecollection) | Represents font sources collection. |
| [FontSubstitution](./fontsubstitution) | Represents a base class fot font substitution strategies. |
| [FontSubstitutionCollection](./fontsubstitutioncollection) | Represents font substitution strategies collection. |
| [MarkupParagraph](./markupparagraph) | Represents a paragraph. |
| [MarkupSection](./markupsection) | Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks. |
| [MemoryFontSource](./memoryfontsource) | Represents single font file source. |
| [PageMarkup](./pagemarkup) | Page markup represented by collections of [`MarkupSection`](../aspose.pdf.text/markupsection) and [`MarkupParagraph`](../aspose.pdf.text/markupparagraph). |
| [ParagraphAbsorber](./paragraphabsorber) | Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via !:TextFragments collections grouped by structure elements. |
| [Position](./position) | Represents a position object |
| [SimpleFontSubstitution](./simplefontsubstitution) | Represents a class for simple font substitution strategy. |
| [SystemFontSource](./systemfontsource) | Represents all fonts installed to the system. |
| [SystemFontsSubstitution](./systemfontssubstitution) | Represents a class for font substitution strategy that substitutes fonts with system fonts. |
| [TableAbsorber](./tableabsorber) | Represents an absorber object of table elements. Performs search and provides access to search results via [`TableList`](../aspose.pdf.text/tableabsorber/tablelist) collection. |
| [TabStop](./tabstop) | Represents a custom Tab stop position in a paragraph. |
| [TabStops](./tabstops) | Represents a collection of [`TabStop`](../aspose.pdf.text/tabstop) objects. |
| [TextAbsorber](./textabsorber) | Represents an absorber object of a text. Performs text extraction and provides access to the result via [`Text`](../aspose.pdf.text/textabsorber/text) object. |
| [TextBuilder](./textbuilder) | Appends text object to Pdf page. |
| [TextEditOptions](./texteditoptions) | Descubes options of text edit operations. |
| [TextExtractionError](./textextractionerror) | Describes the text extraction error has appeared in the PDF document. |
| [TextExtractionErrorLocation](./textextractionerrorlocation) | Represents the location in the PDF document where text extraction error has appeared. |
| [TextExtractionOptions](./textextractionoptions) | Represents text extraction options |
| [TextFormattingOptions](./textformattingoptions) | Represents text formatting options |
| [TextFragment](./textfragment) | Represents fragment of Pdf text. |
| [TextFragmentAbsorber](./textfragmentabsorber) | Represents an absorber object of text fragments. Performs text search and provides access to search results via [`TextFragments`](../aspose.pdf.text/textfragmentabsorber/textfragments) collection. |
| [TextFragmentCollection](./textfragmentcollection) | Represents a text fragments collection |
| [TextFragmentState](./textfragmentstate) | Represents a text state of a text fragment. |
| [TextOptions](./textoptions) | Represents text processing options |
| [TextParagraph](./textparagraph) | Represents text paragraphs as multiline text object. |
| [TextReplaceOptions](./textreplaceoptions) | Represents text replace options |
| [TextSearchOptions](./textsearchoptions) | Represents text search options |
| [TextSegment](./textsegment) | Represents segment of Pdf text. |
| [TextSegmentCollection](./textsegmentcollection) | Represents a text segments collection |
| [TextState](./textstate) | Represents a text state of a text |
## Interfaces

| Interface | Description |
| --- | --- |
| [IFontOptions](./ifontoptions) | Useful properties to tune Font behaviour |
| [ITableElement](./itableelement) | This interface represents an element of existing table extracted by TableAbsorber. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [FontStyles](./fontstyles) | Specifies style information applied to text. |
| [FontTypes](./fonttypes) | Supported font types enumeration. |
| [SubstitutionFontCategories](./substitutionfontcategories) | Represents font categories that can be substituted. |
| [TabAlignmentType](./tabalignmenttype) | Enumerates the tab alignment types. |
| [TabLeaderType](./tableadertype) | Enumerates the tab leader types. |
| [TextRenderingMode](./textrenderingmode) | The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
