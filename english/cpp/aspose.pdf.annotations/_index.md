---
title: Aspose::Pdf::Annotations namespace
linktitle: Aspose::Pdf::Annotations
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations namespace. The Aspose.Pdf.Annotations namespace provides classes for working with various types of actions, destinations and other features of document which traditionally called as interactive providing means user can intercommunicate with it in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.annotations/
---

The **[Aspose.Pdf.Annotations](./)** namespace provides classes for working with various types of actions, destinations and other features of document which traditionally called as interactive providing means user can intercommunicate with it.

## Classes

| Class | Description |
| --- | --- |
| [ActionCollection](./actioncollection/) | [Collection](../aspose.pdf/collection/) of actions. |
| [Annotation](./annotation/) | Class representing annotation object. |
| [AnnotationActionCollection](./annotationactioncollection/) | Represents the collection of annotation actions. |
| [AnnotationCollection](./annotationcollection/) | Class representing annotation collection. |
| [AnnotationFlagsConverter](./annotationflagsconverter/) |  |
| [AnnotationSelector](./annotationselector/) | This class is used for selecting annotations using Visitor template idea. |
| [AnnotationStateConverter](./annotationstateconverter/) |  |
| [AnnotationStateModelConverter](./annotationstatemodelconverter/) |  |
| [AppearanceDictionary](./appearancedictionary/) | [Annotation](./annotation/) appearance dictionary specifying how the annotation shall be presented visually on the page. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Represents a Bleed Mark annotation. |
| [Border](./border/) | Class representing characteristics of annotation border. |
| [BorderEffectConverter](./bordereffectconverter/) |  |
| [BorderStyleConverter](./borderstyleconverter/) |  |
| [CaptionPositionConverter](./captionpositionconverter/) |  |
| [CaretAnnotation](./caretannotation/) | Class representing Caret annotation. |
| [CaretSymbolConverter](./caretsymbolconverter/) |  |
| [Characteristics](./characteristics/) | Represents annotation characteristics. |
| [CircleAnnotation](./circleannotation/) | Class representing Circle annotation. |
| [ColorBarAnnotation](./colorbarannotation/) | Class representing [ColorBarAnnotation](./colorbarannotation/) annotation. Property [Color](../aspose.pdf/color/) ignored, instead used [ColorsOfCMYK](./colorsofcmyk/) color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed). |
| [ColorsOfCMYKConverter](./colorsofcmykconverter/) |  |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstract class representing common figure annotation. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Represents annotation types that are placed in the corners of the printed page. |
| [CustomExplicitDestination](./customexplicitdestination/) | Represents custom explicit destination. |
| [Dash](./dash/) | Class representing line dash pattern. |
| [DefaultAppearance](./defaultappearance/) | Describes default appearance of field (font, text size and color). |
| [DocumentActionCollection](./documentactioncollection/) | Class describes actions performed on some actions with document. |
| [ExplicitDestination](./explicitdestination/) | Represents the base class for explicit destinations in PDF document. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) |  |
| [FdfReader](./fdfreader/) | Class which performes reading of FDF format. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Class describes file attachment annotation. |
| [FileIconConverter](./fileiconconverter/) |  |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged. |
| [FitExplicitDestination](./fitexplicitdestination/) | Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged. |
| [FixedPrint](./fixedprint/) | Represent Fixed print data of [Watermark](../aspose.pdf/watermark/)[Annotation](./annotation/). |
| [FreeTextAnnotation](./freetextannotation/) | Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible. |
| [FreeTextIntentConverter](./freetextintentconverter/) |  |
| [GenericAnnotation](./genericannotation/) | The class describes general annotation. |
| [GoToAction](./gotoaction/) | Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor). |
| [GoToRemoteAction](./gotoremoteaction/) | Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file. |
| [GoToURIAction](./gotouriaction/) | Represents a URI action causes a URI to be resolved. |
| [HideAction](./hideaction/) | Represents a hide action that hides or shows one or more annotations on the screen by setting or clearing their Hidden flags. |
| [HighlightAnnotation](./highlightannotation/) | Represents a highlight annotation that highlights a range of text in the document. |
| [HighlightingModeConverter](./highlightingmodeconverter/) |  |
| [IAnnotationVisitor](./iannotationvisitor/) | Defines Visitor for visiting different document annotations. |
| [IAppointment](./iappointment/) | Represents general interface for actions and destinations. |
| [ImportDataAction](./importdataaction/) | Upon invocation of an import-data action, [Forms](../aspose.pdf.forms/) Data Format (FDF) data shall be imported into the document's interactive form from a specified file. |
| [InkAnnotation](./inkannotation/) | Represents a freehand "scribble" composed of one or more disjoint paths. |
| [JavascriptAction](./javascriptaction/) | Class representing javascript action. |
| [JustificationConverter](./justificationconverter/) |  |
| [LaunchAction](./launchaction/) | Represents a launch action that launches an application or opens or prints a document. |
| [LaunchActionOperationConverter](./launchactionoperationconverter/) |  |
| [LineAnnotation](./lineannotation/) | Class representing line annotation. |
| [LineEndingConverter](./lineendingconverter/) |  |
| [LineIntentConverter](./lineintentconverter/) |  |
| [LinkAnnotation](./linkannotation/) | Represents either a hypertext link to a destination elsewhere in the document or an action to be performed. |
| [MarkupAnnotation](./markupannotation/) | Abstract class representing markup annotation. |
| [Measure](./measure/) | Class which describes [Measure](./measure/) coordinate system. |
| [MediaClip](./mediaclip/) | Class describes media clip object of rendition. |
| [MediaClipData](./mediaclipdata/) | Class describes media clip data. |
| [MediaClipSection](./mediaclipsection/) | This class descibes Media clip section. |
| [MediaRendition](./mediarendition/) | Class describes media rendition. |
| [MovieAnnotation](./movieannotation/) | Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played. |
| [NamedAction](./namedaction/) | Represents named actions that PDF viewer applications are expected to support. |
| [NamedDestination](./nameddestination/) | Instead of being defined directly with the explicit syntax, a destination may be referred to indirectly by means of a name object or a byte string. |
| [PageInformationAnnotation](./pageinformationannotation/) | Represents a [Page](../aspose.pdf/page/) Information annotation in a PDF document. This annotation contains the file name, page number, and the date and time of the annotation creation. |
| [PDF3DAnnotation](./pdf3dannotation/) | Class [PDF3DAnnotation](./pdf3dannotation/). This class cannot be inherited. |
| [PDF3DArtwork](./pdf3dartwork/) | Class [PDF3DArtwork](./pdf3dartwork/). |
| [PDF3DContent](./pdf3dcontent/) | Class [PDF3DContent](./pdf3dcontent/). |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Class [PDF3DCrossSection](./pdf3dcrosssection/). |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Class [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/). |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Class [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/). |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Class [PDF3DLightingScheme](./pdf3dlightingscheme/). |
| [PDF3DRenderMode](./pdf3drendermode/) | Class [PDF3DRenderMode](./pdf3drendermode/). |
| [PDF3DStream](./pdf3dstream/) | Class [PDF3DStream](./pdf3dstream/). |
| [PDF3DView](./pdf3dview/) | Class [PDF3DView](./pdf3dview/). |
| [PDF3DViewArray](./pdf3dviewarray/) | Class [PDF3DViewArray](./pdf3dviewarray/). |
| [PdfAction](./pdfaction/) | Represents Action in PDF document. |
| [PdfActionCollection](./pdfactioncollection/) | Class describes list of actions. |
| [PolyAnnotation](./polyannotation/) | Abstract base class for poly- annotations. |
| [PolygonAnnotation](./polygonannotation/) | Class representing polygon annotation. |
| [PolyIntentConverter](./polyintentconverter/) |  |
| [PolylineAnnotation](./polylineannotation/) | Represents polyline annotation that is similar to polygon, except that the first and last vertex are not implicitly connected. |
| [PopupAnnotation](./popupannotation/) | Represents the pop-up annotation that displays text in a pop-up window for entry and editing. |
| [PredefinedActionConverter](./predefinedactionconverter/) |  |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstract class representing printer mark annotation. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Provides extension methods for the [PrinterMarksKind](./printermarkskind/) enumeration. |
| [RedactionAnnotation](./redactionannotation/) | Represents Redact annotation. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Represents a Registration Mark annotation. |
| [Rendition](./rendition/) | Class which describes rendition object of RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | A rendition action that controls the playing of multimedia content. |
| [ReplyTypeConverter](./replytypeconverter/) |  |
| [RichMediaAnnotation](./richmediaannotation/) | Class describes [RichMediaAnnotation](./richmediaannotation/) which allows embed video/audio data into PDF document. |
| [ScreenAnnotation](./screenannotation/) | A screen annotation that specifies a region of a page upon which media clips may be played. |
| [SelectorRendition](./selectorrendition/) | Class describes selector rendition. |
| [SoundAnnotation](./soundannotation/) | Represents a sound annotation that contains sound recorded from the computer's microphone or imported from a file. |
| [SoundData](./sounddata/) | Represents a sound data defining the sound to be played when the annotation is activated. |
| [SoundEncodingConverter](./soundencodingconverter/) |  |
| [SoundIconConverter](./soundiconconverter/) |  |
| [SoundSampleData](./soundsampledata/) | Represents additional entries specific to a sound object (Section 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Class representing square annotation. |
| [SquigglyAnnotation](./squigglyannotation/) | Represents the squiggly annotation that appears as a jagged underline in the text of a document. |
| [StampAnnotation](./stampannotation/) | Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp. |
| [StampIconConverter](./stampiconconverter/) |  |
| [StrikeOutAnnotation](./strikeoutannotation/) | Represents a strikeout annotation that appears as a strikeout in the text of the document. |
| [SubmitFormAction](./submitformaction/) | Class which describes submit-form action. |
| [TextAnnotation](./textannotation/) | Represents a text annotation that is a 'sticky note' attached to a point in the PDF document. |
| [TextIconConverter](./texticonconverter/) |  |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstract base class for text markup annotations. |
| [TextStyle](./textstyle/) | Class represents style of text in annotation. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Represents a Trim Mark annotation. |
| [UnderlineAnnotation](./underlineannotation/) | Represents an underline annotation that appears as an underline in the text of the document. |
| [WatermarkAnnotation](./watermarkannotation/) | Class describes [Watermark](../aspose.pdf/watermark/) annotation object. |
| [WidgetAnnotation](./widgetannotation/) | Class representing widget annotation. |
| [XfdfReader](./xfdfreader/) | Class which peroformes reading of XFDF format. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value. |
## Enums

| Enum | Description |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | A set of flags specifying various characteristics of the annotation. |
| [AnnotationState](./annotationstate/) | The enumeration of states to which the original annotation can be set. |
| [AnnotationStateModel](./annotationstatemodel/) | The state model corresponding to state of annotation. |
| [AnnotationType](./annotationtype/) | Enumeration of annotation types. |
| [BorderEffect](./bordereffect/) | Describes effect which should be applied to the border of the annotations. |
| [BorderStyle](./borderstyle/) | Describes style of the annotation border. |
| [CapStyle](./capstyle/) | Style of line ending of Ink annotation line. |
| [CaptionPosition](./captionposition/) | Enumeration of the annotation's caption positioning. |
| [CaretSymbol](./caretsymbol/) | A symbol to be associated with the caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colors included in the CMYK color model. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumerates the types of explicit destinations. |
| [FileIcon](./fileicon/) | An icon to be used in displaying the annotation. |
| [FreeTextIntent](./freetextintent/) | Enumerates the intents of the free text annotation. |
| [HighlightingMode](./highlightingmode/) | Enumerates the annotation's highlighting mode, the visual effect to be used when the mouse button is pressed or held down inside its active area. |
| [Justification](./justification/) | Enumerates the forms of quadding (justification) to be used in displaying the annotation's text. |
| [LaunchActionOperation](./launchactionoperation/) | Enumerates the operations to perform with document during launch action executing. |
| [LightingSchemeType](./lightingschemetype/) | Enum [LightingSchemeType](./lightingschemetype/): set of lighting scheme types. |
| [LineEnding](./lineending/) | Enumerates the line ending styles to be used in drawing the line. |
| [LineIntent](./lineintent/) | Enumerates the intents of the line annotation. |
| [PDF3DActivation](./pdf3dactivation/) | Enum [PDF3DActivation](./pdf3dactivation/): set of 3D annotation activation mode. |
| [PolyIntent](./polyintent/) | Enumerates the intents of the polygon or polyline annotation. |
| [PredefinedAction](./predefinedaction/) | Defines different actions which can be triggered from a PDF file. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Represents a position of a mark in a corner of a page. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Represents a position of a registration mark on a page. |
| [PrinterMarksKind](./printermarkskind/) | Specifies the types of printer's marks to be added to a document. |
| [RenderModeType](./rendermodetype/) | Enum [RenderModeType](./rendermodetype/): set of render mode types. |
| [RenditionOperation](./renditionoperation/) | The operation to perform when the action is triggered. |
| [RenditionType](./renditiontype/) | Enumeration describes possible types of [Rendition](./rendition/). |
| [ReplyType](./replytype/) | Enumerates the kinds of the relationships (the "reply type") between the annotation and one specified by InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Options for styling text fragments in RichText. |
| [SoundEncoding](./soundencoding/) | The encoding format for the sample data. |
| [SoundIcon](./soundicon/) | Enumerates the icons to be used in displaying the annotation. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | The encoding format for the sound sample data. |
| [StampIcon](./stampicon/) | Enumerates the icons to be used in displaying the annotation. |
| [TextAlignment](./textalignment/) | Alignment of text in annotation. |
| [TextIcon](./texticon/) | Enumerates the icons to be used in displaying the annotation. |
