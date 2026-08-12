---
title: "Aspose::Pdf::Annotations namnrymd"
linktitle: "Aspose::Pdf::Annotations"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations namnrymd. Aspose.Pdf.Annotations‑namnrymden tillhandahåller klasser för att arbeta med olika typer av åtgärder, destinationer och andra funktioner i dokument som traditionellt kallas interaktiva och ger möjlighet för användaren att kommunicera med det i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.annotations/
---

Den **[Aspose.Pdf.Annotations](./)** namnrymden tillhandahåller klasser för att arbeta med olika typer av åtgärder, destinationer och andra funktioner i dokument som traditionellt kallas interaktiva och ger möjlighet för användaren att kommunicera med det.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [ActionCollection](./actioncollection/) | [Collection](../aspose.pdf/collection/) av åtgärder. |
| [Annotation](./annotation/) | Klass som representerar annoteringsobjekt. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representerar samlingen av annoteringsåtgärder. |
| [AnnotationCollection](./annotationcollection/) | Klass som representerar annoteringssamling. |
| [AnnotationFlagsConverter](./annotationflagsconverter/) |  |
| [AnnotationSelector](./annotationselector/) | Denna klass används för att välja annotationer med Visitor‑mallidé. |
| [AnnotationStateConverter](./annotationstateconverter/) |  |
| [AnnotationStateModelConverter](./annotationstatemodelconverter/) |  |
| [AppearanceDictionary](./appearancedictionary/) | [Annotation](./annotation/) utseendediktionär som specificerar hur annotationen ska presenteras visuellt på sidan. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representerar en Bleed Mark‑annotation. |
| [Border](./border/) | Klass som representerar egenskaper för annoteringsramen. |
| [BorderEffectConverter](./bordereffectconverter/) |  |
| [BorderStyleConverter](./borderstyleconverter/) |  |
| [CaptionPositionConverter](./captionpositionconverter/) |  |
| [CaretAnnotation](./caretannotation/) | Klass som representerar Caret‑annotation. |
| [CaretSymbolConverter](./caretsymbolconverter/) |  |
| [Characteristics](./characteristics/) | Representerar annoteringsegenskaper. |
| [CircleAnnotation](./circleannotation/) | Klass som representerar Circle‑annotation. |
| [ColorBarAnnotation](./colorbarannotation/) | Klass som representerar [ColorBarAnnotation](./colorbarannotation/) annotation. Egenskapen [Color](../aspose.pdf/color/) ignoreras, istället används färgen [ColorsOfCMYK](./colorsofcmyk/). Vid skapande bestämmer förhållandet mellan bredd och höjd orienteringen av annotationen – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till den närmaste platsen utanför TrimBox, med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte). |
| [ColorsOfCMYKConverter](./colorsofcmykconverter/) |  |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstrakt klass som representerar gemensam figur‑annotation. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representerar annotationstyper som placeras i hörnen på den tryckta sidan. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representerar anpassad explicit destination. |
| [Dash](./dash/) | Klass som representerar linjestreckmönster. |
| [DefaultAppearance](./defaultappearance/) | Beskriver standardutseendet för fältet (teckensnitt, textstorlek och färg). |
| [DocumentActionCollection](./documentactioncollection/) | Klass som beskriver åtgärder som utförs på vissa handlingar med dokumentet. |
| [ExplicitDestination](./explicitdestination/) | Representerar basklassen för explicita destinationer i PDF‑dokument. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) |  |
| [FdfReader](./fdfreader/) | Klass som utför läsning av FDF‑format. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Klass som beskriver filbilags‑annotation. |
| [FileIconConverter](./fileiconconverter/) |  |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att dess omgivningsruta helt får plats i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av dem och centrera omgivningsrutan i fönstret i den andra dimensionen. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets överkant och sidans innehåll förstorat precis tillräckligt för att hela bredden av dess omgivningsruta får plats i fönstret. Ett null‑värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis tillräckligt för att hela höjden av dess omgivningsruta får plats i fönstret. Ett null‑värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att hela sidan får plats i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av dem och centrera sidan i fönstret i den andra dimensionen. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets överkant och sidans innehåll förstorat precis tillräckligt för att hela sidans bredd får plats i fönstret. Ett null‑värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att rektangeln som specificeras av koordinaterna left, bottom, right och top får plats helt i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av dem och centrera rektangeln i fönstret i den andra dimensionen. Ett null‑värde för någon av parametrarna kan leda till oförutsägbart beteende. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis tillräckligt för att hela sidans höjd får plats i fönstret. Ett null‑värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FixedPrint](./fixedprint/) | Representerar fast utskriftsdata för [Watermark](../aspose.pdf/watermark/)[Annotation](./annotation/). |
| [FreeTextAnnotation](./freetextannotation/) | Representerar en fri textanteckning som visar text direkt på sidan. Till skillnad från en vanlig textanteckning har en fri textanteckning inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig. |
| [FreeTextIntentConverter](./freetextintentconverter/) |  |
| [GenericAnnotation](./genericannotation/) | Klassen beskriver generell annotation. |
| [GoToAction](./gotoaction/) | Representerar en gå-till‑åtgärd som ändrar vyn till en angiven destination (sida, plats och förstoring). |
| [GoToRemoteAction](./gotoremoteaction/) | Representerar en fjärr‑gå‑till‑åtgärd som liknar en vanlig gå‑till‑åtgärd men hoppar till en destination i en annan PDF‑fil istället för den aktuella filen. |
| [GoToURIAction](./gotouriaction/) | Representerar en URI‑åtgärd som får en URI att lösas upp. |
| [HideAction](./hideaction/) | Representerar en göm‑åtgärd som döljer eller visar en eller flera anteckningar på skärmen genom att sätta eller rensa deras gömda‑flaggor. |
| [HighlightAnnotation](./highlightannotation/) | Representerar en markeringsanteckning som markerar ett textområde i dokumentet. |
| [HighlightingModeConverter](./highlightingmodeconverter/) |  |
| [IAnnotationVisitor](./iannotationvisitor/) | Definierar Visitor för att besöka olika dokumentanteckningar. |
| [IAppointment](./iappointment/) | Representerar ett generellt gränssnitt för åtgärder och destinationer. |
| [ImportDataAction](./importdataaction/) | Vid anrop av en import‑data‑åtgärd ska [Forms](../aspose.pdf.forms/) Data Format (FDF)-data importeras till dokumentets interaktiva formulär från en angiven fil. |
| [InkAnnotation](./inkannotation/) | Representerar en frihands‑\"klotter\" bestående av en eller flera separata banor. |
| [JavascriptAction](./javascriptaction/) | Klass som representerar javascript‑åtgärd. |
| [JustificationConverter](./justificationconverter/) |  |
| [LaunchAction](./launchaction/) | Representerar en start‑åtgärd som startar ett program eller öppnar eller skriver ut ett dokument. |
| [LaunchActionOperationConverter](./launchactionoperationconverter/) |  |
| [LineAnnotation](./lineannotation/) | Klass som representerar linjeanteckning. |
| [LineEndingConverter](./lineendingconverter/) |  |
| [LineIntentConverter](./lineintentconverter/) |  |
| [LinkAnnotation](./linkannotation/) | Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras. |
| [MarkupAnnotation](./markupannotation/) | Abstrakt klass som representerar markup‑anteckning. |
| [Measure](./measure/) | Klass som beskriver [Measure](./measure/) koordinatsystem. |
| [MediaClip](./mediaclip/) | Klass som beskriver media‑klippobjekt för återgivning. |
| [MediaClipData](./mediaclipdata/) | Klass som beskriver media‑klippdata. |
| [MediaClipSection](./mediaclipsection/) | Denna klass beskriver Media‑klippsektion. |
| [MediaRendition](./mediarendition/) | Klass som beskriver mediaåtergivning. |
| [MovieAnnotation](./movieannotation/) | Representerar en filmanteckning som innehåller animerad grafik och ljud som ska visas på datorskärmen och genom högtalarna. När anteckningen aktiveras spelas filmen. |
| [NamedAction](./namedaction/) | Representerar namngivna åtgärder som PDF‑visningsprogram förväntas stödja. |
| [NamedDestination](./nameddestination/) | Istället för att definieras direkt med den explicita syntaxen kan en destination refereras indirekt via ett namnobjekt eller en bytesträng. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representerar en [Page](../aspose.pdf/page/) informationsanteckning i ett PDF‑dokument. Denna anteckning innehåller filnamnet, sidnumret samt datum och tid för anteckningens skapande. |
| [PDF3DAnnotation](./pdf3dannotation/) | Klassen [PDF3DAnnotation](./pdf3dannotation/). Denna klass kan inte ärvas. |
| [PDF3DArtwork](./pdf3dartwork/) | Klassen [PDF3DArtwork](./pdf3dartwork/). |
| [PDF3DContent](./pdf3dcontent/) | Klassen [PDF3DContent](./pdf3dcontent/). |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Klassen [PDF3DCrossSection](./pdf3dcrosssection/). |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Klassen [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/). |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Klassen [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/). |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Klassen [PDF3DLightingScheme](./pdf3dlightingscheme/). |
| [PDF3DRenderMode](./pdf3drendermode/) | Klassen [PDF3DRenderMode](./pdf3drendermode/). |
| [PDF3DStream](./pdf3dstream/) | Klassen [PDF3DStream](./pdf3dstream/). |
| [PDF3DView](./pdf3dview/) | Klassen [PDF3DView](./pdf3dview/). |
| [PDF3DViewArray](./pdf3dviewarray/) | Klassen [PDF3DViewArray](./pdf3dviewarray/). |
| [PdfAction](./pdfaction/) | Representerar en åtgärd i PDF-dokumentet. |
| [PdfActionCollection](./pdfactioncollection/) | Klassen beskriver en lista med åtgärder. |
| [PolyAnnotation](./polyannotation/) | Abstrakt basklass för poly-anteckningar. |
| [PolygonAnnotation](./polygonannotation/) | Klassen som representerar en polygonanteckning. |
| [PolyIntentConverter](./polyintentconverter/) |  |
| [PolylineAnnotation](./polylineannotation/) | Representerar en polylinjeanteckning som liknar polygon, förutom att den första och sista vertexen inte är implicit anslutna. |
| [PopupAnnotation](./popupannotation/) | Representerar pop-up-anteckningen som visar text i ett pop-up-fönster för inmatning och redigering. |
| [PredefinedActionConverter](./predefinedactionconverter/) |  |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstrakt klass som representerar skrivarmärkesanteckning. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Tillhandahåller förlängningsmetoder för uppräkningen [PrinterMarksKind](./printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Representerar Redact-anteckning. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representerar en Registreringsmärke-anteckning. |
| [Rendition](./rendition/) | Klassen som beskriver renditionsobjektet för RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | En renditionsåtgärd som styr uppspelning av multimediainnehåll. |
| [ReplyTypeConverter](./replytypeconverter/) |  |
| [RichMediaAnnotation](./richmediaannotation/) | Klassen beskriver [RichMediaAnnotation](./richmediaannotation/) som tillåter inbäddning av video-/ljuddata i PDF-dokumentet. |
| [ScreenAnnotation](./screenannotation/) | En skärmanteckning som specificerar ett område på en sida där mediaklipp kan spelas upp. |
| [SelectorRendition](./selectorrendition/) | Klassen beskriver selector-återgivning. |
| [SoundAnnotation](./soundannotation/) | Representerar en ljudanteckning som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil. |
| [SoundData](./sounddata/) | Representerar ljuddata som definierar ljudet som ska spelas när anteckningen aktiveras. |
| [SoundEncodingConverter](./soundencodingconverter/) |  |
| [SoundIconConverter](./soundiconconverter/) |  |
| [SoundSampleData](./soundsampledata/) | Representerar ytterligare poster specifika för ett ljudobjekt (Section 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Klassen som representerar fyrkantig annotation. |
| [SquigglyAnnotation](./squigglyannotation/) | Representerar den krusiga annotationen som visas som en ojämn understrykning i dokumentets text. |
| [StampAnnotation](./stampannotation/) | Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om den stämplats på sidan med en gummistämpel. |
| [StampIconConverter](./stampiconconverter/) |  |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representerar en genomstrykningannotation som visas som en genomstrykning i dokumentets text. |
| [SubmitFormAction](./submitformaction/) | Klassen som beskriver submit-form‑åtgärd. |
| [TextAnnotation](./textannotation/) | Representerar en textannotation som är en 'klistrig lapp' fäst vid en punkt i PDF-dokumentet. |
| [TextIconConverter](./texticonconverter/) |  |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstrakt basklass för textmarkeringsannotationer. |
| [TextStyle](./textstyle/) | Klassen representerar stil för text i annotation. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representerar en Trim Mark‑annotation. |
| [UnderlineAnnotation](./underlineannotation/) | Representerar en understrykningannotation som visas som en understrykning i dokumentets text. |
| [WatermarkAnnotation](./watermarkannotation/) | Klassen beskriver [Watermark](../aspose.pdf/watermark/) annotationsobjekt. |
| [WidgetAnnotation](./widgetannotation/) | Klassen som representerar widget‑annotation. |
| [XfdfReader](./xfdfreader/) | Klassen som utför läsning av XFDF-formatet. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Representerar en explicit destination som visar sidan med koordinaterna (left, top) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoomfaktorn. Ett null‑värde för någon av parametrarna left, top eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | En uppsättning flaggor som specificerar olika egenskaper hos annotationen. |
| [AnnotationState](./annotationstate/) | Uppräkningen av tillstånd som den ursprungliga annotationen kan sättas till. |
| [AnnotationStateModel](./annotationstatemodel/) | Tillståndsmodellen som motsvarar annotationens tillstånd. |
| [AnnotationType](./annotationtype/) | Uppräkning av annotationstyper. |
| [BorderEffect](./bordereffect/) | Beskriver den effekt som ska tillämpas på annotationernas kant. |
| [BorderStyle](./borderstyle/) | Beskriver stil för annotationens kant. |
| [CapStyle](./capstyle/) | Stil för linjeändning av bläckannotationslinje. |
| [CaptionPosition](./captionposition/) | Uppräkning av annoteringens bildtextpositionering. |
| [CaretSymbol](./caretsymbol/) | En symbol som ska associeras med markören. |
| [ColorsOfCMYK](./colorsofcmyk/) | Färger som ingår i CMYK-färgmodellen. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumererar typerna av explicita destinationer. |
| [FileIcon](./fileicon/) | En ikon som ska användas vid visning av annoteringen. |
| [FreeTextIntent](./freetextintent/) | Enumererar avsikterna för fri text-annotering. |
| [HighlightingMode](./highlightingmode/) | Enumererar annoteringens markeringsläge, den visuella effekten som ska användas när musknappen trycks ned eller hålls nedtryckt inom dess aktiva område. |
| [Justification](./justification/) | Enumererar formerna av justering (quadding) som ska användas vid visning av annoteringens text. |
| [LaunchActionOperation](./launchactionoperation/) | Enumererar operationerna som ska utföras med dokumentet under körning av startåtgärden. |
| [LightingSchemeType](./lightingschemetype/) | Enum [LightingSchemeType](./lightingschemetype/): uppsättning av belysningsschematyper. |
| [LineEnding](./lineending/) | Enumererar linjeändningsstilarna som ska användas vid ritning av linjen. |
| [LineIntent](./lineintent/) | Enumererar avsikterna för linjeannoteringen. |
| [PDF3DActivation](./pdf3dactivation/) | Enum [PDF3DActivation](./pdf3dactivation/): uppsättning av 3D-annoteringsaktiveringslägen. |
| [PolyIntent](./polyintent/) | Enumererar avsikterna för polygon- eller polylinjeannoteringen. |
| [PredefinedAction](./predefinedaction/) | Definierar olika åtgärder som kan utlösas från en PDF-fil. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representerar en position för en markering i ett hörn på en sida. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representerar en position för en registreringsmarkering på en sida. |
| [PrinterMarksKind](./printermarkskind/) | Specificerar typerna av skrivarens markeringar som ska läggas till i ett dokument. |
| [RenderModeType](./rendermodetype/) | Enum [RenderModeType](./rendermodetype/): uppsättning av renderingslägen. |
| [RenditionOperation](./renditionoperation/) | Operationen som ska utföras när åtgärden utlöses. |
| [RenditionType](./renditiontype/) | Uppräkning beskriver möjliga typer av [Rendition](./rendition/). |
| [ReplyType](./replytype/) | Enumererar typerna av relationerna ("svarstypen") mellan annoteringen och den som specificeras av InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Alternativ för formatering av textfragment i RichText. |
| [SoundEncoding](./soundencoding/) | Kodningsformatet för exempeldata. |
| [SoundIcon](./soundicon/) | Enumererar ikonerna som ska användas vid visning av annoteringen. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Kodningsformatet för ljudsamplingsdata. |
| [StampIcon](./stampicon/) | Enumererar ikonerna som ska användas vid visning av annoteringen. |
| [TextAlignment](./textalignment/) | Justering av text i annotering. |
| [TextIcon](./texticon/) | Enumererar ikonerna som ska användas vid visning av annoteringen. |
