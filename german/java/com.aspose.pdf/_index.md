---
title: "com.aspose.pdf"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Das com.aspose.pdf ist ein Root‑Paket für alle Klassen der Aspose.PDF für Java‑Bibliothek, die entweder direkt darin wie Document oder indirekt über mehrere Unterpakete enthalten sind."
type: docs
weight: 10
url: /de/java/com.aspose.pdf/
---
Das com.aspose.pdf ist ein Root‑Paket für alle Klassen der Aspose.PDF für Java‑Bibliothek, die entweder direkt darin wie Document oder indirekt über mehrere Unterpakete enthalten sind.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | Das Rückrufverfahren für die hocr-Erkennung. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | Das Rückrufverfahren für die hocr-Erkennung. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | Das Rückrufverfahren für die hocr-Erkennung. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Enthält Funktionen zum Anpassen von Schriftarten |
| [IAnnotationVisitor](./iannotationvisitor/) | Definiert einen Visitor zum Durchlaufen verschiedener Dokumentannotationen. |
| [IAppointment](./iappointment/) | Stellt eine allgemeine Schnittstelle für Aktionen und Ziele dar. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Schnittstelle für Farbraumkonvertierungsstrategien. |
| [IDocument](./idocument/) | Schnittstelle, die ein PDF-Dokument darstellt |
| [IFontOptions](./ifontoptions/) | Nützliche Eigenschaften zum Anpassen des Schriftverhaltens |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Diese Schnittstelle ist für die Anpassung von Quantisierungsalgorithmen deklariert. Benutzer können ihre eigene Implementierung dieser Algorithmen bereitstellen (zum Beispiel Algorithmen, die auf nicht verwaltetem Code basieren). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Diese Schnittstelle ist für die Anpassung von Quantisierungsalgorithmen deklariert. Benutzer können ihre eigene Implementierung dieser Algorithmen bereitstellen (zum Beispiel Algorithmen, die auf nicht verwaltetem Code basieren). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Definiert einen Visitor zum Durchlaufen verschiedener PDF-Operatoren. |
| [IPageSetOptions](./ipagesetoptions/) | Definiert Konvertierungsoptionen für einen Satz von zu konvertierenden Seiten. |
| [IPipelineOptions](./ipipelineoptions/) | Definiert Konvertierungsoptionen im Zusammenhang mit der Pipeline-Konfiguration. |
| [ITableElement](./itableelement/) | Diese Schnittstelle stellt ein Element einer vorhandenen Tabelle dar, das von TableAbsorber extrahiert wurde. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Manchmal ist es notwendig, die Verwendung des internen Laders externer Ressourcen (wie Bilder oder CSS-Dateien) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo bezieht. Zum Beispiel ist bei der Verwendung von Aspose.PDf in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich, und benutzerdefinierter Code, der in eine spezielle Methode eingefügt wird, sollte verwendet werden. Dieser Delegat definiert die Signatur einer solchen benutzerdefinierten Methode. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Setze das Flag, ob der temporäre Ordner verwendet wird, um temporäre Schriftartdaten zu hosten. / * Standardmäßig true. / * Verwendet Heap-Speicher, wenn Wert = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Der Eigenschaft dieses Typs können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Verarbeitung des externen Speicherns eines Bildes implementiert, das aus einem aus PDF erstellten SVG extrahiert wurde und während der Konvertierung von PDF zu HTML als externe Ressource gespeichert werden muss. In einem solchen Fall kann die Verarbeitung (wie selbst erstelltes Speichern in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code durchgeführt werden, und dieser benutzerdefinierte Code muss einen Pfad (oder irgendeinen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das erzeugte SVG anstelle des ursprünglich vorgesehenen Pfads zu dieser Bildressource eingefügt wird. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht vom benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle erforderlichen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, als ob kein externer benutzerdefinierter Code vorhanden wäre. |
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Stellt eine Zelle einer Tabelle dar, die auf der Seite existiert. |
| [AbsorbedRow](./absorbedrow/) | Stellt eine Zeile einer Tabelle dar, die auf der Seite existiert. |
| [AbsorbedTable](./absorbedtable/) | Stellt eine Tabelle dar, die auf der Seite existiert. |
| [ActionCollection](./actioncollection/) | Sammlung von Aktionen |
| [Annotation](./annotation/) | Klasse, die ein Annotationsobjekt darstellt. |
| [AnnotationActionCollection](./annotationactioncollection/) | Stellt die Sammlung von Annotationsaktionen dar. |
| [AnnotationCollection](./annotationcollection/) | Klasse, die eine Annotationssammlung darstellt. |
| [AnnotationFlags](./annotationflags/) | Flags Eine Menge binärer Flags, die verschiedene Eigenschaften der Annotation spezifizieren. |
| [AnnotationSelector](./annotationselector/) | Diese Klasse wird verwendet, um Annotationen mithilfe des Visitor-Template-Konzepts auszuwählen. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Klasse zum Rendern von normalem und reichhaltigem Text. |
| [AppearanceDictionary](./appearancedictionary/) | Annotationsaussehens-Wörterbuch, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll. |
| [ApsLoadOptions](./apsloadoptions/) | Klasse beschreibt APS-Ladeoptionen. Option für den Import aus dem APS-XML-Format. |
| [ApsSaveOptions](./apssaveoptions/) | Speicheroptionen für den Export in das APS-XML-Format. |
| [ApsToFlowConverter](./apstoflowconverter/) | APS-zu-Flow-Konvertierung |
| [Artifact](./artifact/) | Klasse stellt ein PDF-Artifact-Objekt dar. |
| [ArtifactCollection](./artifactcollection/) | Klasse stellt eine Artifact-Sammlung dar. |
| [AutoTaggingSettings](./autotaggingsettings/) | Bietet Einstellungen für die Auto-Tagging-Funktionalität in PDF-Dokumenten. Die {@link AutoTaggingSettings} Klasse ermöglicht die Konfiguration von Optionen für das automatische Tagging von PDF-Inhalten. Sie enthält Eigenschaften, um das Auto-Tagging zu aktivieren oder zu deaktivieren, eine Strategie zur Überschrifterkennung festzulegen und Überschriftenebenen basierend auf Schriftgrößen zu definieren. |
| [BackgroundArtifact](./backgroundartifact/) | Klasse beschreibt ein Hintergrund-Artifact. Dieses Artifact ermöglicht das Festlegen des Seitenhintergrunds. |
| [BarcodeField](./barcodefield/) | Klasse stellt ein Barcode-Feld dar. |
| [BaseActionCollection](./baseactioncollection/) | Klasse kapselt grundlegende Aktionen mit interaktiven Aktionen für Seite/Annotation/Feld. |
| [BaseOperatorCollection](./baseoperatorcollection/) | Stellt die Basisklasse für eine Operatorensammlung dar. |
| [BaseParagraph](./baseparagraph/) | Stellt ein abstraktes Basiselement dar, das zur Seite hinzugefügt werden kann (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Klasse beschreibt das Bates-Nummerierungs-Artefakt. |
| [BitmapInfo](./bitmapinfo/) | Objekt, das ein Array von Pixeln und Bitmap-Informationen enthält. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Bitmap-Pixel-Format. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Stellt eine Bleed-Mark-Anmerkung dar. Bleed-Marken werden an den Ecken einer gedruckten Seite platziert, um anzuzeigen, wo die Seite beschnitten werden soll und wie weit sie von den Schnittmarken abweichen darf. |
| [Border](./border/) | Klasse, die die Eigenschaften des Anmerkungsrahmens darstellt. |
| [BorderInfo](./borderinfo/) | Diese Klasse stellt einen Rahmen für Grafikelemente dar. |
| [BorderSide](./borderside/) | Flags enumerieren binär die Randseiten. |
| [BorderStyleConverter](./borderstyleconverter/) | Stellt die Klasse BorderStyleConverter dar |
| [Brush](./brush/) | Diese Klasse stellt einen abstrakten Pinsel dar |
| [BuildVersionInfo](./buildversioninfo/) | Diese Klasse liefert Informationen über den aktuellen Produkt-Build. |
| [ButtonField](./buttonfield/) | Klasse stellt ein Push‑Button‑Feld dar. |
| [CaretAnnotation](./caretannotation/) | Klasse, die eine Caret-Anmerkung darstellt. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Stellt die Klasse CaretSymbolConverter dar |
| [CdrLoadOptions](./cdrloadoptions/) | Klasse beschreibt die CDR-Ladeoptionen. |
| [Cell](./cell/) | Stellt eine Zelle der Tabellenzeile dar. |
| [Cells](./cells/) | Stellt eine Zellsammlung einer Zeile dar. |
| [CgmImportOptions](./cgmimportoptions/) | Importoption für den Import aus dem Computer Graphics Metafile (CGM)-Format. |
| [CgmLoadOptions](./cgmloadoptions/) | Enthält Optionen zum Laden/Importieren von CGM-Dateien in ein PDF-Dokument. |
| [Characteristics](./characteristics/) | Stellt Anmerkungsmerkmale dar |
| [CharInfo](./charinfo/) | Stellt ein Zeicheninformationsobjekt dar. Liefert Positionsinformationen für Zeichen. |
| [CharInfoCollection](./charinfocollection/) | <p> Stellt die CharInfo-Objektsammlung dar. </p> <hr> <pre> Das Beispiel demonstriert, wie man über alle Zeichen iteriert und das Zeichen abruft //öffne Dokument Document pdfDocument = new Document(inFile); //erstelle TextFragmentAbsorber-Objekt, um alle Textobjekte der Seite zu sammeln TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //akzeptiere den Absorber für alle Seiten pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //hole die extrahierten Textfragmente TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //durchlaufe die Fragmente for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //durchlaufe die Segmente for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //durchlaufe die Zeichen {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // gib Zeichenposition und Rechteckinformationen aus System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Bietet Zugriff auf Positionsinformationen von Zeichen in Textsegmenten. </p> |
| [CheckboxField](./checkboxfield/) | Klasse, die ein Kontrollkästchenfeld darstellt |
| [ChoiceField](./choicefield/) | Stellt die Basisklasse für Auswahlfelder dar. |
| [CircleAnnotation](./circleannotation/) | Klasse, die eine Kreis-Anmerkung darstellt. |
| [Collection](./collection/) | Stellt die Klasse für Collection(12.3.5 Collections) dar. |
| [CollectionField](./collectionfield/) | Stellt eine Klasse für ein Dokumentensammlungs‑Schema‑Feld dar. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Stellt den Subtyp‑Parameter eines Feldes in einer Schema‑Sammlung dar. |
| [CollectionItem](./collectionitem/) | Stellt eine Klasse für ein Sammlungs‑Element dar. Das Sammlungs‑Element enthält die im Sammlungs‑Schema beschriebenen Daten. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Stellt eine Klasse für einen Wert eines Sammlungs‑Elements dar. |
| [CollectionSchema](./collectionschema/) | Stellt eine Klasse dar, die das "Schema" einer Dokumentensammlung beschreibt. |
| [Color](./color/) | Stellt eine Klasse für Farbwerte dar, die in verschiedenen Farbräumen ausgedrückt werden können. |
| [ColorBarAnnotation](./colorbarannotation/) | Klasse, die die ColorBarAnnotation‑Annotation darstellt. Die Eigenschaft Color wird ignoriert, stattdessen wird die ColorsOfCMYK‑Farbe verwendet. Bei der Erstellung bestimmt das Verhältnis von Breite und Höhe die Ausrichtung der Annotation – horizontal oder vertikal. Anschließend wird geprüft, ob das Annotationsrechteck außerhalb des TrimBox liegt; falls nicht, wird es an die nächstgelegene Position außerhalb des TrimBox verschoben, wobei die Ausrichtung der Annotation berücksichtigt wird. Es ist möglich, die Breite (Höhe) zu reduzieren, damit die Annotation außerhalb des TrimBox passt. Gibt es keinen Platz für das Layout, können Breite/Höhe auf Null gesetzt werden (in diesem Fall ist die Annotation auf der Seite vorhanden, wird jedoch nicht angezeigt). |
| [ColumnInfo](./columninfo/) | Diese Klasse stellt Informationen einer Spalte dar. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Klasse, die Ereignisse darstellt. |
| [ComboBoxField](./comboboxfield/) | Klasse, die das Kombinationsfeld einer Form darstellt. |
| [ComHelper](./comhelper/) | <p> Stellt Methoden für COM‑Clients bereit, um ein Dokument in Aspose.PDF zu laden. </p> <hr> <p> Verwenden Sie die ComHelper‑Klasse, um ein Dokument aus einer Datei oder einem Stream in ein Document‑Objekt in einer COM‑Anwendung zu laden. Die Document‑Klasse bietet einen Standardkonstruktor zum Erstellen eines neuen Dokuments und ebenfalls überladene Konstruktoren zum Laden eines Dokuments aus einer Datei oder einem Stream. Wenn Sie Aspose.Words aus einer .NET‑Anwendung verwenden, können Sie alle Document‑Konstruktoren direkt nutzen, aber wenn Sie Aspose.PDF aus einer COM‑Anwendung verwenden, ist nur der Standard‑Document‑Konstruktor verfügbar. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Abstrakte Klasse, die eine allgemeine Figuren‑Annotation darstellt. |
| [CompositingParameters](./compositingparameters/) | Stellt ein Objekt dar, das die Kompositing‑Parameter der aktuellen Grafik‑Zustands enthält. |
| [ContentsAppender](./contentsappender/) | Führt Inhaltsänderungen ausschließlich im APPEND‑Modus durch. Dieser Modus ermöglicht es, unnötiges und umfangreiches Parsen des Inhalts zu vermeiden, bevor Änderungen vorgenommen werden. Er fügt neue Operatoren nur am Ende oder am Anfang des Inhalts hinzu. |
| [Copier](./copier/) | Klasse für Kopierobjekte. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Stellt Annotationstypen dar, die in den Ecken der gedruckten Seite platziert werden. |
| [CustomExplicitDestination](./customexplicitdestination/) | Stellt ein benutzerdefiniertes explizites Ziel dar. |
| [CustomSign](./customsign/) | Delegat zum benutzerdefinierten Signieren des Dokuments (Beta). |
| [Dash](./dash/) | Klasse, die das Strichmuster einer Linie darstellt. |
| [DateField](./datefield/) | Datumsfeld mit Kalenderansicht. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Beschreibt das Standardaussehen eines Feldes (Schriftart, Textgröße und Farbe). |
| [DefaultDirectory](./defaultdirectory/) | Gibt den Standardpfad für einen bestimmten Zweck an. |
| [DestinationCollection](./destinationcollection/) | Klasse, die die Sammlung aller Ziele (einen Namensbaum, der Namenszeichenketten zu Zielen abbildet (siehe 12.3.2.3, "Named Destinations") und (siehe 7.7.4, "Name Dictionary")) im PDF‑Dokument darstellt. |
| [DestinationFactory](./destinationfactory/) | Stellt die DestinationFactory‑Klasse dar. |
| [DjvuLoadOptions](./djvuloadoptions/) | Klasse beschreibt DJVU-Ladeoptionen. |
| [DocMDPSignature](./docmdpsignature/) | Stellt die Klasse des Dokument-MDP (Modification Detection and Prevention) Signaturtyps dar. |
| [DocSaveOptions](./docsaveoptions/) | Speicheroptionen für den Export in das Doc-Format |
| [Document](./document/) | Klasse, die ein PDF-Dokument darstellt. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Klasse, die den Dokumentoptimierungsalgorithmus beschreibt. Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden. @deprecated Diese Klasse ist veraltet. Bitte verwenden Sie stattdessen com.aspose.pdf.optimization.OptimizationOptions. |
| [Document.RepairOptions](./document.repairoptions/) | Stellt Optionen zur Reparatur eines PDF-Dokuments dar. Diese Klasse bietet eine Möglichkeit, den Reparaturvorgang eines PDF-Dokuments anzupassen. |
| [DocumentActionCollection](./documentactioncollection/) | Klasse beschreibt Aktionen, die an einem Dokument ausgeführt werden. |
| [DocumentExtensions](./documentextensions/) | Bietet zusätzliche Funktionen für die Document-Klasse. |
| [DocumentFactory](./documentfactory/) | Klasse, die das Erstellen/Laden von Dokumenten verschiedener Typen ermöglicht. |
| [DocumentInfo](./documentinfo/) | Stellt Metainformationen eines PDF-Dokuments dar. |
| [DocumentWeb](./documentweb/) | Stellt die DocumentWeb-Klasse dar |
| [Element](./element/) | Klasse, die das Basiselement der logischen Struktur darstellt. |
| [ElementCollection](./elementcollection/) | Sammlung von Basiselementen der logischen Struktur. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Klasse, die die Sammlung eingebetteter Dateien darstellt. |
| [EncryptedPayload](./encryptedpayload/) | Stellt die verschlüsselte Nutzlast in der Dateispezifikation dar. |
| [EpubLoadOptions](./epubloadoptions/) | Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument. |
| [EpubSaveOptions](./epubsaveoptions/) | Speicheroptionen für den Export in das EPUB-Format |
| [ExcelSaveOptions](./excelsaveoptions/) | Speicheroptionen für den Export in das Excel-Format |
| [ExplicitDestination](./explicitdestination/) | Stellt die Basisklasse für explizite Ziele in einem PDF-Dokument dar. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Stellt die ExplicitDestinationTypeConverter-Klasse dar |
| [ExportFieldsOptions](./exportfieldsoptions/) | Stellt die Basisklasse von Optionen für den Export von Formularfeldern dar. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Stellt Optionen für den Export von Formularfeldern in das Json-Format dar. Erbt von {@link ExportFieldsOptions} und fügt spezifische Optionen für den Json-Export hinzu. |
| [ExportImportMessages](./exportimportmessages/) | Enthält verschiedene Fehlermeldungen für Export- und Importvorgänge von Formularfeldern. |
| [ExternalSignature](./externalsignature/) | Erstellt eine losgelöste PKCS#7Detached-Signatur mithilfe eines X509Certificate2. Sie unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel. |
| [FdfReader](./fdfreader/) | Klasse, die das Lesen des FDF-Formats durchführt. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | Basisklasse für Acro-Formularfelder. |
| [FieldSerializationResult](./fieldserializationresult/) | Stellt das Ergebnis eines Serialisierungsprozesses für Formularfelder dar. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Stellt den Status der Serialisierung von Formularfeldern dar. |
| [FieldValueType](./fieldvaluetype/) | Stellt den Typ des Feldwerts in einer Schemasammlung dar. |
| [FigureElement](./figureelement/) | Klasse, die eine logische Strukturfigur darstellt. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Klasse, die Dateianhang-Annotation beschreibt. |
| [FileFontSource](./filefontsource/) | Stellt eine einzelne Schriftdateiquelle dar. |
| [FileHyperlink](./filehyperlink/) | Stellt ein Dateihyperlink-Objekt dar. |
| [FileIconConverter](./fileiconconverter/) | Stellt die Klasse FileIconConverter dar |
| [FileParams](./fileparams/) | Definiert ein eingebettetes Datei-Parameter-Wörterbuch, das zusätzliche dateispezifische Informationen enthalten soll. |
| [FileSelectBoxField](./fileselectboxfield/) | Feld für das Dateiauswahlfeld-Element. |
| [FileSpecification](./filespecification/) | Klasse, die eine eingebettete Datei darstellt. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass ihr Begrenzungsrahmen vollständig sowohl horizontal als auch vertikal in das Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, wird der kleinere der beiden verwendet, wobei der Begrenzungsrahmen in der anderen Dimension im Fenster zentriert wird. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der vertikalen Koordinate top am oberen Rand des Fensters positioniert und den Seiteninhalt so vergrößert, dass die gesamte Breite ihres Begrenzungsrahmens in das Fenster passt. Ein Nullwert für top gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der horizontalen Koordinate left am linken Rand des Fensters positioniert und den Seiteninhalt so vergrößert, dass die gesamte Höhe ihres Begrenzungsrahmens in das Fenster passt. Ein Nullwert für left gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. |
| [FitExplicitDestination](./fitexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass die gesamte Seite sowohl horizontal als auch vertikal in das Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, wird der kleinere der beiden verwendet, wobei die Seite in der anderen Dimension im Fenster zentriert wird. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit der vertikalen Koordinate top am oberen Rand des Fensters positioniert und den Seiteninhalt so vergrößert, dass die gesamte Breite der Seite in das Fenster passt. Ein Nullwert für top gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass das durch die Koordinaten left, bottom, right und top definierte Rechteck vollständig sowohl horizontal als auch vertikal in das Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, wird der kleinere der beiden verwendet, wobei das Rechteck in der anderen Dimension im Fenster zentriert wird. Ein Nullwert für einen der Parameter kann zu unvorhersehbarem Verhalten führen. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Stellt ein explizites Ziel dar, das die Seite anzeigt, wobei die horizontale Koordinate links am linken Rand des Fensters positioniert ist und der Inhalt der Seite so weit vergrößert wird, dass die gesamte Höhe der Seite in das Fenster passt. Ein Nullwert für links gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. |
| [FixedPrint](./fixedprint/) | Stellt feste Druckdaten der Watermark Annotation dar. |
| [FloatingBox](./floatingbox/) | Stellt eine FloatingBox in einem PDF-Dokument dar. FloatingBox ist benutzerdefiniert positioniert. |
| [FlowConverter](./flowconverter/) | Konvertiere PDF-Dokument in Flow-Formate (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX im EnchanedFlow‑Modus, TableAbsorber im FlowEngine‑Modus. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Daten von der Flow-Bibliothek an TableAbsorber übergeben |
| [FolderFontSource](./folderfontsource/) | Stellt den Ordner dar, der Schriftdateien enthält. |
| [Font](./font/) | <p> Stellt ein Schriftobjekt dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und die Schrift des ersten Suchvorkommens ändert. // Open document Document doc = new Document(\"input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Stellt ein Absorber-Objekt für Schriften dar. Führt eine Suche nach Schriften durch und bietet Zugriff auf die Suchergebnisse über die {@code FontAbsorber.Fonts}-Sammlung. |
| [FontCollection](./fontcollection/) | <p> Stellt eine Schriftartensammlung dar. </p> <hr> <pre> The example demonstrates how to make all font declared on page as embedded. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save(\"D:\\\\Tests\\\\input.pdf\"); </pre> <hr> <p> Schriftartensammlungen, die durch die {@code FontCollection}-Klasse repräsentiert werden, werden in mehreren Szenarien verwendet. Zum Beispiel in Ressourcen mit der {@code Resources.Fonts}-Eigenschaft. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | Der PDF/A-Standard verlangt, dass alle Schriften in das Dokument eingebettet werden. Diese Klasse enthält Flags für Fälle, in denen es nicht möglich ist, eine Schrift einzubetten, weil diese Schrift auf dem Ziel-PC fehlt. |
| [FontRepository](./fontrepository/) | <p> Führt eine Schriftsuche durch. Durchsucht systeminstallierte Schriften und Standard Pdf Schriften. Bietet außerdem die Möglichkeit, benutzerdefinierte Schriften zu öffnen. </p> <hr> <pre> Das Beispiel zeigt, wie man die Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt. // Schriftart finden Font font = FontRepository.findFont("Arial"); // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // TextFragmentAbsorber-Objekt erstellen, um alle "hello world" Textvorkommen zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get_Item(1).accept(absorber); // Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Stellt eine Basisklasse für Schriftquellen dar. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Gibt Stilinformationen an, die auf Text angewendet werden. </p> <hr> <p> Diese Aufzählung hat ein {@code FlagsAttribute}-Attribut, das eine Kombination ihrer Memberwerte ermöglicht. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag enumeriert Strategien für das Subsetting von Schriften. |
| [FooterArtifact](./footerartifact/) | Beschreibt das Fußzeilen‑Artefakt. Dies kann verwendet werden, um die Fußzeile der Seite festzulegen. |
| [Form](./form/) | Klasse, die ein Formularobjekt darstellt. |
| [Form.FlattenSettings](./form.flattensettings/) | Klasse, die Einstellungen für das Formular‑Flattening‑Verfahren beschreibt. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Formulare können Signaturinformationen enthalten und können signiert oder unsigniert sein. Manchmal muss die Ansicht von Formularen im Viewer davon abhängen, ob das Formular signiert ist oder nicht. Dieses Enum enumeriert mögliche Render‑Modi während der Konvertierung des Formulartyps in Bezug auf die Signatur. |
| [FormattedFragment](./formattedfragment/) | Stellt ein abstraktes formatiertes Fragment dar. |
| [FreeTextAnnotation](./freetextannotation/) | Stellt eine Freitext‑Annotation dar, die Text direkt auf der Seite anzeigt. Im Gegensatz zu einer normalen Text‑Annotation hat eine Freitext‑Annotation keinen offenen oder geschlossenen Zustand; anstatt in einem Popup‑Fenster angezeigt zu werden, ist der Text stets sichtbar. |
| [GoToAction](./gotoaction/) | Stellt eine Go‑To‑Aktion dar, die die Ansicht zu einem angegebenen Ziel (Seite, Position und Vergrößerungsfaktor) ändert. |
| [GoToRemoteAction](./gotoremoteaction/) | Stellt eine Remote‑Go‑To‑Aktion dar, die einer normalen Go‑To‑Aktion ähnelt, jedoch zu einem Ziel in einer anderen PDF‑Datei springt statt in der aktuellen Datei. |
| [GoToURIAction](./gotouriaction/) | Stellt eine URI‑Aktion dar, die dazu führt, dass ein URI aufgelöst wird. |
| [GraphInfo](./graphinfo/) | Stellt Grafik‑Informationen dar. |
| [Group](./group/) | Eine Gruppen‑Attribut‑Klasse, die die Attribute der Seiten‑Gruppierung für die Verwendung im transparenten Bildgebungsmodell angibt. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | Klasse beschreibt das Header‑Artefakt. Dieses Artefakt kann verwendet werden, um die Überschrift der Seite festzulegen. |
| [HeaderFooter](./headerfooter/) | Klasse stellt eine Header‑ oder Footer‑Pdf‑Seite dar. |
| [Heading](./heading/) | Stellt eine Überschrift dar. |
| [HideAction](./hideaction/) | Stellt eine Versteck‑Aktion dar, die eine oder mehrere Annotationen auf dem Bildschirm ausblendet oder einblendet, indem ihre Hidden‑Flags gesetzt oder gelöscht werden. |
| [HighlightAnnotation](./highlightannotation/) | Stellt eine Hervorhebungs‑Annotation dar, die einen Textbereich im Dokument hervorhebt. |
| [HtmlFragment](./htmlfragment/) | Stellt ein HTML‑Fragment dar. |
| [HtmlLoadOptions](./htmlloadoptions/) | Stellt Optionen zum Laden/Importieren einer HTML‑Datei in ein PDF‑Dokument dar. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binary Flag Gibt Flags an, die zusammen mit anderen Optionen die Größe und das Layout von Seiten bestimmen. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Speicheroptionen für den Export ins HTML‑Format |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Dieses Enum beschreibt mögliche Antialiasing‑Maßnahmen während der Konvertierung |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Diese Klasse repräsentiert einen Datensatz, der sich auf das benutzerdefinierte Speichern von CSS während der Konvertierung von PDF in das HTML-Format bezieht. |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Sie können dieser Eigenschaft eine benutzerdefinierte Strategie zuweisen, die die Verarbeitung und/oder das Speichern eines CSS-Teils implementiert, das während der Konvertierung von PDF zu HTML erstellt wurde. In einem solchen Fall muss die Verarbeitung (wie das Speichern in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code erfolgen. |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Erstellung der URL von CSS, das im erzeugten HTML-Dokument referenziert wird, implementiert. Zum Beispiel, wenn Sie CSS im HTML z. B. als "otherPage.ASPX?CssID=zjjkklj" referenzieren möchten, muss eine solche benutzerdefinierte Strategie "otherPage.ASPX?CssID=zjjkklj" zurückgeben. |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Repräsentiert einen Datensatz, der sich auf die Anforderung vom Konverter an benutzerdefinierten Code bezieht, um die gewünschte URL (oder URL-Vorlage) des betreffenden CSS zu erhalten. |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Diese Aufzählung definiert Regeln, die die Kodierungslogik anpassen. |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Enumeriert Modi, die zum Speichern von im PDF referenzierten Schriftarten verwendet werden können. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Diese Klasse repräsentiert einen Datensatz, der sich auf das Speichern von externen Bilddateien während der PDF-zu-HTML-Konvertierung bezieht. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | Enumeriert mögliche Typen von Bilddateien, die während der PDF-zu-HTML-Konvertierung als externe Ressourcen gespeichert werden können. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Manchmal gibt es spezifische Anforderungen an das erstellte HTML. Diese Aufzählung definiert HTML-Vorbereitungsmodi, die während der Konvertierung von PDF zu HTML verwendet werden können, um diesen spezifischen Anforderungen gerecht zu werden. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Wenn die Eigenschaft SplitToPages von HtmlSaveOptions gesetzt ist, werden während der Konvertierung von PDF zu HTML mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Klasse repräsentiert einen Datensatz, der sich auf das benutzerdefinierte Speichern des Markups einer HTML-Seite während der PDF-zu-HTML-Konvertierung bezieht. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten (die ebenfalls externe Dateien wie Bilder oder Schriftarten referenzieren können). Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde und die Verarbeitung der erzeugten HTML-Seite (HTML selbst) implementiert, die während der Konvertierung erstellt wurde. In einem solchen Fall kann die Verarbeitung (wie das Speichern in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Markups der HTML-Seite im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diesen oder jenen Fall aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'htmlSavingInfo': Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, so wie es wäre, wenn kein externes benutzerdefiniertes Speichercode vorhanden wäre. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Enumeriert mögliche Typen von Bild‑Eltern, zu denen ein Bild entweder einer HTML-Seite oder einem SVG‑Elternbild gehören kann. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Diese Aufzählung enumeriert mögliche Einbettungsmodi von in HTML referenzierten Dateien. Sie ermöglicht die Kontrolle, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS-Dateien) in die Haupt‑HTML‑Datei eingebettet oder als separate Binärobjekte erzeugt werden. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | Konvertierte PDF kann Rasterbilder (.png, *.jpeg usw.) enthalten. Dieses Enum definiert Methoden, wie Rasterbilder während der Konvertierung von PDF zu HTML behandelt werden können. |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | Für diese Eigenschaft können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer externen Ressource (Schriftart oder Bild) implementiert, die aus dem PDF extrahiert wurde und während der Konvertierung von PDF zu HTML als externe Ressource gespeichert werden muss. In einem solchen Fall kann die Verarbeitung (wie das Speichern in einem Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen und dieser benutzerdefinierte Code muss einen Pfad (oder irgendeinen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das erzeugte HTML eingefügt wird anstelle des ursprünglich erwarteten Pfads zu dieser Bildressource. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung dieser oder jener Datei aus irgendeinem Grund vom Code des Konverters selbst durchgeführt werden muss, nicht im benutzerdefinierten Code, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'resourceSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, als ob kein externer benutzerdefinierter Code vorhanden wäre. |
| [Hyperlink](./hyperlink/) | Stellt einen abstrakten Hyperlink dar. |
| [IconFit](./iconfit/) | Beschreibt, wie das Symbol der Widget-Annotation innerhalb ihres Annotationsrechtecks angezeigt werden soll. |
| [Id](./id/) | <p> Stellt die Dateikennzeichnerstruktur dar. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Stellt ein Bild dar. |
| [ImageDeleteAction](./imagedeleteaction/) | Aktion, die mit dem Bildobjekt ausgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird |
| [ImagePlacement](./imageplacement/) | <p> Stellt die Merkmale eines Bildes dar, das auf einer PDF-Dokumentseite platziert ist. </p> <hr> <pre> Das Beispiel zeigt, wie man Bilder auf der ersten PDF-Dokumentseite findet und Bilder als Bitmaps mit sichtbaren Abmessungen erhält. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Erstelle ein ImagePlacementAbsorber-Objekt, um die Bildplatzierungssuche durchzuführen ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Akzeptiere den Absorber für die erste Seite doc.getPages().get_Item(1).accept(abs); // Rufe Bilder mit sichtbaren Abmessungen ab for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Bild aus Ressourcen abrufen imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Erstelle ein neues Bitmap mit tatsächlichen Abmessungen scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Wenn ein Bild auf einer Seite platziert wird, kann es andere Abmessungen haben als die physischen Abmessungen, die in {@code Resources} definiert sind. Das Objekt {@code ImagePlacement} soll solche Informationen wie Abmessungen, Auflösung und dergleichen bereitstellen. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Stellt ein Absorber-Objekt für Bildplatzierungsobjekte dar. Führt eine Suche nach Bildverwendungen durch und bietet Zugriff auf die Suchergebnisse über die {@code ImagePlacementAbsorber.ImagePlacements}-Sammlung. </p> <hr> <pre> Das Beispiel zeigt, wie man Bilder auf der ersten Seite eines PDF-Dokuments findet und die Bildplatzierungseigenschaften abruft. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> Das {@code ImagePlacementAbsorber}-Objekt wird grundsätzlich im Bildsuch‑Szenario verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen durch {@code ImagePlacement}-Objekte dargestellt, die die {@code ImagePlacementAbsorber.ImagePlacements}-Sammlung enthält. Das {@code ImagePlacement}-Objekt bietet Zugriff auf die Bildplatzierungseigenschaften: Abmessungen, Auflösung usw. </p> Eine positive Bildrotation ist gegen den Uhrzeigersinn, für die Seite ist sie im Uhrzeigersinn. Hier müssen wir den Bildrotationswinkel darstellen, indem wir den Seitenwinkel vom Bildwinkel abziehen. |
| [ImagePlacementCollection](./imageplacementcollection/) | Stellt eine Sammlung von Bildplatzierungen dar |
| [ImageStamp](./imagestamp/) | Stellt einen grafischen Stempel dar. |
| [ImageType](./imagetype/) | Stellt Bildformattypen dar. |
| [ImportDataAction](./importdataaction/) | Bei Aufruf einer Import‑Daten‑Aktion werden Forms Data Format (FDF)-Daten aus einer angegebenen Datei in das interaktive Formular des Dokuments importiert. |
| [ImportFieldsOptions](./importfieldsoptions/) | Stellt die Basisklasse für Optionen zum Importieren von Formularfeldern dar. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Stellt Optionen für den Import von Formularfeldern in das Json-Format dar. Erbt von {@code ImportFieldsOptions} und fügt spezifische Optionen für den Json-Import hinzu. |
| [ImportOptions](./importoptions/) | Der Typ ImportOptions bietet eine Abstraktionsebene für einzelne Importoptionen. |
| [InkAnnotation](./inkannotation/) | Stellt eine Freihand‑„Kritzelei“ dar, die aus einem oder mehreren getrennten Pfaden besteht. |
| [InternalHelper](./internalhelper/) | Interne Klasse |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | Die Ausnahme, die ausgelöst wird, wenn eine Operation mit dem Formulartyp ungültig ist. |
| [JavascriptAction](./javascriptaction/) | Klasse, die eine JavaScript‑Aktion darstellt. |
| [JavaScriptCollection](./javascriptcollection/) | Diese Klasse stellt eine Sammlung von JavaScript dar. |
| [LatexFragment](./latexfragment/) | Stellt ein TeX‑Fragment dar. @deprecated Bitte verwenden Sie stattdessen TeXFragment |
| [LatexLoadOptions](./latexloadoptions/) | Stellt Optionen zum Laden/Importieren einer TeX‑Datei in ein PDF‑Dokument dar. @deprecated Verwenden Sie stattdessen TeXLoadOptions. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Speicheroptionen für den Export ins TeX‑Format. @deprecated Verwenden Sie stattdessen TeXSaveOptions |
| [LaunchAction](./launchaction/) | Stellt eine Start‑Aktion dar, die eine Anwendung startet oder ein Dokument öffnet bzw. druckt. |
| [Layer](./layer/) | Stellt eine Ebene innerhalb einer PDF‑Seite dar. |
| [LevelFormat](./levelformat/) | Stellt das Format des Inhaltsverzeichnisses dar. |
| [License](./license/) | Stellt Methoden zur Lizenzierung der Komponente bereit. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Stellt Lizenzinformationen dar. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Leichte Operatorensammlung. Vorgesehen für Szenarien, in denen der zugrunde liegende Inhaltsstrom nicht angehängt ist und nur eine Operatorensammlung als Ergebnis benötigt wird. |
| [LineAnnotation](./lineannotation/) | Klasse, die eine Linienannotation darstellt. |
| [LineEndingConverter](./lineendingconverter/) | Stellt die Klasse LineEndingConverter dar |
| [LineEndingsDrawer](./lineendingsdrawer/) | Zeichnet Zeilenenden für Annotationen. Interne Klasse nur für den internen Gebrauch. |
| [LinkAnnotation](./linkannotation/) | Stellt entweder einen Hyperlink zu einem Ziel an anderer Stelle im Dokument oder eine auszuführende Aktion dar. |
| [ListBoxField](./listboxfield/) | Klasse stellt ein ListBox-Feld dar. |
| [LoadOptions](./loadoptions/) | Der Typ LoadOptions enthält das Abstraktionsniveau für einzelne Ladeoptionen |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Stellt den Verwendungsmodus des Randbereichs während der Konvertierung dar (wie HTML, EPUB usw.) und definiert die Behandlung von Anweisungen des importierten Formats im Zusammenhang mit der Nutzung der Ränder. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ACHTUNG! Das Feature ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blocker-Problem in der OSHARED-Schicht für das Beispieldokument aufgetreten ist. Stellt den Verwendungsmodus der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass die erforderliche Seitengröße angepasst werden kann. Manchmal gibt der Inhalt jedoch horizontale Positionen oder Größen an, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen. In einem solchen Fall können wir festlegen, was zu tun ist (z. B. wenn die Größe des Inhalts nicht in die erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Ergebnis des benutzerdefinierten Ladens einer Ressource |
| [LocaleOptions](./localeoptions/) | Der Typ LocaleOptions gibt die Gebietsschema-Konfiguration für Aspose.PDF an. |
| [LocalHyperlink](./localhyperlink/) | Stellt ein lokales Hyperlink-Objekt dar. |
| [MarginInfo](./margininfo/) | Diese Klasse stellt einen Rand für verschiedene Objekte dar. |
| [MarkupAnnotation](./markupannotation/) | Abstrakte Klasse, die eine Markup-Annotation darstellt. |
| [MarkupParagraph](./markupparagraph/) | Stellt einen Absatz dar. |
| [MarkupSection](./markupsection/) | Stellt einen Markup-Abschnitt dar – den rechteckigen Bereich einer Seite, der Text enthält und visuell von anderen Textblöcken getrennt werden kann. |
| [Matrix](./matrix/) | Klasse stellt eine Transformationsmatrix dar. |
| [Matrix3D](./matrix3d/) | Klasse stellt eine Transformationsmatrix dar. |
| [MdLoadOptions](./mdloadoptions/) | Ladeoptionen für die Konvertierung des Markdown-Formats. |
| [Measure](./measure/) | Klasse, die das Measure-Koordinatensystem beschreibt. |
| [Measure.NumberFormat](./measure.numberformat/) | Zahlenformat für Measure. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Stellt eine Liste von Zahlenformaten dar. |
| [MediaClip](./mediaclip/) | Klasse beschreibt das Media-Clip-Objekt der Wiedergabe. |
| [MediaClipData](./mediaclipdata/) | Klasse beschreibt Mediaklip-Daten. |
| [MediaClipSection](./mediaclipsection/) | Diese Klasse beschreibt den Media-Clip-Abschnitt. |
| [MediaRendition](./mediarendition/) | Klasse beschreibt Medienrendition. |
| [MemoryCleaner](./memorycleaner/) | Repräsentiert die Klasse MemoryCleaner. |
| [MemoryExtender](./memoryextender/) | Repräsentiert die Klasse MemoryExtender. Bei Verwendung großer Dateien auf einem System mit begrenztem Heap-Speicher kann sie aktiviert werden, um Festplattenspeicher als temporären Auslagerungsspeicher zu nutzen. |
| [MemoryFontSource](./memoryfontsource/) | Stellt eine einzelne Schriftdateiquelle dar. |
| [Metadata](./metadata/) | Stellt Zugriff auf den XMP-Metadaten-Stream bereit. |
| [Metered](./metered/) | <p> Stellt Methoden zum Setzen des gemessenen Schlüssels bereit. </p> <hr> In diesem Beispiel wird versucht, den gemessenen öffentlichen und privaten Schlüssel zu setzen <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Repräsentiert Optionen zum Laden/Importieren von .mht-Dateien in ein PDF-Dokument. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Speicheroptionen für den Export in das XML-Format |
| [MovieAnnotation](./movieannotation/) | Repräsentiert eine Filmannotation, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher wiedergegeben werden. Wenn die Annotation aktiviert wird, wird der Film abgespielt. |
| [NamedAction](./namedaction/) | Repräsentiert benannte Aktionen, die von PDF-Betrachteranwendungen unterstützt werden sollen. |
| [NamedDestination](./nameddestination/) | Anstatt direkt mit der expliziten Syntax definiert zu werden, kann auf ein Ziel indirekt mittels eines Namensobjekts oder einer Byte-Zeichenkette verwiesen werden. |
| [Note](./note/) | Diese Klasse repräsentiert die Generator-Absatz-Notiz. |
| [NumberField](./numberfield/) | Textfeld mit angegebenen gültigen Zeichen @see TextBoxField |
| [NumberTree](./numbertree/) | Klasse, die die Zahlenbaumstruktur einer PDF-Datei darstellt. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Repräsentiert die OCSP-Einstellungen, die während des Signaturvorgangs verwendet werden. |
| [OfdLoadOptions](./ofdloadoptions/) | Ladeoptionen für das OFD-Format. |
| [Operator](./operator/) | Abstrakte Klasse, die einen Operator darstellt. |
| [OperatorCollection](./operatorcollection/) | Klasse stellt eine Sammlung von Operatoren dar |
| [OperatorSelector](./operatorselector/) | Diese Klasse wird verwendet, um Operatoren anhand der Visitor-Vorlagenidee auszuwählen. |
| [Opi](./opi/) | Stellt das Open Prepress Interface (OPI) dar, ein Mechanismus zur Erstellung von Low-Resolution-Platzhaltern oder Proxy-Objekten für hochauflösende Bilder. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Definiert einen MemoryStream, der eine höhere Standardkapazität enthalten kann. |
| [Option](./option/) | Klasse stellt die Option eines Auswahlfeldes dar. |
| [OptionCollection](./optioncollection/) | Klasse, die die Sammlung von Optionen des Auswahlfeldes darstellt. |
| [OutlineCollection](./outlinecollection/) | Stellt die Dokumenten-Gliederungshierarchie dar. |
| [OutlineItemCollection](./outlineitemcollection/) | Stellt einen Gliederungseintrag in der Gliederungshierarchie eines PDF-Dokuments dar. |
| [Outlines](./outlines/) | Klasse beschreibt Sammlung von Gliederungen. |
| [OutputIntent](./outputintent/) | Stellt eine Ausgabeabsicht dar, die die Farbeigenschaften eines PDF-Dokuments mit denen eines Zielausgabegeräts oder einer Produktionsumgebung, in der das Dokument gedruckt wird, abgleicht. |
| [OutputIntents](./outputintents/) | Stellt die Sammlung von {@link OutputIntent} dar. |
| [Page](./page/) | Klasse, die eine Seite eines PDF-Dokuments darstellt. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Verfahren zum Anpassen von Kopf- und Fußzeile. |
| [PageActionCollection](./pageactioncollection/) | Diese Klasse beschreibt Seitenaktionen |
| [PageCollection](./pagecollection/) | Sammlung von PDF-Dokumentseiten. |
| [PageExtensions](./pageextensions/) | Bietet zusätzliche Funktionen für die Page-Klasse. |
| [PageInfo](./pageinfo/) | Stellt die Seiteninformationen für den pdf‑Generator dar. Stellt eine Page‑Information‑Annotation in einem PDF‑Dokument dar. Diese Annotation enthält den Dateinamen, die Seitennummer sowie Datum und Uhrzeit der Annotationserstellung. Diese Klasse wird hauptsächlich verwendet, um Metadaten zu einer bestimmten Seite im PDF‑Dokument hinzuzufügen, was für Nachverfolgungs‑ und Referenzzwecke nützlich sein kann. Beispielsweise kann sie verwendet werden, um Seiten während des Druckvorgangs zu markieren oder zusätzliche Informationen über die Seite beim Betrachten des Dokuments bereitzustellen. |
| [PageInformationAnnotation](./pageinformationannotation/) | Klasse, die einen Page‑Label‑Bereich darstellt. |
| [PageLabel](./pagelabel/) | Klasse, die eine Sammlung von Seitenbeschriftungen darstellt. |
| [PageLabelCollection](./pagelabelcollection/) | Seiten‑Markup dargestellt durch Sammlungen von {@code MarkupSection} und {@code MarkupParagraph}. |
| [PageMarkup](./pagemarkup/) | Stellt einen Seitenzahlstempel dar und wird zum Nummerieren von Seiten verwendet. |
| [PageNumberStamp](./pagenumberstamp/) | Klasse, die die Größe einer Seite in einem PDF‑Dokument darstellt. |
| [PageSize](./pagesize/) | Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar. |
| [PaginationArtifact](./paginationartifact/) | Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Stellt ein Absorber-Objekt der Seitenstruktur-Objekte wie Abschnitte und Absätze dar. Führt die Suche nach Abschnitten und Absätzen im Text durch und bietet Zugriff auf Rechtecke und Polygone, die es im Textkoordinatenraum beschreiben. Führt außerdem die Suche nach Textsegmenten durch und bietet Zugriff auf die Suchergebnisse über {@code TextFragments}-Sammlungen, gruppiert nach Strukturelementen. </p> Das Beispiel zeigt, wie man das erste Textsegment jedes Absatzes auf der ersten PDF-Dokumentseite findet und hervorhebt. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Wenn die Suche abgeschlossen ist, enthält die {@code ParagraphAbsorber.PageMarkups}-Sammlung {@code PageMarkup}-Objekte, die die Seitenstruktur durch Sammlungen von {@code MarkupSection} und {@code MarkupParagraph} darstellen. Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schrift, Schriftgröße, Farbe usw.). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Stellt Optionen für den {@link ParagraphAbsorber} dar. |
| [Paragraphs](./paragraphs/) | Diese Klasse stellt eine Absatzsammlung dar. |
| [PasswordBoxField](./passwordboxfield/) | Klasse beschreibt ein Textfeld zur Eingabe des Passworts. |
| [PclLoadOptions](./pclloadoptions/) | Stellt Optionen für das Laden (Import) einer PCL-Datei in ein PDF-Dokument dar. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Enumeriert Konvertierungs-Engines, die für die Konvertierung verwendet werden können |
| [PDF3DAnnotation](./pdf3dannotation/) | Klasse PDF3DAnnotation. Diese Klasse kann nicht geerbt werden. @see Annotation |
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
| [PdfAction](./pdfaction/) | Stellt eine Aktion in einem PDF-Dokument dar |
| [PdfActionCollection](./pdfactioncollection/) | Klasse beschreibt eine Liste von Aktionen. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Diese Klasse beschreibt Regeln, die verwendet werden können, um den Vorgang des Kopierens von Kodierungsdaten für Fälle zu optimieren, in denen eine TrueType‑Symbolschrift mehr als eine Kodierung hat. Einige PDF‑Dokumente können nach der Konvertierung in das PDF/A‑Format einen Fehler \"More than one encoding in symbolic TrueType font's cmap\" ausgeben. Was ist die Ursache dieses Fehlers? Alle TrueType‑Symbolschriften besitzen eine spezielle Tabelle \"cmap\" in ihren internen Daten. Diese Tabelle ordnet Zeichencodes Glyphen‑Indizes zu. Und diese Tabelle kann verschiedene Kodierungs‑Untertabelle(n) enthalten, die die verwendeten Kodierungen beschreiben. Siehe erweiterte Informationen zu cmap‑Tabellen unter https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Normalerweise enthält die cmap‑Tabelle mehrere Kodierungs‑Untertabelle(n), aber der PDF/A‑Standard verlangt, dass entweder nur eine Kodierungs‑Untertabelle für diese Schrift im PDF/A‑Dokument verbleibt oder dass unter den Unterschrift‑Tabellen dieser Schrift eine (3,0)‑Kodierungs‑Untertabelle vorhanden ist. Und die zentrale Frage hier – welche Daten aus anderen Unterschrift‑Tabellen müssen in die Ziel‑Kodierungstabelle (3,0) kopiert werden? Die Mehrheit der Schriften hat \"wohlgeformte\" cmap‑Tabellen, bei denen jede Kodierungs‑Untertabelle vollständig mit einer anderen Unterschrift‑Tabelle konsistent ist. Einige Schriften besitzen jedoch cmap‑Tabellen mit Kollisionen – zum Beispiel hat eine Unterschrift‑Tabelle den Glyphen‑Index 100 für Unicode 100, während eine andere Unterschrift‑Tabelle den Glyphen‑Index 200 für denselben Unicode 100 hat. Zur Lösung dieses Problems ist eine spezielle Strategie erforderlich. Standardmäßig wird folgende Strategie verwendet: Es wird nach der mac‑Unterschrift‑Tabelle (1,0) gesucht. Wird diese Tabelle gefunden, werden nur deren Daten zum Befüllen der Ziel‑Tabelle (3,0) verwendet. Wird die mac‑Unterschrift‑Tabelle nicht gefunden, werden alle Unterschrift‑Tabellen außer (3,0) durchlaufen und deren Daten in die Ziel‑Unterschrift‑Tabelle (3,0) kopiert. Außerdem wird die Zuordnung für jedes Unicode (Unicode, Glyphen‑Index) nur dann in die Ziel‑Tabelle kopiert, wenn die Ziel‑Tabelle dieses Unicode zum aktuellen Zeitpunkt noch nicht enthält. So wird zum Beispiel, wenn die erste Unterschrift‑Tabelle den Glyphen‑Index 100 für Unicode 100 hat und die nächste Unterschrift‑Tabelle den Glyphen‑Index 200 für dasselbe Unicode 100, nur das Datum der ersten Unterschrift‑Tabelle (Unicode=100, Glyphen‑Index = 100) kopiert. Jede vorherige Unterschrift‑Tabelle hat also Vorrang vor der nächsten. Eigenschaften dieser Klasse { PdfASymbolicFontEncodingStrategy} helfen, das Standardverhalten zu optimieren. Wenn die Eigenschaft {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) vom Typ { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} gesetzt ist, wird die entsprechende Unterschrift‑Tabelle mit Vorrang vor der mac‑Unterschrift‑Tabelle (1,0) verwendet. Der Wert \"MacTable\" aus der Aufzählung {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} hat in diesem Fall keinen Sinn, da er auf dieselbe mac‑Unterschrift‑Tabelle (1,0) verweist, die standardmäßig verwendet wird. Die Eigenschaft {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) verwirft alle Prioritäten für irgendeine Unterschrift‑Tabelle. Ist diese Eigenschaft gesetzt, werden nur Unterschrift‑Tabellen aus der deklarierten Warteschlange in der angegebenen Reihenfolge verwendet. Werden die angegebenen Unterschrift‑Tabellen nicht gefunden, wird die Standarditeration aller Unterschrift‑Tabellen und die oben beschriebene Kopierstrategie verwendet. Das Objekt { PdfASymbolicFontEncodingStrategy.QueueItem} gibt die zu verwendende Kodierungs‑Unterschrift‑Tabelle an. Diese Unterschrift‑Tabelle kann über eine Kombination von Mitgliedern (PlatformID, PlatformSpecificId) oder über die Aufzählung { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} festgelegt werden. Falls die Schrift keine (3,0)‑Unterschrift‑Tabelle besitzt, wird eine andere Unterschrift‑Tabelle verwendet, um die PDF/A‑Kompatibilität aufrechtzuerhalten. Die Auswahl der zu verwendenden Unterschrift‑Tabelle erfolgt nach denselben Regeln wie zuvor beschrieben, sodass {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) und {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) Eigenschaften verwendet werden, um die resultierende Unterschrift‑Tabelle zu bestimmen, und falls die Schrift die angeforderte(n) Unterschrift‑Tabelle(n) nicht hat, wird irgendeine vorhandene Unterschrift‑Tabelle verwendet. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Gibt die Kodierungstabelle an. Jede Kodierungstabelle hat eine eindeutige Kombination von Parametern (PlatformID, PlatformSpecificID). Die Aufzählung {@code CMapEncodingTableType} und die Eigenschaft {@code CMapEncodingTable} wurden implementiert, um die benötigte Auswahl von Kodierungstabellen zu erleichtern. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Deklariert eine Menge bekannter Kodierungstabellen. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | Stellt eine Menge von Optionen zum Konvertieren von PDF-Dokumenten dar. |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Diese Klasse enthält Flags zur Steuerung der PDF/A-Konvertierung für Fälle, in denen das Quell-PDF-Dokument nicht der PDF-Spezifikation entspricht. Wenn die Flags dieser Klasse verwendet werden, verringert sich die Leistung, aber sie sind notwendig, wenn das Quell-PDF-Dokument nicht auf herkömmliche Weise in das PDF/A-Format konvertiert werden kann. Standardmäßig sind alle Flags auf false gesetzt. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Einige PDF-Dokumente enthalten spezielle Unicode‑Symbole, die zum Private Use Area (PUA) gehören; siehe Beschreibung unter https://en.wikipedia.org/wiki/Private_Use_Areas. Diese Symbole verursachen PDF/A‑konforme Fehler wie „Text ist dem Unicode Private Use Area zugeordnet, aber kein ActualText‑Eintrag ist vorhanden“. Diese Aufzählung deklariert Strategien, die zum Umgang mit PUA‑Symbolen verwendet werden können. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Einige Dokumente haben nach der Konvertierung in das PDF/A-Format eine große Dateigröße. Um die Dateigröße für diese Dokumente zu reduzieren, ist es notwendig, eine Strategie zum Entfernen von Schriftarten zu definieren. Diese Aufzählung deklariert Strategien, die zur Optimierung der Schriftartennutzung verwendet werden können. Jede Strategie dieser Aufzählung ist nur sinnvoll, wenn das Flag {@code OptimizeFileSize} gesetzt ist. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Beschreibt Strategien zum Ausrichten von Textsegmenten im Dokument. Derzeit wird nur die Strategie unterstützt, Segmente zu ihren ursprünglichen Grenzen wiederherzustellen. In Zukunft könnten weitere Strategien hinzugefügt werden. |
| [PdfPageStamp](./pdfpagestamp/) | Klasse, die einen Stempel darstellt, der eine PDF‑Seite als Stempel verwendet. |
| [PdfSaveOptions](./pdfsaveoptions/) | Speicheroptionen für den Export in das PDF‑Format. |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Ladeoptionen für das PdfXml‑Format. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Speicheroptionen für das PdfXml‑Format. |
| [Permissions](./permissions/) | Binäres Flag. Diese Aufzählung stellt die Benutzerberechtigungen für ein PDF dar. |
| [PKCS1](./pkcs1/) | Stellt ein Signaturobjekt gemäß dem PKCS#1‑Standard dar. Der RSA‑Verschlüsselungsalgorithmus und die SHA‑1‑Digest‑Methode werden zum Signieren verwendet. |
| [PKCS7](./pkcs7/) | Stellt das PKCS#7‑Objekt dar, das der PKCS#7‑Spezifikation im Internet‑RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5, entspricht. Der SHA1‑Digest des Byte‑Bereichs des Dokuments ist im PKCS#7‑SignedData‑Feld gekapselt. |
| [PKCS7Detached](./pkcs7detached/) | Stellt das PKCS#7‑Objekt dar, das der PKCS#7‑Spezifikation im Internet‑RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5, entspricht. Der ursprünglich signierte Nachrichten‑Digest über den Byte‑Bereich des Dokuments wird als normales PKCS#7‑SignedData‑Feld eingebunden. Es dürfen keine Daten im PKCS#7‑SignedData‑Feld gekapselt werden. |
| [Point](./point/) | Stellt einen Punkt mit Bruchkoordinaten dar. |
| [Point3D](./point3d/) | Stellt einen Punkt mit Bruchkoordinaten dar. |
| [PolyAnnotation](./polyannotation/) | Abstrakte Basisklasse für Poly‑Annotationen. |
| [PolygonAnnotation](./polygonannotation/) | Klasse, die eine Polygon‑Annotation darstellt. |
| [PolylineAnnotation](./polylineannotation/) | Stellt eine Polylinien‑Annotation dar, die einer Polygon‑Annotation ähnlich ist, jedoch sind der erste und der letzte Scheitelpunkt nicht implizit verbunden. |
| [PopupAnnotation](./popupannotation/) | Stellt die Pop‑Up‑Annotation dar, die Text in einem Pop‑Up‑Fenster zur Eingabe und Bearbeitung anzeigt. |
| [Position](./position/) | Stellt ein Positionsobjekt dar |
| [PptxSaveOptions](./pptxsaveoptions/) | Speicheroptionen für den Export in das SVG‑Format |
| [PrintController](./printcontroller/) | Stellt den Druck‑Controller dar. |
| [PrintDuplex](./printduplex/) | Die Papierhandhabungsoption, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Abstrakte Klasse, die eine Druckerzeichen-Anmerkung darstellt. |
| [PrinterMarksKind](./printermarkskind/) | Gibt die Typen der Druckerzeichen an, die zu einem Dokument hinzugefügt werden sollen. Diese Aufzählung hat ein {@link FlagsAttribute} Attribut, das eine bitweise Kombination ihrer Memberwerte ermöglicht. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Stellt Erweiterungsmethoden für die {@link PrinterMarksKind} Aufzählung bereit. |
| [PrintScaling](./printscaling/) | Die Seiten-Skalierungsoption, die ausgewählt werden soll, wenn ein Druckdialog für dieses Dokument angezeigt wird. |
| [ProgressEventType](./progresseventtype/) | Dieses Enum beschreibt mögliche Fortschritt-Ereignistypen, die während der Konvertierung auftreten können. |
| [PsLoadOptions](./psloadoptions/) | Repräsentiert Optionen zum Laden/Importieren von .mht-Dateien in ein PDF-Dokument. |
| [PsSaveOptions](./pssaveoptions/) | Speicheroptionen für den Export zu PS (PostScript) oder EPS-Format. |
| [RadioButtonField](./radiobuttonfield/) | Klasse, die ein Radio-Button-Feld darstellt. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Klasse, die ein Element eines RadioButton-Feldes darstellt. |
| [Rectangle](./rectangle/) | Klasse, die ein Rechteck darstellt. |
| [Redaction](./redaction/) | Nur für den internen Gebrauch @author User |
| [RedactionAnnotation](./redactionannotation/) | Stellt eine Redact-Anmerkung dar. |
| [RegexManager](./regexmanager/) | Stellt einen Wrapper für reguläre Ausdrucksoperationen mit konfigurierbaren Timeout-Einstellungen bereit. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Stellt eine Registration-Mark-Anmerkung dar. Registrierungsmarken sind Symbole, die zu Druckplatten oder Bildschirmen hinzugefügt werden, um während des Druckvorgangs die korrekte Farbabstimmung sicherzustellen. |
| [RenderingOptions](./renderingoptions/) | Stellt Rendering-Optionen dar |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: Menge von Rendermodus-Typen |
| [Rendition](./rendition/) | Klasse, die das Rendition-Objekt von RendtionAnnotation beschreibt. |
| [RenditionAction](./renditionaction/) | Eine Rendition-Aktion, die die Wiedergabe von Multimedia-Inhalten steuert. |
| [RenditionOperation](./renditionoperation/) | Der Vorgang, der ausgeführt werden soll, wenn die Aktion ausgelöst wird. |
| [RenditionType](./renditiontype/) | Aufzählung beschreibt mögliche Typen von Rendition. |
| [Resources](./resources/) | Klasse, die Seitenressourcen darstellt. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Stellt ExtGStates mit einigen Werten dar. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Stellt die Umwandlungsstrategie von RGB zu Gerätegrau-Farbräumen dar. |
| [RichMediaAnnotation](./richmediaannotation/) | Klasse beschreibt RichMediaAnnotation, die das Einbetten von Video-/Audio-Daten in ein PDF-Dokument ermöglicht. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Ereignis, das die Anmerkung aktiviert. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Typ des Multimedia. |
| [RichTextBoxField](./richtextboxfield/) | Klasse beschreibt Rich-Text-Editor-Komponente. |
| [RichTextFontStyles](./richtextfontstyles/) | Optionen zum Stylen von Textfragmenten in RichText. |
| [RootElement](./rootelement/) | Root-Strukturelement. |
| [Row](./row/) | Stellt eine Zeile der Tabelle dar. |
| [Rows](./rows/) | Stellt eine Zeilensammlung einer Tabelle dar. |
| [RtfLoadOptions](./rtfloadoptions/) | Ladeoptionen für das RTF-Format. |
| [SaveOptions](./saveoptions/) | Der Typ SaveOptions hält das Abstraktionsniveau für einzelne Speicheroptionen. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Instanz dieser Klasse repräsentiert Informationen über einen Rand, der auf einem Ergebnisdokument gezeichnet werden kann. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Stellt Informationen über einen Teil des Randes dar (oben, unten, linke Seite oder rechte Seite). |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Instanz dieser Klasse repräsentiert Informationen über Seitenränder, die auf einem Ergebnisdokument gezeichnet werden können. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Stellt Informationen über einen Teil des Seitenrands dar (oben, unten, linke Seite oder rechte Seite). |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Diese Klasse repräsentiert einen Datensatz, der mit dem Speichern externer Ressourcendateien zusammenhängt, das während der Konvertierung von PDF in ein anderes Format (z. B. HTML) auftritt. |
| [ScalingMode](./scalingmode/) | Der Skalierungstyp, der verwendet werden soll. |
| [ScalingReason](./scalingreason/) | Die Umstände, unter denen das Symbol innerhalb des Rechtecks skaliert werden soll. |
| [ScreenAnnotation](./screenannotation/) | Eine Bildschirmannotation, die einen Bereich einer Seite angibt, auf dem Medienclips abgespielt werden können. |
| [SelectorRendition](./selectorrendition/) | Klasse beschreibt die Darstellung des Selektors. |
| [Signature](./signature/) | Eine abstrakte Klasse, die ein Signaturobjekt im PDF-Dokument repräsentiert. Signaturen sind Felder mit Werten von Signaturobjekten, die letztlich Daten enthalten, die zur Überprüfung der Gültigkeit des Dokuments verwendet werden. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Eine abstrakte Klasse, die ein benutzerdefiniertes Signaturdarstellungsobjekt repräsentiert. |
| [SignatureField](./signaturefield/) | Stellt ein Signatur-Formularfeld dar. |
| [SignHash](./signhash/) | Delegat zum benutzerdefinierten Signieren des Dokumenten-Hashes (Beta). |
| [SoundAnnotation](./soundannotation/) | Stellt eine Soundannotation dar, die einen vom Mikrofon des Computers aufgenommenen Ton oder aus einer Datei importierten Ton enthält. |
| [SoundData](./sounddata/) | Stellt Sounddaten dar, die den abzuspielenden Ton definieren, wenn die Annotation aktiviert wird. |
| [SoundEncoding](./soundencoding/) | Das Kodierungsformat für die Beispieldaten. |
| [SoundIcon](./soundicon/) | Enumeriert die Symbole, die bei der Anzeige der Annotation verwendet werden. |
| [SoundIconConverter](./soundiconconverter/) | Stellt die Klasse SoundIconConverter dar. |
| [SoundSampleData](./soundsampledata/) | Stellt zusätzliche Einträge dar, die spezifisch für ein Sound-Objekt sind (Abschnitt 9.2 PDF1-7) |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Das Kodierungsformat für die Sound‑Beispieldaten. |
| [SquareAnnotation](./squareannotation/) | Klasse, die eine quadratische Anmerkung darstellt. |
| [SquigglyAnnotation](./squigglyannotation/) | Stellt die wellenförmige Anmerkung dar, die im Text eines Dokuments als gezackte Unterstreichung erscheint. |
| [Stamp](./stamp/) | Eine abstrakte Klasse für verschiedene Arten von Stempeln, die als Ableitungen vorkommen. |
| [StampAnnotation](./stampannotation/) | <p> Stellt die Gummistempel-Anmerkung dar. Dieser Anmerkungstyp zeigt Text oder Grafiken an, die so aussehen sollen, als wären sie mit einem Gummistempel auf die Seite gestempelt worden. </p> <hr> <pre> Das nächste Code‑Snippet demonstriert, wie man 2 Stempel zur ersten PDF‑Dokumentenseite hinzufügt. Das Eingabedokument stammt aus inFile und Änderungen werden in outFile gespeichert. Der erste Stempel hat das Symbol NotForPublicRelease und der zweite verwendet das Bild aus rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream(\"rubber.jpg\", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Stellt die Klasse StampIconConverter dar. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Stellt eine Durchstreich‑Anmerkung dar, die im Text des Dokuments als Durchstreichung erscheint. |
| [StructElement](./structelement/) | Allgemeines Strukturelement. |
| [SubjectNameElements](./subjectnameelements/) | Aufzählung beschreibt Elemente in der Signatur‑Betreff‑Zeichenkette. |
| [SubmitFormAction](./submitformaction/) | Klasse, die die Aktion submit-form beschreibt. |
| [SvgLoadOptions](./svgloadoptions/) | Stellt Optionen zum Laden/Importieren einer SVG‑Datei in ein PDF‑Dokument dar. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Enumeriert Konvertierungs-Engines, die für die Konvertierung verwendet werden können |
| [SvgSaveOptions](./svgsaveoptions/) | Speicheroptionen für den Export in das SVG‑Format |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Diese Klasse repräsentiert einen Datensatz, der sich auf das Speichern von externen Bilddateien während der PDF-zu-HTML-Konvertierung bezieht. |
| [Symbology](./symbology/) | Eine (Barcode‑)Symbologie definiert die technischen Details eines bestimmten Barcode‑Typs: die Breite der Balken, den Zeichensatz, die Kodierungsmethode, Prüfspezifikationen usw. |
| [SystemFontSource](./systemfontsource/) | Stellt alle im System installierten Schriftarten dar. |
| [TabAlignmentType](./tabalignmenttype/) | Enumeriert die Tab‑Ausrichtungstypen. |
| [Table](./table/) | Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann. |
| [TableAbsorber](./tableabsorber/) | <p> Stellt ein Absorber‑Objekt für Tabellenelemente dar. Führt eine Suche durch und bietet Zugriff auf die Suchergebnisse über die {@code TableAbsorber.TableList}-Sammlung. </p> <hr> <pre> Das Beispiel demonstriert, wie man eine Tabelle auf der ersten PDF‑Dokumentenseite findet und den Text in einer Tabellenzelle ersetzt. // Dokument öffnen Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // TableAbsorber-Objekt erstellen, um Tabellen zu finden TableAbsorber absorber = new TableAbsorber(); // Erste Seite mit Absorber besuchen absorber.visit(doc.getPages().get_Item(1)); // Zugriff auf die erste Tabelle auf der Seite, deren erste Zelle und Textfragmente darin erhalten TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Text des ersten Textfragments in der Zelle ändern fragment.setText(\"hi world\"); // Dokument speichern doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [TabLeaderType](./tableadertype/) | Enumeriert die Tab‑Führungsarten. |
| [TableBroken](./tablebroken/) | Enumeriert die Tabellenunterbrechung. |
| [TabOrder](./taborder/) | Tab‑Reihenfolge auf der Seite |
| [TabStop](./tabstop/) | Stellt eine benutzerdefinierte Tab‑Stopp‑Position in einem Absatz dar. |
| [TabStops](./tabstops/) | Stellt eine Sammlung von {@code TabStop}-Objekten dar. |
| [TeXFragment](./texfragment/) | Stellt ein LaTeX‑Fragment dar. |
| [TeXLoadOptions](./texloadoptions/) | Stellt Optionen für das Laden/Importieren einer TeX-Datei in ein PDF-Dokument dar. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implementiert das Abrufen eines Ausgabestreams aus dem Speicher. Sie können es beispielsweise verwenden, wenn Sie die begleitende Ausgabe (wie eine Protokolldatei) nicht auf die Festplatte schreiben möchten, sondern sie anschließend aus dem Speicher lesen wollen. |
| [TeXSaveOptions](./texsaveoptions/) | Speicheroptionen für den Export ins TeX-Format |
| [TextAbsorber](./textabsorber/) | <p> Stellt ein Absorber-Objekt für Text dar. Führt Textextraktion durch und bietet Zugriff auf das Ergebnis über das {@code TextAbsorber.Text}-Objekt. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Das {@code TextAbsorber}-Objekt wird verwendet, um Text aus einem Pdf-Dokument oder einer Dokumentenseite zu extrahieren. </p> |
| [TextAnnotation](./textannotation/) | Stellt eine Textannotation dar, die ein \"Haftnotiz\" ist und an einem Punkt im PDF-Dokument befestigt ist. |
| [TextBoxField](./textboxfield/) | Klasse, die ein Textfeld darstellt. |
| [TextBuilder](./textbuilder/) | Fügt ein Textobjekt zu einer PDF-Seite hinzu. |
| [TextDefaults](./textdefaults/) | Definiert Standardeinstellungen des Text-Subsystems |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Gibt den Typ der Standardeinstellungen des Text-Subsystems an |
| [TextEditOptions](./texteditoptions/) | Beschreibt Optionen für Textbearbeitungsoperationen. |
| [TextElement](./textelement/) | Allgemeines Textelement der logischen Dokumentstruktur. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Beschreibt, dass ein Textextraktionsfehler im PDF-Dokument aufgetreten ist. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Stellt den Ort im PDF-Dokument dar, an dem ein Textextraktionsfehler aufgetreten ist. |
| [TextExtractionOptions](./textextractionoptions/) | Stellt Optionen für die Textextraktion dar |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Definiert verschiedene Modi, die beim Konvertieren eines PDF-Dokuments in Text verwendet werden können. Siehe {@code TextDevice}-Klasse. |
| [TextFormattingOptions](./textformattingoptions/) | Stellt Optionen für die Textformatierung dar |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Definiert Details zum Zeilenabstand |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Definiert Strategien für den Wortumbruch |
| [TextFragment](./textfragment/) | <p> Stellt ein Fragment von PDF-Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text sowie seine Schriftart ersetzt. // Dokument öffnen Document doc = new Document(\"input.pdf\"); // Schriftart finden, die zum Ändern der Textschriftart des Dokuments verwendet wird Font font = FontRepository.findFont(\"Arial\"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes \"hello world\" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text und Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save(\"output.pdf\"); </pre> <hr> <pre> In wenigen Worten enthält das {@code TextFragment}-Objekt eine Liste von {@code TextSegment}-Objekten. Im Detail: Der Text eines PDF-Dokuments in {@code com.aspose.pdf} wird durch zwei Grundobjekte dargestellt: {@code TextFragment} und {@code TextSegment} Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir das folgende Szenario. Der Benutzer sucht nach dem Text \"hello world\", um damit zu arbeiten, seine Eigenschaften zu ändern, ihn anzusehen usw. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> Die physische Darstellung von PDF-Text ist sehr komplex. Der Text \"hello world\" kann aus mehreren physisch unabhängigen Textsegmenten bestehen. Das Aspose.Pdf-Textmodell legt im Wesentlichen fest, dass das {@code TextFragment}-Objekt einen einzelnen logischen Operationssatz über einer Menge physischer {@code TextSegment}-Objekte bereitstellt, die die Benutzeranfrage repräsentieren. Im Textsuchszenario ist {@code TextFragment} die logische Darstellung des Textes \"hello world\", und die {@code TextSegment}-Objektsammlungen repräsentieren alle physischen Segmente, die das \"hello world\"-Textobjekt bilden. Damit ist {@code TextFragment} nahe an der logischen Textdarstellung. Und {@code TextSegment} ist nahe an der physischen Textdarstellung. Offensichtlich kann jedes {@code TextSegment}-Objekt seine eigene Schriftart, Farbgebung und Positionierungseigenschaften besitzen. {@code TextFragment} bietet eine einfache Möglichkeit, Text mit seinen Eigenschaften zu ändern: Schriftart festlegen, Schriftgröße festlegen, Schriftfarbe festlegen usw. Gleichzeitig sind {@code TextSegment}-Objekte zugänglich und Benutzer können mit {@code TextSegment}-Objekten unabhängig arbeiten. <p> Hinweis darauf, dass das Ändern von TextFragment-Eigenschaften die innere {@code Segments}-Sammlung verändern kann, weil TextFragment ein Aggregatobjekt ist und interne Segmente neu anordnen oder zu einem einzelnen Segment zusammenführen kann. Wenn Ihre Anforderung darin besteht, die {@code Segments}-Sammlung unverändert zu lassen, ändern Sie bitte die internen Segmente einzeln. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Stellt ein Absorber-Objekt für Textfragmente dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextFragmentAbsorber.TextFragments}-Sammlung. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text sowie seine Schriftart ersetzt. // Dokument öffnen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Schriftart finden, die zum Ändern der Textschrift des Dokuments verwendet wird com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text und Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Das {@code TextFragmentAbsorber}-Objekt wird im Wesentlichen im Szenario der Textsuche verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen durch {@code TextFragment}-Objekte dargestellt, die die {@code TextFragmentAbsorber.TextFragments}-Sammlung enthält. Das {@code TextFragment}-Objekt bietet Zugriff auf den Text des Suchvorkommens, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Stellt eine Sammlung von Textfragmenten dar |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Stellt einen Textzustand eines Textfragmentes dar. </p> <hr> <pre> Das Beispiel zeigt, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt ändert. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Schrift ({@code TextFragmentState.Font} Eigenschaft) Schriftgröße ({@code TextFragmentState.FontSize} Eigenschaft) Schriftstil ({@code TextFragmentState.FontStyle} Eigenschaft) Vordergrundfarbe ({@code TextFragmentState.ForegroundColor} Eigenschaft) Hintergrundfarbe ({@code TextFragmentState.BackgroundColor} Eigenschaft) </p> <p> Hinweis: Das Ändern von {@code TextFragmentState}-Eigenschaften kann die innere {@code TextFragment.Segments}-Sammlung verändern, da TextFragment ein Aggregatobjekt ist und interne Segmente neu anordnen oder zu einem einzigen Segment zusammenführen kann. Wenn Ihre Anforderung darin besteht, die {@code TextFragment.Segments}-Sammlung unverändert zu lassen, ändern Sie bitte die inneren Segmente einzeln. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Enumeriert die Symbole, die bei der Anzeige der Annotation verwendet werden. |
| [TextIconConverter](./texticonconverter/) | Stellt die Klasse TextIconConverter dar |
| [TextMarkupAnnotation](./textmarkupannotation/) | Abstrakte Basisklasse für Text-Markup-Annotationen. |
| [TextOptions](./textoptions/) | Stellt Optionen zur Textverarbeitung dar |
| [TextParagraph](./textparagraph/) | <p> Stellt Textabsätze als mehrzeiliges Textobjekt dar. </p> <hr> <pre> Das Beispiel zeigt, wie man ein Textabsatz-Objekt erstellt und es an die PDF-Seite anhängt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Hintergrundmodus für TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Stellt ein Absorber-Objekt für Textabsätze dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextParagraphAbsorber.TextParagraphs}-Sammlung. |
| [TextParagraphCollection](./textparagraphcollection/) | Stellt eine Sammlung von Textabsätzen dar |
| [TextReplaceOptions](./textreplaceoptions/) | Stellt Optionen zum Ersetzen von Text dar |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Bestimmt die Aktion, die nach dem Ersetzen eines Textfragments durch ein kürzeres ausgeführt wird. None - keine Aktion, ersetzter Text kann den Rest der Zeile überlappen; AdjustSpaceWidth - versucht, die Abstände zwischen den Wörtern anzupassen, um die Zeilenlänge beizubehalten; WholeWordsHyphenation - versucht, Wörter zwischen den Absatzzeilen zu verteilen, um das rechte Feld des Absatzes beizubehalten; ShiftRestOfLine - verschiebt den Rest der Zeile entsprechend der veränderten Textlänge, die Zeilenlänge kann geändert werden; Der Standardwert ist ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Stellt Textsuchoptionen dar |
| [TextSegment](./textsegment/) | <p> Stellt ein Segment von PDF-Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt des {@code TextSegment}-Objekts ändert. // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <pre> In wenigen Worten sind {@code TextSegment}-Objekte Kinder des {@code TextFragment}-Objekts. Im Detail: Der Text eines PDF-Dokuments in {@code Aspose.Pdf} wird durch zwei Grundobjekte dargestellt: {@code TextFragment} und {@code TextSegment}. Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir folgendes Szenario. Der Benutzer sucht den Text \"hello world\", um damit zu arbeiten, seine Eigenschaften zu ändern usw. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> <p> Die physische Darstellung von PDF-Text ist sehr komplex. Der Text \"hello world\" kann aus mehreren physisch unabhängigen Textsegmenten bestehen. Das Aspose.PDF-Textmodell legt im Wesentlichen fest, dass das {@code TextFragment}-Objekt einen einzelnen logischen Vorgangssatz über dem physischen {@code TextSegment}-Objekt-Set bereitstellt, das die Benutzerabfrage darstellt. Im Textsuche‑Szenario ist {@code TextFragment} die logische \"hello world\"-Textdarstellung, und die {@code TextSegment}-Objektsammlungen repräsentieren alle physischen Segmente, die das \"hello world\"-Textobjekt bilden. Somit ist {@code TextFragment} nahe an der logischen Textdarstellung und {@code TextSegment} nahe an der physischen Textdarstellung. Offensichtlich kann jedes {@code TextSegment}-Objekt seine eigene Schriftart, Färbung und Positionierungseigenschaften besitzen. {@code TextFragment} bietet einen einfachen Weg, den Text mit seinen Eigenschaften zu ändern: Schriftart setzen, Schriftgröße setzen, Schriftfarbe setzen usw. Währenddessen sind {@code TextSegment}-Objekte zugänglich und Benutzer können unabhängig mit {@code TextSegment}-Objekten arbeiten. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Stellt eine Sammlung von Textsegmenten dar |
| [TextStamp](./textstamp/) | Stellt einen Textstempel dar. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Aktion, die ausgeführt wird, wenn die Schriftart das erforderliche Zeichen nicht enthält. |
| [TextState](./textstate/) | Stellt einen Textzustand eines Textes dar |
| [TextStyle](./textstyle/) | Klasse, die ein Kontrollkästchenfeld darstellt |
| [TimestampSettings](./timestampsettings/) | Repräsentiert die OCSP-Einstellungen, die während des Signaturvorgangs verwendet werden. |
| [TocInfo](./tocinfo/) | Stellt Informationen zum Inhaltsverzeichnis dar. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe‑Preflight‑Fehler \"Text cannot be mapped to Unicode\" zu lösen. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Stellt eine Trim‑Mark‑Annotation dar. Trim‑Marken werden an den Ecken einer gedruckten Seite platziert, um anzuzeigen, wo die Seite beschnitten werden soll. |
| [TxtLoadOptions](./txtloadoptions/) | Ladeoptionen für die TXT-zu-PDF-Konvertierung. |
| [UnderlineAnnotation](./underlineannotation/) | Stellt eine Unterstreichungsannotation dar, die im Text des Dokuments als Unterstreichung erscheint. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Diese Klasse stellt Speicheroptionen dar, die einen einheitlichen Konvertierungsweg verwenden (mit einheitlichem internem Dokumentmodell). |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Stellt eine Klasse mit abstrakter Methode dar, die normalerweise von der Aufrufseite bereitgestellt wird und Fortschrittsereignisse verarbeitet, die vom Konverter kommen. In der Regel kann ein solcher bereitgestellter Kunden-Handler verwendet werden, um den gesamten Konvertierungsfortschritt in der Konsole oder in einer Fortschrittsanzeige anzuzeigen. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Diese Klasse stellt Informationen über den Konvertierungsfortschritt dar, die in einer externen Anwendung verwendet werden können, um den Fortschritt dem Endbenutzer anzuzeigen. |
| [WarningCallback](./warningcallback/) | Schnittstelle zur Unterstützung des Callback-Mechanismus des Benutzers. |
| [WarningInfo](./warninginfo/) | Unveränderliches Objekt zur Kapselung von Warninformationen. |
| [WarningType](./warningtype/) | / * Enum repräsentierter Warnungstyp. / * / |
| [Watermark](./watermark/) | Stellt ein Wasserzeichen der Seite dar. |
| [WatermarkAnnotation](./watermarkannotation/) | Klasse beschreibt das Watermark-Annotationsobjekt. |
| [WatermarkArtifact](./watermarkartifact/) | Klasse beschreibt das Wasserzeichen-Artefakt. Dies kann verwendet werden, um |
| [WebHyperlink](./webhyperlink/) | Stellt ein Web-Hyperlink-Objekt dar. |
| [WidgetAnnotation](./widgetannotation/) | Klasse, die eine Widget-Annotation darstellt. |
| [XFA](./xfa/) | Stellt ein XML-Formular in Bezug auf die XML Forms Architecture (XFA) dar. |
| [XfaParserOptions](./xfaparseroptions/) | Klasse zur Handhabung der zugehörigen Datenkapselung |
| [XfdfReader](./xfdfreader/) | <p> Klasse, die das Lesen des XFDF-Formats durchführt. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Aggregiert Methoden zum Schreiben von Anmerkungen und Feldern in das XFDF-Dateiformat. |
| [XForm](./xform/) | Klasse stellt XForm dar |
| [XFormCollection](./xformcollection/) | Klasse stellt eine Sammlung von XFormCollection dar. |
| [XImage](./ximage/) | Klasse, die ein Bild-X-Objekt darstellt. |
| [XImage.RawParameters](./ximage.rawparameters/) | Klasse, die rohe XImage-Parameter eines Bildes darstellt. |
| [XImageCollection](./ximagecollection/) | Klasse, die eine XImage-Sammlung darstellt. |
| [XmlLoadOptions](./xmlloadoptions/) | Stellt Optionen zum Laden/Importieren einer XML-Datei in ein PDF-Dokument dar. |
| [XmlSaveOptions](./xmlsaveoptions/) | Speicheroptionen für den Export in das XML-Format |
| [XmpField](./xmpfield/) | Stellt ein XMP-Feld dar. |
| [XmpFieldType](./xmpfieldtype/) | Dieses Enum stellt Typen eines XMP-Feldes dar. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Eigenschaftskategorie: intern oder extern. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Dieses Schema beschreibt ein Feld in einem strukturierten Typ. Es ist dem PDF/A Property Value Type Schema sehr ähnlich, definiert jedoch ein Feld in einer Struktur anstelle einer Eigenschaft. Schema-Namespace-URI: http://www.aiim.org/pdfa/ns/field# Erforderliches Schema-Namespace-Präfix: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Stellt die Basisklasse für Feld-, Eigenschaft- und Werttyp-Instanzen dar. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Beschreibt eine einzelne Eigenschaft. Schema-Namespace-URI: http://www.aiim.org/pdfa/ns/property# Erforderliches Schema-Namespace-Präfix: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Beschreibt das XMP-Erweiterungsschema, das von PDF/A-1 bereitgestellt wird. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Stellt die Beschreibung des XMP-Erweiterungsschemas dar, das von PDF/A-1 bereitgestellt wird. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | Das PDF/A ValueType Schema ist für alle Eigenschaftswerttypen erforderlich, die nicht in der XMP‑2004‑Spezifikation definiert sind, d. h. für Werttypen außerhalb der folgenden Liste: - Array‑Typen (dies sind Containertypen, die ein oder mehrere Felder enthalten können): Alt, Bag, Seq - Grundwerttypen: Boolean, (offene und geschlossene) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media‑Management‑Werttypen: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundlegender Job/Workflow‑Werttyp: Job - EXIF‑Schema‑Werttypen: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema-Namespace-URI: http://www.aiim.org/pdfa/ns/type# Erforderliches Schema-Namespace-Präfix: pdfaType |
| [XmpValue](./xmpvalue/) | Stellt XMP‑Wert dar |
| [XpsLoadOptions](./xpsloadoptions/) | Stellt Optionen zum Laden/Importieren von XPS‑Dateien in ein PDF‑Dokument dar. |
| [XpsSaveOptions](./xpssaveoptions/) | Speicheroptionen für den Export ins XPS‑Format |
| [XslFoLoadOptions](./xslfoloadoptions/) | Stellt Optionen zum Laden/Importieren von XSL‑FO‑Dateien in ein PDF‑Dokument dar. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit solchen Formatierungsfehlern. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (left, top) an der oberen linken Ecke des Fensters anzeigt und den Seiteninhalt um den Zoom‑Faktor vergrößert. Ein Nullwert für einen der Parameter left, top oder zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. Ein Zoom‑Wert von 0 hat die gleiche Bedeutung wie ein Nullwert. </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Beschreibung |
| --- | --- |
| [AFRelationship](./afrelationship/) | Die Aufzählung beschreibt die Beziehung zu zugehörigen Dateien. |
| [AnnotationState](./annotationstate/) | Die Aufzählung der Zustände, auf die die ursprüngliche Anmerkung gesetzt werden kann. |
| [AnnotationStateModel](./annotationstatemodel/) | Das Zustandsmodell, das dem Zustand der Anmerkung entspricht. |
| [AnnotationType](./annotationtype/) | Aufzählung der Anmerkungstypen. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Aufzählung möglicher Artefakt‑Untertypen. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Aufzählung möglicher Artefakt‑Typen. |
| [BlendMode](./blendmode/) | Die Aufzählung der Mischmodi. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumeriert die Eckstilarten für den Rand. |
| [BorderEffect](./bordereffect/) | Beschreibt den Effekt, der auf den Rand der Anmerkungen angewendet werden soll. |
| [BorderStyle](./borderstyle/) | Beschreibt den Stil des Anmerkungsrandes. |
| [BoxStyle](./boxstyle/) | Stellt Stile zum Zeichnen von Häkchen in Kontrollkästchen dar. |
| [CapStyle](./capstyle/) | Stil des Zeilenendes der Ink-Anmerkungszeile. |
| [CaptionPosition](./captionposition/) | Aufzählung der Positionierung der Beschriftung der Anmerkung. |
| [CaretSymbol](./caretsymbol/) | Ein Symbol, das mit dem Caret verknüpft werden soll. |
| [ColorsOfCMYK](./colorsofcmyk/) | Farben, die im CMYK-Farbmodell enthalten sind. |
| [ColorSpace](./colorspace/) | Die Aufzählung der Farbräume. |
| [ColorType](./colortype/) | Gibt den Farbtyp von Elementen auf der Seite an. |
| [ColumnAdjustment](./columnadjustment/) | Aufzählen von Spaltenanpassungstypen. |
| [ContentDisposition](./contentdisposition/) | MIME-Protokoll Content-Disposition-Header. |
| [ConvertErrorAction](./converterroraction/) | Diese Klasse stellt eine Aktion für Konvertierungsfehler dar. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Diese Aktion stellt Aktionen für die Konvertierung von Bildern mit Softmask dar. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Diese Klasse stellt eine Aktion für die Konvertierung von Transparenz dar. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Stellt den Typ eines kryptografischen Algorithmus dar, der in Verschlüsselungs-/Entschlüsselungsroutinen verwendet wird. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * Der {@code Aspose.Pdf.Security } Namespace enthält Klassen, die für Verschlüsselung und digitale Signatur verwendet werden. / * / |
| [DefaultState](./defaultstate/) | Stellt den Standardzustand einer PDF-Ebene dar. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Stellt den Typ eines Algorithmus dar, der Daten auf einen "Hash" abbildet |
| [Direction](./direction/) | Textausrichtung. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Die Zugriffsberechtigungen, die für dieses Dokument gewährt werden. Gültige Werte sind: 1 - Keine Änderungen am Dokument sind erlaubt; jede Änderung am Dokument macht die Signatur ungültig. 2 - Erlaubte Änderungen sind das Ausfüllen von Formularen, das Instanziieren von Seitenvorlagen und das Signieren; andere Änderungen machen die Signatur ungültig. 3 - Erlaubte Änderungen entsprechen denen von 2, zusätzlich das Erstellen, Löschen und Ändern von Anmerkungen; andere Änderungen machen die Signatur ungültig. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Ermöglicht die Angabe des .doc- oder .docx-Dateiformats. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Ermöglicht die Steuerung, wie ein PDF-Dokument in ein Textverarbeitungsdokument konvertiert wird. Verwenden Sie den Modus RecognitionMode.Textbox, wenn das resultierende Dokument nicht stark weiter bearbeitet werden soll. Textfelder lassen sich leicht ändern, wenn nicht viel zu tun ist. Verwenden Sie den Modus RecognitionMode.Flow, wenn das Ausgabedokument weitere Bearbeitung benötigt. Absätze und Textzeilen im Flow-Modus ermöglichen eine einfache Textbearbeitung, jedoch sehen nicht unterstützte Formatierungsobjekte schlechter aus als im RecognitionMode.Textbox-Modus. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | Wenn eine PDF-Datei (die normalerweise ein festes Layout hat) konvertiert wird, versucht die Konvertierungsengine, Gruppierungen und mehrstufige Analysen durchzuführen, um die Absicht des ursprünglichen Dokumentautors wiederherzustellen und ein Ergebnis im Flow-Layout zu erzeugen. Diese Eigenschaft stellt diese Konvertierung für die gewünschte Methode der Inhaltserkennung ein. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Zählt die Typen expliziter Ziele auf. |
| [ExtendedBoolean](./extendedboolean/) | Stellt einen Booleschen Typ dar, der den Undefined-Wert unterstützt. |
| [ExtractImageMode](./extractimagemode/) | Definiert verschiedene Modi, die beim Extrahieren von Bildern aus Dokumenten verwendet werden können. |
| [FileEncoding](./fileencoding/) | Kodierung der angehängten Datei. Mögliche Werte: Zip – Datei ist mit ZIP komprimiert, None – Datei ist nicht komprimiert. |
| [FileIcon](./fileicon/) | Ein Symbol, das bei der Anzeige der Anmerkung verwendet wird. |
| [Fixup](./fixup/) | Dieses Enum stellt einen Typ von Fixup dar. |
| [FormType](./formtype/) | Aufzählung der möglichen Typen von Acro Form. |
| [FreeTextIntent](./freetextintent/) | Enumeriert die Absichten der Freitext-Anmerkung. |
| [HighlightingMode](./highlightingmode/) | Enumeriert den Hervorhebungsmodus der Anmerkung, den visuellen Effekt, der verwendet wird, wenn die Maustaste im aktiven Bereich gedrückt oder gehalten wird. |
| [HorizontalAlignment](./horizontalalignment/) | Beschreibt die horizontale Ausrichtung. |
| [HtmlDocumentType](./htmldocumenttype/) | Stellt eine Aufzählung der HTML-Dokumenttypen dar. |
| [HtmlMediaType](./htmlmediatype/) | Gibt mögliche Medientypen an, die beim Rendern verwendet werden. |
| [IconCaptionPosition](./iconcaptionposition/) | Beschreibt die Position des Symbols. |
| [ImageFileType](./imagefiletype/) | Enumeriert die Bilddateitypen. |
| [ImageFilterType](./imagefiltertype/) | Aufzählung, die den Bildfiltertyp darstellt. |
| [ImageFormat](./imageformat/) | Dieses Enum stellt Bildformate dar. |
| [ImportFormat](./importformat/) | Gibt das Importformat an. |
| [Justification](./justification/) | Enumeriert die Formen der Ausrichtung (Justierung), die bei der Anzeige des Anmerkungstextes verwendet werden. |
| [LaunchActionOperation](./launchactionoperation/) | Enumeriert die Vorgänge, die beim Ausführen der Startaktion mit dem Dokument durchgeführt werden sollen. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Es enumeriert mögliche Modi zur Positionierung von Buchstaben in Wörtern im resultierenden HTML. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: Menge von Beleuchtungsschema-Typen. |
| [LineEnding](./lineending/) | Enumeriert die Endstilarten für Linien, die beim Zeichnen der Linie verwendet werden. |
| [LineIntent](./lineintent/) | Enumeriert die Absichten der Linien-Anmerkung. |
| [LoadFormat](./loadformat/) | Gibt das Ladeformat an. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Wert, der angibt, in welcher Weise Bruchwerte angezeigt werden. |
| [NumberingStyle](./numberingstyle/) | Aufzählung des unterstützten Seitenzahlenstils für die Klasse PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Gibt die Position in einem Stream an, die zum Suchen verwendet wird. |
| [PageCoordinateType](./pagecoordinatetype/) | Beschreibt den Seitencoordinate-Typ. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Beschreibt das Seitenlayout. |
| [PageMode](./pagemode/) | Klasse beschreibt die verwendeten Komponenten der Dokumentenseite. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Gibt die Variante zur Bestimmung des Standorts des Elements auf der Seite an. |
| [PasswordType](./passwordtype/) | Dieses Enum stellt bekannte Passworttypen dar, die für passwortgeschützte PDF-Dokumente verwendet werden. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: Menge von 3D-Anmerkungsaktivierungsmodi. |
| [PdfFormat](./pdfformat/) | Diese Klasse stellt ein PDF-Format dar. |
| [PdfVersion](./pdfversion/) | Dieses Enum stellt die Version einer PDF-Datei dar. |
| [PolyIntent](./polyintent/) | Enumeriert die Absichten der Polygon- oder Polylinien-Anmerkung. |
| [PredefinedAction](./predefinedaction/) | Definiert verschiedene Aktionen, die aus einer PDF-Datei ausgelöst werden können. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Stellt eine Position einer Markierung in einer Ecke einer Seite dar. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Stellt eine Position einer Registrierungsmarkierung auf einer Seite dar. |
| [ReplyType](./replytype/) | Enumeriert die Arten von Beziehungen (den "Antworttyp") zwischen der Anmerkung und einer, die durch InReplyTo angegeben ist. |
| [ReturnAction](./returnaction/) | Enum stellte eine Programmarbeitsablauf-Aktion dar, falls die Methode {@code IWarningCallback.Warning(WarningInfo)} aufgerufen wird. |
| [Rotation](./rotation/) | Aufzählung möglicher Rotationswerte. |
| [SaveFormat](./saveformat/) | Gibt das Format an |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Stellt Linientypen dar, die im Ergebnisdokument zum Zeichnen von Rahmen oder anderen Linien verwendet werden können |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | Enumeriert mögliche Typen gespeicherter externer Ressourcen |
| [StampIcon](./stampicon/) | Enumeriert die Symbole, die bei der Anzeige der Annotation verwendet werden. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | Enumeriert mögliche Typen von Bilddateien, die während der PDF-zu-SVG-Konvertierung als externe Ressourcen gespeichert werden können |
| [TextAlignment](./textalignment/) | Ausrichtung des Textes in der Anmerkung. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Verarbeitungsmodi für Beschneidungspfade |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Verhalten beim Ersetzen von Schriftarten. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Sprachtransformationsmodi |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Aktion, die ausgeführt wird, wenn die Schriftart das erforderliche Zeichen nicht enthält |
| [TextRenderingMode](./textrenderingmode/) | Der Textdarstellungsmodus, Tmode, bestimmt, ob das Anzeigen von Text dazu führt, dass Glyphenkonturen gestrichelt, gefüllt, als Beschneidungsgrenze verwendet werden oder eine Kombination dieser drei Optionen. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Gibt eine Richtlinie dafür an, wie die Schriftgröße von Text angepasst werden soll, um in einen umgebenden Bereich zu passen. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Geltungsbereich, in dem die Ersetzungs-Text-Operation angewendet wird; standardmäßig REPLACE_FIRST. Diese veraltete Option wurde aus Kompatibilitätsgründen beibehalten. Sie wirkt sich auf PdfContentEditor aus und hat keine Wirkung auf TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Aufzählung möglicher vertikaler Ausrichtungswerte. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
