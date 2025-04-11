---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations-namnområdet tillhandahåller klasser för att arbeta med olika typer av åtgärder, destinationer och andra funktioner i dokumentet som traditionellt kallas interaktiva och ger användaren möjlighet att kommunicera med det.
type: docs
weight: 50
url: /sv/net/aspose.pdf.annotations/
---
Namnområdet **Aspose.Pdf.Annotations** tillhandahåller klasser för att arbeta med olika typer av åtgärder, destinationer och andra funktioner i dokumentet som traditionellt kallas interaktiva och ger användaren möjlighet att kommunicera med det.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [ActionCollection](./actioncollection/) | Samling av åtgärder |
| [Annotation](./annotation/) | Klass som representerar annotationsobjekt. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representerar samlingen av annotationsåtgärder. |
| [AnnotationCollection](./annotationcollection/) | Klass som representerar annotationssamling. |
| [AnnotationSelector](./annotationselector/) | Denna klass används för att välja annotationer med hjälp av Visitor-mallens idé. |
| [AppearanceDictionary](./appearancedictionary/) | Annotationens utseendediktionär som specificerar hur annotationen ska presenteras visuellt på sidan. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representerar en Bleed Mark-annotation. |
| [Border](./border/) | Klass som representerar egenskaperna för annotationens kant. |
| [CaretAnnotation](./caretannotation/) | Klass som representerar Caret-annotation. |
| [Characteristics](./characteristics/) | Representerar annotationsegenskaper |
| [CircleAnnotation](./circleannotation/) | Klass som representerar Circle-annotation. |
| [ColorBarAnnotation](./colorbarannotation/) | Klass som representerar ColorBarAnnotation-annotation. Egenskapen Color ignoreras, istället används ColorsOfCMYK-färgen. Vid skapande bestämmer förhållandet mellan bredd och höjd orienteringen av annotationen - horisontell eller vertikal. Därefter kontrolleras att annotationens rektangel ligger utanför TrimBox, och om inte, flyttas den till närmaste plats utanför TrimBox, med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen passar utanför TrimBox. Om det inte finns något utrymme för layouten kan bredd/höjd sättas till noll (i detta fall är annotationen närvarande på sidan, men inte synlig). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstrakt klass som representerar vanlig figurannotation. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representerar annotationstyper som placeras i hörnen av den tryckta sidan. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representerar anpassad explicit destination. |
| [Dash](./dash/) | Klass som representerar linjedashmönster. |
| [DefaultAppearance](./defaultappearance/) | Beskriver standardutseendet för fältet (teckensnitt, textstorlek och färg). |
| [DocumentActionCollection](./documentactioncollection/) | Klass som beskriver åtgärder som utförs på vissa åtgärder med dokumentet |
| [ExplicitDestination](./explicitdestination/) | Representerar basklassen för explicita destinationer i PDF-dokument. |
| [FdfReader](./fdfreader/) | Klass som utför läsning av FDF-format. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Klass som beskriver filbilagda annotationer. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representerar en explicit destination som visar sidan med sitt innehåll förstorat precis tillräckligt för att passa hela dess begränsningsruta inom fönstret både horisontellt och vertikalt. Om de nödvändiga horisontella och vertikala förstoringarna är olika, använd den mindre av de två, centrerande begränsningsrutan inom fönstret i den andra dimensionen. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten högst placerad vid fönstrets övre kant och innehållet på sidan förstorat precis tillräckligt för att passa hela bredden av dess begränsningsruta inom fönstret. Ett nullvärde för toppen anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten vänster placerad vid fönstrets vänstra kant och innehållet på sidan förstorat precis tillräckligt för att passa hela höjden av dess begränsningsruta inom fönstret. Ett nullvärde för vänster anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representerar en explicit destination som visar sidan med sitt innehåll förstorat precis tillräckligt för att passa hela sidan inom fönstret både horisontellt och vertikalt. Om de nödvändiga horisontella och vertikala förstoringarna är olika, använd den mindre av de två, centrerande sidan inom fönstret i den andra dimensionen. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten högst placerad vid fönstrets övre kant och innehållet på sidan förstorat precis tillräckligt för att passa hela bredden av sidan inom fönstret. Ett nullvärde för toppen anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representerar en explicit destination som visar sidan med sitt innehåll förstorat precis tillräckligt för att passa rektangeln som specificeras av koordinaterna vänster, botten, höger och topp helt inom fönstret både horisontellt och vertikalt. Om de nödvändiga horisontella och vertikala förstoringarna är olika, använd den mindre av de två, centrerande rektangeln inom fönstret i den andra dimensionen. Ett nullvärde för någon av parametrarna kan resultera i oförutsägbart beteende. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten vänster placerad vid fönstrets vänstra kant och innehållet på sidan förstorat precis tillräckligt för att passa hela höjden av sidan inom fönstret. Ett nullvärde för vänster anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FixedPrint](./fixedprint/) | Representerar fast utskriftsdata för vattenstämpelannotation. |
| [FreeTextAnnotation](./freetextannotation/) | Representerar en fri textannotation som visar text direkt på sidan. Till skillnad från en vanlig textannotation har en fri textannotation inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig. |
| [GoToAction](./gotoaction/) | Representerar en gå-till-åtgärd som ändrar vyn till en specificerad destination (sida, plats och förstoring). |
| [GoToRemoteAction](./gotoremoteaction/) | Representerar en fjärrgå-till-åtgärd som liknar en vanlig gå-till-åtgärd men hoppar till en destination i en annan PDF-fil istället för den aktuella filen. |
| [GoToURIAction](./gotouriaction/) | Representerar en URI-åtgärd som orsakar att en URI löses. |
| [HideAction](./hideaction/) | Representerar en dölja-åtgärd som döljer eller visar en eller flera annotationer på skärmen genom att ställa in eller rensa deras dolda flaggor. |
| [HighlightAnnotation](./highlightannotation/) | Representerar en markeringsannotation som markerar ett textområde i dokumentet. |
| [ImportDataAction](./importdataaction/) | Vid anrop av en importdataåtgärd ska Forms Data Format (FDF) data importeras till dokumentets interaktiva formulär från en specificerad fil. |
| [InkAnnotation](./inkannotation/) | Representerar en frihand "klotter" som består av en eller flera åtskilda vägar. |
| [JavascriptAction](./javascriptaction/) | Klass som representerar javascriptåtgärd. |
| [LaunchAction](./launchaction/) | Representerar en startåtgärd som startar en applikation eller öppnar eller skriver ut ett dokument. |
| [LineAnnotation](./lineannotation/) | Klass som representerar linjeannotation. |
| [LinkAnnotation](./linkannotation/) | Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras. |
| [MarkupAnnotation](./markupannotation/) | Abstrakt klass som representerar markup-annotation. |
| [Measure](./measure/) | Klass som beskriver måttkoordinatsystem. |
| [MediaClip](./mediaclip/) | Klass som beskriver medieklippobjekt av rendition. |
| [MediaClipData](./mediaclipdata/) | Klass som beskriver medieklippdata. |
| [MediaClipSection](./mediaclipsection/) | Denna klass beskriver medieklippssektion. |
| [MediaRendition](./mediarendition/) | Klass som beskriver mediarendition. |
| [MovieAnnotation](./movieannotation/) | Representerar en filmannotation som innehåller animerad grafik och ljud som ska presenteras på datorskärmen och genom högtalarna. När annotationen aktiveras spelas filmen. |
| [NamedAction](./namedaction/) | Representerar namngivna åtgärder som PDF-visningsprogram förväntas stödja. |
| [NamedDestination](./nameddestination/) | Istället för att definieras direkt med den explicita syntaksen kan en destination hänvisas indirekt genom ett namnobjekt eller en byte-sträng. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representerar en sidinformationannotation i ett PDF-dokument. Denna annotation innehåller filnamn, sidnummer och datum och tid för annotationens skapande. |
| [PDF3DAnnotation](./pdf3dannotation/) | Klass PDF3DAnnotation. Denna klass kan inte ärvas. |
| [PDF3DArtwork](./pdf3dartwork/) | Klass PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Klass PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Klass PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Klass PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Klass PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Klass PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Klass PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Klass PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Klass PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Klass PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Representerar åtgärd i PDF-dokument |
| [PdfActionCollection](./pdfactioncollection/) | Klass som beskriver lista över åtgärder. |
| [PolyAnnotation](./polyannotation/) | Abstrakt basklass för poly-annotationer. |
| [PolygonAnnotation](./polygonannotation/) | Klass som representerar polygonannotation. |
| [PolylineAnnotation](./polylineannotation/) | Representerar polyline-annotation som liknar polygon, förutom att den första och sista hörnpunkten inte är implicit kopplade. |
| [PopupAnnotation](./popupannotation/) | Representerar popup-annotation som visar text i ett popup-fönster för inmatning och redigering. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstrakt klass som representerar printermark-annotation. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Tillhandahåller extensionsmetoder för [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) uppräkning. |
| [RedactionAnnotation](./redactionannotation/) | Representerar Redact-annotation. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representerar en registreringsmarkering-annotation. |
| [Rendition](./rendition/) | Klass som beskriver renditionsobjekt av RenditionAnnotation. |
| [RenditionAction](./renditionaction/) | En renditionsåtgärd som kontrollerar uppspelningen av multimediainnehåll. |
| [RichMediaAnnotation](./richmediaannotation/) | Klass som beskriver RichMediaAnnotation som tillåter inbäddning av video-/ljuddata i PDF-dokument. |
| [ScreenAnnotation](./screenannotation/) | En skärmanotation som specificerar ett område av en sida där medieklipp kan spelas. |
| [SelectorRendition](./selectorrendition/) | Klass som beskriver selector-rendition. |
| [SoundAnnotation](./soundannotation/) | Representerar en ljudannotation som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil. |
| [SoundData](./sounddata/) | Representerar ljuddata som definierar ljudet som ska spelas när annotationen aktiveras. |
| [SoundSampleData](./soundsampledata/) | Representerar ytterligare poster specifika för ett ljudobjekt (Avsnitt 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Klass som representerar fyrkantig annotation. |
| [SquigglyAnnotation](./squigglyannotation/) | Representerar den vågiga annotationen som visas som en taggig understrykning i texten i ett dokument. |
| [StampAnnotation](./stampannotation/) | Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om den stämplats på sidan med en gummistämpel. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representerar en genomstruken annotation som visas som en genomstrykning i texten i dokumentet. |
| [SubmitFormAction](./submitformaction/) | Klass som beskriver submit-form-åtgärd. |
| [TextAnnotation](./textannotation/) | Representerar en textannotation som är en 'klisterlapp' fäst vid en punkt i PDF-dokumentet. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstrakt basklass för textmarkup-annotationer. |
| [TextStyle](./textstyle/) | Klass som representerar stil av text i annotation |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representerar en Trim Mark-annotation. |
| [UnderlineAnnotation](./underlineannotation/) | Representerar en understrykning-annotation som visas som en understrykning i texten i dokumentet. |
| [WatermarkAnnotation](./watermarkannotation/) | Klass som beskriver vattenstämpelannotationsobjekt. |
| [WidgetAnnotation](./widgetannotation/) | Klass som representerar widget-annotation. |
| [XfdfReader](./xfdfreader/) | Klass som utför läsning av XFDF-format. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Representerar en explicit destination som visar sidan med koordinaterna (vänster, topp) placerade i det övre vänstra hörnet av fönstret och innehållet på sidan förstorat med faktorn zoom. Ett nullvärde för någon av parametrarna vänster, topp eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett nullvärde. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Definierar Visitor för att besöka olika dokumentannotationer. |
| [IAppointment](./iappointment/) | Representerar allmän gränssnitt för åtgärder och destinationer. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | En uppsättning flaggor som specificerar olika egenskaper hos annotationen. |
| [AnnotationState](./annotationstate/) | Uppräkningen av tillstånd som den ursprungliga annotationen kan sättas till. |
| [AnnotationStateModel](./annotationstatemodel/) | Tillståndsmodellen som motsvarar tillståndet för annotationen. |
| [AnnotationType](./annotationtype/) | Uppräkning av annotationstyper. |
| [BorderEffect](./bordereffect/) | Beskriver effekt som ska tillämpas på kanten av annotationerna. |
| [BorderStyle](./borderstyle/) | Beskriver stil på annotationens kant. |
| [CapStyle](./capstyle/) | Stil på linjeändningen av bläckannotationens linje. |
| [CaptionPosition](./captionposition/) | Uppräkning av annotationens bildtextpositionering. |
| [CaretSymbol](./caretsymbol/) | Ett symbol som ska kopplas till markören. |
| [ColorsOfCMYK](./colorsofcmyk/) | Färger som ingår i CMYK-färgsystemet. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Uppräkning av typer av explicita destinationer. |
| [FileIcon](./fileicon/) | En ikon som ska användas för att visa annotationen. |
| [FreeTextIntent](./freetextintent/) | Uppräkning av avsikterna för fri textannotation. |
| [HighlightingMode](./highlightingmode/) | Uppräkning av annotationens markeringsläge, den visuella effekten som ska användas när musknappen trycks ned eller hålls nere inom dess aktiva område. |
| [Justification](./justification/) | Uppräkning av former av kvadrering (justering) som ska användas vid visning av annotationens text. |
| [LaunchActionOperation](./launchactionoperation/) | Uppräkning av operationerna som ska utföras med dokumentet under utförandet av startåtgärden. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: uppsättning av belysningsschematyper. |
| [LineEnding](./lineending/) | Uppräkning av linjeändningsstilar som ska användas vid ritning av linjen. |
| [LineIntent](./lineintent/) | Uppräkning av avsikterna för linjeannotation. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: uppsättning av 3D-annotationsaktiveringsläge. |
| [PolyIntent](./polyintent/) | Uppräkning av avsikterna för polygon- eller polyline-annotation. |
| [PredefinedAction](./predefinedaction/) | Definierar olika åtgärder som kan utlösas från en PDF-fil. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representerar en position av en markering i ett hörn av en sida. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representerar en position av en registreringsmarkering på en sida. |
| [PrinterMarksKind](./printermarkskind/) | Specificerar typerna av skrivarmärken som ska läggas till ett dokument. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: uppsättning av renderingsmodetyper |
| [RenditionOperation](./renditionoperation/) | Åtgärden som ska utföras när åtgärden utlöses. |
| [RenditionType](./renditiontype/) | Uppräkning som beskriver möjliga typer av rendition. |
| [ReplyType](./replytype/) | Uppräkning av typerna av relationer ("svarstyp") mellan annotationen och en som specificeras av InReplyTo. |
| [SoundEncoding](./soundencoding/) | Det kodningsformat för provdata. |
| [SoundIcon](./soundicon/) | Uppräkning av ikoner som ska användas för att visa annotationen. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Det kodningsformat för ljudprovdata. |
| [StampIcon](./stampicon/) | Uppräkning av ikoner som ska användas för att visa annotationen. |
| [TextIcon](./texticon/) | Uppräkning av ikoner som ska användas för att visa annotationen. |