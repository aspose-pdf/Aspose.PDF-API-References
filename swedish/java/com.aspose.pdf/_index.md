---
title: "com.aspose.pdf"
second_title: "Aspose.PDF för Java API-referens"
description: "com.aspose.pdf är ett rotpaket för alla klasser i Aspose.PDF för Java‑biblioteket som antingen finns direkt i det, som Document, eller indirekt via flera underpaket."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf/
---
com.aspose.pdf är ett rotpaket för alla klasser i Aspose.PDF för Java‑biblioteket som antingen finns direkt i det, som Document, eller indirekt via flera underpaket.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | Återuppringningsproceduren för hocr-igenkänning. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | Återuppringningsproceduren för hocr-igenkänning. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | Återuppringningsproceduren för hocr-igenkänning. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Innehåller funktionalitet för att justera typsnitt |
| [IAnnotationVisitor](./iannotationvisitor/) | Definierar en besökare för att besöka olika dokumentanteckningar. |
| [IAppointment](./iappointment/) | Representerar ett generellt gränssnitt för åtgärder och destinationer. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Gränssnitt för färgrymdsomvandlingsstrategier. |
| [IDocument](./idocument/) | gränssnitt som representerar PDF-dokument |
| [IFontOptions](./ifontoptions/) | Användbara egenskaper för att justera typsnittsbeteende |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Detta gränssnitt deklareras för anpassningsalgoritmer för kvantisering. Användare kan implementera sin egen realisering av dessa algoritmer (till exempel algoritmer baserade på okontrollerad kod). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Detta gränssnitt deklareras för anpassningsalgoritmer för kvantisering. Användare kan implementera sin egen realisering av dessa algoritmer (till exempel algoritmer baserade på okontrollerad kod). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Definierar en besökare för att besöka olika pdf-operatorer. |
| [IPageSetOptions](./ipagesetoptions/) | Definierar konverteringsalternativ relaterade till en uppsättning sidor som ska konverteras. |
| [IPipelineOptions](./ipipelineoptions/) | Definierar konverteringsalternativ relaterade till pipeline-konfiguration. |
| [ITableElement](./itableelement/) | Detta gränssnitt representerar ett element i en befintlig tabell som extraherats av TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.PDf i molnet är direkt åtkomst till refererade filer omöjlig, och någon anpassad kod som placeras i en speciell metod bör användas. Detta delegat definierar signaturen för en sådan anpassad metod. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Ställ in flaggan om den temporära mappen ska användas för att lagra temporära teckensnittsdata. / * Sant som standard. / * Använder heap-minne om värdet = falskt; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Till en egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparning av en bild som extraherats från SVG skapad från PDF och som måste sparas som en extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. egen sparning till en ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter infogas i den genererade SVG:n istället för den ursprungliga förväntade sökvägen till bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i den anpassade koden, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo' i parametern. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns. |
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Representerar en cell i en tabell som finns på sidan |
| [AbsorbedRow](./absorbedrow/) | Representerar en rad i en tabell som finns på sidan |
| [AbsorbedTable](./absorbedtable/) | Representerar en tabell som finns på sidan |
| [ActionCollection](./actioncollection/) | Samling av åtgärder |
| [Annotation](./annotation/) | Klass som representerar ett annoteringsobjekt. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representerar samlingen av annoteringsåtgärder. |
| [AnnotationCollection](./annotationcollection/) | Klass som representerar en annoteringssamling. |
| [AnnotationFlags](./annotationflags/) | Flaggor En uppsättning binära flaggor som specificerar olika egenskaper hos annoteringen. |
| [AnnotationSelector](./annotationselector/) | Denna klass används för att välja annoteringar med Visitor‑mallidé. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Klass för rendering av normal och rik text. |
| [AppearanceDictionary](./appearancedictionary/) | Annoteringsutseendedictionary som specificerar hur annoteringen ska visas visuellt på sidan. |
| [ApsLoadOptions](./apsloadoptions/) | Klass beskriver APS‑laddningsalternativ. Alternativ för import från APS XML-format. |
| [ApsSaveOptions](./apssaveoptions/) | Spara alternativ för export till APS XML-format. |
| [ApsToFlowConverter](./apstoflowconverter/) | APS till Flow-konvertering |
| [Artifact](./artifact/) | Klass representerar PDF‑artefaktobjekt. |
| [ArtifactCollection](./artifactcollection/) | Klass representerar en artefaktsamling. |
| [AutoTaggingSettings](./autotaggingsettings/) | Tillhandahåller inställningar för automatisk taggning i PDF‑dokument. Klassen {@link AutoTaggingSettings} möjliggör konfiguration av alternativ för automatisk taggning av PDF‑innehåll. Den inkluderar egenskaper för att aktivera eller inaktivera automatisk taggning, specificera en strategi för rubrikigenkänning och definiera rubriknivåer baserat på teckenstorlekar. |
| [BackgroundArtifact](./backgroundartifact/) | Klass beskriver bakgrundsartefakt. Denna artefakt möjliggör att sätta bakgrund för sidan. |
| [BarcodeField](./barcodefield/) | Klass representerar ett streckkodsfält. |
| [BaseActionCollection](./baseactioncollection/) | Klass kapslar in grundläggande åtgärder med interaktiva åtgärder för sida/annotering/fält |
| [BaseOperatorCollection](./baseoperatorcollection/) | Representerar basklass för operatörssamling. |
| [BaseParagraph](./baseparagraph/) | Representerar ett abstrakt basobjekt som kan läggas till på sidan (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Klassen beskriver Bates-numreringsartefakt. |
| [BitmapInfo](./bitmapinfo/) | Objekt som innehåller en array av pixlar och bitmapinformation. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Bitmap-pixelformat. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representerar en Bleed Mark-annotation. Bleed-markeringar placeras i hörnen på en tryckt sida för att ange var sidan ska beskäras och hur långt den får avvika från beskärningsmarkeringarna. |
| [Border](./border/) | Klassen som representerar egenskaper för annoteringsram. |
| [BorderInfo](./borderinfo/) | Denna klass representerar ram för grafikelement. |
| [BorderSide](./borderside/) | Flaggor enumererar binärt kantens sidor. |
| [BorderStyleConverter](./borderstyleconverter/) | Representerar BorderStyleConverter-klassen |
| [Brush](./brush/) | Denna klass representerar en abstrakt pensel |
| [BuildVersionInfo](./buildversioninfo/) | Denna klass tillhandahåller information om den aktuella produktbyggnaden. |
| [ButtonField](./buttonfield/) | Klassen representerar tryckknappfält. |
| [CaretAnnotation](./caretannotation/) | Klassen som representerar Caret-annotation. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Representerar CaretSymbolConverter-klassen |
| [CdrLoadOptions](./cdrloadoptions/) | Klassen beskriver CDR-inläsningsalternativ. |
| [Cell](./cell/) | Representerar en cell i tabellens rad. |
| [Cells](./cells/) | Representerar en samling av celler i raden. |
| [CgmImportOptions](./cgmimportoptions/) | Importalternativ för import från Computer Graphics Metafile (CGM)-format. |
| [CgmLoadOptions](./cgmloadoptions/) | Innehåller alternativ för att läsa in/ importera CGM-fil till PDF-dokument. |
| [Characteristics](./characteristics/) | Representerar annoteringsegenskaper |
| [CharInfo](./charinfo/) | Representerar ett teckeninformationsobjekt. Tillhandahåller information om teckenpositionering. |
| [CharInfoCollection](./charinfocollection/) | <p> Representerar CharInfo-objektssamling. </p> <hr> <pre> Exemplet demonstrerar hur man itererar genom alla tecken och hämtar tecknet //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Tillhandahåller åtkomst till positionsinformation för teckensegmentets tecken. </p> |
| [CheckboxField](./checkboxfield/) | Klassen som representerar kryssrutfält. |
| [ChoiceField](./choicefield/) | Representerar basklass för valfält. |
| [CircleAnnotation](./circleannotation/) | Klassen som representerar cirkelannotation. |
| [Collection](./collection/) | Representerar klass för Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Representerar en fältklass för dokumentsamlingens schema. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Representerar subtypparametern för ett fält i en schemasamling. |
| [CollectionItem](./collectionitem/) | Representerar en klass för ett samlingsobjekt. Samlingsobjektet innehåller de data som beskrivs av samlingens schema. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Representerar en klass för ett värde av ett samlingsobjekt. |
| [CollectionSchema](./collectionschema/) | Representerar en klass som beskriver "Schema" för en dokumentsamling. |
| [Color](./color/) | Representerar en klass för färgvärde som kan uttryckas i olika färgrymder. |
| [ColorBarAnnotation](./colorbarannotation/) | Klass som representerar ColorBarAnnotation-annotation. Egenskapen Color ignoreras, istället används ColorsOfCMYK-färgen. Vid skapande bestämmer förhållandet mellan bredd och höjd annotationens orientering – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till närmaste plats utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte). |
| [ColumnInfo](./columninfo/) | Denna klass representerar information om en kolumn. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Klass som representerar händelser. |
| [ComboBoxField](./comboboxfield/) | Klass som representerar kombinationsrutan i formuläret. |
| [ComHelper](./comhelper/) | <p> Tillhandahåller metoder för COM-klienter att läsa in ett dokument i Aspose.PDF. </p> <hr> <p> Använd ComHelper-klassen för att läsa in ett dokument från en fil eller ström till ett Document-objekt i en COM-applikation. Document-klassen erbjuder en standardkonstruktor för att skapa ett nytt dokument och erbjuder även överlagrade konstruktorer för att läsa in ett dokument från en fil eller ström. Om du använder Aspose.Words från en .NET-applikation kan du använda alla Document-konstruktorer direkt, men om du använder Aspose.PDF från en COM-applikation är endast standardkonstruktorn för Document tillgänglig. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstrakt klass som representerar vanlig figurannotation. |
| [CompositingParameters](./compositingparameters/) | Representerar ett objekt som innehåller sammansättningsparametrar för grafik i det aktuella grafikläget. |
| [ContentsAppender](./contentsappender/) | Utför innehållsmodifieringar enbart i APPEND-läge. Detta läge möjliggör att undvika onödig och tung parsning av innehållet innan någon förändring görs. Det lägger bara till nya operatorer i slutet eller i början av innehållet. |
| [Copier](./copier/) | Klass för kopiering av objekt. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representerar annoteringstyper som placeras i hörnen på den utskrivna sidan. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representerar en anpassad explicit destination. |
| [CustomSign](./customsign/) | Delegat för anpassad signering av dokumentet (Beta). |
| [Dash](./dash/) | Klass som representerar linjestreckmönster. |
| [DateField](./datefield/) | Datumfält med kalendervy. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Beskriver standardutseendet för fältet (teckensnitt, textstorlek och färg). |
| [DefaultDirectory](./defaultdirectory/) | Anger standardväg för ett visst ändamål. |
| [DestinationCollection](./destinationcollection/) | Klass som representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, "Named Destinations") och (se 7.7.4, "Name Dictionary")) i pdf-dokumentet. |
| [DestinationFactory](./destinationfactory/) | Representerar DestinationFactory-klassen. |
| [DjvuLoadOptions](./djvuloadoptions/) | Klass som beskriver DJVU-inläsningsalternativ. |
| [DocMDPSignature](./docmdpsignature/) | Representerar klassen för dokument‑MDP (modification detection and prevention) signaturtyp. |
| [DocSaveOptions](./docsaveoptions/) | Spara alternativ för export till Doc-format |
| [Document](./document/) | Klass som representerar PDF-dokument. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Klass som beskriver dokumentoptimeringsalgoritm. En instans av denna klass kan användas som parameter till metoden OptimizeResources(). @deprecated Denna klass är föråldrad. Använd com.aspose.pdf.optimization.OptimizationOptions istället. |
| [Document.RepairOptions](./document.repairoptions/) | Representerar alternativ för reparation av ett PDF-dokument. Denna klass erbjuder ett sätt att anpassa reparationsprocessen för ett PDF-dokument. |
| [DocumentActionCollection](./documentactioncollection/) | Klass beskriver åtgärder som utförs på vissa handlingar med dokumentet. |
| [DocumentExtensions](./documentextensions/) | Tillhandahåller ytterligare funktioner för Document-klassen. |
| [DocumentFactory](./documentfactory/) | Klass som möjliggör att skapa/ladda dokument av olika typer. |
| [DocumentInfo](./documentinfo/) | Representerar metadata för PDF-dokument. |
| [DocumentWeb](./documentweb/) | Representerar DocumentWeb-klassen |
| [Element](./element/) | Klass som representerar baselementet i den logiska strukturen. |
| [ElementCollection](./elementcollection/) | Samling av baslogiska strukturelement. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Klass som representerar samling av inbäddade filer. |
| [EncryptedPayload](./encryptedpayload/) | Representerar krypterad nyttolast i filspecifikationen. |
| [EpubLoadOptions](./epubloadoptions/) | Innehåller alternativ för inläsning/import av EPUB-fil till PDF-dokument. |
| [EpubSaveOptions](./epubsaveoptions/) | Spara alternativ för export till EPUB-format |
| [ExcelSaveOptions](./excelsaveoptions/) | Spara alternativ för export till Excel-format |
| [ExplicitDestination](./explicitdestination/) | Representerar basklassen för explicita destinationer i PDF-dokument. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Representerar ExplicitDestinationTypeConverter-klassen |
| [ExportFieldsOptions](./exportfieldsoptions/) | Representerar basklass för alternativ för export av formulärfält. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Representerar alternativ för export av formulärfält till Json-format. Ärver från {@link ExportFieldsOptions} och lägger till specifika alternativ för Json-export. |
| [ExportImportMessages](./exportimportmessages/) | Innehåller olika felmeddelanden för export- och importoperationer av formulärfält. |
| [ExternalSignature](./externalsignature/) | Skapar en fristående PKCS#7Detached-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar. |
| [FdfReader](./fdfreader/) | Klass som utför läsning av FDF-format. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | Basklass för acro-formulärfält. |
| [FieldSerializationResult](./fieldserializationresult/) | Representerar resultatet av en serialiseringsprocess för ett formulärfält. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Representerar statusen för formulärfältets serialisering. |
| [FieldValueType](./fieldvaluetype/) | Representerar typen av fältvärde i en schemakollektion. |
| [FigureElement](./figureelement/) | Klass som representerar en logisk strukturföreställning. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Klass som beskriver filbilaggsannotation. |
| [FileFontSource](./filefontsource/) | Representerar en enskild teckensnittsfilkälla. |
| [FileHyperlink](./filehyperlink/) | Representerar ett filhyperlänksobjekt. |
| [FileIconConverter](./fileiconconverter/) | Representerar klassen FileIconConverter |
| [FileParams](./fileparams/) | Definierar en inbäddad filparameterordbok som ska innehålla ytterligare filspecifik information. |
| [FileSelectBoxField](./fileselectboxfield/) | Fält för filväljarruta-element. |
| [FileSpecification](./filespecification/) | Klass som representerar en inbäddad fil. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att dess omgivningsruta helt får plats i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av de två och centrera omgivningsrutan i fönstret i den andra dimensionen. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorat precis tillräckligt för att den hela bredden av dess omgivningsruta får plats i fönstret. Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis tillräckligt för att den hela höjden av dess omgivningsruta får plats i fönstret. Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att hela sidan får plats i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av de två och centrera sidan i fönstret i den andra dimensionen. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorat precis tillräckligt för att hela sidans bredd får plats i fönstret. Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att rektangeln som anges av koordinaterna left, bottom, right och top får plats helt i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av de två och centrera rektangeln i fönstret i den andra dimensionen. Ett null-värde för någon av parametrarna kan leda till oförutsägbart beteende. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis tillräckligt för att hela sidans höjd får plats i fönstret. Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| [FixedPrint](./fixedprint/) | Representerar fast utskriftsdata för vattenstämpelannotation. |
| [FloatingBox](./floatingbox/) | Representerar en FloatingBox i ett PDF-dokument. FloatingBox är anpassat placerad. |
| [FlowConverter](./flowconverter/) | Konvertera PDF-dokument till Flow-format (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX i EnchanedFlow-läge, TableAbsorber i FlowEngine-läge. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Skicka data från Flow-biblioteket till TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Representerar mappen som innehåller teckensnitts-filer. |
| [Font](./font/) | <p> Representerar teckensnitt-objekt. </p> <hr> <pre> Exemplet visar hur man söker text på första sidan och ändrar teckensnittet för den första sökträffen. // Öppna dokument Document doc = new Document("input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Skapa teckensnitt och markera det för inbäddning Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Ändra teckensnittet för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Spara dokument doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Representerar ett absorber-objekt för teckensnitt. Utför sökning efter teckensnitt och ger åtkomst till sökresultaten via {@code FontAbsorber.Fonts}-samlingen. |
| [FontCollection](./fontcollection/) | <p> Representerar teckensnittssamling. </p> <hr> <pre> Exemplet visar hur man gör alla teckensnitt som deklarerats på sidan inbäddade. // Öppna dokument Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // säkerställ att alla teckensnitt som deklarerats i sidresurser är inbäddade // notera att om teckensnitt deklareras i formulärresurser är de inte åtkomliga från sidresurser for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> Fontsamlingar som representeras av {@code FontCollection}-klassen används i flera scenarier. Till exempel i resurser med {@code Resources.Fonts}-egenskapen. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | PDF/A-standarden kräver att alla teckensnitt måste vara inbäddade i dokumentet. Denna klass innehåller flaggor för fall då det inte är möjligt att bädda in vissa teckensnitt eftersom de saknas på mål‑datorn. |
| [FontRepository](./fontrepository/) | <p> Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt. </p> <hr> <pre> Exemplet visar hur man hittar ett teckensnitt och ersätter teckensnittet för text på första sidan. // Hitta teckensnitt Font font = FontRepository.findFont("Arial"); // Öppna dokument Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(absorber); // Ändra teckensnittet för den första textförekomsten absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Spara dokument doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Representerar en basklass för teckensnittskälla. |
| [FontStyles](./fontstyles/) | Binär Flagga <p> Anger stilinformation som tillämpas på text. </p> <hr> <p> Denna uppräkning har ett {@code FlagsAttribute}-attribut som möjliggör en kombination av dess medlemsvärden. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binär Flagga uppräkning av strategier för teckensnittssubsetting |
| [FooterArtifact](./footerartifact/) | Beskriver sidfotartefakt. Detta kan användas för att ange sidfoten på sidan. |
| [Form](./form/) | Klass som representerar formulärobjekt. |
| [Form.FlattenSettings](./form.flattensettings/) | Klass som beskriver inställningar för formulärplattläggningsprocedur. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Formulär kan innehålla signeringsinformation och kan vara signerade eller osignerade. Ibland måste visningen av formulär i visaren bero på om formuläret är signerat eller inte. Denna enum listar möjliga renderingslägen under konvertering av formulärtypen med avseende på signatur. |
| [FormattedFragment](./formattedfragment/) | Representerar ett abstrakt formaterat fragment. |
| [FreeTextAnnotation](./freetextannotation/) | Representerar en fri textanteckning som visar text direkt på sidan. Till skillnad från en vanlig textanteckning har en fri textanteckning inget öppet eller stängt tillstånd; istället för att visas i ett popup‑fönster är texten alltid synlig. |
| [GoToAction](./gotoaction/) | Representerar en gå‑till‑åtgärd som ändrar vyn till en angiven destination (sida, plats och förstoring). |
| [GoToRemoteAction](./gotoremoteaction/) | Representerar en fjärr‑gå‑till‑åtgärd som liknar en vanlig gå‑till‑åtgärd men hoppar till en destination i en annan PDF‑fil istället för den aktuella filen. |
| [GoToURIAction](./gotouriaction/) | Representerar en URI‑åtgärd som får en URI att lösas upp. |
| [GraphInfo](./graphinfo/) | Representerar grafikinformation. |
| [Group](./group/) | En gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta avbildningsmodellen. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | Klass beskriver rubrikartefakt. Detta artefakt kan användas för att ange sidans rubrik. |
| [HeaderFooter](./headerfooter/) | Klass representerar header‑ eller footer‑PDF‑sida. |
| [Heading](./heading/) | Representerar rubrik. |
| [HideAction](./hideaction/) | Representerar en göm‑åtgärd som döljer eller visar en eller flera anteckningar på skärmen genom att sätta eller rensa deras gömda‑flaggor. |
| [HighlightAnnotation](./highlightannotation/) | Representerar en markeringsanteckning som markerar ett textområde i dokumentet. |
| [HtmlFragment](./htmlfragment/) | Representerar HTML‑fragment. |
| [HtmlLoadOptions](./htmlloadoptions/) | Representerar alternativ för inläsning/import av HTML‑fil till PDF‑dokument. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binär flagga specificerar flaggor som tillsammans med andra alternativ bestämmer storlekar och layouter för sidor. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Spara alternativ för export till HTML‑format. |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Denna enum beskriver möjliga antialiasing‑åtgärder under konvertering. |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Denna klass representerar en uppsättning data som är relaterade till anpassad sparning av CSS under konvertering av PDF till HTML‑format. |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Du kan tilldela den här egenskapen en anpassad strategi som implementerar bearbetning och/eller sparning av en del av CSS som skapades under konvertering av PDF till HTML. I så fall måste bearbetning (t.ex. sparning till ström eller disk) utföras i den anpassade koden. |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML‑dokumentet. T.ex. om du vill göra CSS refererad i HTML som "otherPage.ASPX?CssID=zjjkklj" måste en sådan anpassad strategi returnera "otherPage.ASPX?CssID=zjjkklj". |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Representerar en uppsättning data som är relaterade till en begäran från konverteraren till anpassad kod för att erhålla önskad URL (eller URL‑mall) för den aktuella CSS‑en. |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Denna uppräkning definierar regler som finjusterar kodningslogiken |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Enumererar lägen som kan användas för att spara teckensnitt som refereras i sparad PDF. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Denna klass representerar en uppsättning data som är relaterade till sparande av externa bildresursfiler under PDF till HTML-konvertering. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | enumererar möjliga typer av bildfiler som kan sparas som externa resurser under PDF till HTML-konvertering |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Ibland finns specifika krav på den skapade HTML:n. Denna enum definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Om egenskapen SplitToPages i HtmlSaveOptions är aktiverad, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konvertering av PDF till HTML. Denna klass representerar en uppsättning data som är relaterade till anpassad sparning av en HTML-sidas markup under konvertering av PDF till HTML |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Resultatet av konverteringen kan innehålla en eller flera HTML-sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av den erhållna HTML-sidan (HTML själv) som skapades under konverteringen. I sådant fall kan bearbetning (som att spara i en ström eller på disk) göras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML-sidans markup utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad sparkod fanns. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Enumererar möjliga typer av bildföräldrar som en bild kan tillhöra, HTML-sida eller SVG-föräldrabild |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Denna enum enumererar möjliga lägen för inbäddning av filer som refereras i HTML. Den möjliggör att styra om refererade filer (HTML, teckensnitt, bilder, CSS) ska inbäddas i huvud‑HTML‑filen eller genereras som separata binära enheter |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | En konverterad PDF kan innehålla rasterbilder (.png, *.jpeg osv.). Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resurs (Font eller Bild) som extraherades från PDF och måste sparas som en extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. sparande i ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade HTML:n istället för den ursprungliga antagna sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'resourceSavingInfo' parameter. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod. |
| [Hyperlink](./hyperlink/) | Representerar abstrakt hyperlänk. |
| [IconFit](./iconfit/) | Beskriver hur widget-annotationens ikon ska visas inom dess annoteringsrektangel. |
| [Id](./id/) | <p> Representerar filidentifieringsstruktur. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Representerar bild. |
| [ImageDeleteAction](./imagedeleteaction/) | Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort |
| [ImagePlacement](./imageplacement/) | <p> Representerar egenskaper hos en bild placerad på en PDF-dokumentsida. </p> <hr> <pre> Exemplet visar hur man hittar bilder på den första PDF-dokumentsidan och får bilder som bitmaps med synliga dimensioner. // Öppna dokument Document doc = new Document(\"D:\\\\\\Tests\\\\\\\\input.pdf\"); // Skapa ImagePlacementAbsorber-objekt för att utföra bildplaceringssökning ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Acceptera absorberaren för första sidan doc.getPages().get_Item(1).accept(abs); // Hämta bilder med synliga dimensioner for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Hämta bild från resurser imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Skapa ny bitmap med faktiska dimensioner scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> När en bild placeras på en sida kan den ha andra dimensioner än de fysiska dimensioner som definieras i {@code Resources}. Objektet {@code ImagePlacement} är avsett att tillhandahålla sådan information som dimensioner, upplösning osv. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning av bildanvändningar och ger åtkomst till sökresultat via {@code ImagePlacementAbsorber.ImagePlacements} samling. </p> <hr> <pre> Exemplet visar hur man hittar bilder på den första PDF-dokumentets sida och hämtar bildplaceringsegenskaperna. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber}-objektet används i huvudsak i bildsökningsscenario. När sökningen är klar representeras förekomsterna med {@code ImagePlacement}-objekt som samlingen {@code ImagePlacementAbsorber.ImagePlacements} innehåller. {@code ImagePlacement}-objektet ger åtkomst till bildplaceringsegenskaperna: dimensioner, upplösning etc. </p> Bildens positiva rotation är moturs, för sidan är den medurs. Här behöver vi representera bildens rotationsvinkel, så vi drar av sidans vinkel från bildens vinkel. |
| [ImagePlacementCollection](./imageplacementcollection/) | Representerar en samling av bildplaceringar |
| [ImageStamp](./imagestamp/) | Representerar en grafisk stämpel. |
| [ImageType](./imagetype/) | Representerar bildformatstyper. |
| [ImportDataAction](./importdataaction/) | Vid anrop av en import‑data‑åtgärd ska Forms Data Format (FDF)-data importeras till dokumentets interaktiva formulär från en angiven fil. |
| [ImportFieldsOptions](./importfieldsoptions/) | Representerar basklass för alternativ för import av formulärfält. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Representerar alternativ för import av formulärfält till Json-format. Ärver från {@code ImportFieldsOptions} och lägger till specifika alternativ för Json‑import. |
| [ImportOptions](./importoptions/) | ImportOptions‑typen innehåller ett abstraktionsnivå för enskilda importalternativ. |
| [InkAnnotation](./inkannotation/) | Representerar en frihands‑"klotter" bestående av en eller flera separata banor. |
| [InternalHelper](./internalhelper/) | Intern klass |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | Det undantag som kastas när en operation med formulärtyp inte är giltig. |
| [JavascriptAction](./javascriptaction/) | Klass som representerar javascript‑åtgärd. |
| [JavaScriptCollection](./javascriptcollection/) | Denna klass representerar en samling av JavaScript. |
| [LatexFragment](./latexfragment/) | Representerar TeX‑fragment. @deprecated Använd TeXFragment istället |
| [LatexLoadOptions](./latexloadoptions/) | Representerar alternativ för att ladda/importera TeX‑fil till PDF‑dokument. @deprecated Använd TeXLoadOptions istället. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Spara alternativ för export till TeX-format. @deprecated Använd TeXSaveOptions istället |
| [LaunchAction](./launchaction/) | Representerar en startåtgärd som startar ett program eller öppnar eller skriver ut ett dokument. |
| [Layer](./layer/) | Representerar ett lager inom en PDF‑sida. |
| [LevelFormat](./levelformat/) | Representerar formatet för innehållsförteckningen. |
| [License](./license/) | Tillhandahåller metoder för att licensiera komponenten. I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för ingångssamlingen och sedan i de inbäddade resurserna för den anropande samlingen. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Representerar licensinformation. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Lättviktig operator-samling. Avsedd att användas i scenarier när underliggande innehållsström inte är bifogad, där endast en operator-samling krävs som resultat. |
| [LineAnnotation](./lineannotation/) | Klass som representerar linjeanteckning. |
| [LineEndingConverter](./lineendingconverter/) | Representerar LineEndingConverter-klassen |
| [LineEndingsDrawer](./lineendingsdrawer/) | Ritar linjeändar för anteckningar. Intern klass för enbart internt bruk. |
| [LinkAnnotation](./linkannotation/) | Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras. |
| [ListBoxField](./listboxfield/) | Klass representerar ListBox-fält. |
| [LoadOptions](./loadoptions/) | LoadOptions-typen håller abstraktionsnivå på individuella laddningsalternativ |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Representerar användningsläge för marginalområde under konvertering (som HTML, EPUB etc), definierar behandling av instruktioner för importerat format relaterade till användning av marginaler. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | OBS! Funktionen är implementerad men har ännu inte placerats i det offentliga API:t på grund av blockerande problem i OSHARED-lagret som upptäcktes för exempel-dokumentet. Representerar användningsläge för sidstorlek under konvertering. Format (som HTML, EPUB etc) har vanligtvis flytande design, så den tillåter att anpassa till önskad sidstorlek. Men ibland specificerar innehållet horisontella positioner eller storlek som inte tillåter att placera innehållet i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras i detta fall (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF-dokumentet). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Resultat av anpassad inläsning av resurs |
| [LocaleOptions](./localeoptions/) | LocaleOptions-typen specificerar lokal konfiguration för Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Representerar lokalt hyperlänk-objekt. |
| [MarginInfo](./margininfo/) | Denna klass representerar en marginal för olika objekt. |
| [MarkupAnnotation](./markupannotation/) | Abstrakt klass som representerar markup-anteckning. |
| [MarkupParagraph](./markupparagraph/) | Representerar ett stycke. |
| [MarkupSection](./markupsection/) | Representerar en markup-sektion – det rektangulära området på en sida som innehåller text och kan visuellt separeras från andra textblock. |
| [Matrix](./matrix/) | Klass representerar transformationsmatris. |
| [Matrix3D](./matrix3d/) | Klass representerar transformationsmatris. |
| [MdLoadOptions](./mdloadoptions/) | Laddningsalternativ för konvertering av Markdown-format. |
| [Measure](./measure/) | Klass som beskriver Measure-koordinatsystemet. |
| [Measure.NumberFormat](./measure.numberformat/) | Talformat för mått. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Representerar lista över talformat. |
| [MediaClip](./mediaclip/) | Klass beskriver media-klipp-objekt för återgivning. |
| [MediaClipData](./mediaclipdata/) | Klass beskriver media-klippdata. |
| [MediaClipSection](./mediaclipsection/) | Denna klass beskriver Media-klippsektionen. |
| [MediaRendition](./mediarendition/) | Klassen beskriver mediarendition. |
| [MemoryCleaner](./memorycleaner/) | Representerar MemoryCleaner-klassen. |
| [MemoryExtender](./memoryextender/) | Representerar MemoryExtender-klassen. Genom att använda stora filer på ett system med begränsat heap-minne kan den aktiveras för att använda diskutrymme som temporärt swap-minne. |
| [MemoryFontSource](./memoryfontsource/) | Representerar en enskild teckensnittsfilkälla. |
| [Metadata](./metadata/) | Tillhandahåller åtkomst till XMP-metadataström. |
| [Metered](./metered/) | <p> Tillhandahåller metoder för att ställa in mättad nyckel. </p> <hr> I detta exempel kommer ett försök att göras att sätta mättad publik och privat nyckel <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Representerar alternativ för inläsning/import av .mht-fil till pdf-dokument. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Spara alternativ för export till Xml-format |
| [MovieAnnotation](./movieannotation/) | Representerar en filmanteckning som innehåller animerad grafik och ljud som ska visas på datorskärmen och spelas upp via högtalarna. När anteckningen aktiveras spelas filmen. |
| [NamedAction](./namedaction/) | Representerar namngivna åtgärder som PDF‑visningsprogram förväntas stödja. |
| [NamedDestination](./nameddestination/) | Istället för att definieras direkt med den explicita syntaxen kan en destination refereras indirekt via ett namnobjekt eller en byte‑sträng. |
| [Note](./note/) | Denna klass representerar generator‑paragraf‑not. |
| [NumberField](./numberfield/) | Textfält med specificerade giltiga tecken @see TextBoxField |
| [NumberTree](./numbertree/) | Klassen representerar nummerträdstruktur i PDF‑filen. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Representerar ocsp-inställningarna som används under signeringsprocessen. |
| [OfdLoadOptions](./ofdloadoptions/) | Läsalternativ för OFD-format. |
| [Operator](./operator/) | Abstrakt klass som representerar operatör. |
| [OperatorCollection](./operatorcollection/) | Klassen representerar en samling av operatörer |
| [OperatorSelector](./operatorselector/) | Denna klass används för att välja operatörer med Visitor‑mallidé. |
| [Opi](./opi/) | Representerar Open Prepress Interface (OPI), ett mekanism för att skapa lågupplösta platshållare eller proxy‑objekt för sådana högupplösta bilder. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Definierar en MemoryStream som kan innehålla större standardkapacitet |
| [Option](./option/) | Klassen representerar alternativ för valfält. |
| [OptionCollection](./optioncollection/) | Klassen representerar en samling av alternativ för valfältet. |
| [OutlineCollection](./outlinecollection/) | Representerar dokumentets dispositionshierarki. |
| [OutlineItemCollection](./outlineitemcollection/) | Representerar dispositionspost i dispositionshierarkin för PDF‑dokumentet. |
| [Outlines](./outlines/) | Klassen beskriver en samling av konturer. |
| [OutputIntent](./outputintent/) | Representerar ett output‑intent som matchar färgkaraktäristiken hos ett PDF‑dokument med den hos en mål‑utmatningsenhet eller produktionsmiljö där dokumentet kommer att skrivas ut. |
| [OutputIntents](./outputintents/) | Representerar samlingen av {@link OutputIntent}. |
| [Page](./page/) | Klassen som representerar en sida i ett PDF‑dokument. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Procedur för att anpassa sidhuvud och sidfot. |
| [PageActionCollection](./pageactioncollection/) | Denna klass beskriver sidåtgärder |
| [PageCollection](./pagecollection/) | Samling av PDF‑dokumentets sidor. |
| [PageExtensions](./pageextensions/) | Tillhandahåller ytterligare funktioner för Page‑klassen. |
| [PageInfo](./pageinfo/) | Representerar sidinformationen för pdf‑generatorn. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representerar en Page Information‑annotation i ett PDF‑dokument. Denna annotation innehåller filnamnet, sidnumret samt datum och tid för annotationens skapande. Klassen används främst för att lägga till metadata till en specifik sida i PDF‑dokumentet, vilket kan vara användbart för spårnings- och referensändamål. Till exempel kan den användas för att markera sidor under utskriftsprocessen eller för att tillhandahålla ytterligare information om sidan när dokumentet visas. |
| [PageLabel](./pagelabel/) | Klassen som representerar ett Page Label‑intervall. |
| [PageLabelCollection](./pagelabelcollection/) | Klassen som representerar en samling av Page Label. |
| [PageMarkup](./pagemarkup/) | Sidmarkup representerad av samlingar av {@code MarkupSection} och {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Representerar sidnumreringsstämpel och används för att numrera sidor. |
| [PageSize](./pagesize/) | Klassen som representerar sidans storlek i ett PDF‑dokument. |
| [PaginationArtifact](./paginationartifact/) | Representerar en abstrakt basklass för pagineringsartefakter i ett dokument. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Representerar ett absorberande objekt för sidstrukturobjekt såsom sektioner och stycken. Utför sökning efter sektioner och stycken i text och tillhandahåller åtkomst till rektanglar och polygoner som beskriver dem i textkoordinatrymden. Utför också sökning av textsegment och ger åtkomst till sökresultat via {@code TextFragments}‑samlingar grupperade efter strukturelement. </p> Exemplet demonstrerar hur man hittar det första textsegmentet i varje stycke på den första PDF‑dokumentets sida och markerar det. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> När sökningen är klar kommer {@code ParagraphAbsorber.PageMarkups}-samlingen att innehålla {@code PageMarkup}-objekt som representerar sidstruktur genom samlingar av {@code MarkupSection} och {@code MarkupParagraph}. {@code TextFragment}-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av texttillståndet (teckensnitt, teckenstorlek, färg osv). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Representerar alternativ för {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | Denna klass representerar en stycke‑samling. |
| [PasswordBoxField](./passwordboxfield/) | Klassen beskriver ett textfält för att ange lösenord. |
| [PclLoadOptions](./pclloadoptions/) | Representerar alternativ för att ladda (importera) PCL‑fil till pdf‑dokument. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Enumererar konverteringsmotorer som kan användas för konvertering |
| [PDF3DAnnotation](./pdf3dannotation/) | Klassen PDF3DAnnotation. Denna klass kan inte ärvas. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | Klassen PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Klassen PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Klassen PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Klassen PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Klassen PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Klassen PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Klassen PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Klassen PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Klassen PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Klassen PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Representerar Action i PDF-dokument |
| [PdfActionCollection](./pdfactioncollection/) | Klassen beskriver en lista med åtgärder. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Denna klass beskriver regler som kan användas för att finjustera processen för att kopiera kodningsdata i fall då TrueType-symboliska teckensnitt har mer än en kodning. Vissa PDF-dokument efter konvertering till PDF/A-format kan ge ett fel \"More than one encoding in symbolic TrueType font's cmap\". Vad är orsaken till detta fel? Alla TrueType-symboliska teckensnitt har en speciell tabell \"cmap\" i sin interna data. Denna tabell mappar teckenkoder till glyfindex. Och denna tabell kan innehålla olika kodningsundertabeller som beskriver de använda kodningarna. Se avancerad information om cmap-tabeller på https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Vanligtvis innehåller cmap-tabellen flera kodningsundertabeller, men PDF/A-standarden kräver att antingen endast en kodningsundertabell får finnas kvar för detta teckensnitt i PDF/A-dokumentet eller att det måste finnas en (3,0) kodningsundertabell bland teckensnittets undertabeller. Och den centrala frågan här – vilken data måste tas från andra undertabeller för att kopieras till destinationskodningstabellen (3,0)? Majoriteten av teckensnitten har 'välformade' cmap-tabeller där varje kodningsundertabell är fullt konsistent med en annan undertabell. Men vissa teckensnitt har cmap-tabeller med kollisioner – där till exempel en undertabell har glyfindex 100 för unicode 100, men en annan undertabell har glyfindex 200 för samma unicode 100. För att lösa dessa problem behövs en speciell strategi. Som standard används följande strategi: mac-undertabell(1,0) söks. Om denna tabell hittas används endast denna data för att fylla destinationstabellen (3,0). Om mac-undertabellen inte hittas itereras alla undertabeller förutom (3,0) och används för att kopiera data till destinationsundertabellen (3,0). Dessutom kopieras mappning för varje unicode (unicode, glyfindex) till destinationstabellen endast om destinationstabellen för närvarande inte har denna unicode. Så, till exempel om den första undertabellen har glyfindex 100 för unicode 100, och nästa undertabell har glyfindex 200 för samma unicode 100, kommer endast data från den första undertabellen (unicode=100, glyfindex = 100) att kopieras. Så varje föregående undertabell har företräde framför den nästa. Egenskaper i denna klass { PdfASymbolicFontEncodingStrategy} hjälper till att finjustera standardbeteendet. Om egenskapen {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) av typen { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} är satt, kommer relevant undertabell att användas med företräde framför mac-undertabell(1,0). Värdet 'MacTable' från uppräkningen {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} har ingen mening i detta fall, eftersom det pekar på samma mac-undertabell (1,0) som används som standard. Egenskapen {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) förkastar alla prioriteringar för någon undertabell. Om denna egenskap är satt, kommer endast undertabeller från den deklarerade kön att användas i angiven ordning. Om de specificerade undertabellerna inte hittas används standarditeration av alla undertabeller och kopieringsstrategin som beskrivits ovan. Objektet { PdfASymbolicFontEncodingStrategy.QueueItem} specificerar den använda kodningsundertabellen. Denna undertabell kan sättas via en kombination av medlemmar(PlatformID, PlatformSpecificId) eller via uppräkningen { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Om teckensnittet saknar (3,0) undertabell kommer någon annan undertabell att användas för att upprätthålla PDF/A-kompatibiliteten. Valet av vilken undertabell som ska användas görs enligt samma regler som beskrivits tidigare, så att {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) och {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) egenskaper används för att bestämma den resulterande undertabellen, och om teckensnittet inte har den begärda undertabellen/undertabellerna kommer någon befintlig undertabell att användas. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Specificerar en kodningstabell. Varje kodningstabell har en unik kombination av parametrar (PlatformID, PlatformSpecificID). Uppräkning {@code CMapEncodingTableType} och egenskap {@code CMapEncodingTable} implementerades för att underlätta att ange den kodningstabell som behövs. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Deklarerar en uppsättning av några kända kodningstabeller. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | representerar en uppsättning alternativ för att konvertera PDF-dokument. |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Denna klass innehåller flaggor för att styra PDF/A-konvertering i fall då källdokumentet PDF inte överensstämmer med PDF-specifikationen. Om flaggorna i denna klass används minskar prestandan, men det är nödvändigt när källdokumentet PDF inte kan konverteras till PDF/A-format på vanligt sätt. Som standard är alla flaggor satta till false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Vissa PDF-dokument har speciella Unicode-symboler som tillhör Private Use Area (PUA), se beskrivningen på https://en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler orsakar PDF/A-kompatibla fel som "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA-symboler. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Vissa dokument får stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi i denna uppräkning är meningsfull endast när flaggan {@code OptimizeFileSize} är satt. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Beskriver strategier som används för att justera dokumentets textsegment. För närvarande stöds endast en strategi för att återställa segment till sina ursprungliga gränser. I framtiden kan ytterligare strategier läggas till. |
| [PdfPageStamp](./pdfpagestamp/) | Klassen representerar en stämpel som använder en PDF-sida som stämpel. |
| [PdfSaveOptions](./pdfsaveoptions/) | Spara alternativ för export till Pdf-format |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Läsalternativ för PdfXml-format. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Spara alternativ för PdfXml-format. |
| [Permissions](./permissions/) | Binär flagga Detta enum representerar användarens behörigheter för en PDF. |
| [PKCS1](./pkcs1/) | Representerar signaturobjekt enligt PKCS#1-standarden. RSA-krypteringsalgoritm och SHA-1-digestmetod används för signering. |
| [PKCS7](./pkcs7/) | Representerar PKCS#7-objektet som följer PKCS#7-specifikationen i Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. SHA1-digesten av dokumentets byteintervall kapslas in i PKCS#7 SignedData-fältet. |
| [PKCS7Detached](./pkcs7detached/) | Representerar PKCS#7-objektet som följer PKCS#7-specifikationen i Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. Den ursprungliga signerade meddelandedigesten över dokumentets byteintervall inkluderas som det normala PKCS#7 SignedData-fältet. Ingen data skall kapslas in i PKCS#7 SignedData-fältet. |
| [Point](./point/) | Representerar en punkt med bråkliga koordinater. |
| [Point3D](./point3d/) | Representerar en punkt med bråkliga koordinater. |
| [PolyAnnotation](./polyannotation/) | Abstrakt basklass för poly-annotationer. |
| [PolygonAnnotation](./polygonannotation/) | Klassen representerar polygonannotation. |
| [PolylineAnnotation](./polylineannotation/) | Representerar polylinjeannotation som liknar polygon, förutom att den första och sista vertexen inte är implicit anslutna. |
| [PopupAnnotation](./popupannotation/) | Representerar popup-annotation som visar text i ett popup-fönster för inmatning och redigering. |
| [Position](./position/) | Representerar ett positionsobjekt |
| [PptxSaveOptions](./pptxsaveoptions/) | Spara alternativ för export till SVG-format |
| [PrintController](./printcontroller/) | Representerar utskriftskontroller. |
| [PrintDuplex](./printduplex/) | Pappershanteringsalternativet att använda när filen skrivs ut från utskriftsdialogen.. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstrakt klass som representerar skrivarmärkesannotation. |
| [PrinterMarksKind](./printermarkskind/) | Anger typerna av skrivarmärken som ska läggas till i ett dokument. Denna uppräkning har ett {@link FlagsAttribute}-attribut som möjliggör en bitvis kombination av dess medlemsvärden. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Tillhandahåller förlängningsmetoder för {@link PrinterMarksKind}-uppräkningen. |
| [PrintScaling](./printscaling/) | Sidskalningsalternativet som ska väljas när en utskriftsdialog visas för detta dokument. |
| [ProgressEventType](./progresseventtype/) | Denna uppräkning beskriver möjliga typer av förloppshändelser som kan inträffa under konvertering. |
| [PsLoadOptions](./psloadoptions/) | Representerar alternativ för inläsning/import av .mht-fil till pdf-dokument. |
| [PsSaveOptions](./pssaveoptions/) | Sparaalternativ för export till PS (PostScript) eller EPS-format. |
| [RadioButtonField](./radiobuttonfield/) | Klass som representerar radioknappsfält. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Klass som representerar ett objekt i RadioButton-fält. |
| [Rectangle](./rectangle/) | Klass som representerar en rektangel. |
| [Redaction](./redaction/) | Endast för internt bruk @author User |
| [RedactionAnnotation](./redactionannotation/) | Representerar Redact-annotation. |
| [RegexManager](./regexmanager/) | Tillhandahåller ett omslag för reguljära uttrycksoperationer med konfigurerbara tidsgränsinställningar. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representerar en Registreringsmarkering-annotation. Registreringsmarkeringar är symboler som läggs till på tryckplåtar eller skärmar för att säkerställa korrekt färgjustering under tryckprocessen. |
| [RenderingOptions](./renderingoptions/) | Representerar renderingsalternativ |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: uppsättning av renderingslägen |
| [Rendition](./rendition/) | Klass som beskriver renditionsobjektet för RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | En renditionsåtgärd som styr uppspelning av multimedia-innehåll. |
| [RenditionOperation](./renditionoperation/) | Operationen som ska utföras när åtgärden utlöses. |
| [RenditionType](./renditiontype/) | Uppräkning beskriver möjliga typer av Rendition. |
| [Resources](./resources/) | Klass som representerar sidresurser. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Representerar ExtGStates med vissa värden. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Representerar konverteringsstrategi för rgb till enhetlig grå färgrymd. |
| [RichMediaAnnotation](./richmediaannotation/) | Klass beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljuddata i PDF-dokument. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Händelse som aktiverar annotation. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Typ av multimedia. |
| [RichTextBoxField](./richtextboxfield/) | Klass beskriver komponent för rik textredigerare. |
| [RichTextFontStyles](./richtextfontstyles/) | Alternativ för formatering av textfragment i RichText. |
| [RootElement](./rootelement/) | Rotstrukturselement. |
| [Row](./row/) | Representerar en rad i tabellen. |
| [Rows](./rows/) | Representerar en samling rader i tabellen. |
| [RtfLoadOptions](./rtfloadoptions/) | Läsalternativ för RTF-format. |
| [SaveOptions](./saveoptions/) | SaveOptions-typ håller abstraktionsnivå på enskilda sparaalternativ. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Instans av denna klass representerar information om kant som kan ritas på ett resultatdokument. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Representerar information om en del av kanten (övre, nedre, vänstra eller högra sidan). |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Instans av denna klass representerar information om sidmarginal som kan ritas på ett resultatdokument. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Representerar information om en del av marginalen (övre, nedre, vänstra eller högra sidan). |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursfiler som sker under konvertering av PDF till något annat format (t.ex. HTML). |
| [ScalingMode](./scalingmode/) | Typen av skalning som ska användas. |
| [ScalingReason](./scalingreason/) | Omständigheterna under vilka ikonen ska skalas inom annoteringsrektangeln. |
| [ScreenAnnotation](./screenannotation/) | En skärmannotering som specificerar ett område på en sida där mediaklipp kan spelas. |
| [SelectorRendition](./selectorrendition/) | Klassen beskriver selector‑återgivning. |
| [Signature](./signature/) | En abstrakt klass som representerar signaturobjekt i PDF-dokumentet. Signaturer är fält med värden av signaturobjekt, där de sista innehåller data som används för att verifiera dokumentets giltighet. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | En abstrakt klass som representerar ett anpassat utseendeobjekt för signatur. |
| [SignatureField](./signaturefield/) | Representerar signaturformulärfält. |
| [SignHash](./signhash/) | Delegat för anpassad signering av dokumenthash (Beta). |
| [SoundAnnotation](./soundannotation/) | Representerar en ljudannotering som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil. |
| [SoundData](./sounddata/) | Representerar ljuddata som definierar ljudet som ska spelas när annoteringen aktiveras. |
| [SoundEncoding](./soundencoding/) | Kodningsformatet för exempeldata. |
| [SoundIcon](./soundicon/) | Enumererar ikonerna som ska användas vid visning av annoteringen. |
| [SoundIconConverter](./soundiconconverter/) | Representerar SoundIconConverter-klassen. |
| [SoundSampleData](./soundsampledata/) | Representerar ytterligare poster specifika för ett ljudobjekt (Avsnitt 9.2 PDF1-7). |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Kodningsformatet för ljudsamplingsdata. |
| [SquareAnnotation](./squareannotation/) | Klass som representerar fyrkantig annotation. |
| [SquigglyAnnotation](./squigglyannotation/) | Representerar den snirkliga annotationen som visas som en ojämn understrykning i dokumentets text. |
| [Stamp](./stamp/) | En abstrakt klass för olika typer av stämplar som kommer som underklasser. |
| [StampAnnotation](./stampannotation/) | <p> Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om den var stämplad på sidan med en gummistämpel. </p> <hr> <pre> Nästa kodsnutt demonstrerar hur man lägger till 2 stämplar på den första PDF-dokumentets sida. Indatadokumentet kommer från inFile och ändringar sparas till outFile. Den första stämpeln har ikonen NotForPublicRelease och den andra kommer med bilden från rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Representerar StampIconConverter-klassen |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representerar en genomstruken annotation som visas som en genomstrykning i dokumentets text. |
| [StructElement](./structelement/) | Allmänt strukturelement. |
| [SubjectNameElements](./subjectnameelements/) | Enumeration beskriver element i signaturens ämnessträng. |
| [SubmitFormAction](./submitformaction/) | Klass som beskriver submit-form-åtgärden. |
| [SvgLoadOptions](./svgloadoptions/) | Representerar alternativ för att ladda/importera SVG-fil till PDF-dokument. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Enumererar konverteringsmotorer som kan användas för konvertering |
| [SvgSaveOptions](./svgsaveoptions/) | Spara alternativ för export till SVG-format |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Denna klass representerar en uppsättning data som är relaterade till sparande av externa bildresursfiler under PDF till HTML-konvertering. |
| [Symbology](./symbology/) | En (Streckkod) Symbolik definierar de tekniska detaljerna för en viss typ av streckkod: staplarnas bredd, teckenuppsättning, kodningsmetod, kontrollsummaspecifikationer osv. |
| [SystemFontSource](./systemfontsource/) | Representerar alla teckensnitt som är installerade på systemet. |
| [TabAlignmentType](./tabalignmenttype/) | Enumeratorar tabbjusteringstyperna. |
| [Table](./table/) | Representerar en tabell som kan läggas till på sidan. |
| [TableAbsorber](./tableabsorber/) | <p> Representerar ett absorberingsobjekt för tabell-element. Utför sökning och ger åtkomst till sökresultat via {@code TableAbsorber.TableList}-samlingen. </p> <hr> <pre> Exemplet demonstrerar hur man hittar en tabell på den första PDF-dokumentets sida och ersätter texten i en tabellcell. // Öppna dokument Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Skapa TableAbsorber-objekt för att hitta tabeller TableAbsorber absorber = new TableAbsorber(); // Besök första sidan med absorberaren absorber.visit(doc.getPages().get_Item(1)); // Få åtkomst till den första tabellen på sidan, dess första cell och textfragment i den TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Ändra texten för det första textfragmentet i cellen fragment.setText("hi world"); // Spara dokumentet doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Enumeratorar tabbledartyperna. |
| [TableBroken](./tablebroken/) | Enumeratorar den trasiga tabellen. |
| [TabOrder](./taborder/) | Tabbordning på sidan |
| [TabStop](./tabstop/) | Representerar en anpassad tabbposition i ett stycke. |
| [TabStops](./tabstops/) | Representerar en samling av {@code TabStop}-objekt. |
| [TeXFragment](./texfragment/) | Representerar LaTeX-fragment. |
| [TeXLoadOptions](./texloadoptions/) | Representerar alternativ för att ladda/importera TeX-fil till PDF-dokument. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implementerar hämtning av en utdataström från minnet. Du kan använda den till exempel när du inte vill att den medföljande utdata (som en loggfil) ska skrivas till disk men du vill läsa den senare från minnet. |
| [TeXSaveOptions](./texsaveoptions/) | Spara alternativ för export till TeX-format |
| [TextAbsorber](./textabsorber/) | <p> Representerar ett absorberingsobjekt för text. Utför textutdragning och ger åtkomst till resultatet via {@code TextAbsorber.Text}-objektet. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Objektet {@code TextAbsorber} används för att extrahera text från ett PDF-dokument eller dokumentets sida. </p> |
| [TextAnnotation](./textannotation/) | Representerar en textanteckning som är en "sticky note" fäst vid en punkt i PDF-dokumentet. |
| [TextBoxField](./textboxfield/) | Klass som representerar ett textrutefält. |
| [TextBuilder](./textbuilder/) | Lägger till textobjekt på PDF-sida. |
| [TextDefaults](./textdefaults/) | Definierar standardinställningar för textsystemet |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Anger typ av standardinställningar för textsystemet |
| [TextEditOptions](./texteditoptions/) | Beskriver alternativ för textredigeringsoperationer. |
| [TextElement](./textelement/) | Allmänt textelement i dokumentets logiska struktur. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Beskriver att textutdragningsfelet har uppstått i PDF-dokumentet. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Representerar platsen i PDF-dokumentet där textutdragningsfelet har uppstått. |
| [TextExtractionOptions](./textextractionoptions/) | Representerar alternativ för textutdragning |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se {@code TextDevice}-klassen. |
| [TextFormattingOptions](./textformattingoptions/) | Representerar alternativ för textformatering |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Definierar specifikationer för radavstånd |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Definierar strategier för ordbrytning |
| [TextFragment](./textfragment/) | <p> Representerar ett fragment av PDF-text. </p> <hr> <pre> Exemplet demonstrerar hur man hittar text på den första PDF-dokumentets sida och ersätter texten och dess teckensnitt. // Open document Document doc = new Document(\"input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"output.pdf\"); </pre> <hr> <pre> Med några ord innehåller {@code TextFragment}-objektet en lista med {@code TextSegment}-objekt. I detalj: Texten i en pdf-dokument i {@code com.aspose.pdf} representeras av två grundläggande objekt: {@code TextFragment} och {@code TextSegment} Skillnaderna mellan dem är mest kontextberoende. Låt oss överväga följande scenario. Användaren söker texten \"hello world\" för att arbeta med den, ändra dess egenskaper, titta etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> Den fysiska representationen av pdf-text är mycket komplex. Texten \"hello world\" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf-textmodellen fastställer i princip att {@code TextFragment}-objektet tillhandahåller en enda logisk operationsuppsättning över fysiska {@code TextSegment}-objekt som representerar användarens fråga. I textsökningsscenario är {@code TextFragment} en logisk representation av texten \"hello world\", och {@code TextSegment}-objektkollektionen representerar alla fysiska segment som bygger upp \"hello world\"-textobjektet. Alltså är {@code TextFragment} nära den logiska textrepresentationen. Och {@code TextSegment} är nära den fysiska textrepresentationen. Uppenbarligen kan varje {@code TextSegment}-objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. {@code TextFragment} erbjuder ett enkelt sätt att ändra text med dess egenskaper: sätt teckensnitt, sätt teckenstorlek, sätt teckenfärg etc. Samtidigt är {@code TextSegment}-objekt tillgängliga och användare kan arbeta med {@code TextSegment}-objekt oberoende. <p> Notera att ändring av TextFragment-egenskaper kan ändra den inre {@code Segments}-samlingen eftersom TextFragment är ett aggregatobjekt och kan omarrangera interna segment eller slå ihop dem till ett enda segment. Om ditt krav är att lämna {@code Segments}-samlingen oförändrad, vänligen ändra interna segment individuellt. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Representerar ett absorberingsobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via {@code TextFragmentAbsorber.TextFragments} samling. </p> <hr> <pre> Exemplet demonstrerar hur man hittar text på den första PDF-dokumentets sida och ersätter texten och dess teckensnitt. // Öppna dokument Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra text och teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Spara dokument doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Objektet {@code TextFragmentAbsorber} används i princip i textsökningsscenario. När sökningen är slutförd representeras förekomsterna med {@code TextFragment}-objekt som samlingen {@code TextFragmentAbsorber.TextFragments} innehåller. Objektet {@code TextFragment} ger åtkomst till sökförekomstens text, textegenskaper och möjliggör redigering av text samt ändring av texttillståndet (teckensnitt, teckenstorlek, färg osv). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Representerar en samling av textfragment |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Representerar ett texttillstånd för ett textfragment. </p> <hr> <pre> Exemplet demonstrerar hur man ändrar textfärg och teckenstorlek för texten med {@code TextState}-objektet. // Öppna dokument Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra förgrundsfärg för den första textförekomsten absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Ändra teckenstorlek för den första textförekomsten absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Spara dokument doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: font ({@code TextFragmentState.Font} egenskap) font size ({@code TextFragmentState.FontSize} egenskap) font style ({@code TextFragmentState.FontStyle} egenskap) foreground color ({@code TextFragmentState.ForegroundColor} egenskap) background color ({@code TextFragmentState.BackgroundColor} egenskap) </p> <p> Observera att ändring av {@code TextFragmentState}-egenskaper kan ändra den inre {@code TextFragment.Segments}-samlingen eftersom TextFragment är ett aggregatobjekt och kan omarrangera interna segment eller slå ihop dem till ett enda segment. Om ditt krav är att lämna {@code TextFragment.Segments}-samlingen oförändrad, vänligen ändra de inre segmenten individuellt. </p> |
| [TextIcon](./texticon/) | Enumererar ikonerna som ska användas vid visning av annoteringen. |
| [TextIconConverter](./texticonconverter/) | Representerar klassen TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstrakt basklass för textmarkeringanteckningar. |
| [TextOptions](./textoptions/) | Representerar alternativ för textbehandling |
| [TextParagraph](./textparagraph/) | <p> Representerar textparagrafer som ett flerradigt textobjekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textparagrafobjekt och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textparagraf TextParagraph paragraph = new TextParagraph(); // sätt paragrafens rektangel paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // sätt ordbrytningsalternativ paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // lägg till strängrader paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // lägg till paragrafen på Pdf-sidan med TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // spara Pdf-dokument doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Bakgrundsläge för TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Representerar ett absorberingsobjekt för textparagrafer. Utför textsökning och ger åtkomst till sökresultat via {@code TextParagraphAbsorber.TextParagraphs} samling. |
| [TextParagraphCollection](./textparagraphcollection/) | Representerar en samling textparagrafer |
| [TextReplaceOptions](./textreplaceoptions/) | Representerar alternativ för textersättning |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Bestämmer åtgärden som ska utföras efter ersättning av textfragment till kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera mellanslag mellan ord för att behålla radlängden; WholeWordsHyphenation - försöker fördela ord mellan paragrafrader för att behålla paragrafens högra fält; ShiftRestOfLine - förskjuter resten av raden enligt förändrad textlängd, radlängden kan ändras; Standardvärdet är ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Representerar alternativ för textsökning |
| [TextSegment](./textsegment/) | <p> Representerar ett segment av PDF-text. </p> <hr> <pre> Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med {@code TextState}-objektet av {@code TextSegment}-objektet. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> Med några ord är {@code TextSegment}-objekt barn till {@code TextFragment}-objektet. Detaljerat: Texten i en pdf-dokument i {@code Aspose.Pdf} representeras av två grundläggande objekt: {@code TextFragment} och {@code TextSegment}. Skillnaderna mellan dem är mest kontextberoende. Låt oss överväga följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, visa etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Den fysiska representationen av pdf-text är mycket komplex. Texten "hello world" kan bestå av flera fysiskt oberoende textsegment. Aspose.PDF-textmodellen fastställer i princip att {@code TextFragment}-objektet tillhandahåller en enda logisk operation över en uppsättning fysiska {@code TextSegment}-objekt som representerar användarens sökfråga. I ett textsökscenario är {@code TextFragment} den logiska "hello world"-textrepresentationen, och {@code TextSegment}-objektkollektionen representerar alla fysiska segment som bygger upp "hello world"-textobjektet. Således är {@code TextFragment} nära den logiska textrepresentationen. Och {@code TextSegment} är nära den fysiska textrepresentationen. Uppenbarligen kan varje {@code TextSegment}-objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. {@code TextFragment} erbjuder ett enkelt sätt att ändra text med dess egenskaper: sätt teckensnitt, sätt teckenstorlek, sätt teckensnittsfärg osv. Samtidigt är {@code TextSegment}-objekt tillgängliga och användare kan arbeta med {@code TextSegment}-objekt oberoende. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Representerar en samling av textsegment |
| [TextStamp](./textstamp/) | Representerar en textstämpel. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet. |
| [TextState](./textstate/) | Representerar ett texttillstånd för en text |
| [TextStyle](./textstyle/) | Klassen som representerar kryssrutfält. |
| [TimestampSettings](./timestampsettings/) | Representerar ocsp-inställningarna som används under signeringsprocessen. |
| [TocInfo](./tocinfo/) | Representerar information om innehållsförteckning. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Denna klass beskriver regler som kan användas för att lösa Adobe Preflight‑felet "Text cannot be mapped to Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representerar en Trim Mark‑annotation. Trim‑markeringar placeras i hörnen på en tryckt sida för att ange var sidan ska beskäras. |
| [TxtLoadOptions](./txtloadoptions/) | Laddningsalternativ för konvertering från TXT till PDF. |
| [UnderlineAnnotation](./underlineannotation/) | Representerar en understrykningsannotation som visas som en understrykning i dokumentets text. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Denna klass representerar sparalternativ för sparning som använder ett enhetligt konverteringssätt (med enhetlig intern dokumentmodell) |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Representerar en klass med en abstrakt metod som vanligtvis tillhandahålls av anropande sida och hanterar förloppshändelser som kommer från konverteraren. Sådan levererad kundhanterare kan vanligtvis användas för att visa total konverteringsprogress på konsolen eller i ett förloppsfält. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Denna klass representerar information om konverteringsprogress som kan användas i ett externt program för att visa konverteringsprogress för slutanvändaren. |
| [WarningCallback](./warningcallback/) | Gränssnitt för stöd av användarens återuppringningsmekanism. |
| [WarningInfo](./warninginfo/) | Oföränderligt objekt för att kapsla in varningsinformation. |
| [WarningType](./warningtype/) | /* Enum representerade varningstyp. */ |
| [Watermark](./watermark/) | Representerar en vattenstämpel på sidan. |
| [WatermarkAnnotation](./watermarkannotation/) | Klassen beskriver Watermark-annoteringsobjektet. |
| [WatermarkArtifact](./watermarkartifact/) | Klassen beskriver vattenstämpelartefakt. Detta kan användas för att |
| [WebHyperlink](./webhyperlink/) | Representerar webblänksobjekt. |
| [WidgetAnnotation](./widgetannotation/) | Klassen som representerar widget-annotering. |
| [XFA](./xfa/) | Representerar XML-formulär enligt XML Forms Architecture (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | klass för att hantera relaterad datakapsling |
| [XfdfReader](./xfdfreader/) | <p> Klassen som utför läsning av XFDF-format. </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save(\"example_out.pdf\"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Samlar metoder för att skriva annoteringar och fält till XFDF-filformatet |
| [XForm](./xform/) | Klassen representerar XForm |
| [XFormCollection](./xformcollection/) | Klassen representerar en samling av XFormCollection. |
| [XImage](./ximage/) | Klassen som representerar bild X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | Klassen som representerar råa XImage-parametrar för bild. |
| [XImageCollection](./ximagecollection/) | Klassen som representerar XImage-samling. |
| [XmlLoadOptions](./xmlloadoptions/) | Representerar alternativ för inläsning/import av XML-fil i pdf-dokument. |
| [XmlSaveOptions](./xmlsaveoptions/) | Spara alternativ för export till Xml-format |
| [XmpField](./xmpfield/) | Representerar XMP-fält. |
| [XmpFieldType](./xmpfieldtype/) | Denna enum representerar typer av ett XMP-fält. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Egenskapskategori: intern eller extern. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Detta schema beskriver ett fält i en strukturerad typ. Det är mycket likt PDF/A Property Value Type-schemat, men definierar ett fält i en struktur istället för en egenskap. Schema namespace URI: http://www.aiim.org/pdfa/ns/field# Krävd schema namespace prefix: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Representerar basklassen för fält-, egenskaps- och värdetypinstanser. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Beskriver en enskild egenskap. Schemanamnutrymme URI: http://www.aiim.org/pdfa/ns/property# Krävt schemanamns prefix: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Beskriver XMP-utökningens schema som tillhandahålls av PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Representerar beskrivningen av XMP-utökningens schema som tillhandahålls av PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | PDF/A ValueType-schema krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004-specifikationen, d.v.s. för värdetyper utanför följande lista: - Arraytyper (detta är behållartyper som kan innehålla ett eller flera fält): Alt, Bag, Seq - Grundläggande värdetyper: Boolean, (öppen och sluten) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management-värdetyper: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundläggande Jobb/Arbetsflöde-värdetyp: Job - EXIF-schema värdetyper: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schemanamnutrymme URI: http://www.aiim.org/pdfa/ns/type# Krävt schemanamns prefix: pdfaType |
| [XmpValue](./xmpvalue/) | Representerar XMP-värde |
| [XpsLoadOptions](./xpsloadoptions/) | Representerar alternativ för inläsning/import av xps-fil till pdf-dokument. |
| [XpsSaveOptions](./xpssaveoptions/) | Spara alternativ för export till Xps-format |
| [XslFoLoadOptions](./xslfoloadoptions/) | Representerar alternativ för inläsning/import av XSL-FO-fil till pdf-dokument. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Representerar explicit destination som visar sidan med koordinaterna (left, top) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorad med zoomfaktorn. Ett null‑värde för någon av parametrarna left, top eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett null‑värde. </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [AFRelationship](./afrelationship/) | Enumeration beskriver relationen mellan associerade filer. |
| [AnnotationState](./annotationstate/) | Enumeration av tillstånd som den ursprungliga annoteringen kan sättas till. |
| [AnnotationStateModel](./annotationstatemodel/) | Tillståndsmodellen som motsvarar annoteringens tillstånd. |
| [AnnotationType](./annotationtype/) | Enumeration av annoteringstyper. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Enumeration av möjliga artefaktsundertyper. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Enumeration av möjliga artefakttyper. |
| [BlendMode](./blendmode/) | Enumeration av blandningslägen. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumererar hörnstilar för ram. |
| [BorderEffect](./bordereffect/) | Beskriver effekt som ska tillämpas på annoteringarnas ram. |
| [BorderStyle](./borderstyle/) | Beskriver stil för annoteringens ram. |
| [BoxStyle](./boxstyle/) | Representerar stilar för att rita kryss i kryssruta. |
| [CapStyle](./capstyle/) | Stil för linjeändning av bläckannoteringslinje. |
| [CaptionPosition](./captionposition/) | Enumeration av annoteringens bildtextpositionering. |
| [CaretSymbol](./caretsymbol/) | En symbol som ska associeras med markören. |
| [ColorsOfCMYK](./colorsofcmyk/) | Färger som ingår i CMYK-färgmodellen. |
| [ColorSpace](./colorspace/) | Färgrymdens uppräkning. |
| [ColorType](./colortype/) | Anger färgtyp för element på sidan. |
| [ColumnAdjustment](./columnadjustment/) | Uppräkning av kolumnjusteringstyper. |
| [ContentDisposition](./contentdisposition/) | MIME-protokollets Content-Disposition-header. |
| [ConvertErrorAction](./converterroraction/) | Denna klass representerar en åtgärd för konverteringsfel. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Denna åtgärd representerar handlingar för konvertering av bilder med mjuk mask. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Denna klass representerar en åtgärd för konvertering av transparens. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Representerar typ av kryptografisk algoritm som används i krypterings-/dekrypteringsrutiner. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * Namnutrymmet {@code Aspose.Pdf.Security } innehåller klasser som används för kryptering och digital signering. / * / |
| [DefaultState](./defaultstate/) | Representerar standardtillståndet för ett PDF-lager. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Representerar typ av algoritm som mappar data till en "hash" |
| [Direction](./direction/) | Textriktning. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Åtkomstbehörigheterna som beviljas för detta dokument. Giltiga värden är: 1 - Inga ändringar i dokumentet är tillåtna; varje ändring i dokumentet ogiltigförklarar signaturen. 2 - Tillåtna ändringar är ifyllning av formulär, instansiering av sidmallar och signering; andra ändringar ogiltigförklarar signaturen. 3 - Tillåtna ändringar är samma som för 2, samt skapande, borttagning och modifiering av annotationer; andra ändringar ogiltigförklarar signaturen. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Tillåter att specificera .doc- eller .docx-filformat. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Tillåter att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument. Använd läget RecognitionMode.Textbox när det resulterande dokumentet inte kommer att redigeras kraftigt vidare. Textboxar är enkla att modifiera när det inte finns mycket att göra. Använd läget RecognitionMode.Flow när utdata-dokumentet kräver ytterligare redigering. Stycken och textrader i flödesläget möjliggör enkel modifiering av text, men ej stödjade formateringsobjekt kommer att se sämre ut än i läget RecognitionMode.Textbox. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | När en PDF-fil (som vanligtvis har fast layout) konverteras försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga författarens avsikt och producera resultat i flödeslayout. Denna egenskap finjusterar den konverteringen för den önskade metoden för innehållsigenkänning. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Uppräkning av typer av explicita destinationer. |
| [ExtendedBoolean](./extendedboolean/) | Representerar boolesk typ som stödjer värdet Undefined. |
| [ExtractImageMode](./extractimagemode/) | Definierar olika lägen som kan användas vid extrahering av bilder från dokument. |
| [FileEncoding](./fileencoding/) | Kodning av den bifogade filen. Möjliga värden: Zip - filen är komprimerad med ZIP, None - filen är okomprimerad. |
| [FileIcon](./fileicon/) | En ikon som ska användas vid visning av annotationen. |
| [Fixup](./fixup/) | Denna enum representerar en typ av Fixup. |
| [FormType](./formtype/) | Uppräkning av möjliga typer av Acro Form. |
| [FreeTextIntent](./freetextintent/) | Enumererar avsikterna för den fria textanteckningen. |
| [HighlightingMode](./highlightingmode/) | Enumererar annoteringens markeringsläge, den visuella effekt som ska användas när musknappen trycks ned eller hålls ned inne i dess aktiva område. |
| [HorizontalAlignment](./horizontalalignment/) | Beskriver horisontell justering. |
| [HtmlDocumentType](./htmldocumenttype/) | Representerar uppräkning av HTML-dokumenttyper. |
| [HtmlMediaType](./htmlmediatype/) | Anger möjliga mediatyper som används under rendering. |
| [IconCaptionPosition](./iconcaptionposition/) | Beskriver ikonens position. |
| [ImageFileType](./imagefiletype/) | Enumererar bildfiltyperna. |
| [ImageFilterType](./imagefiltertype/) | Uppräkning som representerar bildfiltertyp. |
| [ImageFormat](./imageformat/) | Denna uppräkning representerar bildformat. |
| [ImportFormat](./importformat/) | Anger importformat. |
| [Justification](./justification/) | Enumererar formerna av justering (justering) som ska användas vid visning av annoteringens text. |
| [LaunchActionOperation](./launchactionoperation/) | Enumererar operationerna som ska utföras med dokumentet under körning av startåtgärden. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Den enumererar möjliga lägen för placering av bokstäver i ord i resulterande HTML. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: uppsättning av belysningsschematyper. |
| [LineEnding](./lineending/) | Enumererar linjeavslutningsstilarna som ska användas vid ritning av linjen. |
| [LineIntent](./lineintent/) | Enumererar avsikterna för linjeanteckningen. |
| [LoadFormat](./loadformat/) | Anger laddningsformat. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Värde som indikerar på vilket sätt bråkvärden visas. |
| [NumberingStyle](./numberingstyle/) | Uppräkning av stödjda sidnumreringsstilar för PageLabel-klassen. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Anger positionen i en ström att använda för sökning. |
| [PageCoordinateType](./pagecoordinatetype/) | Beskriver sidkoordinattyp. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Beskriver sidlayout. |
| [PageMode](./pagemode/) | Klassen beskriver använda komponenter på dokumentsidan. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Anger variant för att bestämma elementets placering på sidan. |
| [PasswordType](./passwordtype/) | Denna uppräkning representerar kända lösenordstyper som används för lösenordsskyddade PDF-dokument. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: uppsättning av 3D-annoteringsaktiveringsläge. |
| [PdfFormat](./pdfformat/) | Denna klass representerar ett pdf-format. |
| [PdfVersion](./pdfversion/) | Denna enum representerar versionen av en pdf-fil. |
| [PolyIntent](./polyintent/) | Enumererar avsikterna för polygon- eller polylinjeannoteringen. |
| [PredefinedAction](./predefinedaction/) | Definierar olika åtgärder som kan utlösas från en PDF-fil. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representerar en position för en markering i ett hörn på en sida. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representerar en position för en registreringsmarkering på en sida. |
| [ReplyType](./replytype/) | Enumererar typerna av relationer (\"svarstypen\") mellan annoteringen och den som anges av InReplyTo. |
| [ReturnAction](./returnaction/) | Enum representerade en programarbetsflödesåtgärd vid anrop av {@code IWarningCallback.Warning(WarningInfo)}-metoden. |
| [Rotation](./rotation/) | Enumeration av möjliga rotationsvärden. |
| [SaveFormat](./saveformat/) | Specificerar format |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Representerar linjetyper som kan användas i resultatsdokumentet för att rita kanter eller andra linjer |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | enumererar möjliga typer av sparade externa resurser |
| [StampIcon](./stampicon/) | Enumererar ikonerna som ska användas vid visning av annoteringen. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | enumererar möjliga typer av bildfiler som kan sparas som externa resurser under PDF till SVG-konvertering |
| [TextAlignment](./textalignment/) | Justering av text i annotering. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Beskärningsvägsbearbetningslägen |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Beteende för teckensnittsersättning. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Språktransformeringslägen |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet |
| [TextRenderingMode](./textrenderingmode/) | Textrenderingsläget, Tmode, bestämmer om visning av text ska leda till att glyfkonturer streckas, fylls, används som en beskärningsgräns, eller någon kombination av de tre. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Specificerar en policy för hur textens teckensnittsstorlek ska justeras för att passa inom ett omgivande område. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Omfattning där ersättning av textoperationen tillämpas REPLACE_FIRST som standard. Detta föråldrade alternativ behölls för kompatibilitet. Det påverkar PdfContentEditor och har ingen effekt på TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Enumeration av möjliga vertikala justeringsvärden. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
