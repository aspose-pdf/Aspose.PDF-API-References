---
title: "Aspose.Pdf.Annotations"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Namnutrymmet Aspose.Pdf.Annotations tillhandahåller klasser för att arbeta med olika typer av åtgärdsdestinationer och andra funktioner i dokument som traditionellt kallas interaktiva och ger möjlighet för användaren att interkommunicera med det."
type: docs
weight: 50
url: /sv/net/aspose.pdf.annotations/
---
Namnområdet **Aspose.Pdf.Annotations** tillhandahåller klasser för att arbeta med olika typer av åtgärder, destinationer och andra funktioner i dokumentet som traditionellt kallas interaktiva och ger användaren möjlighet att kommunicera med det.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [ActionCollection](./actioncollection/) | Samling av åtgärder |
| [Annotation](./annotation/) | Klass som representerar annoteringsobjekt. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representerar samlingen av annoteringsåtgärder. |
| [AnnotationCollection](./annotationcollection/) | Klass som representerar en annoteringssamling. |
| [AnnotationSelector](./annotationselector/) | Denna klass används för att välja annotationer med hjälp av Visitor‑mallidén. |
| [AppearanceDictionary](./appearancedictionary/) | Ordbok för annoteringsutseende som specificerar hur annotationen ska visas visuellt på sidan. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representerar en Bleed Mark‑annotation. |
| [Border](./border/) | Klass som representerar egenskaperna för annoteringsramen. |
| [CaretAnnotation](./caretannotation/) | Klass som representerar Caret‑annotation. |
| [Characteristics](./characteristics/) | Representerar annoteringsegenskaper |
| [CircleAnnotation](./circleannotation/) | Klass som representerar Circle‑annotation. |
| [ColorBarAnnotation](./colorbarannotation/) | Klass som representerar ColorBarAnnotation‑annotation. Property Color ignoreras, istället används ColorsOfCMYK‑färgen. Vid skapande bestämmer förhållandet mellan bredd och höjd orienteringen av annotationen – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till den närmaste platsen utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstrakt klass som representerar en gemensam figurannotation. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representerar annoteringstyper som placeras i hörnen på den utskrivna sidan. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representerar en anpassad explicit destination. |
| [Dash](./dash/) | Klass som representerar linjestreckmönster. |
| [DefaultAppearance](./defaultappearance/) | Beskriver standardutseendet för fältet (teckensnitt, textstorlek och färg). |
| [DocumentActionCollection](./documentactioncollection/) | Klass beskriver åtgärder som utförs på vissa handlingar med dokumentet. |
| [ExplicitDestination](./explicitdestination/) | Representerar basklassen för explicita destinationer i PDF-dokument. |
| [FdfReader](./fdfreader/) | Klass som läser FDF-format. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Klass som beskriver filbilagsannotation. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis så att dess begränsningsruta får plats helt i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringarna är olika, använd den mindre av de två och centrera begränsningsrutan i fönstret i den andra dimensionen. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorat precis så att hela bredden av dess begränsningsruta får plats i fönstret. Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis så att hela höjden av dess begränsningsruta får plats i fönstret. Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis så att hela sidan får plats i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringarna är olika, använd den mindre av de två och centrera sidan i fönstret i den andra dimensionen. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorat precis så att hela sidans bredd får plats i fönstret. Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis så att den rektangel som anges av koordinaterna left, bottom, right och top får plats helt i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringarna är olika, använd den mindre av de två och centrera rektangeln i fönstret i den andra dimensionen. Ett null-värde för någon av parametrarna kan leda till oförutsägbart beteende. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis så att hela sidans höjd får plats i fönstret. Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FixedPrint](./fixedprint/) | Representerar fast utskriftsdata för vattenstämpelannotation. |
| [FreeTextAnnotation](./freetextannotation/) | Representerar en fri text-annotation som visar text direkt på sidan. Till skillnad från en vanlig text-annotation har en fri text-annotation inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig. |
| [GoToAction](./gotoaction/) | Representerar en gå-till‑åtgärd som ändrar vyn till en angiven destination (sida, plats och förstoring). |
| [GoToRemoteAction](./gotoremoteaction/) | Representerar en fjärr‑gå‑till‑åtgärd som liknar en vanlig gå‑till‑åtgärd men hoppar till en destination i en annan PDF‑fil istället för den aktuella filen. |
| [GoToURIAction](./gotouriaction/) | Representerar en URI‑åtgärd som får en URI att lösas upp. |
| [HideAction](./hideaction/) | Representerar en göm‑åtgärd som döljer eller visar en eller flera annotationer på skärmen genom att sätta eller rensa deras gömda‑flaggor. |
| [HighlightAnnotation](./highlightannotation/) | Representerar en markerings‑annotation som markerar ett textområde i dokumentet. |
| [ImportDataAction](./importdataaction/) | Vid anrop av en import‑data‑åtgärd ska Forms Data Format (FDF)-data importeras till dokumentets interaktiva formulär från en angiven fil. |
| [InkAnnotation](./inkannotation/) | Representerar en frihands‑"klotter" bestående av en eller flera separata banor. |
| [JavascriptAction](./javascriptaction/) | Klass som representerar en javascript‑åtgärd. |
| [LaunchAction](./launchaction/) | Representerar en start‑åtgärd som startar ett program eller öppnar eller skriver ut ett dokument. |
| [LineAnnotation](./lineannotation/) | Klass som representerar en linje‑annotation. |
| [LinkAnnotation](./linkannotation/) | Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras. |
| [MarkupAnnotation](./markupannotation/) | Abstrakt klass som representerar en markup‑annotation. |
| [Measure](./measure/) | Klass som beskriver mätsystemets koordinater. |
| [MediaClip](./mediaclip/) | Klass som beskriver media‑klippobjektet för återgivning. |
| [MediaClipData](./mediaclipdata/) | Klass som beskriver media‑klippdata. |
| [MediaClipSection](./mediaclipsection/) | Denna klass beskriver media‑klippssektionen. |
| [MediaRendition](./mediarendition/) | Klass som beskriver media‑återgivning. |
| [MovieAnnotation](./movieannotation/) | Representerar en film‑annotation som innehåller animerad grafik och ljud som ska visas på datorskärmen och genom högtalarna. När annotationen aktiveras spelas filmen upp. |
| [NamedAction](./namedaction/) | Representerar namngivna åtgärder som PDF‑visningsprogram förväntas stödja. |
| [NamedDestination](./nameddestination/) | Istället för att definieras direkt med den explicita syntaxen kan en destination refereras indirekt via ett namnobjekt eller en bytesträng. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representerar en sidinformation‑annotation i ett PDF‑dokument. Denna annotation innehåller filnamnet, sidnumret samt datum och tid för annotationens skapande. |
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
| [PdfActionCollection](./pdfactioncollection/) | Klass beskriver lista över åtgärder. |
| [PolyAnnotation](./polyannotation/) | Abstrakt basklass för poly-anteckningar. |
| [PolygonAnnotation](./polygonannotation/) | Klass som representerar polygonanteckning. |
| [PolylineAnnotation](./polylineannotation/) | Representerar polylinjeanteckning som liknar polygon, förutom att den första och sista vertexen inte är implicit anslutna. |
| [PopupAnnotation](./popupannotation/) | Representerar popup-anteckningen som visar text i ett popup-fönster för inmatning och redigering. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstrakt klass som representerar skrivarmärkesanteckning. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Tillhandahåller förlängningsmetoder för [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/)‑enumerationen. |
| [RedactionAnnotation](./redactionannotation/) | Representerar Redact-anteckning. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representerar en Registreringsmärkesanteckning. |
| [Rendition](./rendition/) | Klass som beskriver renditionsobjektet för RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | En renditionsåtgärd som styr uppspelning av multimedia-innehåll. |
| [RichMediaAnnotation](./richmediaannotation/) | Klass beskriver RichMediaAnnotation som tillåter inbäddning av video-/ljuddata i PDF-dokument. |
| [ScreenAnnotation](./screenannotation/) | En skärmanteckning som specificerar ett område på en sida där mediaklipp kan spelas. |
| [SelectorRendition](./selectorrendition/) | Klass beskriver selector-rendition. |
| [SoundAnnotation](./soundannotation/) | Representerar en ljudanteckning som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil. |
| [SoundData](./sounddata/) | Representerar ljuddata som definierar ljudet som ska spelas när anteckningen aktiveras. |
| [SoundSampleData](./soundsampledata/) | Representerar ytterligare poster som är specifika för ett ljudobjekt (Avsnitt 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Klass som representerar fyrkantig annotation. |
| [SquigglyAnnotation](./squigglyannotation/) | Representerar den krusiga annotationen som visas som en ojämn understrykning i texten i ett dokument. |
| [StampAnnotation](./stampannotation/) | Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om den stämplats på sidan med en gummistämpel. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representerar en genomstruken annotation som visas som en genomstrykning i dokumentets text. |
| [SubmitFormAction](./submitformaction/) | Klass som beskriver submit-form‑åtgärd. |
| [TextAnnotation](./textannotation/) | Representerar en textannotation som är en 'klistrig lapp' fäst vid en punkt i PDF‑dokumentet. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstrakt basklass för textmarkeringsannotationer. |
| [TextStyle](./textstyle/) | Klass som representerar stil för text i annotation |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representerar en Trim‑mark‑annotation. |
| [UnderlineAnnotation](./underlineannotation/) | Representerar en understrykningannotation som visas som en understrykning i dokumentets text. |
| [WatermarkAnnotation](./watermarkannotation/) | Klass som beskriver vattenstämpel‑annotationsobjekt. |
| [WidgetAnnotation](./widgetannotation/) | Klass som representerar widget‑annotation. |
| [XfdfReader](./xfdfreader/) | Klass som utför läsning av XFDF‑format. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Representerar en explicit destination som visar sidan med koordinaterna (vänster, topp) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoom‑faktorn. Ett null‑värde för någon av parametrarna vänster, topp eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Definierar Visitor för att besöka olika dokumentannotationer. |
| [IAppointment](./iappointment/) | Representerar ett generellt gränssnitt för åtgärder och destinationer. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | En uppsättning flaggor som specificerar olika egenskaper hos annotationen. |
| [AnnotationState](./annotationstate/) | Uppräkningen av tillstånd som den ursprungliga annotationen kan sättas till. |
| [AnnotationStateModel](./annotationstatemodel/) | Tillståndsmodellen som motsvarar annotationens tillstånd. |
| [AnnotationType](./annotationtype/) | Uppräkning av annotationstyper. |
| [BorderEffect](./bordereffect/) | Beskriver effekt som ska tillämpas på kantlinjen för annotationerna. |
| [BorderStyle](./borderstyle/) | Beskriver stil för annotationens kantlinje. |
| [CapStyle](./capstyle/) | Stil för linjeändning på bläck‑annotationslinjen. |
| [CaptionPosition](./captionposition/) | Uppräkning av placeringen för annotationens rubrik. |
| [CaretSymbol](./caretsymbol/) | En symbol som ska associeras med markören. |
| [ColorsOfCMYK](./colorsofcmyk/) | Färger som ingår i CMYK-färgmodellen. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumererar typerna av explicita destinationer. |
| [FileIcon](./fileicon/) | En ikon som ska användas vid visning av annotationen. |
| [FreeTextIntent](./freetextintent/) | Enumererar avsikterna för fri text-annotation. |
| [HighlightingMode](./highlightingmode/) | Enumererar annotationens markeringsläge, den visuella effekten som ska användas när musknappen trycks ned eller hålls ned i dess aktiva område. |
| [Justification](./justification/) | Enumererar formerna av justering (quadding) som ska användas vid visning av annotationens text. |
| [LaunchActionOperation](./launchactionoperation/) | Enumererar operationerna som ska utföras med dokumentet under körning av startåtgärden. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: uppsättning av belysningsschematyper. |
| [LineEnding](./lineending/) | Enumererar linjeändningsstilarna som ska användas vid ritning av linjen. |
| [LineIntent](./lineintent/) | Enumererar avsikterna för linjeannotation. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: uppsättning av 3D-annotationsaktiveringslägen. |
| [PolyIntent](./polyintent/) | Enumererar avsikterna för polygon- eller polylinjeannotation. |
| [PredefinedAction](./predefinedaction/) | Definierar olika åtgärder som kan utlösas från en PDF-fil. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representerar en position för en markering i ett hörn på en sida. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representerar en position för en registreringsmarkering på en sida. |
| [PrinterMarksKind](./printermarkskind/) | Specificerar typerna av skrivarens markeringar som ska läggas till i ett dokument. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: uppsättning av renderingslägen |
| [RenditionOperation](./renditionoperation/) | Operationen som ska utföras när åtgärden utlöses. |
| [RenditionType](./renditiontype/) | Enumeration beskriver möjliga typer av rendition. |
| [ReplyType](./replytype/) | Enumererar typerna av relationer ("svarstypen") mellan annotationen och den som anges av InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Alternativ för formatering av textfragment i RichText. |
| [SoundEncoding](./soundencoding/) | Kodningsformatet för exempeldata. |
| [SoundIcon](./soundicon/) | Enumererar ikonerna som ska användas vid visning av annotationen. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Kodningsformatet för ljudexempeldata. |
| [StampIcon](./stampicon/) | Enumererar ikonerna som ska användas vid visning av annotationen. |
| [TextIcon](./texticon/) | Enumererar ikonerna som ska användas vid visning av annotationen. |


