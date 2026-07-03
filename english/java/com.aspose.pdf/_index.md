---
title: com.aspose.pdf
linktitle: com.aspose.pdf
second_title: Aspose.PDF for Java API Reference
description: The com.aspose.pdf is a root package for all classes of Aspose.PDF for Java library which are either directly in it like Document or indirectly through several subpackages.
type: docs
weight: 10
url: /java/com.aspose.pdf/
---
The com.aspose.pdf is a root package for all classes of Aspose.PDF for Java library which are either directly in it like Document or indirectly through several subpackages.

## Interfaces

| Interface | Description |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | The call back procedure for hocr recognize. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | The call back procedure for hocr recognize. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | The call back procedure for hocr recognize. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Holds functionality to tune fonts |
| [IAnnotationVisitor](./iannotationvisitor/) | Defines Visitor for visiting different document annotations. |
| [IAppointment](./iappointment/) | Represents general interface for actions and destinations. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Interface for color space conversion strategies. |
| [IDocument](./idocument/) | interface representing PDF document |
| [IFontOptions](./ifontoptions/) | Useful properties to tune Font behavior |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | This interface declared for customization algorithms of quantization. Users can implement their own realization of this algorithms (for example algorithms based on unmanaged code). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | This interface declared for customization algorithms of quantization. Users can implement their own realization of this algorithms (for example algorithms based on unmanaged code). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Defines Visitor for visiting different pdf operators. |
| [IPageSetOptions](./ipagesetoptions/) | Defines conversion options related to a set of pages to convert. |
| [IPipelineOptions](./ipipelineoptions/) | Defines conversion options related to pipeline configuration. |
| [ITableElement](./itableelement/) | This interface represents an element of existing table extracted by TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.PDf in cloud direct access to referenced files impossible, and some custom code put into special method should be used. This delegate defines signature of such custom method. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Set the flag whether the temporary folder will be used to host temporary font data. / * True by default. / * Used heap memory if value = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | To property of such type You can assign delegate created from custom method that implements processing of external saving of image that was extracted from SVG created from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like self-made saving into stream or on disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated SVG instead of original supposed path to that image resource. In such case all the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code . |
## Classes

