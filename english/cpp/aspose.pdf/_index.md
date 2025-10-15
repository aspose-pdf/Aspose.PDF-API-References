---
title: Aspose::Pdf namespace
linktitle: Aspose::Pdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf namespace. The Aspose.Pdf is a root namespace for all classes of Aspose.Pdf library which are either directly in it like Document or indirectly through several subnamespaces in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/
---

The **[Aspose.Pdf](./)** is a root namespace for all classes of [Aspose.Pdf](./) library which are either directly in it like **[Document](./document/)** or indirectly through several subnamespaces.

## Classes

| Class | Description |
| --- | --- |
| [ApsLoadOptions](./apsloadoptions/) | Class describes aps load options. |
| [ApsSaveOptions](./apssaveoptions/) | Save options for export to APS XML format. |
| [Artifact](./artifact/) | Class represents PDF [Artifact](./artifact/) object. |
| [ArtifactCollection](./artifactcollection/) | Class represents artifact collection. |
| [AssemblyConstants](./assemblyconstants/) | Defines the constants that participate in the license check for the component. These used to be defined directly as assembly attributes, but I moved them into separate class because in .NET Compact Framework I cannot access assembly attributes. Now the licensing code when compiled for the .NET Compact Framework uses these constants instead of the assembly attributes. |
| [AutoTaggingSettings](./autotaggingsettings/) | Provides settings for the auto-tagging functionality in PDF documents. |
| [BackgroundArtifact](./backgroundartifact/) | Class descibes background artifact. This artifact allows to set background of the page. |
| [BaseActionCollection](./baseactioncollection/) | Class incapsulates basic actions wuth page/annotation/field interactive actions. |
| [BaseOperatorCollection](./baseoperatorcollection/) | Represents base class for operator collection. |
| [BaseParagraph](./baseparagraph/) | Represents a abstract base object can be added to the page(doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Class describes Bates Numbering artifact. |
| [BitmapInfo](./bitmapinfo/) | Object containing array of pixels and bitmap information. |
| [BorderInfo](./borderinfo/) | This class represents border for graphics elements. |
| [BoundsCheckableList](./boundscheckablelist/) | Represents [BoundsCheckableList](./boundscheckablelist/) - wrapper around [System.Collections.Generic.List](../system.collections.generic/list/). |
| [BuildVersionInfo](./buildversioninfo/) | This class provides information about current product build. |
| [CdrLoadOptions](./cdrloadoptions/) | Class describes CDR load options. |
| [Cell](./cell/) | Represents a cell of the table's row. |
| [Cells](./cells/) | Represents a cells collection of row. |
| [Center](./center/) | Represents the center alignment settings for header and footer data. |
| [CgmImportOptions](./cgmimportoptions/) | Import option for import from Computer Graphics Metafile(CGM) format. |
| [CgmLoadOptions](./cgmloadoptions/) | Contains options for loading/importing CGM file into pdf document. |
| [Collection](./collection/) | Represents class for [Collection](./collection/)(12.3.5 [Collections](../aspose.pdf.collections/)). |
| [CollectionField](./collectionfield/) | Represents a document collection schema field class. |
| [CollectionFieldSubtypeConverter](./collectionfieldsubtypeconverter/) | Represents a class for converting [CollectionFieldSubtype](./collectionfieldsubtype/) values. |
| [CollectionItem](./collectionitem/) | Represents a collection item class. The collection item contains the data described by the collection schema. |
| [CollectionSchema](./collectionschema/) | Represents a class that describes the "Schema" of a document collection. |
| [CollectionSort](./collectionsort/) | Represents a class for a collection sort definition. |
| [Color](./color/) | Represents class for color value which can be expressed in different color space. |
| [ColorSpaceConverter](./colorspaceconverter/) |  |
| [ColumnInfo](./columninfo/) | This class represents a columns info. |
| [ComHelper](./comhelper/) | Provides methods for COM clients to load a document into [Aspose.Pdf](./). |
| [CompositingParameters](./compositingparameters/) | Represents an object containing graphics compositing parameters of current graphics state. |
| [CrashReportOptions](./crashreportoptions/) | Options for crash report generating. |
| [DateComponent](./datecomponent/) | Represents a base class for date components with a format attribute. |
| [DestinationCollection](./destinationcollection/) | Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document. |
| [DirectionConverter](./directionconverter/) |  |
| [DjvuLoadOptions](./djvuloadoptions/) | Class describes DJVU load options. |
| [DocSaveOptions](./docsaveoptions/) | Save options for export to Doc format. |
| [Document](./document/) | Class representing PDF document. |
| [DocumentExtensions](./documentextensions/) | Provides additional capabilities for the [Document](./document/) class. |
| [DocumentFactory](./documentfactory/) | Class which allows to create/load documents of different types. |
| [DocumentInfo](./documentinfo/) | Represents meta information of PDF document. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Class representing embedded files collection. |
| [EncryptedPayload](./encryptedpayload/) | Represents encrypted payload in file specification. |
| [EpubLoadOptions](./epubloadoptions/) | Contains options for loading/importing EPUB file into pdf document. |
| [EpubSaveOptions](./epubsaveoptions/) | Save options for export to EPUB format. |
| [ExcelSaveOptions](./excelsaveoptions/) | Save options for export to Excel format. |
| [ExportFieldsOptions](./exportfieldsoptions/) | Represents base class of options for exporting form fields. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Represents options for exporting form fields to Json format. |
| [ExportImportMessages](./exportimportmessages/) | Contains various error messages for export and import operations of form fields. |
| [FieldSerializationResult](./fieldserializationresult/) | Represents the result of a form field serialization process. |
| [FileChecker](./filechecker/) | Represents a class for checking file security. |
| [FileHyperlink](./filehyperlink/) | Represents file hyperlink object. |
| [FileParams](./fileparams/) | Defines an embedded file parameter dictionary that shall contain additional file-specific information. |
| [FileSpecification](./filespecification/) | Class representing embedded file. |
| [FileSpecificationComparer](./filespecificationcomparer/) | Represents a comparator class for a file specification. The comparator compares according to the specification, using the list of fields to sort in the collection definition. According to the specification, sorting is done by collection items values. If there is no collection items dictionary, then sorting is done by Params values. |
| [FloatingBox](./floatingbox/) | Represents a [FloatingBox](./floatingbox/) in a [Pdf](./) document. [FloatingBox](./floatingbox/) is custom positioned. |
| [FontEmbeddingOptions](./fontembeddingoptions/) | PDF/A standard requires, that all fonts must be embedded into document. This class includes flags for cases when it's not possible to embed some font cause this font is absent on destination PC. |
| [Footer](./footer/) | Represents the footer settings. |
| [FooterArtifact](./footerartifact/) | Describes footer artifact. This may be used to set footer of the page. |
| [FormattedFragment](./formattedfragment/) | Represents abstract formatted fragment. |
| [GraphInfo](./graphinfo/) | Represents graphics info. |
| [Group](./group/) | A group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [Header](./header/) | Represents the header settings. |
| [HeaderArtifact](./headerartifact/) | Class describes Heaader artifact. This artifacgt may be used to set heading of the page. |
| [HeaderFooter](./headerfooter/) | Class represents header or footer pdf page. |
| [HeaderFooterData](./headerfooterdata/) | Represents the pagination data for header and footer. |
| [HeaderFooterSettings](./headerfootersettings/) | Represents the settings for header and footer artifacts. |
| [Heading](./heading/) | Represents heading. |
| [HeadingLevels](./headinglevels/) | Represents a class to work with header levels based on font size. |
| [HtmlFragment](./htmlfragment/) | Represents html fragment. |
| [HtmlLoadOptions](./htmlloadoptions/) | Represents options for loading/importing html file into pdf document. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Save options for export to Html format. |
| [Hyperlink](./hyperlink/) | Represents abstract hyperlink. |
| [IBoundsCheckableItem](./iboundscheckableitem/) |  |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Interface for color space conversion strategies. |
| [Id](./id/) | Represents file identifier structure. |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | This interface declared for customization algorithms of quantization. Users can implement their own realization of this algorithms (for example algorithms based on unmanaged code). |
| [Image](./image/) | Represents image. |
| [ImagePlacement](./imageplacement/) | Represents characteristics of an image placed to [Pdf](./) document page. |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via [ImagePlacementAbsorber::ImagePlacements](../) collection. |
| [ImagePlacementCollection](./imageplacementcollection/) | Represents an image placements collection. |
| [ImageStamp](./imagestamp/) | Represents a graphic stamp. |
| [ImportFieldsOptions](./importfieldsoptions/) | Represents base class of options for importing form fields. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Represents options for importing form fields to Json format. |
| [ImportOptions](./importoptions/) | [ImportOptions](./importoptions/) type hold level of abstraction on individual import options. |
| [INamedDestinationCollection](./inameddestinationcollection/) | [Collection](./collection/) of Named Destinations. |
| [IOperatorContainer](./ioperatorcontainer/) | Represents objects that contain a collection of operators as their contents. |
| [IOperatorSelector](./ioperatorselector/) | Defines Visitor for visiting different pdf operators. |
| [IPageSetOptions](./ipagesetoptions/) | Defines conversion options related to a set of pages to convert. |
| [IPipelineOptions](./ipipelineoptions/) | Defines conversion options related to pipeline configuration. |
| [ISupportsMemoryCleanup](./isupportsmemorycleanup/) | The interface defines ways to cleanup memory in case mass operations. |
| [ITeXInputDirectory](./itexinputdirectory/) | Interface of generalized TeX input directory. |
| [ITeXOutputDirectory](./itexoutputdirectory/) | Interface of generalized TeX output directory. |
| [IWarningCallback](./iwarningcallback/) | Interface for user's callback mechanism support. |
| [JavaScriptCollection](./javascriptcollection/) | This class represents collection of JavaScript. |
| [LatexFragment](./latexfragment/) | Represents TeX fragment. |
| [LatexLoadOptions](./latexloadoptions/) | Represents options for loading/importing TeX file into PDF document. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Save options for export to TeX format. |
| [Layer](./layer/) | Represents a layer within a PDF page. |
| [Left](./left/) | Represents the left alignment settings for header and footer data. |
| [LevelFormat](./levelformat/) | Represents format of the table of contents. |
| [License](./license/) | Provides methods to license the component. |
| [LicenseInfo](./licenseinfo/) | Represents a license information. |
| [LoadOptions](./loadoptions/) | [LoadOptions](./loadoptions/) type holds level of abstraction on individual load options. |
| [LocalHyperlink](./localhyperlink/) | Represents local hyperlink object. |
| [MarginInfo](./margininfo/) | This class represents a margin for different objects. |
| [MarkdownSaveOptions](./markdownsaveoptions/) | Represents the document save option class in the markdown format. |
| [Matrix](./matrix/) | Class represents transformation matrix. |
| [Matrix3D](./matrix3d/) | Class represents transformation matrix. |
| [MdLoadOptions](./mdloadoptions/) | Load options for Markdown format conversion. |
| [Metadata](./metadata/) | Provides access to XMP metadata stream. |
| [Metered](./metered/) | Provides methods to set metered key. |
| [MhtLoadOptions](./mhtloadoptions/) | Represents options for loading/importing of .mht-file into pdf document. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Save options for export to Xml format. |
| [NamedDestinationCollection](./nameddestinationcollection/) | Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document. |
| [Note](./note/) | This class represents generator paragraph note. |
| [OcspSettings](./ocspsettings/) | Represents the ocsp settings using during signing process. |
| [OfdLoadOptions](./ofdloadoptions/) | Load options for [OFD](../aspose.pdf.ofd/) format. |
| [Operator](./operator/) | Abstract class representing operator. |
| [OperatorCollection](./operatorcollection/) | Class represents collection of operators. |
| [OperatorSelector](./operatorselector/) | This class is used for selecting operators using Visitor template idea. |
| [Opi](./opi/) | Represents The Open Prepress Interface (OPI) is a mechanism for creating low-resolution placeholders, or proxies, for such high-resolution images. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Defines a MemoryStream that can contains more standard capacity. |
| [OutlineCollection](./outlinecollection/) | Represents document outline hierarchy. |
| [OutlineItemCollection](./outlineitemcollection/) | Represents outline entry in outline hierarchy of PDF document. |
| [Outlines](./outlines/) | Class describes collection of outlines. |
| [OutputIntent](./outputintent/) | Represents an output intent that matches the color characteristics of a PDF document with those of a target output device or production environment in which the document will be printed. |
| [OutputIntents](./outputintents/) | Represents the collection of [OutputIntent](./outputintent/). |
| [Page](./page/) | Class representing page of PDF document. |
| [PageActionCollection](./pageactioncollection/) | This class describes page actions. |
| [PageCollection](./pagecollection/) | [Collection](./collection/) of PDF document pages. |
| [PageCollectionExtensions](./pagecollectionextensions/) | Represents the extension method for updating header and footer pagination. |
| [PageDate](./pagedate/) | Represents a date format composed of day, month, and year components. |
| [PageInfo](./pageinfo/) | Represents the page information. |
| [PageLabel](./pagelabel/) | Class representing [Page](./page/) Label range. |
| [PageLabelCollection](./pagelabelcollection/) | Class represeingting page label collection. |
| [PageLayoutConverter](./pagelayoutconverter/) |  |
| [PageModeConverter](./pagemodeconverter/) |  |
| [PageNumber](./pagenumber/) | Represents a page number format that includes an index, total number of pages, and a delimiter. |
| [PageNumberStamp](./pagenumberstamp/) | Represents page number stamp and used to number pages. |
| [PageRange](./pagerange/) | Represents the range of pages for header and footer settings. |
| [PageSize](./pagesize/) | Class representing size of page in PDF document. |
| [PaginationArtifact](./paginationartifact/) | Represents an abstract base class for pagination artifacts in a document. |
| [Paragraphs](./paragraphs/) | This class represents paragraph collection. |
| [PclLoadOptions](./pclloadoptions/) | Represents options for loading(import) PCL file into pdf document. |
| [PdfANonSpecificationFlags](./pdfanonspecificationflags/) | This class holds flags to control PDF/A conversion for cases when source PDF document doesn't correspond to PDF specification. If flags of this clas are used it decreases performance but it's necessary when source PDF document can't be convert into PDF/A format by usual way. By default all flags are set to false. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | This class describes rules which can be used to tune process of copying encoding data for cases when TrueType symbolic font has more than one encoding. Some PDF documents after conversion into PDF/A format could give an error "More than one encoding in symbolic TrueType font's cmap". What is a reason of this error? All TrueType symbolic fonts have special table "cmap" in it's internal data. This table maps character codes to glyph indices. And this table could contain different encoding subtables which describe encodings used. See advanced info about cmap tables at [https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html](https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html). Usually cmap table contains several encoding subtables, but PDF/A standard requires that either only one encoding subtable must be left for this font in PDF/A document or there must be a (3,0) encoding subtable among this font subtables. And key question here - what data must be taken from another subtables to copy into destination encoding table (3,0)? Majority of fonts have 'well-formed' cmap tables where every encoding subtable is fully consistent with another subtable. But some fonts have cmap tables with collisions - where for example one subtable has glyph index 100 for unicode 100, but another subtable has glyph index 200 for the same unicode 100. To solve this problems special strategy needed. By default following strategy used: mac subtable(1,0) is looked for. If this table is found, only this data used to fill destination table (3,0). If mac subtable is not found then all subtables except (3,0) are iterated and used to copy data into destination (3,0) subtable. Also mapping for every unicode(unicode, glyph index) is copied into destination table only if destination table does not have this unicode at current moment. So, for example if first subtabe has glyph index 100 for unicode 100, and next subtable has glyph index 200 for the same unicode 100, only data from first subtable (unicode=100, glyph index = 100) will be copied. So each previous subtable takes precedence over the next. Properties of this class [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) help tune default behaviour. If property [PreferredCmapEncodingTable](../) of type [QueueItem::CMapEncodingTableType](./pdfasymbolicfontencodingstrategy/queueitem/cmapencodingtabletype/) is set, then relevant subtable will be used in precedence to mac subtable(1,0). Value 'MacTable' from enumeration [QueueItem::CMapEncodingTableType](./pdfasymbolicfontencodingstrategy/queueitem/cmapencodingtabletype/) has no sense in this case, cause it points on the same mac subtable (1,0) which will be used by default. Property [CmapEncodingTablesPriorityQueue](../) discards all priorities for any subtable. If this property is set, then only subtables from declared queue will be used in specified order. If subtables specified are not found then default iteration of all subtables and copy strategy described above will be used. Object [QueueItem](./pdfasymbolicfontencodingstrategy/queueitem/) specifies encoding subtable used. This subtable can be set via combination of members(PlatformID, PlatformSpecificId) or via [QueueItem::CMapEncodingTableType](./pdfasymbolicfontencodingstrategy/queueitem/cmapencodingtabletype/) enumeration. In case when the font has no (3,0) subtable some other subtable will be used to maintain the PDF/A compatibility. The choice of the subtable to use is made under the same rules as described earlier, so that [PreferredCmapEncodingTable](../) and [CmapEncodingTablesPriorityQueue](../) properties are used to determine the resultant subtable, and if the font doesn't have the requested subtable(s) either then any existant subtable will be used. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | represents set of options for convert PDF document |
| [PdfPageStamp](./pdfpagestamp/) | Class represents stamp which uses PDF page as stamp. |
| [PdfSaveOptions](./pdfsaveoptions/) | Save options for export to [Pdf](./) format. |
| [PdfVersionMethods](./pdfversionmethods/) | Extra methods for enum [PdfVersion](./pdfversion/). |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Load options for PdfXml format. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Save options for PdfXml format. |
| [Point](./point/) | Represent point with fractional coordinates. |
| [Point3D](./point3d/) | Represent point with fractional coordinates. |
| [PptxSaveOptions](./pptxsaveoptions/) | Save options for export to SVG format. |
| [PrintDuplexConverter](./printduplexconverter/) |  |
| [PrintScalingConverter](./printscalingconverter/) | Represents conversion routines between [PrintScaling](./printscaling/) value and string representation. |
| [PsLoadOptions](./psloadoptions/) | Represents options for loading/importing of .mht-file into pdf document. |
| [PsSaveOptions](./pssaveoptions/) | Save options for export to PS (PostScript) or EPS format. |
| [Rectangle](./rectangle/) | Class represents rectangle. |
| [RenderingOptions](./renderingoptions/) | Represents rendering options. |
| [Resources](./resources/) | Class representing page resources. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Represents rgb to device gray color spaces conversion strategy. |
| [Right](./right/) | Represents the right alignment settings for header and footer data. |
| [Row](./row/) | Represents a row of the table. |
| [Rows](./rows/) | Represents a rows collection of table. |
| [SaveOptions](./saveoptions/) | [SaveOptions](./saveoptions/) type hold level of abstraction on individual save options. |
| [SignaturesCompromiseDetector](./signaturescompromisedetector/) | Represents a class for checking compromising signatures of the document. |
| [Stamp](./stamp/) | An abstract class for various kinds of stamps which come as descendants. |
| [SvgLoadOptions](./svgloadoptions/) | Represents options for loading/importing SVG file into pdf document. |
| [SvgSaveOptions](./svgsaveoptions/) | Save options for export to SVG format. |
| [Table](./table/) | Represents a table that can be added to the page. |
| [TeXFileSystemInputDirectory](./texfilesysteminputdirectory/) | Implements the regular file system's method for getting a file stream to read from. |
| [TeXFileSystemOutputDirectory](./texfilesystemoutputdirectory/) | Implements the regular file system's method for getting a file stream to write to. |
| [TeXFragment](./texfragment/) | Represents TeX fragment. |
| [TeXLoadOptions](./texloadoptions/) | Represents options for loading/importing TeX file into PDF document. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implements fetching an output stream from memory. You can use it, for example, when you don't want the accompanying output (like a log file) to be written to disk but you'd like to read it afterwards from memory. |
| [TeXSaveOptions](./texsaveoptions/) | Save options for export to TeX format. |
| [TextStamp](./textstamp/) | Represents textual stamp. |
| [TimestampSettings](./timestampsettings/) | Represents the ocsp settings using during signing process. |
| [TocInfo](./tocinfo/) | Represents table of contents info. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode". |
| [TxtLoadOptions](./txtloadoptions/) | Load options for TXT to PDF conversion. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | This class represents saving options for saving that uses unified conversion way (with unified internal document model) |
| [WarningInfo](./warninginfo/) | Immutable object for encapsulating warning information. |
| [Watermark](./watermark/) | Represents a watermark of the page. |
| [WatermarkArtifact](./watermarkartifact/) | Class describes watermark artifact. This may be used to. |
| [WebHyperlink](./webhyperlink/) | Represents web hyperlink object. |
| [XForm](./xform/) | Class represent [XForm](./xform/). |
| [XFormCollection](./xformcollection/) | Class represents collection of [XFormCollection](./xformcollection/). |
| [XImage](./ximage/) | Class representing image X-Object. |
| [XImageAddingParams](./ximageaddingparams/) |  |
| [XImageCollection](./ximagecollection/) | Class representing [XImage](./ximage/) collection. |
| [XmlLoadOptions](./xmlloadoptions/) | Represents options for loading/importing XML file into pdf document. |
| [XmlSaveOptions](./xmlsaveoptions/) | Save options for export to Xml format. |
| [XmpField](./xmpfield/) | Represents XMP field. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI: [http://www.aiim.org/pdfa/ns/field#](http://www.aiim.org/pdfa/ns/field#) Required schema namespace prefix: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Represents the base class for field, property, value type instances. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Describes a single property. Schema namespace URI: [http://www.aiim.org/pdfa/ns/property#](http://www.aiim.org/pdfa/ns/property#) Required schema namespace prefix: pdfaProperty. |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Describes the XMP extension schema which is provided by PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Represents the description of XMP extension schema which is provided by PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: |
| [XmpValue](./xmpvalue/) | Represents XMP value. |
| [XpsLoadOptions](./xpsloadoptions/) | Represents options for loading/importing xps file into pdf document. |
| [XpsSaveOptions](./xpssaveoptions/) | Save options for export to Xps format. |
| [XslFoLoadOptions](./xslfoloadoptions/) | Represents options for loading/importing XSL-FO file into pdf document. |
## Enums

| Enum | Description |
| --- | --- |
| [AFRelationship](./afrelationship/) | Enumeration describes associated files relationship. |
| [BlendMode](./blendmode/) | The blend modes enumeration. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumerates the border corner styles for border. |
| [BorderSide](./borderside/) | Enumerates the border sides. |
| [BoundsCheckMode](./boundscheckmode/) | Specifies the behavior for bounds checking when adding items to a collection. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Represents the subtype parameter of a field in a sceme collection. |
| [ColorSpace](./colorspace/) | The color spaces enumeration. |
| [ColorType](./colortype/) | Specifies color type of elements on page. |
| [ColumnAdjustment](./columnadjustment/) | Enumerates column adjustment types. |
| [ContentDisposition](./contentdisposition/) | MIME protocol Content-Disposition header. |
| [ConvertErrorAction](./converterroraction/) | This class represents action for conversion errors. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | This action represents actions for conversion of images with soft mask. |
| [ConvertTransparencyAction](./converttransparencyaction/) | This class represents action for conversion of transparency. |
| [CryptoAlgorithm](./cryptoalgorithm/) | Represent type of cryptographic algorithm that used in encryption/decryption routines. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Represent type of algorithm that maps data to a "hash". |
| [Direction](./direction/) | [Text](../aspose.pdf.text/) direction. |
| [EditionType](./editiontype/) | Specifies the edition type of the license. |
| [EmphasisStyle](./emphasisstyle/) | Defines the available serialization styles for emphasis and strong emphasis. For specification see CommonMark - Emphasis and strong emphasis. |
| [ExtendedBoolean](./extendedboolean/) | Represents boolean type that supports Undefined value. |
| [ExtractImageMode](./extractimagemode/) | Defines different modes which can be used while extracting images from documents. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Represents the status of the form field serialization. |
| [FieldValueType](./fieldvaluetype/) | Represents the type of a field value in a schema collection. |
| [FileEncoding](./fileencoding/) | Encoding of the attached file. Possible values: Zip - file is compressed with ZIP, None - file is non compressed. |
| [Fixup](./fixup/) | This enum represents an type of [Fixup](./fixup/). |
| [FontSubsetStrategy](./fontsubsetstrategy/) | enumerates strategies for font subsetting |
| [HeadingRecognitionStrategy](./headingrecognitionstrategy/) | Represents types of header recognition strategies. |
| [HeadingStyle](./headingstyle/) | Defines the available serialization styles for headings. For specification see CommonMark - ATX headings, respectively CommonMark - Setext headings. |
| [HorizontalAlignment](./horizontalalignment/) | Describes horizontal alignment. |
| [HtmlDocumentType](./htmldocumenttype/) | Represents enumeration of the Html document types. |
| [HtmlMediaType](./htmlmediatype/) | Specifies possible media types used during rendering. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Specifies flags that together other options determine sizes and layouts of pages. |
| [ImageDeleteAction](./imagedeleteaction/) | Action which performed with image object when image is removed from collection. If image object is removed. |
| [ImageFileType](./imagefiletype/) | Enumerates the image file types. |
| [ImageFilterType](./imagefiltertype/) | Enumeration representing image filter type. |
| [ImportFormat](./importformat/) | Specifies import format. |
| [LicenseState](./licensestate/) | Represents possible license states. |
| [LineBreakStyle](./linebreakstyle/) | Represents the possible line break styles for a file. |
| [LoadFormat](./loadformat/) | Specifies load format. |
| [NumberingStyle](./numberingstyle/) | Enumeration of supported page numbering style for [PageLabel](./pagelabel/) class. |
| [PageCoordinateType](./pagecoordinatetype/) | Describes page coordinate type. |
| [PageLayout](./pagelayout/) | Descibes page layout. |
| [PageMode](./pagemode/) | Class descibes used components of the document page. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Specifies variant for determining the location of the element on the page. |
| [PasswordType](./passwordtype/) | This enum represents known password types used for password protected pdf documents. |
| [PdfFormat](./pdfformat/) | This class represents an pdf format. |
| [PdfVersion](./pdfversion/) | This enum represents version of pdf file. |
| [Permissions](./permissions/) | This enum represents user's permissions for a pdf. |
| [PrintDuplex](./printduplex/) | The paper handling option to use when printing the file from the print dialog.. |
| [PrintScaling](./printscaling/) | The page scaling option that shall be selected when a print dialog is displayed for this document. |
| [ProductType](./producttype/) | Which product of the license or black list : **Aspose**, Conholdate. |
| [ProgressEventType](./progresseventtype/) | This enum describes possible progress event types that can occure during conversion. |
| [ReturnAction](./returnaction/) | Enum represented a program workflow action in case of invoking the [IWarningCallback::Warning(Aspose::Pdf::WarningInfo)](../) method. |
| [Rotation](./rotation/) | Enumeration of possible rotation values. |
| [SaveFormat](./saveformat/) | Specifies format. |
| [Subset](./subset/) | Represents the subset of pages to which a pagination artifact can apply. |
| [TableBroken](./tablebroken/) | Enumerates the table broken. |
| [TabOrder](./taborder/) | Tab order on the page. |
| [TeXLoadResult](./texloadresult/) | Results for TeX load and compiling. |
| [VerticalAlignment](./verticalalignment/) | Enumeration of possible vertical alignment values. |
| [WarningType](./warningtype/) | Enum represented warning type. |
| [XfaTag](./xfatag/) | The xfa stream tag. |
| [XmpFieldType](./xmpfieldtype/) | This enum represents types of a XMP field. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Property category: internal or external. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BoundsOutOfRangeException](./boundsoutofrangeexception/) |  |
| [ConvertException](./convertexception/) |  |
| [DeprecatedFeatureException](./deprecatedfeatureexception/) |  |
| [EmbeddedFilesDoesNotExists](./embeddedfilesdoesnotexists/) |  |
| [EmptyValueException](./emptyvalueexception/) |  |
| [FontEmbeddingException](./fontembeddingexception/) |  |
| [FontNotFoundException](./fontnotfoundexception/) |  |
| [IncorrectCMapUsageException](./incorrectcmapusageexception/) |  |
| [IncorrectFontUsageException](./incorrectfontusageexception/) |  |
| [InvalidCgmFileFormatException](./invalidcgmfileformatexception/) |  |
| [InvalidFileFormatException](./invalidfileformatexception/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) |  |
| [InvalidPasswordException](./invalidpasswordexception/) |  |
| [InvalidPdfFileFormatException](./invalidpdffileformatexception/) |  |
| [InvalidValueFormatException](./invalidvalueformatexception/) |  |
| [JavascriptExtensionsException](./javascriptextensionsexception/) |  |
| [ObjectReferenceCorruptedException](./objectreferencecorruptedexception/) |  |
| [PdfException](./pdfexception/) |  |
| [UnsupportedFontTypeException](./unsupportedfonttypeexception/) |  |
## Functions

| Function | Description |
| --- | --- |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
