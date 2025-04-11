---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Der Aspose.Pdf.Annotations-Namespace bietet Klassen zum Arbeiten mit verschiedenen Arten von Aktionen, Zielen und anderen Funktionen von Dokumenten, die traditionell als interaktiv bezeichnet werden und es dem Benutzer ermöglichen, mit ihnen zu interagieren.
type: docs
weight: 50
url: /de/net/aspose.pdf.annotations/
---
Der **Aspose.Pdf.Annotations**-Namespace bietet Klassen zum Arbeiten mit verschiedenen Arten von Aktionen, Zielen und anderen Funktionen von Dokumenten, die traditionell als interaktiv bezeichnet werden und es dem Benutzer ermöglichen, mit ihnen zu interagieren.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [ActionCollection](./actioncollection/) | Sammlung von Aktionen |
| [Annotation](./annotation/) | Klasse, die das Annotationsobjekt darstellt. |
| [AnnotationActionCollection](./annotationactioncollection/) | Stellt die Sammlung von Annotationsaktionen dar. |
| [AnnotationCollection](./annotationcollection/) | Klasse, die die Annotationssammlung darstellt. |
| [AnnotationSelector](./annotationselector/) | Diese Klasse wird verwendet, um Anmerkungen mithilfe der Visitor-Template-Idee auszuwählen. |
| [AppearanceDictionary](./appearancedictionary/) | Annotationsdarstellungswörterbuch, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Stellt eine Bleed Mark-Annotation dar. |
| [Border](./border/) | Klasse, die die Eigenschaften des Annotationsrahmens darstellt. |
| [CaretAnnotation](./caretannotation/) | Klasse, die die Caret-Annotation darstellt. |
| [Characteristics](./characteristics/) | Stellt die Eigenschaften der Annotation dar |
| [CircleAnnotation](./circleannotation/) | Klasse, die die Kreisannotation darstellt. |
| [ColorBarAnnotation](./colorbarannotation/) | Klasse, die die ColorBarAnnotation-Annotation darstellt. Die Eigenschaft Color wird ignoriert, stattdessen wird ColorsOfCMYK verwendet. Bei der Erstellung bestimmt das Verhältnis von Breite und Höhe die Ausrichtung der Annotation - horizontal oder vertikal. Anschließend wird überprüft, ob das Annotationsrechteck außerhalb des TrimBox liegt, und falls nicht, wird es an den nächstgelegenen Ort außerhalb des TrimBox verschoben, wobei die Ausrichtung der Annotation berücksichtigt wird. Es ist möglich, die Breite (Höhe) zu reduzieren, damit die Annotation außerhalb des TrimBox passt. Wenn kein Platz für das Layout vorhanden ist, kann die Breite/Höhe auf null gesetzt werden (in diesem Fall ist die Annotation auf der Seite vorhanden, wird jedoch nicht angezeigt). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstrakte Klasse, die die allgemeine Figurenannotation darstellt. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Stellt Annotationsarten dar, die in den Ecken der gedruckten Seite platziert sind. |
| [CustomExplicitDestination](./customexplicitdestination/) | Stellt ein benutzerdefiniertes explizites Ziel dar. |
| [Dash](./dash/) | Klasse, die das Linienstreumuster darstellt. |
| [DefaultAppearance](./defaultappearance/) | Beschreibt das Standardaussehen des Feldes (Schriftart, Textgröße und Farbe). |
| [DocumentActionCollection](./documentactioncollection/) | Klasse beschreibt Aktionen, die bei einigen Aktionen mit dem Dokument ausgeführt werden |
| [ExplicitDestination](./explicitdestination/) | Stellt die Basisklasse für explizite Ziele im PDF-Dokument dar. |
| [FdfReader](./fdfreader/) | Klasse, die das Lesen des FDF-Formats durchführt. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Klasse beschreibt die Datei-Anhang-Annotation. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass sie vollständig innerhalb des Fensters sowohl horizontal als auch vertikal passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie das Begrenzungsrechteck innerhalb des Fensters in der anderen Dimension. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der vertikalen Koordinate oben positioniert am oberen Rand des Fensters anzeigt und den Inhalt der Seite so vergrößert, dass die gesamte Breite des Begrenzungsrechtecks innerhalb des Fensters passt. Ein Nullwert für oben gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der horizontalen Koordinate links positioniert am linken Rand des Fensters anzeigt und den Inhalt der Seite so vergrößert, dass die gesamte Höhe des Begrenzungsrechtecks innerhalb des Fensters passt. Ein Nullwert für links gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| [FitExplicitDestination](./fitexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass die gesamte Seite sowohl horizontal als auch vertikal innerhalb des Fensters passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie die Seite innerhalb des Fensters in der anderen Dimension. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der vertikalen Koordinate oben positioniert am oberen Rand des Fensters anzeigt und den Inhalt der Seite so vergrößert, dass die gesamte Breite der Seite innerhalb des Fensters passt. Ein Nullwert für oben gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass das Rechteck, das durch die Koordinaten links, unten, rechts und oben angegeben ist, vollständig innerhalb des Fensters sowohl horizontal als auch vertikal passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie das Rechteck innerhalb des Fensters in der anderen Dimension. Ein Nullwert für einen der Parameter kann zu unvorhersehbarem Verhalten führen. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der horizontalen Koordinate links positioniert am linken Rand des Fensters anzeigt und den Inhalt der Seite so vergrößert, dass die gesamte Höhe der Seite innerhalb des Fensters passt. Ein Nullwert für links gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| [FixedPrint](./fixedprint/) | Stellt die festen Druckdaten der Wasserzeichenannotation dar. |
| [FreeTextAnnotation](./freetextannotation/) | Stellt eine Freitextannotation dar, die Text direkt auf der Seite anzeigt. Im Gegensatz zu einer gewöhnlichen Textannotation hat eine Freitextannotation keinen offenen oder geschlossenen Zustand; anstelle von einem Popup-Fenster wird der Text immer angezeigt. |
| [GoToAction](./gotoaction/) | Stellt eine Go-To-Aktion dar, die die Ansicht zu einem bestimmten Ziel (Seite, Standort und Vergrößerungsfaktor) ändert. |
| [GoToRemoteAction](./gotoremoteaction/) | Stellt eine Remote-Go-To-Aktion dar, die einer gewöhnlichen Go-To-Aktion ähnelt, aber zu einem Ziel in einer anderen PDF-Datei anstelle der aktuellen Datei springt. |
| [GoToURIAction](./gotouriaction/) | Stellt eine URI-Aktion dar, die eine URI auflöst. |
| [HideAction](./hideaction/) | Stellt eine Hide-Aktion dar, die eine oder mehrere Anmerkungen auf dem Bildschirm ausblendet oder anzeigt, indem ihre Hidden-Flags gesetzt oder gelöscht werden. |
| [HighlightAnnotation](./highlightannotation/) | Stellt eine Hervorhebungsannotation dar, die einen Textbereich im Dokument hervorhebt. |
| [ImportDataAction](./importdataaction/) | Bei der Ausführung einer Importdatenaktion werden Daten im Forms Data Format (FDF) in das interaktive Formular des Dokuments aus einer angegebenen Datei importiert. |
| [InkAnnotation](./inkannotation/) | Stellt eine Freihand-"Kritzelei" dar, die aus einem oder mehreren disjunkten Pfaden besteht. |
| [JavascriptAction](./javascriptaction/) | Klasse, die die JavaScript-Aktion darstellt. |
| [LaunchAction](./launchaction/) | Stellt eine Startaktion dar, die eine Anwendung startet oder ein Dokument öffnet oder druckt. |
| [LineAnnotation](./lineannotation/) | Klasse, die die Linienannotation darstellt. |
| [LinkAnnotation](./linkannotation/) | Stellt entweder einen Hypertextlink zu einem Ziel an anderer Stelle im Dokument oder eine auszuführende Aktion dar. |
| [MarkupAnnotation](./markupannotation/) | Abstrakte Klasse, die die Markup-Annotation darstellt. |
| [Measure](./measure/) | Klasse, die das Maßkoordinatensystem beschreibt. |
| [MediaClip](./mediaclip/) | Klasse beschreibt das Medienclipobjekt der Wiedergabe. |
| [MediaClipData](./mediaclipdata/) | Klasse beschreibt die Mediendaten des Clips. |
| [MediaClipSection](./mediaclipsection/) | Diese Klasse beschreibt den Medienclipabschnitt. |
| [MediaRendition](./mediarendition/) | Klasse beschreibt die Medienwiedergabe. |
| [MovieAnnotation](./movieannotation/) | Stellt eine Filmannotation dar, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher präsentiert werden. Wenn die Annotation aktiviert wird, wird der Film abgespielt. |
| [NamedAction](./namedaction/) | Stellt benannte Aktionen dar, die von PDF-Viewer-Anwendungen unterstützt werden sollen. |
| [NamedDestination](./nameddestination/) | Anstatt direkt mit der expliziten Syntax definiert zu werden, kann ein Ziel indirekt durch ein Namensobjekt oder eine Byte-Zeichenfolge referenziert werden. |
| [PageInformationAnnotation](./pageinformationannotation/) | Stellt eine Seiteninformationsannotation in einem PDF-Dokument dar. Diese Annotation enthält den Dateinamen, die Seitennummer sowie das Datum und die Uhrzeit der Erstellung der Annotation. |
| [PDF3DAnnotation](./pdf3dannotation/) | Klasse PDF3DAnnotation. Diese Klasse kann nicht vererbt werden. |
| [PDF3DArtwork](./pdf3dartwork/) | Klasse PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Klasse PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Klasse PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Klasse PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Klasse PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Klasse PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Klasse PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Klasse PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Klasse PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Klasse PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Stellt die Aktion im PDF-Dokument dar |
| [PdfActionCollection](./pdfactioncollection/) | Klasse beschreibt die Liste der Aktionen. |
| [PolyAnnotation](./polyannotation/) | Abstrakte Basisklasse für Poly-Annotationen. |
| [PolygonAnnotation](./polygonannotation/) | Klasse, die die Polygonannotation darstellt. |
| [PolylineAnnotation](./polylineannotation/) | Stellt die Polyline-Annotation dar, die ähnlich wie ein Polygon ist, mit dem Unterschied, dass der erste und der letzte Scheitelpunkt nicht implizit verbunden sind. |
| [PopupAnnotation](./popupannotation/) | Stellt die Popup-Annotation dar, die Text in einem Popup-Fenster zur Eingabe und Bearbeitung anzeigt. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstrakte Klasse, die die Druckmarkierungsannotation darstellt. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Bietet Erweiterungsmethoden für die [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) Enumeration. |
| [RedactionAnnotation](./redactionannotation/) | Stellt die Redaktionsannotation dar. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Stellt eine Registrierungsmarkierungsannotation dar. |
| [Rendition](./rendition/) | Klasse, die das Wiedergabeobjekt der RenditionAnnotation beschreibt. |
| [RenditionAction](./renditionaction/) | Eine Wiedergabeaktion, die die Wiedergabe von Multimedia-Inhalten steuert. |
| [RichMediaAnnotation](./richmediaannotation/) | Klasse beschreibt die RichMediaAnnotation, die es ermöglicht, Video-/Audiodaten in ein PDF-Dokument einzubetten. |
| [ScreenAnnotation](./screenannotation/) | Eine Bildschirmannotation, die einen Bereich einer Seite angibt, auf dem Medienclips abgespielt werden können. |
| [SelectorRendition](./selectorrendition/) | Klasse beschreibt die Selektorwiedergabe. |
| [SoundAnnotation](./soundannotation/) | Stellt eine Soundannotation dar, die den Ton enthält, der vom Mikrofon des Computers aufgenommen oder aus einer Datei importiert wurde. |
| [SoundData](./sounddata/) | Stellt eine Sounddaten dar, die den Ton definiert, der abgespielt werden soll, wenn die Annotation aktiviert wird. |
| [SoundSampleData](./soundsampledata/) | Stellt zusätzliche Einträge dar, die spezifisch für ein Soundobjekt sind (Abschnitt 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Klasse, die die Quadratannotation darstellt. |
| [SquigglyAnnotation](./squigglyannotation/) | Stellt die gewellte Annotation dar, die als gezackte Unterstreichung im Text eines Dokuments erscheint. |
| [StampAnnotation](./stampannotation/) | Stellt die Gummistempelannotation dar. Diese Art von Annotation zeigt Text oder Grafiken an, die so aussehen, als wären sie mit einem Gummistempel auf die Seite gestempelt worden. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Stellt eine Durchstreichannotation dar, die als Durchstreichung im Text des Dokuments erscheint. |
| [SubmitFormAction](./submitformaction/) | Klasse, die die Submit-Formularaktion beschreibt. |
| [TextAnnotation](./textannotation/) | Stellt eine Textannotation dar, die eine 'Haftnotiz' ist, die an einem Punkt im PDF-Dokument angeheftet ist. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstrakte Basisklasse für Textmarkup-Annotationen. |
| [TextStyle](./textstyle/) | Klasse, die den Stil des Textes in der Annotation darstellt |
| [TrimMarkAnnotation](./trimmarkannotation/) | Stellt eine Trim Mark-Annotation dar. |
| [UnderlineAnnotation](./underlineannotation/) | Stellt eine Unterstreichannotation dar, die als Unterstreichung im Text des Dokuments erscheint. |
| [WatermarkAnnotation](./watermarkannotation/) | Klasse beschreibt das Wasserzeichenannotationsobjekt. |
| [WidgetAnnotation](./widgetannotation/) | Klasse, die die Widget-Annotation darstellt. |
| [XfdfReader](./xfdfreader/) | Klasse, die das Lesen des XFDF-Formats durchführt. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (links, oben) anzeigt, die in der oberen linken Ecke des Fensters positioniert sind, und den Inhalt der Seite um den Faktor Zoom vergrößert. Ein Nullwert für einen der Parameter links, oben oder Zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. Ein Zoomwert von 0 hat die gleiche Bedeutung wie ein Nullwert. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Definiert einen Visitor zum Besuchen verschiedener Dokumentannotations. |
| [IAppointment](./iappointment/) | Stellt die allgemeine Schnittstelle für Aktionen und Ziele dar. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Eine Menge von Flags, die verschiedene Eigenschaften der Annotation spezifizieren. |
| [AnnotationState](./annotationstate/) | Die Aufzählung der Zustände, in die die ursprüngliche Annotation gesetzt werden kann. |
| [AnnotationStateModel](./annotationstatemodel/) | Das Zustandsmodell, das dem Zustand der Annotation entspricht. |
| [AnnotationType](./annotationtype/) | Aufzählung der Annotationsarten. |
| [BorderEffect](./bordereffect/) | Beschreibt den Effekt, der auf den Rand der Annotationen angewendet werden soll. |
| [BorderStyle](./borderstyle/) | Beschreibt den Stil des Annotationsrahmens. |
| [CapStyle](./capstyle/) | Stil des Linienendes der Tintenannotationslinie. |
| [CaptionPosition](./captionposition/) | Aufzählung der Positionierung der Beschriftung der Annotation. |
| [CaretSymbol](./caretsymbol/) | Ein Symbol, das mit dem Caret assoziiert werden soll. |
| [ColorsOfCMYK](./colorsofcmyk/) | Farben, die im CMYK-Farbmodell enthalten sind. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumeriert die Arten von expliziten Zielen. |
| [FileIcon](./fileicon/) | Ein Symbol, das bei der Anzeige der Annotation verwendet werden soll. |
| [FreeTextIntent](./freetextintent/) | Enumeriert die Absichten der Freitextannotation. |
| [HighlightingMode](./highlightingmode/) | Enumeriert den Hervorhebungsmodus der Annotation, den visuellen Effekt, der verwendet werden soll, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt oder gehalten wird. |
| [Justification](./justification/) | Enumeriert die Formen des Quaddings (Rechtfertigung), die bei der Anzeige des Textes der Annotation verwendet werden sollen. |
| [LaunchActionOperation](./launchactionoperation/) | Enumeriert die Operationen, die mit dem Dokument während der Ausführung der Startaktion durchgeführt werden sollen. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: Menge von Beleuchtungsschemata. |
| [LineEnding](./lineending/) | Enumeriert die Linienendstile, die beim Zeichnen der Linie verwendet werden sollen. |
| [LineIntent](./lineintent/) | Enumeriert die Absichten der Linienannotation. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: Menge von 3D-Annotationsaktivierungsmodi. |
| [PolyIntent](./polyintent/) | Enumeriert die Absichten der Polygon- oder Polyline-Annotation. |
| [PredefinedAction](./predefinedaction/) | Definiert verschiedene Aktionen, die aus einer PDF-Datei ausgelöst werden können. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Stellt eine Position einer Markierung in einer Ecke einer Seite dar. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Stellt eine Position einer Registrierungsmarkierung auf einer Seite dar. |
| [PrinterMarksKind](./printermarkskind/) | Gibt die Arten von Druckmarken an, die zu einem Dokument hinzugefügt werden sollen. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: Menge von Render-Modi |
| [RenditionOperation](./renditionoperation/) | Die Operation, die ausgeführt werden soll, wenn die Aktion ausgelöst wird. |
| [RenditionType](./renditiontype/) | Aufzählung beschreibt mögliche Typen von Wiedergaben. |
| [ReplyType](./replytype/) | Enumeriert die Arten der Beziehungen (der "Antworttyp") zwischen der Annotation und einer durch InReplyTo angegebenen. |
| [SoundEncoding](./soundencoding/) | Das Codierungsformat für die Beispieldaten. |
| [SoundIcon](./soundicon/) | Enumeriert die Symbole, die bei der Anzeige der Annotation verwendet werden sollen. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Das Codierungsformat für die Soundbeispieldaten. |
| [StampIcon](./stampicon/) | Enumeriert die Symbole, die bei der Anzeige der Annotation verwendet werden sollen. |
| [TextIcon](./texticon/) | Enumeriert die Symbole, die bei der Anzeige der Annotation verwendet werden sollen. |