| Class | Description |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Represents cell of table that exist on the page |
| [AbsorbedRow](./absorbedrow/) | Represents row of table that exist on the page |
| [AbsorbedTable](./absorbedtable/) | Represents table that exist on the page |
| [ActionCollection](./actioncollection/) | Collection of actions |
| [Annotation](./annotation/) | Class representing an annotation object. |
| [AnnotationActionCollection](./annotationactioncollection/) | Represents the collection of annotation actions. |
| [AnnotationCollection](./annotationcollection/) | Class representing annotation collection. |
| [AnnotationFlags](./annotationflags/) | Flags A set of binary flags specifying various characteristics of the annotation. |
| [AnnotationSelector](./annotationselector/) | This class is used for selecting annotations using Visitor template idea. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Class for rendering normal and rich text. |
| [AppearanceDictionary](./appearancedictionary/) | Annotation appearance dictionary specifying how the annotation shall be presented visually on the page. |
| [ApsLoadOptions](./apsloadoptions/) | Class describes aps load options. Option for import from APS XML format. |
| [ApsSaveOptions](./apssaveoptions/) | Save options for export to APS XML format. |
| [ApsToFlowConverter](./apstoflowconverter/) | APS to Flow Conversion |
| [Artifact](./artifact/) | Class represents PDF Artifact object. |
| [ArtifactCollection](./artifactcollection/) | Class represents artifact collection. |
| [AutoTaggingSettings](./autotaggingsettings/) | Provides settings for the auto-tagging functionality in PDF documents. The {@link AutoTaggingSettings} class allows configuring options for automatic tagging of PDF content. It includes properties to enable or disable auto-tagging, specify a strategy for heading recognition, and define heading levels based on font sizes. |
| [BackgroundArtifact](./backgroundartifact/) | Class describes background artifact. This artifact allows to set background of the page. |
| [BarcodeField](./barcodefield/) | Class represents barcode field. |
| [BaseActionCollection](./baseactioncollection/) | Class encapsulates basic actions with page/annotation/field interactive actions |
| [BaseOperatorCollection](./baseoperatorcollection/) | Represents base class for operator collection. |
| [BaseParagraph](./baseparagraph/) | Represents a abstract base object can be added to the page(doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Class describes Bates Numbering artifact. |
| [BitmapInfo](./bitmapinfo/) | Object containing array of pixels and bitmap information. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Bitmap pixel format. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Represents a Bleed Mark annotation. Bleed marks are placed at the corners of a printed page to indicate where the page is to be trimmed and how far it is allowed to deviate from the trim marks. |
| [Border](./border/) | Class representing characteristics of annotation border. |
| [BorderInfo](./borderinfo/) | This class represents border for graphics elements. |
| [BorderSide](./borderside/) | Flags Enumerates binary the border sides. |
| [BorderStyleConverter](./borderstyleconverter/) | Represents BorderStyleConverter class |
| [Brush](./brush/) | This class represents abstract brush |
| [BuildVersionInfo](./buildversioninfo/) | This class provides information about current product build. |
| [ButtonField](./buttonfield/) | Class represents push button field. |
| [CaretAnnotation](./caretannotation/) | Class representing Caret annotation. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Represents CaretSymbolConverter class |
| [CdrLoadOptions](./cdrloadoptions/) | Class describes CDR load options. |
| [Cell](./cell/) | Represents a cell of the table's row. |
| [Cells](./cells/) | Represents a cells collection of row. |
| [CgmImportOptions](./cgmimportoptions/) | Import option for import from Computer Graphics Metafile(CGM) format. |
| [CgmLoadOptions](./cgmloadoptions/) | Contains options for loading/importing CGM file into pdf document. |
| [Characteristics](./characteristics/) | Represents annotation characteristics |
| [CharInfo](./charinfo/) | Represents a character info object. Provides character positioning information. |
| [CharInfoCollection](./charinfocollection/) | <p> Represents CharInfo objects collection. </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Provides access to positioning information of text segment characters. </p> |
| [CheckboxField](./checkboxfield/) | Class representing checkbox field |
| [ChoiceField](./choicefield/) | Represents base class for choice fields. |
| [CircleAnnotation](./circleannotation/) | Class representing Circle annotation. |
| [Collection](./collection/) | Represents class for Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Represents a document collection schema field class. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Represents the subtype parameter of a field in a sceme collection. |
| [CollectionItem](./collectionitem/) | Represents a collection item class. The collection item contains the data described by the collection schema. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Represents a class for a value of collection item. |
| [CollectionSchema](./collectionschema/) | Represents a class that describes the "Schema" of a document collection. |
| [Color](./color/) | Represents class for color value which can be expressed in different color space. |
| [ColorBarAnnotation](./colorbarannotation/) | Class representing ColorBarAnnotation annotation. Property Color ignored, instead used ColorsOfCMYK color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed). |
| [ColumnInfo](./columninfo/) | This class represents a column's info. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Class representing events |
| [ComboBoxField](./comboboxfield/) | Class representing Combobox field of the form. |
| [ComHelper](./comhelper/) | <p> Provides methods for COM clients to load a document into Aspose.PDF. </p> <hr> <p> Use the ComHelper class to load a document from a file or stream into a Document object in a COM application. The Document class provides a default constructor to create a new document and also provides overloaded constructors to load a document from a file or stream. If you are using Aspose.Words from a .NET application, you can use all of the Document constructors directly, but if you are using Aspose.PDF from a COM application, only the default Document constructor is available. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstract class representing common figure annotation. |
| [CompositingParameters](./compositingparameters/) | Represents an object containing graphics compositing parameters of current graphics state. |
| [ContentsAppender](./contentsappender/) | Performs contents modifications in APPEND mode only. this mode allows to avoid unneeded and heavy contents parsing before some change is made to the contents. It only appends new operators to the end or to the begin of the contents |
| [Copier](./copier/) | Class for coping object |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Represents annotation types that are placed in the corners of the printed page. |
| [CustomExplicitDestination](./customexplicitdestination/) | Represents custom explicit destination. |
| [CustomSign](./customsign/) | Delegate for custom sign the document (Beta). |
| [Dash](./dash/) | Class representing line dash pattern. |
| [DateField](./datefield/) | Date field with calendar view. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Describes default appearance of field (font, text size and color). |
| [DefaultDirectory](./defaultdirectory/) | Specifies default path for some purpose |
| [DestinationCollection](./destinationcollection/) | Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document. |
| [DestinationFactory](./destinationfactory/) | Represents DestinationFactory class |
| [DjvuLoadOptions](./djvuloadoptions/) | Class describes DJVU load options. |
| [DocMDPSignature](./docmdpsignature/) | Represents the class of document MDP (modification detection and prevention) signature type. |
| [DocSaveOptions](./docsaveoptions/) | Save options for export to Doc format |
| [Document](./document/) | Class representing PDF document. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method. @deprecated This class is obsolete. Please use com.aspose.pdf.optimization.OptimizationOptions instead. |
| [Document.RepairOptions](./document.repairoptions/) | Represents options for repairing a PDF document. This class provides a way to customize the repair process of a PDF document. |
| [DocumentActionCollection](./documentactioncollection/) | Class describes actions performed on some actions with document |
| [DocumentExtensions](./documentextensions/) | Provides additional capabilities for the Document class. |
| [DocumentFactory](./documentfactory/) | Class which allows to create/load documents of different types. |
| [DocumentInfo](./documentinfo/) | Represents meta information of PDF document. |
| [DocumentWeb](./documentweb/) | Represents DocumentWeb class |
| [Element](./element/) | Class representing base element of logical structure. |
| [ElementCollection](./elementcollection/) | Collection of base logical structure elements. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Class representing embedded files collection. |
| [EncryptedPayload](./encryptedpayload/) | Represents encrypted payload in file specification. |
| [EpubLoadOptions](./epubloadoptions/) | Contains options for loading/importing EPUB file into pdf document. |
| [EpubSaveOptions](./epubsaveoptions/) | Save options for export to EPUB format |
| [ExcelSaveOptions](./excelsaveoptions/) | Save options for export to Excel format |
| [ExplicitDestination](./explicitdestination/) | Represents the base class for explicit destinations in PDF document. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Represents ExplicitDestinationTypeConverter class |
| [ExportFieldsOptions](./exportfieldsoptions/) | Represents base class of options for exporting form fields. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Represents options for exporting form fields to Json format. Inherits from {@link ExportFieldsOptions} and adds specific options for Json export. |
| [ExportImportMessages](./exportimportmessages/) | Contains various error messages for export and import operations of form fields. |
| [ExternalSignature](./externalsignature/) | Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [FdfReader](./fdfreader/) | Class which performs reading of FDF format. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | Base class for acro form fields. |
| [FieldSerializationResult](./fieldserializationresult/) | Represents the result of a form field serialization process. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Represents the status of the form field serialization. |
| [FieldValueType](./fieldvaluetype/) | Represents the type of field value in a schema collection. |
| [FigureElement](./figureelement/) | Class representing logical structure figure. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Class describes file attachment annotation. |
| [FileFontSource](./filefontsource/) | Represents single font file source. |
| [FileHyperlink](./filehyperlink/) | Represents file hyperlink object. |
| [FileIconConverter](./fileiconconverter/) | Represents FileIconConverter class |
| [FileParams](./fileparams/) | Defines an embedded file parameter dictionary that shall contain additional file-specific information. |
| [FileSelectBoxField](./fileselectboxfield/) | Field for file select box element. |
| [FileSpecification](./filespecification/) | Class representing embedded file. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged. |
| [FitExplicitDestination](./fitexplicitdestination/) | Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged. |
| [FixedPrint](./fixedprint/) | Represent Fixed print data of Watermark Annotation. |
| [FloatingBox](./floatingbox/) | Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned. |
| [FlowConverter](./flowconverter/) | Convert PDF Document to Flow formats (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX in EnchanedFlow mode, TableAbsorber in FlowEngine mode. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Passing data from Flow library to TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Represents the folder that contains font files. |
| [Font](./font/) | <p> Represents font object. </p> <hr> <pre> The example demonstrates how to search text on first page and change font of a first search occurrence. // Open document Document doc = new Document("input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Represents an absorber object of fonts. Performs search for fonts and provides access to search results via {@code FontAbsorber.Fonts} collection. |
| [FontCollection](./fontcollection/) | <p> Represents font collection. </p> <hr> <pre> The example demonstrates how to make all font declared on page as embedded. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> Font collections represented by {@code FontCollection} class are used in several scenarios. For example, in resources with {@code Resources.Fonts} property. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | PDF/A standard requires, that all fonts must be embedded into document. This class includes flags for cases when it's not possible to embed some font cause this font is absent on destination PC. |
| [FontRepository](./fontrepository/) | <p> Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Represents a base class fot font source. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Specifies style information applied to text. </p> <hr> <p> This enumeration has a {@code FlagsAttribute} attribute that allows a combination of its member values. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag enumerates strategies for font subsetting |
| [FooterArtifact](./footerartifact/) | Describes footer artifact. This may be used to set footer of the page. |
| [Form](./form/) | Class representing form object. |
| [Form.FlattenSettings](./form.flattensettings/) | Class which describes settings for Form flattening procedure. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Forms can contain signing information and can be signed or unsigned. Sometimes view of forms in viewer must depend on whether form is signed or not. This enum enumerates possible rendering modes during conversion of form type in regard to sign. |
| [FormattedFragment](./formattedfragment/) | Represents abstract formatted fragment. |
| [FreeTextAnnotation](./freetextannotation/) | Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible. |
| [GoToAction](./gotoaction/) | Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor). |
| [GoToRemoteAction](./gotoremoteaction/) | Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file. |
| [GoToURIAction](./gotouriaction/) | Represents a URI action causes a URI to be resolved. |
| [GraphInfo](./graphinfo/) | Represents graphics info. |
| [Group](./group/) | A group attributes class specifying the attributes of the page’s page group for use in the transparent imaging model. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | Class describes Heaader artifact. This artifacgt may be used to set heading of the page. |
| [HeaderFooter](./headerfooter/) | Class represents header or footer pdf page. |
| [Heading](./heading/) | Represents heading. |
| [HideAction](./hideaction/) | Represents a hide action that hides or shows one or more annotations on the screen by setting or clearing their Hidden flags. |
| [HighlightAnnotation](./highlightannotation/) | Represents a highlight annotation that highlights a range of text in the document. |
| [HtmlFragment](./htmlfragment/) | Represents html fragment. |
| [HtmlLoadOptions](./htmlloadoptions/) | Represents options for loading/importing html file into pdf document. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binary Flag Specifies flags that together other options determine sizes and layouts of pages. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Save options for export to Html format |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | This enum describes possible antialiasing measures during conversion |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | You can assign to this property custom strategy that implements processing or/and saving of one CSS's part that was created during conversion of PDF to HTML . In such case processing (like saving to stream or disk) must be done in that custom code |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as "otherPage.ASPX?CssID=zjjkklj" Then such custom strategy must return "otherPage.ASPX?CssID=zjjkklj" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Represents set of data that related to request from converter to custom code aimed to get desirable URL (or URL template)of subject CSS |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | This enumeration defines rules which tune encoding logic |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Enumerates modes that can be used for saving of fonts referenced in saved PDF. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | This class represents set of data that related to external resource image file's saving during PDF to HTML conversion. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | enumerates possible types of image files that can be saved as external resources during Pdf to Html conversion |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Sometimes specific reqirments to created HTML are present. This enum defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | If SplitToPages property of HtmlSaveOptions, then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTML-page's markup during conversion of PDF to HTML |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Result of conversion can contain one or several HTML-pages ( that also can reference external files like images or fonts) You can assign to this property delegate created from custom method that implements processing of got HTML-page(HTML itself) that was created during conversion. In such case processing (like saving in stream or disk) can be done in that custom code . In such case All the necessary actions for saving of HTML page's markup must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it signals to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom saving code . |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Enumerates possible types of image's parents Image can pertain to HTML page or to SVG parent image |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | Converted PDF can contain raster images(.png, *.jpeg etc.) This enum defines methods of how raster images can be handled during conversion of PDF to HTML |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code . |
| [Hyperlink](./hyperlink/) | Represents abstract hyperlink. |
| [IconFit](./iconfit/) | Describes how the widget annotation's icon shall be displayed within its annotation rectangle. |
| [Id](./id/) | <p> Represents file identifier structure. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Represents image. |
| [ImageDeleteAction](./imagedeleteaction/) | Action which performed with image object when image is removed from collection. If image object is removed |
| [ImagePlacement](./imageplacement/) | <p> Represents characteristics of an image placed to Pdf document page. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> When an image is placed to a page it may have dimensions other than physical dimensions defined in {@code Resources}. The object {@code ImagePlacement} is intended to provide such information like dimensions, resolution and so on. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via {@code ImagePlacementAbsorber.ImagePlacements} collection. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get the image placement properties. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> The {@code ImagePlacementAbsorber} object is basically used in images search scenario. When the search is completed the occurrences are represented with {@code ImagePlacement} objects that the {@code ImagePlacementAbsorber.ImagePlacements} collection contains. The {@code ImagePlacement} object provides access to the image placement properties: dimensions, resolution etc. </p> Image positive rotation is counterclockwise, for the page, it is clockwise. Here, we need to represent the image rotation angle, so we deduct the page angle from the image angle. |
| [ImagePlacementCollection](./imageplacementcollection/) | Represents an image placements collection |
| [ImageStamp](./imagestamp/) | Represents a graphic stamp. |
| [ImageType](./imagetype/) | Represents image format types. |
| [ImportDataAction](./importdataaction/) | Upon invocation of an import-data action, Forms Data Format (FDF) data shall be imported into the document's interactive form from a specified file. |
| [ImportFieldsOptions](./importfieldsoptions/) | Represents base class of options for importing form fields. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Represents options for importing form fields to Json format. Inherits from {@code ImportFieldsOptions} and adds specific options for Json import. |
| [ImportOptions](./importoptions/) | ImportOptions type hold level of abstraction on individual import options. |
| [InkAnnotation](./inkannotation/) | Represents a freehand "scribble" composed of one or more disjoint paths. |
| [InternalHelper](./internalhelper/) | Internal class |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | The exception that is thrown when an operation with form type is not valid. |
| [JavascriptAction](./javascriptaction/) | Class representing javascript action. |
| [JavaScriptCollection](./javascriptcollection/) | This class represents collection of JavaScript. |
| [LatexFragment](./latexfragment/) | Represents TeX fragment. @deprecated Please use TeXFragment instead |
| [LatexLoadOptions](./latexloadoptions/) | Represents options for loading/importing TeX file into PDF document. @deprecated Use TeXLoadOptions instead. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Save options for export to TeX format. @deprecated Use TeXSaveOptions instead |
| [LaunchAction](./launchaction/) | Represents a launch action that launches an application or opens or prints a document. |
| [Layer](./layer/) | Represents a layer within a PDF page. |
| [LevelFormat](./levelformat/) | Represents format of the table of contents. |
| [License](./license/) | Provides methods to license the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Represents a license information. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Lightweight operator collection. Intended to be used in scenarios when underlying contents stream is not attached, where just operator collection is required as a result. |
| [LineAnnotation](./lineannotation/) | Class representing line annotation. |
| [LineEndingConverter](./lineendingconverter/) | Represents LineEndingConverter class |
| [LineEndingsDrawer](./lineendingsdrawer/) | Draws line endings for annotations. Internal class for internal usage only. |
| [LinkAnnotation](./linkannotation/) | Represents either a hypertext link to a destination elsewhere in the document or an action to be performed. |
| [ListBoxField](./listboxfield/) | Class represents ListBox field. |
| [LoadOptions](./loadoptions/) | LoadOptions type holds level of abstraction on individual load options |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specifies horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Result of custom loading of resource |
| [LocaleOptions](./localeoptions/) | LocaleOptions type specifies locale configuration for Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Represents local hyperlink object. |
| [MarginInfo](./margininfo/) | This class represents a margin for different objects. |
| [MarkupAnnotation](./markupannotation/) | Abstract class representing markup annotation. |
| [MarkupParagraph](./markupparagraph/) | Represents a paragraph. |
| [MarkupSection](./markupsection/) | Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks. |
| [Matrix](./matrix/) | Class represents transformation matrix. |
| [Matrix3D](./matrix3d/) | Class represents transformation matrix. |
| [MdLoadOptions](./mdloadoptions/) | Load options for Markdown format conversion. |
| [Measure](./measure/) | Class which describes Measure coordinate system. |
| [Measure.NumberFormat](./measure.numberformat/) | Number format for measure. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Represents list of number formats. |
| [MediaClip](./mediaclip/) | Class describes media clip object of rendition. |
| [MediaClipData](./mediaclipdata/) | Class describes media clip data. |
| [MediaClipSection](./mediaclipsection/) | This class descibes Media clip section. |
| [MediaRendition](./mediarendition/) | Class describes media rendition. |
| [MemoryCleaner](./memorycleaner/) | Represents MemoryCleaner class |
| [MemoryExtender](./memoryextender/) | Represents MemoryExtender class Using large files on a system with limited heap memory, can be enabled to use disk space as a temporary swap memory. |
| [MemoryFontSource](./memoryfontsource/) | Represents single font file source. |
| [Metadata](./metadata/) | Provides access to XMP metadata stream. |
| [Metered](./metered/) | <p> Provides methods to set metered key. </p> <hr> In this example, an attempt will be made to set metered public and private key <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Represents options for loading/importing of .mht-file into pdf document. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Save options for export to Xml format |
| [MovieAnnotation](./movieannotation/) | Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played. |
| [NamedAction](./namedaction/) | Represents named actions that PDF viewer applications are expected to support. |
| [NamedDestination](./nameddestination/) | Instead of being defined directly with the explicit syntax, a destination may be referred to indirectly by means of a name object or a byte string. |
| [Note](./note/) | This class represents generator paragraph note. |
| [NumberField](./numberfield/) | Text Field with specified valid chars @see TextBoxField |
| [NumberTree](./numbertree/) | Class representing Number tree structure of PDF file. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Represents the ocsp settings using during signing process. |
| [OfdLoadOptions](./ofdloadoptions/) | Load options for OFD format. |
| [Operator](./operator/) | Abstract class representing operator. |
| [OperatorCollection](./operatorcollection/) | Class represents collection of operators |
| [OperatorSelector](./operatorselector/) | This class is used for selecting operators using Visitor template idea. |
| [Opi](./opi/) | Represents The Open Prepress Interface (OPI) is a mechanism for creating low-resolution placeholders, or proxies, for such high-resolution images. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Defines a MemoryStream that can contains more standard capacity |
| [Option](./option/) | Class represents option of choice field. |
| [OptionCollection](./optioncollection/) | Class representing collection of options of the choice field. |
| [OutlineCollection](./outlinecollection/) | Represents document outline hierarchy. |
| [OutlineItemCollection](./outlineitemcollection/) | Represents outline entry in outline hierarchy of PDF document. |
| [Outlines](./outlines/) | Class describes collection of outlines. |
| [OutputIntent](./outputintent/) | Represents an output intent that matches the color characteristics of a PDF document with those of a target output device or production environment in which the document will be printed. |
| [OutputIntents](./outputintents/) | Represents the collection of {@link OutputIntent}. |
| [Page](./page/) | Class representing page of PDF document. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Procedure for customize header and footer. |
| [PageActionCollection](./pageactioncollection/) | This class describes page actions |
| [PageCollection](./pagecollection/) | Collection of PDF document pages. |
| [PageExtensions](./pageextensions/) | Provides additional capabilities for the Page class. |
| [PageInfo](./pageinfo/) | Represents the page information for pdf generator. |
| [PageInformationAnnotation](./pageinformationannotation/) | Represents a Page Information annotation in a PDF document. This annotation contains the file name, page number, and the date and time of the annotation creation. This class is primarily used to add metadata to a specific page in the PDF document, which can be useful for tracking and referencing purposes. For instance, it can be used to mark pages during the printing process or to provide additional information about the page when viewing the document. |
| [PageLabel](./pagelabel/) | Class representing Page Label range. |
| [PageLabelCollection](./pagelabelcollection/) | Class represeingting page label collection. |
| [PageMarkup](./pagemarkup/) | Page markup represented by collections of {@code MarkupSection} and {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Represents page number stamp and used to number pages. |
| [PageSize](./pagesize/) | Class representing size of page in PDF document. |
| [PaginationArtifact](./paginationartifact/) | Represents an abstract base class for pagination artifacts in a document. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via {@code TextFragments} collections grouped by structure elements. </p> The example demonstrates how to find first text segment of each paragraph on the first PDF document page and highlight it. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> When the search is completed the {@code ParagraphAbsorber.PageMarkups} collection will contains {@code PageMarkup} objects that represents page structure by collections of {@code MarkupSection} and {@code MarkupParagraph}. The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Represents options for the {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | This class represents paragraph collection. |
| [PasswordBoxField](./passwordboxfield/) | Class descibes text field for entering password. |
| [PclLoadOptions](./pclloadoptions/) | Represents options for loading(import) PCL file into pdf document. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Enumerates conversion engines that can be used for conversion |
| [PDF3DAnnotation](./pdf3dannotation/) | Class PDF3DAnnotation. This class cannot be inherited. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | Class PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Class PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Class PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Class PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Class PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Class PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Class PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Class PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Class PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Class PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Represents Action in PDF document |
| [PdfActionCollection](./pdfactioncollection/) | Class describes list of actions. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | This class describes rules which can be used to tune process of copying encoding data for cases when TrueType symbolic font has more than one encoding. Some PDF documents after conversion into PDF/A format could give an error "More than one encoding in symbolic TrueType font's cmap". What is a reason of this error? All TrueType symbolic fonts have special table "cmap" in it's internal data. This table maps character codes to glyph indices. And this table could contain different encoding subtables which describe encodings used. See advanced info about cmap tables at https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Usually cmap table contains several encoding subtables, but PDF/A standard requires that either only one encoding subtable must be left for this font in PDF/A document or there must be a (3,0) encoding subtable among this font subtables. And key question here - what data must be taken from another subtables to copy into destination encoding table (3,0)? Majority of fonts have 'well-formed' cmap tables where every encoding subtable is fully consistent with another subtable. But some fonts have cmap tables with collisions - where for example one subtable has glyph index 100 for unicode 100, but another subtable has glyph index 200 for the same unicode 100. To solve this problems special strategy needed. By default following strategy used: mac subtable(1,0) is looked for. If this table is found, only this data used to fill destination table (3,0). If mac subtable is not found then all subtables except (3,0) are iterated and used to copy data into destination (3,0) subtable. Also mapping for every unicode(unicode, glyph index) is copied into destination table only if destination table does not have this unicode at current moment. So, for example if first subtabe has glyph index 100 for unicode 100, and next subtable has glyph index 200 for the same unicode 100, only data from first subtable (unicode=100, glyph index = 100) will be copied. So each previous subtable takes precedence over the next. Properties of this class { PdfASymbolicFontEncodingStrategy} help tune default behaviour. If property {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) of type { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} is set, then relevant subtable will be used in precedence to mac subtable(1,0). Value 'MacTable' from enumeration {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} has no sense in this case, cause it points on the same mac subtable (1,0) which will be used by default. Property {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) discards all priorities for any subtable. If this property is set, then only subtables from declared queue will be used in specified order. If subtables specified are not found then default iteration of all subtables and copy strategy described above will be used. Object { PdfASymbolicFontEncodingStrategy.QueueItem} specifies encoding subtable used. This subtable can be set via combination of members(PlatformID, PlatformSpecificId) or via { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} enumeration. In case when the font has no (3,0) subtable some other subtable will be used to maintain the PDF/A compatibility. The choice of the subtable to use is made under the same rules as described earlier, so that {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) and {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) properties are used to determine the resultant subtable, and if the font doesn't have the requested subtable(s) either then any existent subtable will be used. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificID). Enumeration {@code CMapEncodingTableType} and property {@code CMapEncodingTable} were implemented to make easier set of encoding subtable needed. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Declares set of some known encoding subtables |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | represents set of options for convert PDF document |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | This class holds flags to control PDF/A conversion for cases when source PDF document doesn't correspond to PDF specification. If flags of this clas are used it decreases performance but it's necessary when source PDF document can't be convert into PDF/A format by usual way. By default all flags are set to false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Some PDF documents have special unicode symbols, which are belonged to Private Use Area (PUA), see description at https://en.wikipedia.org/wiki/Private_Use_Areas. This symbols cause an PDF/A compliant errors like "Text is mapped to Unicode Private Use Area but no ActualText entry is present". This enumeration declares a strategies which can be used to handle PUA symbols. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Some documens have large size after converison into PDF/A format. To reduce file size for these documents it's necessary to define a strategy of fonts removing. This enumeration declares a strategies which can be used to optimize fonts usage. Every strategy from this enumeration has sense only when flag {@code OptimizeFileSize} is set. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Describes strategies used to align document text segments. Now only strategy to restore segments to original bounds is supported. In future another strategies could be added. |
| [PdfPageStamp](./pdfpagestamp/) | Class represents stamp which uses PDF page as stamp. |
| [PdfSaveOptions](./pdfsaveoptions/) | Save options for export to Pdf format |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Load options for PdfXml format. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Save options for PdfXml format. |
| [Permissions](./permissions/) | Binary Flag This enum represents user's permissions for a pdf. |
| [PKCS1](./pkcs1/) | Represents signature object regarding PKCS#1 standard. RSA encryption algorithm and SHA-1 digest method are used for signing. |
| [PKCS7](./pkcs7/) | Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. The SHA1 digest of the document's byte range is encapsulated in the PKCS#7 SignedData field. |
| [PKCS7Detached](./pkcs7detached/) | Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. The original signed message digest over the document's byte range is incorporated as the normal PKCS#7 SignedData field. No data shall is encapsulated in the PKCS#7 SignedData field. |
| [Point](./point/) | Represent point with fractional coordinates. |
| [Point3D](./point3d/) | Represent point with fractional coordinates. |
| [PolyAnnotation](./polyannotation/) | Abstract base class for poly-annotations. |
| [PolygonAnnotation](./polygonannotation/) | Class representing polygon annotation. |
| [PolylineAnnotation](./polylineannotation/) | Represents polyline annotation that is similar to polygon, except that the first and last vertex are not implicitly connected. |
| [PopupAnnotation](./popupannotation/) | Represents the pop-up annotation that displays text in a pop-up window for entry and editing. |
| [Position](./position/) | Represents a position object |
| [PptxSaveOptions](./pptxsaveoptions/) | Save options for export to SVG format |
| [PrintController](./printcontroller/) | Represents print controller. |
| [PrintDuplex](./printduplex/) | The paper handling option to use when printing the file from the print dialog.. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstract class representing printer mark annotation. |
| [PrinterMarksKind](./printermarkskind/) | Specifies the types of printer's marks to be added to a document. This enumeration has a {@link FlagsAttribute} attribute that allows a bitwise combination of its member values. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Provides extension methods for the {@link PrinterMarksKind} enumeration. |
| [PrintScaling](./printscaling/) | The page scaling option that shall be selected when a print dialog is displayed for this document. |
| [ProgressEventType](./progresseventtype/) | This enum describes possible progress event types that can occure during conversion |
| [PsLoadOptions](./psloadoptions/) | Represents options for loading/importing of .mht-file into pdf document. |
| [PsSaveOptions](./pssaveoptions/) | Save options for export to PS (PostScript) or EPS format. |
| [RadioButtonField](./radiobuttonfield/) | Class representing radio button field. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Class represents item of RadioButton field. |
| [Rectangle](./rectangle/) | Class represents rectangle. |
| [Redaction](./redaction/) | For internal usage only @author User |
| [RedactionAnnotation](./redactionannotation/) | Represents Redact annotation. |
| [RegexManager](./regexmanager/) | Provides a wrapper for regular expression operations with configurable timeout settings. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Represents a Registration Mark annotation. Registration marks are symbols added to printing plates or screens to ensure proper alignment of colors during the printing process. |
| [RenderingOptions](./renderingoptions/) | Represents rendering options |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: set of render mode types |
| [Rendition](./rendition/) | Class which describes rendition object of RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | A rendition action that controls the playing of multimedia content. |
| [RenditionOperation](./renditionoperation/) | The operation to perform when the action is triggered. |
| [RenditionType](./renditiontype/) | Enumeration describes possible types of Rendition. |
| [Resources](./resources/) | Class representing page resources. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Represents ExtGStates with some values. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Represents rgb to device gray color spaces conversion strategy. |
| [RichMediaAnnotation](./richmediaannotation/) | Class describes RichMediaAnnotation which allows embed video/audio data into PDF document. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Event which activates annotation. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Type of the multimedia. |
| [RichTextBoxField](./richtextboxfield/) | Class describes rich text editor component. |
| [RichTextFontStyles](./richtextfontstyles/) | Options for styling text fragments in RichText. |
| [RootElement](./rootelement/) | Root structure element. |
| [Row](./row/) | Represents a row of the table. |
| [Rows](./rows/) | Represents a rows collection of table. |
| [RtfLoadOptions](./rtfloadoptions/) | Load options for RTF format. |
| [SaveOptions](./saveoptions/) | SaveOptions type hold level of abstraction on individual save options |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Instance of this class represents information about border That can be drown on some result document. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Represents information of one part of border(top, bottom, left side or right side) |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Instance of this class represents information about page margin That can be drown on some result document. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Represents information of one part of margin(top, botom, left side or right side) |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML) |
| [ScalingMode](./scalingmode/) | The type of scaling that shall be used. |
| [ScalingReason](./scalingreason/) | The circumstances under which the icon shall be scaled inside the annotation rectangle. |
| [ScreenAnnotation](./screenannotation/) | A screen annotation that specifies a region of a page upon which media clips may be played. |
| [SelectorRendition](./selectorrendition/) | Class describes selector rendition. |
| [Signature](./signature/) | An abstract class which represents signature object in the pdf document. Signatures are fields with values of signature objects, the last contain data which is used to verify the document validity. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | An abstract class which represents signature custon appearance object. |
| [SignatureField](./signaturefield/) | Represents signature form field. |
| [SignHash](./signhash/) | Delegate for custom sign the document hash (Beta). |
| [SoundAnnotation](./soundannotation/) | Represents a sound annotation that contains sound recorded from the computer's microphone or imported from a file. |
| [SoundData](./sounddata/) | Represents a sound data defining the sound to be played when the annotation is activated. |
| [SoundEncoding](./soundencoding/) | The encoding format for the sample data. |
| [SoundIcon](./soundicon/) | Enumerates the icons to be used in displaying the annotation. |
| [SoundIconConverter](./soundiconconverter/) | Represents SoundIconConverter class |
| [SoundSampleData](./soundsampledata/) | Represents additional entries specific to a sound object (Section 9.2 PDF1-7) |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | The encoding format for the sound sample data. |
| [SquareAnnotation](./squareannotation/) | Class representing square annotation. |
| [SquigglyAnnotation](./squigglyannotation/) | Represents the squiggly annotation that appears as a jagged underline in the text of a document. |
| [Stamp](./stamp/) | An abstract class for various kinds of stamps which come as descendants. |
| [StampAnnotation](./stampannotation/) | <p> Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp. </p> <hr> <pre> Next code snippet demonstrates how to add 2 stamps into the first pdf document page. Input document comes from inFile and changes are saved into the outFile. The first stamp has icon NotForPublicRelease and the second comes with image from rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Represents StampIconConverter class |
| [StrikeOutAnnotation](./strikeoutannotation/) | Represents a strikeout annotation that appears as a strikeout in the text of the document. |
| [StructElement](./structelement/) | General structure element. |
| [SubjectNameElements](./subjectnameelements/) | Enumeration describes elements in signature subject string. |
| [SubmitFormAction](./submitformaction/) | Class which describes submit-form action. |
| [SvgLoadOptions](./svgloadoptions/) | Represents options for loading/importing SVG file into pdf document. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Enumerates conversion engines that can be used for conversion |
| [SvgSaveOptions](./svgsaveoptions/) | Save options for export to SVG format |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | This class represents set of data that related to external resource image file's saving during PDF to HTML conversion. |
| [Symbology](./symbology/) | A (Barcode) Symbology defines the technical details of a particular type of barcode: the width of the bars, character set, method of encoding, checksum specifications, etc. |
| [SystemFontSource](./systemfontsource/) | Represents all fonts installed to the system. |
| [TabAlignmentType](./tabalignmenttype/) | Enumerates the tab alignment types. |
| [Table](./table/) | Represents a table that can be added to the page. |
| [TableAbsorber](./tableabsorber/) | <p> Represents an absorber object of table elements. Performs search and provides access to search results via {@code TableAbsorber.TableList} collection. </p> <hr> <pre> The example demonstrates how to find table on the first PDF document page and replace the text in a table cell. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Enumerates the tab leader types. |
| [TableBroken](./tablebroken/) | Enumerates the table broken. |
| [TabOrder](./taborder/) | Tab order on the page |
| [TabStop](./tabstop/) | Represents a custom Tab stop position in a paragraph. |
| [TabStops](./tabstops/) | Represents a collection of {@code TabStop} objects. |
| [TeXFragment](./texfragment/) | Represents LaTeX fragment. |
| [TeXLoadOptions](./texloadoptions/) | Represents options for loading/importing TeX file into PDF document. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implements fetching an output stream from memory. You can use it, for example, when you don't want the accompanying output (like a log file) to be written to disk but you'd like to read it afterwards from memory. |
| [TeXSaveOptions](./texsaveoptions/) | Save options for export to TeX format |
| [TextAbsorber](./textabsorber/) | <p> Represents an absorber object of a text. Performs text extraction and provides access to the result via {@code TextAbsorber.Text} object. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> The {@code TextAbsorber} object is used to extract text from a Pdf document or the document's page. </p> |
| [TextAnnotation](./textannotation/) | Represents a text annotation that is a "sticky note" attached to a point in the PDF document. |
| [TextBoxField](./textboxfield/) | Class representing text box field. |
| [TextBuilder](./textbuilder/) | Appends text object to Pdf page. |
| [TextDefaults](./textdefaults/) | Defines text subsystem defaults |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Specifies type of text subsystem defaults |
| [TextEditOptions](./texteditoptions/) | Descubes options of text edit operations. |
| [TextElement](./textelement/) | General text element of document logical structure. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Describes the text extraction error has appeared in the PDF document. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Represents the location in the PDF document where text extraction error has appeared. |
| [TextExtractionOptions](./textextractionoptions/) | Represents text extraction options |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Defines different modes which can be used while converting pdf document into text. See {@code TextDevice} class. |
| [TextFormattingOptions](./textformattingoptions/) | Represents text formatting options |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Defines line spacing specifics |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Defines word wrapping strategies |
| [TextFragment](./textfragment/) | <p> Represents fragment of Pdf text. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> In a few words, {@code TextFragment} object contains list of {@code TextSegment} objects. In details: Text of pdf document in {@code com.aspose.pdf} is represented by two basic objects: {@code TextFragment} and {@code TextSegment} The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that {@code TextFragment} object provides single logic operation set over physical {@code TextSegment} objects set that represent user's query. In text search scenario, {@code TextFragment} is logical "hello world" text representation, and {@code TextSegment} object collection represents all physical segments that construct "hello world" text object. So, {@code TextFragment} is close to logical text representation. And {@code TextSegment} is close to physical text representation. Obviously each {@code TextSegment} object may have it's own font, coloring, positioning properties. {@code TextFragment} provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile {@code TextSegment} objects are accessible and users are able to operate with {@code TextSegment} objects independently. <p> Note that changing TextFragment properties may change inner {@code Segments} collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the {@code Segments} collection unchanged, please change inner segments individually. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Represents an absorber object of text fragments. Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> The {@code TextFragmentAbsorber} object is basically used in text search scenario. When the search is completed the occurrences are represented with {@code TextFragment} objects that the {@code TextFragmentAbsorber.TextFragments} collection contains. The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Represents a text fragments collection |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Represents a text state of a text fragment. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Provides a way to change following properties of the text: font ({@code TextFragmentState.Font} property) font size ({@code TextFragmentState.FontSize} property) font style ( {@code TextFragmentState.FontStyle} property) foreground color ( {@code TextFragmentState.ForegroundColor} property) background color ( {@code TextFragmentState.BackgroundColor} property) <p> Note that changing {@code TextFragmentState} properties may change inner {@code TextFragment.Segments} collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the {@code TextFragment.Segments} collection unchanged, please change inner segments individually. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Enumerates the icons to be used in displaying the annotation. |
| [TextIconConverter](./texticonconverter/) | Represents TextIconConverter class |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstract base class for text markup annotations. |
| [TextOptions](./textoptions/) | Represents text processing options |
| [TextParagraph](./textparagraph/) | <p> Represents text paragraphs as multiline text object. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Background mode for TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Represents an absorber object of text paragraphs. Performs text search and provides access to search results via {@code TextParagraphAbsorber.TextParagraphs} collection. |
| [TextParagraphCollection](./textparagraphcollection/) | Represents a text paragraphs collection |
| [TextReplaceOptions](./textreplaceoptions/) | Represents text replace options |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries to adjust spaces between words to keep line length; WholeWordsHyphenation - tries to distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Represents text search options |
| [TextSegment](./textsegment/) | <p> Represents segment of Pdf text. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object of {@code TextSegment} object. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> In a few words, {@code TextSegment} objects are children of {@code TextFragment} object. In details: Text of pdf document in {@code Aspose.Pdf} is represented by two basic objects: {@code TextFragment} and {@code TextSegment} The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Physically pdf text's representation is very complex. The text "hello world" may consist of several physically independent text segments. The Aspose.PDF text model basically establishes that {@code TextFragment} object provides single logic operation set over physical {@code TextSegment} objects set that represent user's query. In text search scenario, {@code TextFragment} is logical "hello world" text representation, and {@code TextSegment} object collection represents all physical segments that construct "hello world" text object. So, {@code TextFragment} is close to logical text representation. And {@code TextSegment} is close to physical text representation. Obviously each {@code TextSegment} object may have it's own font, coloring, positioning properties. {@code TextFragment} provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile {@code TextSegment} objects are accessible and users are able to operate with {@code TextSegment} objects independently. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Represents a text segments collection |
| [TextStamp](./textstamp/) | Reresents textual stamp. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Action to perform if font does not contain required character. |
| [TextState](./textstate/) | Represents a text state of a text |
| [TextStyle](./textstyle/) | Class representing checkbox field |
| [TimestampSettings](./timestampsettings/) | Represents the ocsp settings using during signing process. |
| [TocInfo](./tocinfo/) | Represents table of contents info. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Represents a Trim Mark annotation. Trim marks are placed at the corners of a printed page to indicate where the page is to be trimmed. |
| [TxtLoadOptions](./txtloadoptions/) | Load options for TXT to PDF conversion. |
| [UnderlineAnnotation](./underlineannotation/) | Represents an underline annotation that appears as an underline in the text of the document. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | This class represents saving options for saving that uses unified conversion way (with unified internal document model) |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Represents class with abstract method that usually supplied by calling side and handles progress events that comes from converter. Usually such supplied customer's handler can be used to show total conversion progress on console or in progress bar. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | This class represents information about conversion progress that can be used in external application to show conversion progress to end user |
| [WarningCallback](./warningcallback/) | Interface for user's callback mechanism support. |
| [WarningInfo](./warninginfo/) | Immutable object for encapsulating warning information. |
| [WarningType](./warningtype/) | / * Enum represented warning type. / * / |
| [Watermark](./watermark/) | Represents a watermark of the page. |
| [WatermarkAnnotation](./watermarkannotation/) | Class describes Watermark annotation object. |
| [WatermarkArtifact](./watermarkartifact/) | Class describes watermark artifact. This may be used to |
| [WebHyperlink](./webhyperlink/) | Represents web hyperlink object. |
| [WidgetAnnotation](./widgetannotation/) | Class representing widget annotation. |
| [XFA](./xfa/) | Represents XML form regarding XML Forms Architecture (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | class to handle related data encapsulation |
| [XfdfReader](./xfdfreader/) | <p> Class which performs reading of XFDF format. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Aggregates methods of writing annotations and fields to XFDF file format |
| [XForm](./xform/) | Class represent XForm |
| [XFormCollection](./xformcollection/) | Class represents collection of XFormCollection. |
| [XImage](./ximage/) | Class representing image X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | Class representing image raw XImage parameters. |
| [XImageCollection](./ximagecollection/) | Class representing XImage collection. |
| [XmlLoadOptions](./xmlloadoptions/) | Represents options for loading/importing XML file into pdf document. |
| [XmlSaveOptions](./xmlsaveoptions/) | Save options for export to Xml format |
| [XmpField](./xmpfield/) | Represents XMP field. |
| [XmpFieldType](./xmpfieldtype/) | This enum represents types of a XMP field. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Property category: internal or external. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI: http://www.aiim.org/pdfa/ns/field# Required schema namespace prefix: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Represents the base class for field, property, value type instances. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Describes a single property. Schema namespace URI: http://www.aiim.org/pdfa/ns/property# Required schema namespace prefix: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Describes the XMP extension schema which is provided by PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Represents the description of XMP extension schema which is provided by PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType |
| [XmpValue](./xmpvalue/) | Represents XMP value |
| [XpsLoadOptions](./xpsloadoptions/) | Represents options for loading/importing xps file into pdf document. |
| [XpsSaveOptions](./xpssaveoptions/) | Save options for export to Xps format |
| [XslFoLoadOptions](./xslfoloadoptions/) | Represents options for loading/importing XSL-FO file into pdf document. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Description |
| --- | --- |
| [AFRelationship](./afrelationship/) | Enumeration describes associated files relationship. |
| [AnnotationState](./annotationstate/) | The enumeration of states to which the original annotation can be set. |
| [AnnotationStateModel](./annotationstatemodel/) | The state model corresponding to state of annotation. |
| [AnnotationType](./annotationtype/) | Enumeration of annotation types. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Enumeration of possible artifacts subtype. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Enumeration of possible artifact types. |
| [BlendMode](./blendmode/) | The blend modes enumeration. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumerates the border corner styles for border. |
| [BorderEffect](./bordereffect/) | Describes effect which should be applied to the border of the annotations. |
| [BorderStyle](./borderstyle/) | Describes style of the annotation border. |
| [BoxStyle](./boxstyle/) | Represents styles for drawing check in check box. |
| [CapStyle](./capstyle/) | Style of line ending of Ink annotation line. |
| [CaptionPosition](./captionposition/) | Enumeration of the annotation's caption positioning. |
| [CaretSymbol](./caretsymbol/) | A symbol to be associated with the caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colors included in the CMYK color model. |
| [ColorSpace](./colorspace/) | The color spaces enumeration. |
| [ColorType](./colortype/) | Specifies color type of elements on page. |
| [ColumnAdjustment](./columnadjustment/) | Enumerates column adjustment types. |
| [ContentDisposition](./contentdisposition/) | MIME protocol Content-Disposition header. |
| [ConvertErrorAction](./converterroraction/) | This class represents action for conversion errors. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | This action represents actions for conversion of images with soft mask. |
| [ConvertTransparencyAction](./converttransparencyaction/) | This class represents action for conversion of transparency. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Represent type of cryptographic algorithm that used in encryption/decryption routines. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * The {@code Aspose.Pdf.Security } namespace contains classes used for encryption and digital signing. / * / |
| [DefaultState](./defaultstate/) | Represents the default state of a PDF layer. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Represent type of algorithm that maps data to a "hash" |
| [Direction](./direction/) | Text direction. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | The access permissions granted for this document. Valid values are: 1 - No changes to the document are permitted; any change to the document invalidates the signature. 2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature. 3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Allows to specify .doc or .docx file format. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Allows to control how a PDF document is converted into a word processing document. Use the RecognitionMode.Textbox mode when the resulting document is not goining to be heavily edited futher. Textboxes are easy to modify when there is not a lot to do. Use the RecognitionMode.Flow mode when the output document needs further editing. Paragraphs and texlines in the flow mode allow easy modification of text, but unupported formatting objects will look worse than in the RecognitionMode.Textbox mode. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumerates the types of explicit destinations. |
| [ExtendedBoolean](./extendedboolean/) | Represents boolean type that supports Undefined value. |
| [ExtractImageMode](./extractimagemode/) | Defines different modes which can be used while extracting images from documents. |
| [FileEncoding](./fileencoding/) | Encoding of the attached file. Possible values: Zip - file is compressed with ZIP, None - file is non compressed. |
| [FileIcon](./fileicon/) | An icon to be used in displaying the annotation. |
| [Fixup](./fixup/) | This enum represents an type of Fixup. |
| [FormType](./formtype/) | Enumeration of possible types of Acro Form. |
| [FreeTextIntent](./freetextintent/) | Enumerates the intents of the free text annotation. |
| [HighlightingMode](./highlightingmode/) | Enumerates the annotation's highlighting mode, the visual effect to be used when the mouse button is pressed or held down inside its active area. |
| [HorizontalAlignment](./horizontalalignment/) | Describes horizontal alignment. |
| [HtmlDocumentType](./htmldocumenttype/) | Represents enumeration of the Html document types. |
| [HtmlMediaType](./htmlmediatype/) | Specifies possible media types used during rendering. |
| [IconCaptionPosition](./iconcaptionposition/) | Describes position of icon. |
| [ImageFileType](./imagefiletype/) | Enumerates the image file types. |
| [ImageFilterType](./imagefiltertype/) | Enumeration representing image filter type. |
| [ImageFormat](./imageformat/) | This enum represents image formats. |
| [ImportFormat](./importformat/) | Specifies import format. |
| [Justification](./justification/) | Enumerates the forms of quadding (justification) to be used in displaying the annotation's text. |
| [LaunchActionOperation](./launchactionoperation/) | Enumerates the operations to perform with document during launch action executing. |
| [LettersPositioningMethods](./letterspositioningmethods/) | It enumerates possible modes of positioning of letters in words in result HTML |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: set of lighting scheme types. |
| [LineEnding](./lineending/) | Enumerates the line ending styles to be used in drawing the line. |
| [LineIntent](./lineintent/) | Enumerates the intents of the line annotation. |
| [LoadFormat](./loadformat/) | Specifies load format. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Value which indicates in which manner fraction values are displayed. |
| [NumberingStyle](./numberingstyle/) | Enumeration of supported page numbering style for PageLabel class. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Specifies the position in a stream to use for seeking. |
| [PageCoordinateType](./pagecoordinatetype/) | Describes page coordinate type. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Descibes page layout. |
| [PageMode](./pagemode/) | Class descibes used components of the document page. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Specifies variant for determining the location of the element on the page. |
| [PasswordType](./passwordtype/) | This enum represents known password types used for password protected pdf documents. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: set of 3D annotation activation mode. |
| [PdfFormat](./pdfformat/) | This class represents an pdf format. |
| [PdfVersion](./pdfversion/) | This enum represents version of pdf file. |
| [PolyIntent](./polyintent/) | Enumerates the intents of the polygon or polyline annotation. |
| [PredefinedAction](./predefinedaction/) | Defines different actions which can be triggered from a PDF file. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Represents a position of a mark in a corner of a page. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Represents a position of a registration mark on a page. |
| [ReplyType](./replytype/) | Enumerates the kinds of the relationships (the "reply type") between the annotation and one specified by InReplyTo. |
| [ReturnAction](./returnaction/) | Enum represented a program workflow action in case of invoking the {@code IWarningCallback.Warning(WarningInfo)} method. |
| [Rotation](./rotation/) | Enumeration of possible rotation values. |
| [SaveFormat](./saveformat/) | Specifies format |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Represents line types that can be used in result document for drawing borders or another lines |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | enumerates possible types of saved external resources |
| [StampIcon](./stampicon/) | Enumerates the icons to be used in displaying the annotation. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | enumerates possible types of image files that can be saved as external resources during during Pdf to SVG conversion |
| [TextAlignment](./textalignment/) | Alignment of text in annotation. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Clipping path processing modes |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Font replacement behavior. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Language transformation modes |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Action to perform if font does not contain required character |
| [TextRenderingMode](./textrenderingmode/) | The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Specifies a policy for how the font size of text should be adjusted to fit within a containing area. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Scope where replace text operation is applied REPLACE_FIRST by default This obsolete option was kept for compatibility. It affects to PdfContentEditor and has no effect to TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Enumeration of possible vertical alignment values. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
