---
title: Aspose::Pdf::Text namespace
linktitle: Aspose::Pdf::Text
second_title: Aspose.PDF for C++ API Reference
description: 'How to use Aspose::Pdf::Text namespace in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.text/
---



## Classes

| Class | Description |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Represents cell of table that exist on the page. |
| [AbsorbedRow](./absorbedrow/) | Represents row of table that exist on the page. |
| [AbsorbedTable](./absorbedtable/) | Represents table that exist on the page. |
| [CharInfo](./charinfo/) | Represents a character info object. Provides character positioning information. |
| [CharInfoCollection](./charinfocollection/) | Represents [CharInfo](./charinfo/) objects collection. |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase/) | Represents a base class for custom font substitution strategy. |
| [FileFontSource](./filefontsource/) | Represents single font file source. |
| [FolderFontSource](./folderfontsource/) | Represents the folder that contains font files. |
| [Font](./font/) | Represents font object. |
| [FontAbsorber](./fontabsorber/) | Represents an absorber object of fonts. Performs search for fonts and provides access to search results via [FontAbsorber::Fonts](../) collection. |
| [FontCollection](./fontcollection/) | Represents font collection. |
| [FontRepository](./fontrepository/) | Performs font search. Searches in system installed fonts and standard [Pdf](../aspose.pdf/) fonts. Also provides functionality to open custom fonts. |
| [FontSource](./fontsource/) | Represents a base class fot font source. |
| [FontSourceCollection](./fontsourcecollection/) | Represents font sources collection. |
| [FontSubstitution](./fontsubstitution/) | Represents a base class fot font substitution strategies. |
| [FontSubstitutionCollection](./fontsubstitutioncollection/) | Represents font substitution strategies collection. |
| [IFontOptions](./ifontoptions/) | Useful properties to tune [Font](./font/) behaviour. |
| [IFontSubstitutionCallback](./ifontsubstitutioncallback/) | This interface declares a callback mechanism to send notifications. |
| [IFontSubstitutionRegistrator](./ifontsubstitutionregistrator/) | This interface declares necessary functionality for register font substitutions. |
| [ITableElement](./itableelement/) | This interface represents an element of existing table extracted by [TableAbsorber](./tableabsorber/). |
| [MarkupParagraph](./markupparagraph/) | Represents a paragraph. |
| [MarkupSection](./markupsection/) | Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks. |
| [MemoryFontSource](./memoryfontsource/) | Represents single font file source. |
| [OnSegmentChangedEventArgs](./onsegmentchangedeventargs/) | Contains additional information about OnSegmentChangedEvent that is delivered to listeners. |
| [PageMarkup](./pagemarkup/) | [Page](../aspose.pdf/page/) markup represented by collections of [MarkupSection](./markupsection/) and [MarkupParagraph](./markupparagraph/). |
| [ParagraphAbsorber](./paragraphabsorber/) | Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via [TextFragments](../) collections grouped by structure elements. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Represents options for the [ParagraphAbsorber](./paragraphabsorber/). |
| [Position](./position/) | Represents a position object. |
| [RegexManager](./regexmanager/) | Provides a wrapper for regular expression operations with configurable timeout settings. |
| [SimpleFontSubstitution](./simplefontsubstitution/) | Represents a class for simple font substitution strategy. |
| [SystemFontSource](./systemfontsource/) | Represents all fonts installed to the system. |
| [SystemFontsSubstitution](./systemfontssubstitution/) | Represents a class for font substitution strategy that substitutes fonts with system fonts. |
| [TableAbsorber](./tableabsorber/) | Represents an absorber object of table elements. Performs search and provides access to search results via [TableAbsorber::TableList](../) collection. |
| [TabStop](./tabstop/) | Represents a custom Tab stop position in a paragraph. |
| [TabStops](./tabstops/) | Represents a collection of [TabStop](./tabstop/) objects. |
| [TextAbsorber](./textabsorber/) | Represents an absorber object of a text. Performs text extraction and provides access to the result via [TextAbsorber::Text](../) object. |
| [TextBuilder](./textbuilder/) | Appends text object to [Pdf](../aspose.pdf/) page. |
| [TextEditOptions](./texteditoptions/) | Descubes options of text edit operations. |
| [TextExtractionError](./textextractionerror/) | Describes the text extraction error has appeared in the PDF document. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Represents the location in the PDF document where text extraction error has appeared. |
| [TextExtractionOptions](./textextractionoptions/) | Represents text extraction options. |
| [TextFormattingOptions](./textformattingoptions/) | Represents text formatting options. |
| [TextFragment](./textfragment/) | Represents fragment of [Pdf](../aspose.pdf/) text. |
| [TextFragmentAbsorber](./textfragmentabsorber/) | Represents an absorber object of text fragments. Performs text search and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection. |
| [TextFragmentCollection](./textfragmentcollection/) | Represents a text fragments collection. |
| [TextFragmentState](./textfragmentstate/) | Represents a text state of a text fragment. |
| [TextOptions](./textoptions/) | Represents text processing options. |
| [TextParagraph](./textparagraph/) | Represents text paragraphs as multiline text object. |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Represents an absorber object of text paragraphs. Performs text search and provides access to search results via [TextParagraphAbsorber::TextParagraphs](../) collection. |
| [TextParagraphCollection](./textparagraphcollection/) | Represents a text paragraphs collection. |
| [TextReplaceOptions](./textreplaceoptions/) | Represents text replace options. |
| [TextSearchOptions](./textsearchoptions/) | Represents text search options. |
| [TextSegment](./textsegment/) | Represents segment of [Pdf](../aspose.pdf/) text. |
| [TextSegmentCollection](./textsegmentcollection/) | Represents a text segments collection. |
| [TextState](./textstate/) | Represents a text state of a text. |
| [UnicodeSubstitution](./unicodesubstitution/) | Represents character code substitution. |
## Enums

| Enum | Description |
| --- | --- |
| [CoordinateOrigin](./coordinateorigin/) | [Text](./)[CoordinateOrigin](./coordinateorigin/) enumeration. |
| [FontStyles](./fontstyles/) | Specifies style information applied to text. |
| [FontTypes](./fonttypes/) | Supported font types enumeration. |
| [SubstitutionFontCategories](./substitutionfontcategories/) | Represents font categories that can be substituted. |
| [TabAlignmentType](./tabalignmenttype/) | Enumerates the tab alignment types. |
| [TabLeaderType](./tableadertype/) | Enumerates the tab leader types. |
| [TextRenderingMode](./textrenderingmode/) | The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three. |
