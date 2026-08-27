---
title: "com.aspose.pdf"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le com.aspose.pdf est un package racine pour toutes les classes de la bibliothèque Aspose.PDF pour Java qui sont soit directement dedans comme Document, soit indirectement via plusieurs sous‑packages."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf/
---
Le com.aspose.pdf est un package racine pour toutes les classes de la bibliothèque Aspose.PDF pour Java qui sont soit directement dedans comme Document, soit indirectement via plusieurs sous‑packages.

## Interfaces

| Interface | Description |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | La procédure de rappel pour la reconnaissance hocr. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | La procédure de rappel pour la reconnaissance hocr. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | La procédure de rappel pour la reconnaissance hocr. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Contient des fonctionnalités pour ajuster les polices |
| [IAnnotationVisitor](./iannotationvisitor/) | Définit le visiteur pour parcourir différentes annotations de document. |
| [IAppointment](./iappointment/) | Représente une interface générale pour les actions et les destinations. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Interface pour les stratégies de conversion d'espace colorimétrique. |
| [IDocument](./idocument/) | interface représentant un document PDF |
| [IFontOptions](./ifontoptions/) | Propriétés utiles pour ajuster le comportement des polices |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Cette interface est déclarée pour la personnalisation des algorithmes de quantification. Les utilisateurs peuvent implémenter leur propre réalisation de ces algorithmes (par exemple des algorithmes basés sur du code non géré). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Cette interface est déclarée pour la personnalisation des algorithmes de quantification. Les utilisateurs peuvent implémenter leur propre réalisation de ces algorithmes (par exemple des algorithmes basés sur du code non géré). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Définit le visiteur pour parcourir différents opérateurs PDF. |
| [IPageSetOptions](./ipagesetoptions/) | Définit les options de conversion liées à un ensemble de pages à convertir. |
| [IPipelineOptions](./ipipelineoptions/) | Définit les options de conversion liées à la configuration du pipeline. |
| [ITableElement](./itableelement/) | Cette interface représente un élément d'un tableau existant extrait par TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.PDf dans le cloud, l'accès direct aux fichiers référencés est impossible, et du code personnalisé placé dans une méthode spéciale doit être utilisé. Ce délégué définit la signature d'une telle méthode personnalisée. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Définir le drapeau indiquant si le dossier temporaire sera utilisé pour héberger les données de police temporaires. / * Vrai par défaut. / * Utilise la mémoire du tas si valeur = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | À la propriété de ce type, vous pouvez affecter un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de l'enregistrement externe d'une image extraite d'un SVG généré à partir d'un PDF et qui doit être sauvegardée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme un enregistrement fait maison dans un flux ou sur disque) peut être effectué dans ce code personnalisé et ce code doit renvoyer un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite intégré dans le SVG généré à la place du chemin original supposé de la ressource image. Dans ce cas, toutes les actions nécessaires à l'enregistrement de l'image doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s'il n'existait aucun code personnalisé externe. |
## Classes

| Classe | Description |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Représente une cellule de tableau qui existe sur la page |
| [AbsorbedRow](./absorbedrow/) | Représente une ligne de tableau qui existe sur la page |
| [AbsorbedTable](./absorbedtable/) | Représente un tableau qui existe sur la page |
| [ActionCollection](./actioncollection/) | Collection d'actions |
| [Annotation](./annotation/) | Classe représentant un objet d'annotation. |
| [AnnotationActionCollection](./annotationactioncollection/) | Représente la collection d'actions d'annotation. |
| [AnnotationCollection](./annotationcollection/) | Classe représentant une collection d'annotations. |
| [AnnotationFlags](./annotationflags/) | Drapeaux Un ensemble de drapeaux binaires spécifiant diverses caractéristiques de l'annotation. |
| [AnnotationSelector](./annotationselector/) | Cette classe est utilisée pour sélectionner des annotations en utilisant le concept de modèle Visitor. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Classe pour le rendu du texte normal et enrichi. |
| [AppearanceDictionary](./appearancedictionary/) | Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page. |
| [ApsLoadOptions](./apsloadoptions/) | Classe décrivant les options de chargement APS. Option d'importation depuis le format APS XML. |
| [ApsSaveOptions](./apssaveoptions/) | Options d'enregistrement pour l'exportation au format APS XML. |
| [ApsToFlowConverter](./apstoflowconverter/) | Conversion APS vers Flow |
| [Artifact](./artifact/) | Classe représentant un objet PDF Artifact. |
| [ArtifactCollection](./artifactcollection/) | Classe représentant une collection d'artifacts. |
| [AutoTaggingSettings](./autotaggingsettings/) | Fournit les paramètres pour la fonctionnalité de balisage automatique dans les documents PDF. La classe {@link AutoTaggingSettings} permet de configurer les options de balisage automatique du contenu PDF. Elle comprend des propriétés pour activer ou désactiver le balisage automatique, spécifier une stratégie de reconnaissance des titres, et définir les niveaux de titres en fonction des tailles de police. |
| [BackgroundArtifact](./backgroundartifact/) | Classe décrivant l'artifact d'arrière-plan. Cet artifact permet de définir l'arrière-plan de la page. |
| [BarcodeField](./barcodefield/) | Classe représentant un champ de code-barres. |
| [BaseActionCollection](./baseactioncollection/) | Classe encapsulant les actions de base avec les actions interactives de page/annotation/champ |
| [BaseOperatorCollection](./baseoperatorcollection/) | Représente la classe de base pour la collection d'opérateurs. |
| [BaseParagraph](./baseparagraph/) | Représente un objet de base abstrait pouvant être ajouté à la page (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | La classe décrit l'artifact de numérotation Bates. |
| [BitmapInfo](./bitmapinfo/) | Objet contenant un tableau de pixels et des informations bitmap. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Format de pixel bitmap. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Représente une annotation de repère de débordement. Les repères de débordement sont placés aux coins d'une page imprimée pour indiquer où la page doit être découpée et jusqu'à quel point elle peut s'écarter des marques de coupe. |
| [Border](./border/) | Classe représentant les caractéristiques de la bordure de l'annotation. |
| [BorderInfo](./borderinfo/) | Cette classe représente la bordure pour les éléments graphiques. |
| [BorderSide](./borderside/) | Les drapeaux énumèrent les côtés de la bordure en binaire. |
| [BorderStyleConverter](./borderstyleconverter/) | Représente la classe BorderStyleConverter |
| [Brush](./brush/) | Cette classe représente un pinceau abstrait |
| [BuildVersionInfo](./buildversioninfo/) | Cette classe fournit des informations sur la version actuelle du produit. |
| [ButtonField](./buttonfield/) | Classe représentant le champ bouton poussoir. |
| [CaretAnnotation](./caretannotation/) | Classe représentant l'annotation de caret. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Représente la classe CaretSymbolConverter |
| [CdrLoadOptions](./cdrloadoptions/) | Classe décrivant les options de chargement CDR. |
| [Cell](./cell/) | Représente une cellule de la ligne du tableau. |
| [Cells](./cells/) | Représente une collection de cellules d'une ligne. |
| [CgmImportOptions](./cgmimportoptions/) | Option d'importation depuis le format Computer Graphics Metafile (CGM). |
| [CgmLoadOptions](./cgmloadoptions/) | Contient des options pour charger/importer un fichier CGM dans un document PDF. |
| [Characteristics](./characteristics/) | Représente les caractéristiques de l'annotation |
| [CharInfo](./charinfo/) | Représente un objet d'information de caractère. Fournit des informations de positionnement des caractères. |
| [CharInfoCollection](./charinfocollection/) | <p> Représente la collection d'objets CharInfo. </p> <hr> <pre> L'exemple montre comment parcourir tous les caractères et récupérer le caractère //ouvrir le document Document pdfDocument = new Document(inFile); //créer l'objet TextFragmentAbsorber pour collecter tous les objets texte de la page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accepter l'absorbeur pour toutes les pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //obtenir les fragments de texte extraits TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //boucler sur les fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //boucler sur les segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //boucler sur les caractères {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); //afficher les informations de position et de rectangle du caractère System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Fournit l'accès aux informations de positionnement des caractères du segment de texte. </p> |
| [CheckboxField](./checkboxfield/) | Classe représentant le champ case à cocher. |
| [ChoiceField](./choicefield/) | Représente la classe de base pour les champs de choix. |
| [CircleAnnotation](./circleannotation/) | Classe représentant l'annotation Cercle. |
| [Collection](./collection/) | Représente la classe pour Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Représente une classe de champ de schéma de collection de documents. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Représente le paramètre de sous-type d'un champ dans une collection de schéma. |
| [CollectionItem](./collectionitem/) | Représente une classe d'élément de collection. L'élément de collection contient les données décrites par le schéma de la collection. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Représente une classe pour une valeur d'élément de collection. |
| [CollectionSchema](./collectionschema/) | Représente une classe qui décrit le \"Schéma\" d'une collection de documents. |
| [Color](./color/) | Représente une classe pour la valeur de couleur qui peut être exprimée dans différents espaces colorimétriques. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe représentant l'annotation ColorBarAnnotation. La propriété Color est ignorée, à la place la couleur ColorsOfCMYK est utilisée. Lors de la création, le rapport entre la largeur et la hauteur détermine l'orientation de l'annotation – horizontale ou verticale. Ensuite, il vérifie que le rectangle de l'annotation se trouve à l'extérieur du TrimBox, et si ce n'est pas le cas, il est déplacé vers l'emplacement le plus proche à l'extérieur du TrimBox, en tenant compte de l'orientation de l'annotation. Il est possible de réduire la largeur (ou la hauteur) afin que l'annotation tienne à l'extérieur du TrimBox. S'il n'y a pas d'espace pour la mise en page, la largeur/hauteur peut être mise à zéro (dans ce cas, l'annotation est présente sur la page, mais n'est pas affichée). |
| [ColumnInfo](./columninfo/) | Cette classe représente les informations d'une colonne. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Classe représentant des événements |
| [ComboBoxField](./comboboxfield/) | Classe représentant le champ Combobox du formulaire. |
| [ComHelper](./comhelper/) | <p> Fournit des méthodes pour les clients COM afin de charger un document dans Aspose.PDF. </p> <hr> <p> Utilisez la classe ComHelper pour charger un document depuis un fichier ou un flux dans un objet Document dans une application COM. La classe Document fournit un constructeur par défaut pour créer un nouveau document et propose également des constructeurs surchargés pour charger un document depuis un fichier ou un flux. Si vous utilisez Aspose.Words depuis une application .NET, vous pouvez utiliser directement tous les constructeurs de Document, mais si vous utilisez Aspose.PDF depuis une application COM, seul le constructeur par défaut de Document est disponible. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe abstraite représentant une annotation de figure commune. |
| [CompositingParameters](./compositingparameters/) | Représente un objet contenant les paramètres de composition graphique de l'état graphique actuel. |
| [ContentsAppender](./contentsappender/) | Effectue des modifications du contenu uniquement en mode APPEND. Ce mode permet d'éviter l'analyse inutile et lourde du contenu avant qu'une modification ne soit apportée. Il ajoute seulement de nouveaux opérateurs à la fin ou au début du contenu. |
| [Copier](./copier/) | Classe pour la copie d'objet. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Représente les types d'annotation placés dans les coins de la page imprimée. |
| [CustomExplicitDestination](./customexplicitdestination/) | Représente une destination explicite personnalisée. |
| [CustomSign](./customsign/) | Délégué pour la signature personnalisée du document (Beta). |
| [Dash](./dash/) | Classe représentant le motif de tirets de ligne. |
| [DateField](./datefield/) | Champ de date avec vue calendrier. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Décrit l'apparence par défaut du champ (police, taille du texte et couleur). |
| [DefaultDirectory](./defaultdirectory/) | Spécifie le chemin par défaut à des fins diverses |
| [DestinationCollection](./destinationcollection/) | Classe représentant la collection de toutes les destinations (un arbre de noms associant des chaînes de noms aux destinations (voir 12.3.2.3, \"Named Destinations\") et (voir 7.7.4, \"Name Dictionary\")) dans le document PDF. |
| [DestinationFactory](./destinationfactory/) | Représente la classe DestinationFactory |
| [DjvuLoadOptions](./djvuloadoptions/) | Classe décrivant les options de chargement DJVU. |
| [DocMDPSignature](./docmdpsignature/) | Représente la classe du type de signature de document MDP (détection et prévention de modification). |
| [DocSaveOptions](./docsaveoptions/) | Options d'enregistrement pour l'exportation au format Doc |
| [Document](./document/) | Classe représentant un document PDF. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Classe décrivant l'algorithme d'optimisation de document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources(). @deprecated Cette classe est obsolète. Veuillez utiliser com.aspose.pdf.optimization.OptimizationOptions à la place. |
| [Document.RepairOptions](./document.repairoptions/) | Représente les options de réparation d'un document PDF. Cette classe offre un moyen de personnaliser le processus de réparation d'un document PDF. |
| [DocumentActionCollection](./documentactioncollection/) | Classe décrivant les actions effectuées sur certaines actions avec le document |
| [DocumentExtensions](./documentextensions/) | Fournit des capacités supplémentaires pour la classe Document. |
| [DocumentFactory](./documentfactory/) | Classe qui permet de créer/charger des documents de différents types. |
| [DocumentInfo](./documentinfo/) | Représente les métadonnées d'un document PDF. |
| [DocumentWeb](./documentweb/) | Représente la classe DocumentWeb |
| [Element](./element/) | Classe représentant l'élément de base de la structure logique. |
| [ElementCollection](./elementcollection/) | Collection d'éléments de base de la structure logique. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Classe représentant la collection de fichiers intégrés. |
| [EncryptedPayload](./encryptedpayload/) | Représente la charge utile chiffrée dans la spécification du fichier. |
| [EpubLoadOptions](./epubloadoptions/) | Contient les options de chargement/importation d'un fichier EPUB dans un document PDF. |
| [EpubSaveOptions](./epubsaveoptions/) | Options d'enregistrement pour l'exportation au format EPUB |
| [ExcelSaveOptions](./excelsaveoptions/) | Options d'enregistrement pour l'exportation au format Excel |
| [ExplicitDestination](./explicitdestination/) | Représente la classe de base pour les destinations explicites dans un document PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Représente la classe ExplicitDestinationTypeConverter |
| [ExportFieldsOptions](./exportfieldsoptions/) | Représente la classe de base des options d'exportation des champs de formulaire. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Représente les options d'exportation des champs de formulaire au format Json. Hérite de {@link ExportFieldsOptions} et ajoute des options spécifiques pour l'exportation Json. |
| [ExportImportMessages](./exportimportmessages/) | Contient divers messages d'erreur pour les opérations d'exportation et d'importation des champs de formulaire. |
| [ExternalSignature](./externalsignature/) | Crée une signature détachée PKCS#7Detached en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables. |
| [FdfReader](./fdfreader/) | Classe qui effectue la lecture du format FDF. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | Classe de base pour les champs de formulaire acro. |
| [FieldSerializationResult](./fieldserializationresult/) | Représente le résultat d'un processus de sérialisation de champ de formulaire. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Représente l'état de la sérialisation du champ de formulaire. |
| [FieldValueType](./fieldvaluetype/) | Représente le type de valeur de champ dans une collection de schéma. |
| [FigureElement](./figureelement/) | Classe représentant la figure de structure logique. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe décrivant l'annotation de pièce jointe de fichier. |
| [FileFontSource](./filefontsource/) | Représente une source de fichier de police unique. |
| [FileHyperlink](./filehyperlink/) | Représente un objet de lien hypertexte de fichier. |
| [FileIconConverter](./fileiconconverter/) | Représente la classe FileIconConverter |
| [FileParams](./fileparams/) | Définit un dictionnaire de paramètres de fichier intégré qui doit contenir des informations supplémentaires spécifiques au fichier. |
| [FileSelectBoxField](./fileselectboxfield/) | Champ pour l'élément de boîte de sélection de fichier. |
| [FileSpecification](./filespecification/) | Classe représentant le fichier intégré. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs de zoom horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la boîte englobante dans la fenêtre dans l'autre dimension. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur entière de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur entière de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitExplicitDestination](./fitexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que la page entière tienne dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs de zoom horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la page dans la fenêtre dans l'autre dimension. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur entière de la page tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées left, bottom, right et top tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs de zoom horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur entière de la page tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FixedPrint](./fixedprint/) | Représente les données d'impression fixes de l'annotation de filigrane. |
| [FloatingBox](./floatingbox/) | Représente un FloatingBox dans un document Pdf. FloatingBox est positionné de façon personnalisée. |
| [FlowConverter](./flowconverter/) | Convertir le document PDF en formats Flow (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX en mode EnchanedFlow, TableAbsorber en mode FlowEngine. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Transmission de données de la bibliothèque Flow vers TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Représente le dossier qui contient les fichiers de police. |
| [Font](./font/) | <p> Représente l'objet police. </p> <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et modifier la police de la première occurrence trouvée. // Ouvrir le document Document doc = new Document(\"input.pdf\"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Créer la police et la marquer pour être incorporée Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Enregistrer le document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Représente un objet absorbeur de polices. Effectue la recherche de polices et fournit l'accès aux résultats de recherche via la collection {@code FontAbsorber.Fonts}. |
| [FontCollection](./fontcollection/) | <p> Représente une collection de polices. </p> <hr> <pre> L'exemple montre comment rendre toutes les polices déclarées sur la page incorporées. // Ouvrir le document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // s'assurer que toutes les polices déclarées dans les ressources de la page sont incorporées // noter que si les polices sont déclarées dans les ressources de formulaire, elles ne sont pas accessibles depuis les ressources de la page for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save(\"D:\\\\Tests\\\\input.pdf\"); </pre> <hr> <p> Les collections de polices représentées par la classe {@code FontCollection} sont utilisées dans plusieurs scénarios. Par exemple, dans les ressources avec la propriété {@code Resources.Fonts}. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | La norme PDF/A exige que toutes les polices soient incorporées dans le document. Cette classe inclut des indicateurs pour les cas où il n'est pas possible d'incorporer une police parce que cette police est absente sur le PC de destination. |
| [FontRepository](./fontrepository/) | <p> Effectue une recherche de police. Recherche parmi les polices installées sur le système et les polices PDF standard. Fournit également la fonctionnalité d'ouvrir des polices personnalisées. </p> <hr> <pre> L'exemple montre comment trouver une police et remplacer la police du texte de la première page. // Trouver la police Font font = FontRepository.findFont(\"Arial\"); // Ouvrir le document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Enregistrer le document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Représente une classe de base pour la source de police. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Spécifie les informations de style appliquées au texte. </p> <hr> <p> Cette énumération possède un attribut {@code FlagsAttribute} qui permet une combinaison de ses valeurs membres. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag énumère les stratégies de sous-ensemble de police |
| [FooterArtifact](./footerartifact/) | Décrit l'artefact de pied de page. Cela peut être utilisé pour définir le pied de page de la page. |
| [Form](./form/) | Classe représentant l'objet formulaire. |
| [Form.FlattenSettings](./form.flattensettings/) | Classe qui décrit les paramètres de la procédure d'aplatissement du formulaire. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Les formulaires peuvent contenir des informations de signature et peuvent être signés ou non signés. Parfois, la vue des formulaires dans le visualiseur doit dépendre du fait que le formulaire soit signé ou non. Cette énumération énumère les modes de rendu possibles lors de la conversion du type de formulaire en fonction de la signature. |
| [FormattedFragment](./formattedfragment/) | Représente un fragment formaté abstrait. |
| [FreeTextAnnotation](./freetextannotation/) | Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé ; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible. |
| [GoToAction](./gotoaction/) | Représente une action d'aller à qui modifie la vue vers une destination spécifiée (page, emplacement et facteur de zoom). |
| [GoToRemoteAction](./gotoremoteaction/) | Représente une action d'aller à distante similaire à une action d'aller à ordinaire mais qui saute vers une destination dans un autre fichier PDF au lieu du fichier actuel. |
| [GoToURIAction](./gotouriaction/) | Représente une action URI qui entraîne la résolution d'un URI. |
| [GraphInfo](./graphinfo/) | Représente les informations graphiques. |
| [Group](./group/) | Une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparent. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | La classe décrit l'artéfact Heaader. Cet artifacgt peut être utilisé pour définir l'en-tête de la page. |
| [HeaderFooter](./headerfooter/) | La classe représente la page pdf d'en-tête ou de pied de page. |
| [Heading](./heading/) | Représente l'en-tête. |
| [HideAction](./hideaction/) | Représente une action de masquage qui masque ou affiche une ou plusieurs annotations à l'écran en définissant ou en effaçant leurs drapeaux Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Représente une annotation de surlignage qui met en évidence une plage de texte dans le document. |
| [HtmlFragment](./htmlfragment/) | Représente un fragment html. |
| [HtmlLoadOptions](./htmlloadoptions/) | Représente les options de chargement/importation d'un fichier html dans un document pdf. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Le drapeau binaire spécifie des drapeaux qui, combinés à d'autres options, déterminent les tailles et la mise en page des pages. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Options d'enregistrement pour l'exportation au format Html |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Cette énumération décrit les mesures d'anticrénelage possibles pendant la conversion |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Cette classe représente un ensemble de données liées à l'enregistrement personnalisé de CSS pendant la conversion de PDF au format HTML |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Vous pouvez affecter à cette propriété une stratégie personnalisée qui implémente le traitement et/ou l'enregistrement d'une partie de CSS créée lors de la conversion de PDF en HTML. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur disque) doit être effectué dans ce code personnalisé |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente la création de l'URL du CSS référencé dans le document HTML généré. Par ex., si vous souhaitez que le CSS soit référencé dans le HTML, par ex. comme "otherPage.ASPX?CssID=zjjkklj", alors cette stratégie personnalisée doit renvoyer "otherPage.ASPX?CssID=zjjkklj" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Représente un ensemble de données liées à la requête du convertisseur vers le code personnalisé visant à obtenir l'URL souhaitée (ou le modèle d'URL) du CSS concerné |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Cette énumération définit les règles qui ajustent la logique d'encodage |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Énumère les modes pouvant être utilisés pour l'enregistrement des polices référencées dans le PDF enregistré. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion de PDF en HTML. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | Énumère les types possibles de fichiers image pouvant être enregistrés comme ressources externes pendant la conversion de Pdf en Html. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Parfois, des exigences spécifiques pour le HTML créé sont présentes. Cette énumération définit les modes de préparation du HTML qui peuvent être utilisés lors de la conversion de PDF en HTML afin de répondre à ces exigences spécifiques. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Si la propriété SplitToPages de HtmlSaveOptions est activée, plusieurs fichiers HTML (un fichier HTML par page convertie) sont créés lors de la conversion de PDF en HTML. Cette classe représente un ensemble de données liées à l'enregistrement personnalisé du balisage d'une page HTML pendant la conversion de PDF en HTML. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Le résultat de la conversion peut contenir une ou plusieurs pages HTML (qui peuvent également référencer des fichiers externes tels que des images ou des polices). Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la page HTML obtenue (le HTML lui‑même) qui a été créée lors de la conversion. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires à l'enregistrement du balisage de la page HTML doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement de ce cas ou de celui‑ci doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même, comme si aucun code d'enregistrement personnalisé externe n'existait. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Énumère les types possibles de parents d'image ; l'image peut appartenir à une page HTML ou à une image parent SVG. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Cette énumération énumère les modes possibles d'intégration des fichiers référencés dans le HTML. Elle permet de contrôler si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou générés comme des entités binaires séparées. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | Le PDF converti peut contenir des images raster (.png, *.jpeg, etc.). Cette énumération définit les méthodes de gestion des images raster lors de la conversion de PDF en HTML. |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | À cette propriété, vous pouvez affecter un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une ressource externe (police ou image) extraite du PDF et qui doit être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur le disque) peut être effectué dans ce code personnalisé et ce code personnalisé doit renvoyer un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite incorporé dans le HTML généré à la place du chemin original supposé vers cette ressource d'image. Dans ce cas, toutes les actions nécessaires à l'enregistrement de l'image doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci, pour une raison quelconque, doit être effectué par le code du convertisseur lui‑même, et non par le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'resourceSavingInfo'. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même comme s'il n'existait aucun code personnalisé externe. |
| [Hyperlink](./hyperlink/) | Représente un hyperlien abstrait. |
| [IconFit](./iconfit/) | Décrit comment l'icône de l'annotation widget doit être affichée à l'intérieur de son rectangle d'annotation. |
| [Id](./id/) | <p> Représente la structure d'identifiant de fichier. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Représente une image. |
| [ImageDeleteAction](./imagedeleteaction/) | Action qui est effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé |
| [ImagePlacement](./imageplacement/) | <p> Représente les caractéristiques d'une image placée sur une page de document PDF. </p> <hr> <pre> L'exemple montre comment trouver les images sur la première page du document PDF et obtenir les images sous forme de bitmaps avec leurs dimensions visibles. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Créer l'objet ImagePlacementAbsorber pour effectuer la recherche de placement d'image ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(abs); // Récupérer les images avec leurs dimensions visibles for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Récupérer l'image depuis les ressources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Créer un nouveau bitmap avec les dimensions réelles scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Lorsqu'une image est placée sur une page, elle peut avoir des dimensions différentes des dimensions physiques définies dans {@code Resources}. L'objet {@code ImagePlacement} est destiné à fournir de telles informations telles que les dimensions, la résolution, etc. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Représente un objet absorbeur d'objets de placement d'image. Effectue la recherche d'utilisations d'images et fournit l'accès aux résultats de recherche via la collection {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get the image placement properties. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> L'objet {@code ImagePlacementAbsorber} est essentiellement utilisé dans le scénario de recherche d'images. Lorsque la recherche est terminée, les occurrences sont représentées par des objets {@code ImagePlacement} que la collection {@code ImagePlacementAbsorber.ImagePlacements} contient. L'objet {@code ImagePlacement} fournit l'accès aux propriétés de placement d'image : dimensions, résolution, etc. </p> La rotation positive d'une image est dans le sens antihoraire, pour la page, elle est dans le sens horaire. Ici, nous devons représenter l'angle de rotation de l'image, donc nous soustrayons l'angle de la page de l'angle de l'image. |
| [ImagePlacementCollection](./imageplacementcollection/) | Représente une collection de placements d'images |
| [ImageStamp](./imagestamp/) | Représente un tampon graphique. |
| [ImageType](./imagetype/) | Représente les types de format d'image. |
| [ImportDataAction](./importdataaction/) | Lors de l'invocation d'une action d'importation de données, les données du Forms Data Format (FDF) doivent être importées dans le formulaire interactif du document à partir d'un fichier spécifié. |
| [ImportFieldsOptions](./importfieldsoptions/) | Représente la classe de base des options d'importation de champs de formulaire. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Représente les options d'importation de champs de formulaire au format Json. Hérite de {@code ImportFieldsOptions} et ajoute des options spécifiques pour l'importation Json. |
| [ImportOptions](./importoptions/) | Le type ImportOptions représente un niveau d'abstraction sur les options d'importation individuelles. |
| [InkAnnotation](./inkannotation/) | Représente un gribouillage à main levée composé d'un ou plusieurs chemins disjoints. |
| [InternalHelper](./internalhelper/) | Classe interne |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | L'exception qui est levée lorsqu'une opération avec le type de formulaire n'est pas valide. |
| [JavascriptAction](./javascriptaction/) | Classe représentant une action JavaScript. |
| [JavaScriptCollection](./javascriptcollection/) | Cette classe représente une collection de JavaScript. |
| [LatexFragment](./latexfragment/) | Représente un fragment TeX. @deprecated Veuillez utiliser TeXFragment à la place |
| [LatexLoadOptions](./latexloadoptions/) | Représente les options de chargement/importation d'un fichier TeX dans un document PDF. @deprecated Utilisez TeXLoadOptions à la place. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Options d'enregistrement pour l'exportation au format TeX. @deprecated Utilisez TeXSaveOptions à la place |
| [LaunchAction](./launchaction/) | Représente une action de lancement qui lance une application ou ouvre ou imprime un document. |
| [Layer](./layer/) | Représente un calque au sein d'une page PDF. |
| [LevelFormat](./levelformat/) | Représente le format de la table des matières. |
| [License](./license/) | Fournit des méthodes pour licencier le composant. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Représente une information de licence. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Collection d'opérateurs légère. Destinée à être utilisée dans les scénarios où le flux de contenu sous-jacent n'est pas attaché, et où seule la collection d'opérateurs est requise en résultat. |
| [LineAnnotation](./lineannotation/) | Classe représentant une annotation de ligne. |
| [LineEndingConverter](./lineendingconverter/) | Représente la classe LineEndingConverter |
| [LineEndingsDrawer](./lineendingsdrawer/) | Dessine les terminaisons de ligne pour les annotations. Classe interne à usage interne uniquement. |
| [LinkAnnotation](./linkannotation/) | Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à exécuter. |
| [ListBoxField](./listboxfield/) | La classe représente le champ ListBox. |
| [LoadOptions](./loadoptions/) | Le type LoadOptions contient le niveau d'abstraction sur les options de chargement individuelles. |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Représente le mode d'utilisation de la zone des marges lors de la conversion (comme HTML, EPUB, etc.), définit le traitement des instructions du format importé liées à l'utilisation des marges. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ATTENTION ! La fonctionnalité est implémentée mais n’a pas encore été exposée dans l’API publique en raison d’un problème bloquant dans la couche OSHARED détecté pour le document d’exemple. Représente le mode d’utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d’ajuster la taille de page requise. Mais parfois le contenu spécifie des positions ou une taille horizontales qui ne permettent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Résultat du chargement personnalisé de la ressource |
| [LocaleOptions](./localeoptions/) | Le type LocaleOptions spécifie la configuration locale pour Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Représente un objet de lien hypertexte local. |
| [MarginInfo](./margininfo/) | Cette classe représente une marge pour différents objets. |
| [MarkupAnnotation](./markupannotation/) | Classe abstraite représentant une annotation de balisage. |
| [MarkupParagraph](./markupparagraph/) | Représente un paragraphe. |
| [MarkupSection](./markupsection/) | Représente une section de balisage – la région rectangulaire d’une page qui contient du texte et qui peut être visuellement séparée d’autres blocs de texte. |
| [Matrix](./matrix/) | La classe représente une matrice de transformation. |
| [Matrix3D](./matrix3d/) | La classe représente une matrice de transformation. |
| [MdLoadOptions](./mdloadoptions/) | Options de chargement pour la conversion du format Markdown. |
| [Measure](./measure/) | Classe qui décrit le système de coordonnées Measure. |
| [Measure.NumberFormat](./measure.numberformat/) | Format numérique pour la mesure. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Représente une liste de formats numériques. |
| [MediaClip](./mediaclip/) | Classe décrivant l’objet media clip du rendu. |
| [MediaClipData](./mediaclipdata/) | Classe décrivant les données du media clip. |
| [MediaClipSection](./mediaclipsection/) | Cette classe décrit la section Media clip. |
| [MediaRendition](./mediarendition/) | Classe décrivant le rendu média. |
| [MemoryCleaner](./memorycleaner/) | Représente la classe MemoryCleaner |
| [MemoryExtender](./memoryextender/) | Représente la classe MemoryExtender. Lors de l’utilisation de gros fichiers sur un système avec une mémoire tampon limitée, elle peut être activée pour utiliser l’espace disque comme mémoire d’échange temporaire. |
| [MemoryFontSource](./memoryfontsource/) | Représente une source de fichier de police unique. |
| [Metadata](./metadata/) | Fournit l’accès au flux de métadonnées XMP. |
| [Metered](./metered/) | <p> Fournit des méthodes pour définir la clé mesurée. </p> <hr> Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey(\"PublicKey\", \"PrivateKey\"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Représente les options de chargement/importation du fichier .mht dans un document PDF. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Options d'enregistrement pour l'exportation au format Xml |
| [MovieAnnotation](./movieannotation/) | Représente une annotation vidéo qui contient des graphiques animés et du son à présenter sur l'écran de l'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, la vidéo est lue. |
| [NamedAction](./namedaction/) | Représente des actions nommées que les applications de visualisation PDF sont censées prendre en charge. |
| [NamedDestination](./nameddestination/) | Au lieu d'être définie directement avec la syntaxe explicite, une destination peut être référencée indirectement au moyen d'un objet nom ou d'une chaîne d'octets. |
| [Note](./note/) | Cette classe représente une note de paragraphe générateur. |
| [NumberField](./numberfield/) | Champ texte avec des caractères valides spécifiés @see TextBoxField |
| [NumberTree](./numbertree/) | Classe représentant la structure d'arbre de nombres d'un fichier PDF. 7.9.7Arbres de nombres |
| [OcspSettings](./ocspsettings/) | Représente les paramètres OCSP utilisés pendant le processus de signature. |
| [OfdLoadOptions](./ofdloadoptions/) | Options de chargement pour le format OFD. |
| [Operator](./operator/) | Classe abstraite représentant un opérateur. |
| [OperatorCollection](./operatorcollection/) | Classe représentant une collection d'opérateurs |
| [OperatorSelector](./operatorselector/) | Cette classe est utilisée pour sélectionner des opérateurs en utilisant le concept de modèle Visitor. |
| [Opi](./opi/) | Représente l'Open Prepress Interface (OPI), un mécanisme de création de substituts à basse résolution, ou proxys, pour de telles images haute résolution. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Définit un MemoryStream qui peut contenir une capacité plus standard |
| [Option](./option/) | Classe représentant l'option d'un champ de choix. |
| [OptionCollection](./optioncollection/) | Classe représentant la collection d'options du champ de choix. |
| [OutlineCollection](./outlinecollection/) | Représente la hiérarchie du plan du document. |
| [OutlineItemCollection](./outlineitemcollection/) | Représente une entrée de plan dans la hiérarchie du plan du document PDF. |
| [Outlines](./outlines/) | Classe décrivant une collection de plans. |
| [OutputIntent](./outputintent/) | Représente une intention de sortie qui correspond aux caractéristiques colorimétriques d'un document PDF avec celles d'un dispositif de sortie cible ou d'un environnement de production dans lequel le document sera imprimé. |
| [OutputIntents](./outputintents/) | Représente la collection de {@link OutputIntent}. |
| [Page](./page/) | Classe représentant une page d'un document PDF. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Procédure pour personnaliser l'en-tête et le pied de page. |
| [PageActionCollection](./pageactioncollection/) | Cette classe décrit les actions de page |
| [PageCollection](./pagecollection/) | Collection de pages de document PDF. |
| [PageExtensions](./pageextensions/) | Fournit des capacités supplémentaires pour la classe Page. |
| [PageInfo](./pageinfo/) | Représente les informations de page pour le générateur pdf. |
| [PageInformationAnnotation](./pageinformationannotation/) | Représente une annotation Page Information dans un document PDF. Cette annotation contient le nom du fichier, le numéro de page, ainsi que la date et l'heure de création de l'annotation. Cette classe est principalement utilisée pour ajouter des métadonnées à une page spécifique du document PDF, ce qui peut être utile pour le suivi et la référence. Par exemple, elle peut être utilisée pour marquer des pages lors du processus d'impression ou pour fournir des informations supplémentaires sur la page lors de la visualisation du document. |
| [PageLabel](./pagelabel/) | Classe représentant la plage de Page Label. |
| [PageLabelCollection](./pagelabelcollection/) | Classe représentant la collection de page label. |
| [PageMarkup](./pagemarkup/) | Le markup de page est représenté par des collections de {@code MarkupSection} et {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Représente le tampon du numéro de page et est utilisé pour numéroter les pages. |
| [PageSize](./pagesize/) | Classe représentant la taille de la page dans le document PDF. |
| [PaginationArtifact](./paginationartifact/) | Représente une classe de base abstraite pour les artefacts de pagination dans un document. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Représente un objet absorbeur des objets de structure de page tels que les sections et les paragraphes. Effectue une recherche de sections et de paragraphes de texte et fournit un accès aux rectangles et aux polygones qui les décrivent dans l'espace de coordonnées du texte. Effectue également une recherche de segments de texte et fournit un accès aux résultats de recherche via les collections {@code TextFragments} regroupées par éléments de structure. </p> L'exemple montre comment trouver le premier segment de texte de chaque paragraphe sur la première page du document PDF et le mettre en surbrillance. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Lorsque la recherche est terminée, la collection {@code ParagraphAbsorber.PageMarkups} contiendra des objets {@code PageMarkup} qui représentent la structure de la page par des collections de {@code MarkupSection} et {@code MarkupParagraph}. L'objet {@code TextFragment} fournit un accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc.). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Représente les options pour le {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | Cette classe représente la collection de paragraphes. |
| [PasswordBoxField](./passwordboxfield/) | Classe décrivant le champ texte pour saisir le mot de passe. |
| [PclLoadOptions](./pclloadoptions/) | Représente les options de chargement (import) d'un fichier PCL dans un document pdf. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Énumère les moteurs de conversion qui peuvent être utilisés pour la conversion |
| [PDF3DAnnotation](./pdf3dannotation/) | Classe PDF3DAnnotation. Cette classe ne peut pas être héritée. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | Classe PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Classe PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Classe PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Classe PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Classe PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Classe PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Classe PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Classe PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Classe PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Classe PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Représente Action dans le document PDF |
| [PdfActionCollection](./pdfactioncollection/) | Classe décrit liste d'actions. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Cette classe décrit les règles qui peuvent être utilisées pour ajuster le processus de copie des données d'encodage dans les cas où une police symbolique TrueType possède plus d'un encodage. Certains documents PDF après conversion au format PDF/A peuvent générer une erreur "More than one encoding in symbolic TrueType font's cmap". Quelle est la raison de cette erreur ? Toutes les polices symboliques TrueType ont une table spéciale "cmap" dans leurs données internes. Cette table associe les codes de caractères aux indices de glyphes. Et cette table peut contenir différentes sous‑tables d'encodage qui décrivent les encodages utilisés. Voir des informations avancées sur les tables cmap à https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Habituellement, la table cmap contient plusieurs sous‑tables d'encodage, mais la norme PDF/A exige qu'il ne reste qu'une seule sous‑table d'encodage pour cette police dans le document PDF/A ou qu'il y ait une sous‑table d'encodage (3,0) parmi les sous‑tables de cette police. Et la question clé ici – quelles données doivent être prises à partir des autres sous‑tables pour être copiées dans la table d'encodage de destination (3,0) ? La majorité des polices ont des tables cmap « bien formées » où chaque sous‑table d'encodage est entièrement cohérente avec une autre sous‑table. Mais certaines polices ont des tables cmap avec des collisions – où, par exemple, une sous‑table possède l'indice de glyphe 100 pour le caractère unicode 100, tandis qu'une autre sous‑table possède l'indice de glyphe 200 pour le même unicode 100. Pour résoudre ces problèmes, une stratégie spéciale est nécessaire. Par défaut, la stratégie suivante est utilisée : la sous‑table mac (1,0) est recherchée. Si cette table est trouvée, seules ces données sont utilisées pour remplir la table de destination (3,0). Si la sous‑table mac n'est pas trouvée, alors toutes les sous‑tables sauf (3,0) sont parcourues et utilisées pour copier les données dans la sous‑table de destination (3,0). De plus, le mappage pour chaque unicode (unicode, indice de glyphe) est copié dans la table de destination uniquement si la table de destination ne possède pas cet unicode à ce moment‑là. Ainsi, par exemple, si la première sous‑table a l'indice de glyphe 100 pour l'unicode 100, et que la sous‑table suivante a l'indice de glyphe 200 pour le même unicode 100, seules les données de la première sous‑table (unicode=100, indice de glyphe = 100) seront copiées. Ainsi chaque sous‑table précédente a la priorité sur la suivante. Les propriétés de cette classe { PdfASymbolicFontEncodingStrategy} aident à ajuster le comportement par défaut. Si la propriété {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) de type { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} est définie, alors la sous‑table pertinente sera utilisée en priorité par rapport à la sous‑table mac (1,0). La valeur 'MacTable' de l'énumération {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} n'a aucun sens dans ce cas, car elle pointe sur la même sous‑table mac (1,0) qui sera utilisée par défaut. La propriété {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) supprime toutes les priorités pour toute sous‑table. Si cette propriété est définie, alors seules les sous‑tables de la file d'attente déclarée seront utilisées dans l'ordre spécifié. Si les sous‑tables spécifiées ne sont pas trouvées, alors l'itération par défaut de toutes les sous‑tables et la stratégie de copie décrite ci‑dessus seront utilisées. L'objet { PdfASymbolicFontEncodingStrategy.QueueItem} spécifie la sous‑table d'encodage utilisée. Cette sous‑table peut être définie via une combinaison de membres (PlatformID, PlatformSpecificId) ou via l'énumération { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Dans le cas où la police n'a pas de sous‑table (3,0), une autre sous‑table sera utilisée pour maintenir la compatibilité PDF/A. Le choix de la sous‑table à utiliser est fait selon les mêmes règles décrites précédemment, de sorte que les propriétés {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) et {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) sont utilisées pour déterminer la sous‑table résultante, et si la police ne possède pas la ou les sous‑tables demandées, alors toute sous‑table existante sera utilisée. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Spécifie la sous-table d'encodage. Chaque sous-table d'encodage a une combinaison unique de paramètres (PlatformID, PlatformSpecificID). L'énumération {@code CMapEncodingTableType} et la propriété {@code CMapEncodingTable} ont été implémentées pour faciliter la définition de la sous-table d'encodage requise. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Déclare un ensemble de certaines sous-tables d'encodage connues |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | représente un ensemble d'options pour convertir un document PDF |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Cette classe contient des indicateurs pour contrôler la conversion PDF/A dans les cas où le document PDF source ne correspond pas à la spécification PDF. Si les indicateurs de cette classe sont utilisés, cela diminue les performances mais c'est nécessaire lorsque le document PDF source ne peut pas être converti au format PDF/A de manière habituelle. Par défaut, tous les indicateurs sont définis sur false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Certains documents PDF contiennent des symboles Unicode spéciaux, appartenant à la zone d'utilisation privée (PUA) ; voir la description sur https://en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles provoquent des erreurs de conformité PDF/A telles que "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Cette énumération déclare des stratégies pouvant être utilisées pour gérer les symboles PUA. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Certains documents ont une taille importante après conversion au format PDF/A. Pour réduire la taille du fichier de ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération déclare des stratégies pouvant être utilisées pour optimiser l'utilisation des polices. Chaque stratégie de cette énumération n'a de sens que lorsque l'indicateur {@code OptimizeFileSize} est activé. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Décrit les stratégies utilisées pour aligner les segments de texte du document. Actuellement, seule la stratégie de restauration des segments à leurs limites d'origine est prise en charge. D'autres stratégies pourraient être ajoutées à l'avenir. |
| [PdfPageStamp](./pdfpagestamp/) | La classe représente un tampon qui utilise une page PDF comme tampon. |
| [PdfSaveOptions](./pdfsaveoptions/) | Options d'enregistrement pour l'exportation au format Pdf |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Options de chargement pour le format PdfXml. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Options d'enregistrement pour le format PdfXml. |
| [Permissions](./permissions/) | Indicateur binaire Cette énumération représente les autorisations de l'utilisateur pour un pdf. |
| [PKCS1](./pkcs1/) | Représente un objet signature conformément à la norme PKCS#1. L'algorithme de chiffrement RSA et la méthode de condensat SHA-1 sont utilisés pour la signature. |
| [PKCS7](./pkcs7/) | Représente l'objet PKCS#7 conforme à la spécification PKCS#7 de la RFC 2315 d'Internet, PKCS #7 : Cryptographic Message Syntax, version 1.5. Le condensat SHA1 de la plage d'octets du document est encapsulé dans le champ SignedData de PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Représente l'objet PKCS#7 conforme à la spécification PKCS#7 de la RFC 2315 d'Internet, PKCS #7 : Cryptographic Message Syntax, version 1.5. Le condensat du message signé original sur la plage d'octets du document est incorporé comme le champ SignedData normal de PKCS#7. Aucune donnée ne doit être encapsulée dans le champ SignedData de PKCS#7. |
| [Point](./point/) | Représente un point avec des coordonnées fractionnaires. |
| [Point3D](./point3d/) | Représente un point avec des coordonnées fractionnaires. |
| [PolyAnnotation](./polyannotation/) | Classe de base abstraite pour les poly-annotations. |
| [PolygonAnnotation](./polygonannotation/) | Classe représentant une annotation de polygone. |
| [PolylineAnnotation](./polylineannotation/) | Représente une annotation de polyligne similaire à un polygone, sauf que le premier et le dernier sommet ne sont pas implicitement connectés. |
| [PopupAnnotation](./popupannotation/) | Représente l'annotation pop-up qui affiche du texte dans une fenêtre pop-up pour la saisie et la modification. |
| [Position](./position/) | Représente un objet position |
| [PptxSaveOptions](./pptxsaveoptions/) | Options d'enregistrement pour l'exportation au format SVG |
| [PrintController](./printcontroller/) | Représente le contrôleur d'impression. |
| [PrintDuplex](./printduplex/) | L'option de gestion du papier à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe abstraite représentant une annotation de marque d'imprimante. |
| [PrinterMarksKind](./printermarkskind/) | Spécifie les types de marques d'imprimante à ajouter à un document. Cette énumération possède un attribut {@link FlagsAttribute} qui permet une combinaison bit à bit de ses valeurs membres. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fournit des méthodes d'extension pour l'énumération {@link PrinterMarksKind}. |
| [PrintScaling](./printscaling/) | L'option de mise à l'échelle de la page qui doit être sélectionnée lorsqu'une boîte de dialogue d'impression est affichée pour ce document. |
| [ProgressEventType](./progresseventtype/) | Cette énumération décrit les types d'événements de progression possibles qui peuvent survenir pendant la conversion. |
| [PsLoadOptions](./psloadoptions/) | Représente les options de chargement/importation du fichier .mht dans un document PDF. |
| [PsSaveOptions](./pssaveoptions/) | Options d'enregistrement pour l'exportation au format PS (PostScript) ou EPS. |
| [RadioButtonField](./radiobuttonfield/) | Classe représentant le champ bouton radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe représentant un élément du champ RadioButton. |
| [Rectangle](./rectangle/) | Classe représentant un rectangle. |
| [Redaction](./redaction/) | À usage interne uniquement @author User |
| [RedactionAnnotation](./redactionannotation/) | Représente l'annotation Redact. |
| [RegexManager](./regexmanager/) | Fournit un wrapper pour les opérations d'expressions régulières avec des paramètres de délai d'attente configurables. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Représente une annotation de repère d'enregistrement. Les repères d'enregistrement sont des symboles ajoutés aux plaques d'impression ou aux écrans pour garantir un alignement correct des couleurs pendant le processus d'impression. |
| [RenderingOptions](./renderingoptions/) | Représente les options de rendu |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType : ensemble de types de mode de rendu |
| [Rendition](./rendition/) | Classe qui décrit l'objet de rendu de RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Une action de rendu qui contrôle la lecture de contenu multimédia. |
| [RenditionOperation](./renditionoperation/) | L'opération à effectuer lorsque l'action est déclenchée. |
| [RenditionType](./renditiontype/) | L'énumération décrit les types possibles de Rendition. |
| [Resources](./resources/) | Classe représentant les ressources de page. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Représente les ExtGStates avec certaines valeurs. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Représente la stratégie de conversion des espaces colorimétriques rgb vers gris dispositif. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe décrivant RichMediaAnnotation qui permet d'intégrer des données vidéo/audio dans un document PDF. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Événement qui active l'annotation. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Type du multimédia. |
| [RichTextBoxField](./richtextboxfield/) | Classe décrivant le composant éditeur de texte enrichi. |
| [RichTextFontStyles](./richtextfontstyles/) | Options pour le style des fragments de texte dans RichText. |
| [RootElement](./rootelement/) | Élément de structure racine. |
| [Row](./row/) | Représente une ligne du tableau. |
| [Rows](./rows/) | Représente une collection de lignes du tableau. |
| [RtfLoadOptions](./rtfloadoptions/) | Options de chargement pour le format RTF. |
| [SaveOptions](./saveoptions/) | Le type SaveOptions maintient le niveau d'abstraction sur les options de sauvegarde individuelles. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Une instance de cette classe représente des informations sur la bordure qui peut être dessinée sur un document résultant. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Représente les informations d'une partie de la bordure (haut, bas, côté gauche ou côté droit). |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Une instance de cette classe représente des informations sur la marge de page qui peut être dessinée sur un document résultant. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Représente les informations d'une partie de la marge (haut, bas, côté gauche ou côté droit). |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Cette classe représente un ensemble de données liées à l'enregistrement de fichiers de ressources externes qui se produit lors de la conversion de PDF vers un autre format (par ex. HTML). |
| [ScalingMode](./scalingmode/) | Le type de mise à l'échelle qui doit être utilisé. |
| [ScalingReason](./scalingreason/) | Les circonstances dans lesquelles l'icône doit être mise à l'échelle à l'intérieur du rectangle. |
| [ScreenAnnotation](./screenannotation/) | Une annotation d'écran qui spécifie une région d'une page sur laquelle des clips multimédias peuvent être lus. |
| [SelectorRendition](./selectorrendition/) | La classe décrit le rendu du sélecteur. |
| [Signature](./signature/) | Une classe abstraite qui représente un objet de signature dans le document PDF. Les signatures sont des champs contenant des objets de signature, ces derniers contenant des données utilisées pour vérifier la validité du document. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Une classe abstraite qui représente un objet d'apparence personnalisée de signature. |
| [SignatureField](./signaturefield/) | Représente le champ de formulaire de signature. |
| [SignHash](./signhash/) | Délégataire pour signer de façon personnalisée le hachage du document (Beta). |
| [SoundAnnotation](./soundannotation/) | Représente une annotation sonore contenant un son enregistré depuis le microphone de l'ordinateur ou importé depuis un fichier. |
| [SoundData](./sounddata/) | Représente des données sonores définissant le son à jouer lorsque l'annotation est activée. |
| [SoundEncoding](./soundencoding/) | Le format d'encodage des données d'échantillon. |
| [SoundIcon](./soundicon/) | Énumère les icônes à utiliser pour l'affichage de l'annotation. |
| [SoundIconConverter](./soundiconconverter/) | Représente la classe SoundIconConverter. |
| [SoundSampleData](./soundsampledata/) | Représente des entrées supplémentaires spécifiques à un objet sonore (Section 9.2 PDF1-7). |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Le format d'encodage des données d'échantillon sonore. |
| [SquareAnnotation](./squareannotation/) | Classe représentant l'annotation carrée. |
| [SquigglyAnnotation](./squigglyannotation/) | Représente l'annotation ondulée qui apparaît comme un soulignement irrégulier dans le texte d'un document. |
| [Stamp](./stamp/) | Une classe abstraite pour différents types de tampons qui sont des descendants. |
| [StampAnnotation](./stampannotation/) | <p> Représente l'annotation de tampon en caoutchouc. Ce type d'annotation affiche du texte ou des graphiques destinés à ressembler à un tampon appliqué sur la page. </p> <hr> <pre> Le fragment de code suivant montre comment ajouter 2 tampons à la première page du document PDF. Le document d'entrée provient de inFile et les modifications sont enregistrées dans outFile. Le premier tampon a l'icône NotForPublicRelease et le second utilise l'image provenant de rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Représente la classe StampIconConverter |
| [StrikeOutAnnotation](./strikeoutannotation/) | Représente une annotation de barré qui apparaît comme un texte barré dans le document. |
| [StructElement](./structelement/) | Élément de structure général. |
| [SubjectNameElements](./subjectnameelements/) | L'énumération décrit les éléments de la chaîne du sujet de la signature. |
| [SubmitFormAction](./submitformaction/) | Classe qui décrit l'action submit-form. |
| [SvgLoadOptions](./svgloadoptions/) | Représente les options de chargement/importation d'un fichier SVG dans un document PDF. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Énumère les moteurs de conversion qui peuvent être utilisés pour la conversion |
| [SvgSaveOptions](./svgsaveoptions/) | Options d'enregistrement pour l'exportation au format SVG |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion de PDF en HTML. |
| [Symbology](./symbology/) | Une symbologie (code-barres) définit les détails techniques d'un type particulier de code-barres : la largeur des barres, le jeu de caractères, la méthode d'encodage, les spécifications de la somme de contrôle, etc. |
| [SystemFontSource](./systemfontsource/) | Représente toutes les polices installées sur le système. |
| [TabAlignmentType](./tabalignmenttype/) | Énumère les types d'alignement des onglets. |
| [Table](./table/) | Représente une table qui peut être ajoutée à la page. |
| [TableAbsorber](./tableabsorber/) | <p> Représente un objet absorbeur d'éléments de tableau. Effectue une recherche et fournit l'accès aux résultats de recherche via la collection {@code TableAbsorber.TableList}. </p> <hr> <pre> L'exemple montre comment trouver un tableau sur la première page du document PDF et remplacer le texte dans une cellule de tableau. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Énumère les types de tirets d'onglet. |
| [TableBroken](./tablebroken/) | Énumère le tableau cassé. |
| [TabOrder](./taborder/) | Ordre des onglets sur la page |
| [TabStop](./tabstop/) | Représente une position d'arrêt d'onglet personnalisée dans un paragraphe. |
| [TabStops](./tabstops/) | Représente une collection d'objets {@code TabStop}. |
| [TeXFragment](./texfragment/) | Représente un fragment LaTeX. |
| [TeXLoadOptions](./texloadoptions/) | Représente les options de chargement/importation d'un fichier TeX dans un document PDF. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implémente la récupération d'un flux de sortie depuis la mémoire. Vous pouvez l'utiliser, par exemple, lorsque vous ne souhaitez pas que la sortie associée (comme un fichier journal) soit écrite sur le disque mais que vous souhaitez la lire ensuite depuis la mémoire. |
| [TeXSaveOptions](./texsaveoptions/) | Options d'enregistrement pour l'exportation au format TeX |
| [TextAbsorber](./textabsorber/) | <p> Représente un objet absorbant de texte. Effectue l'extraction de texte et fournit l'accès au résultat via l'objet {@code TextAbsorber.Text}. </p> <hr> <pre> L'exemple montre comment extraire le texte de la première page du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> L'objet {@code TextAbsorber} est utilisé pour extraire le texte d'un document Pdf ou de la page du document. </p> |
| [TextAnnotation](./textannotation/) | Représente une annotation de texte qui est un "sticky note" attaché à un point dans le document PDF. |
| [TextBoxField](./textboxfield/) | Classe représentant le champ de zone de texte. |
| [TextBuilder](./textbuilder/) | Ajoute un objet texte à la page Pdf. |
| [TextDefaults](./textdefaults/) | Définit les valeurs par défaut du sous-système texte |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Spécifie le type des valeurs par défaut du sous-système texte |
| [TextEditOptions](./texteditoptions/) | Décrit les options des opérations d'édition de texte. |
| [TextElement](./textelement/) | Élément texte général de la structure logique du document. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Décrit l'erreur d'extraction de texte qui est apparue dans le document PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Représente l'emplacement dans le document PDF où l'erreur d'extraction de texte est apparue. |
| [TextExtractionOptions](./textextractionoptions/) | Représente les options d'extraction de texte |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Définit différents modes pouvant être utilisés lors de la conversion d'un document pdf en texte. Voir la classe {@code TextDevice}. |
| [TextFormattingOptions](./textformattingoptions/) | Représente les options de mise en forme du texte |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Définit les spécificités de l'espacement des lignes |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Définit les stratégies de retour à la ligne |
| [TextFragment](./textfragment/) | <p> Représente un fragment de texte PDF. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte ainsi que sa police. // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> En quelques mots, l'objet {@code TextFragment} contient une liste d'objets {@code TextSegment}. En détail : Le texte du document PDF dans {@code com.aspose.pdf} est représenté par deux objets de base : {@code TextFragment} et {@code TextSegment} Les différences entre eux sont principalement dépendantes du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour le manipuler, changer ses propriétés, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> La représentation physique du texte PDF est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que l'objet {@code TextFragment} fournit un ensemble d'opérations logiques unique sur l'ensemble d'objets {@code TextSegment} physiques qui représente la requête de l'utilisateur. Dans le scénario de recherche de texte, {@code TextFragment} est la représentation logique du texte "hello world", et la collection d'objets {@code TextSegment} représente tous les segments physiques qui construisent l'objet texte "hello world". Ainsi, {@code TextFragment} se rapproche de la représentation logique du texte. Et {@code TextSegment} se rapproche de la représentation physique du texte. Évidemment, chaque objet {@code TextSegment} peut avoir sa propre police, couleur et propriétés de positionnement. {@code TextFragment} offre un moyen simple de modifier le texte avec ses propriétés : définir la police, la taille de police, la couleur de police, etc. Par ailleurs, les objets {@code TextSegment} sont accessibles et les utilisateurs peuvent manipuler les objets {@code TextSegment} de manière indépendante. <p> Notez que la modification des propriétés de TextFragment peut modifier la collection interne {@code Segments} car TextFragment est un objet agrégé et il peut réarranger les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection {@code Segments} inchangée, veuillez modifier les segments internes individuellement. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page d'un document PDF et remplacer le texte ainsi que sa police. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour changer la police du texte du document com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte et la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> L'objet {@code TextFragmentAbsorber} est essentiellement utilisé dans un scénario de recherche de texte. Lorsque la recherche est terminée, les occurrences sont représentées par des objets {@code TextFragment} que contient la collection {@code TextFragmentAbsorber.TextFragments}. L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc.). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Représente une collection de fragments de texte |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Représente l'état du texte d'un fragment de texte. </p> <hr> <pre> L'exemple montre comment changer la couleur du texte et la taille de police du texte avec l'objet {@code TextState}. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier la couleur de premier plan de la première occurrence de texte absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Modifier la taille de police de la première occurrence de texte absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : police ({@code TextFragmentState.Font} property) taille de police ({@code TextFragmentState.FontSize} property) style de police ({@code TextFragmentState.FontStyle} property) couleur de premier plan ({@code TextFragmentState.ForegroundColor} property) couleur d'arrière-plan ({@code TextFragmentState.BackgroundColor} property) <p> Notez que la modification des propriétés {@code TextFragmentState} peut modifier la collection interne {@code TextFragment.Segments} car TextFragment est un objet agrégé et il peut réarranger les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection {@code TextFragment.Segments} inchangée, veuillez modifier les segments internes individuellement. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Énumère les icônes à utiliser pour l'affichage de l'annotation. |
| [TextIconConverter](./texticonconverter/) | Représente la classe TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe de base abstraite pour les annotations de balisage de texte. |
| [TextOptions](./textoptions/) | Représente les options de traitement du texte |
| [TextParagraph](./textparagraph/) | <p> Représente les paragraphes de texte comme un objet texte multiligne. </p> <hr> <pre> L'exemple montre comment créer un objet paragraphe de texte et l'ajouter à la page Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // créer un paragraphe de texte TextParagraph paragraph = new TextParagraph(); // définir le rectangle du paragraphe paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // définir les options de retour à la ligne paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // ajouter des lignes de chaîne paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // ajouter le paragraphe à la page Pdf avec le TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // enregistrer le document Pdf doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Mode d'arrière-plan pour TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Représente un objet absorbeur de paragraphes de texte. Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextParagraphAbsorber.TextParagraphs}. |
| [TextParagraphCollection](./textparagraphcollection/) | Représente une collection de paragraphes de texte |
| [TextReplaceOptions](./textreplaceoptions/) | Représente les options de remplacement de texte |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un texte plus court. None - aucune action, le texte remplacé peut chevaucher le reste de la ligne ; AdjustSpaceWidth - tente d'ajuster les espaces entre les mots pour conserver la longueur de la ligne ; WholeWordsHyphenation - tente de répartir les mots entre les lignes du paragraphe pour conserver le champ droit du paragraphe ; ShiftRestOfLine - décale le reste de la ligne en fonction de la longueur changeante du texte, la longueur de la ligne peut être modifiée ; La valeur par défaut est ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Représente les options de recherche de texte |
| [TextSegment](./textsegment/) | <p> Représente un segment de texte PDF. </p> <hr> <pre> L'exemple montre comment changer la couleur du texte et la taille de police du texte avec l'objet {@code TextState} de l'objet {@code TextSegment}. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier la couleur de premier plan du premier segment de texte de la première occurrence de texte absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Modifier la taille de police du premier segment de texte de la première occurrence de texte absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> En quelques mots, les objets {@code TextSegment} sont des enfants de l'objet {@code TextFragment}. En détail : le texte d'un document pdf dans {@code Aspose.Pdf} est représenté par deux objets de base : {@code TextFragment} et {@code TextSegment}. Les différences entre eux sont principalement dépendantes du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour le manipuler, modifier ses propriétés, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Physiquement, la représentation du texte pdf est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.PDF établit essentiellement que l'objet {@code TextFragment} fournit un ensemble d'opérations logiques unique sur l'ensemble d'objets {@code TextSegment} physiques qui représentent la requête de l'utilisateur. Dans un scénario de recherche de texte, {@code TextFragment} est la représentation logique du texte "hello world", et la collection d'objets {@code TextSegment} représente tous les segments physiques qui construisent l'objet texte "hello world". Ainsi, {@code TextFragment} se rapproche de la représentation logique du texte. Et {@code TextSegment} se rapproche de la représentation physique du texte. Évidemment chaque objet {@code TextSegment} peut avoir sa propre police, couleur, propriétés de positionnement. {@code TextFragment} offre un moyen simple de modifier le texte avec ses propriétés : définir la police, définir la taille de police, définir la couleur de police, etc. Pendant ce temps, les objets {@code TextSegment} sont accessibles et les utilisateurs peuvent travailler avec les objets {@code TextSegment} de manière indépendante. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Représente une collection de segments de texte |
| [TextStamp](./textstamp/) | Représente un tampon textuel. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Action à effectuer si la police ne contient pas le caractère requis. |
| [TextState](./textstate/) | Représente l'état du texte |
| [TextStyle](./textstyle/) | Classe représentant le champ case à cocher. |
| [TimestampSettings](./timestampsettings/) | Représente les paramètres OCSP utilisés pendant le processus de signature. |
| [TocInfo](./tocinfo/) | Représente les informations de la table des matières. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Cette classe décrit les règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight "Le texte ne peut pas être mappé à Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Représente une annotation de repère de coupe. Les repères de coupe sont placés aux coins d'une page imprimée pour indiquer où la page doit être découpée. |
| [TxtLoadOptions](./txtloadoptions/) | Options de chargement pour la conversion TXT vers PDF. |
| [UnderlineAnnotation](./underlineannotation/) | Représente une annotation de soulignement qui apparaît comme un soulignement dans le texte du document. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Cette classe représente les options d'enregistrement qui utilisent une méthode de conversion unifiée (avec un modèle de document interne unifié). |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Représente une classe avec une méthode abstraite généralement fournie par le côté appelant et qui gère les événements de progression provenant du convertisseur. Habituellement, ce gestionnaire fourni par le client peut être utilisé pour afficher la progression totale de la conversion dans la console ou dans une barre de progression. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Cette classe représente les informations sur la progression de la conversion qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final. |
| [WarningCallback](./warningcallback/) | Interface de support du mécanisme de rappel de l'utilisateur. |
| [WarningInfo](./warninginfo/) | Objet immuable pour encapsuler les informations d'avertissement. |
| [WarningType](./warningtype/) | /* Type d'avertissement représenté par l'énumération. */ |
| [Watermark](./watermark/) | Représente un filigrane de la page. |
| [WatermarkAnnotation](./watermarkannotation/) | Classe décrivant l'objet d'annotation de filigrane. |
| [WatermarkArtifact](./watermarkartifact/) | Classe décrivant l'artefact de filigrane. Cela peut être utilisé pour |
| [WebHyperlink](./webhyperlink/) | Représente un objet de lien hypertexte web. |
| [WidgetAnnotation](./widgetannotation/) | Classe représentant une annotation de widget. |
| [XFA](./xfa/) | Représente le formulaire XML concernant l'Architecture des formulaires XML (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | classe pour gérer l'encapsulation des données associées |
| [XfdfReader](./xfdfreader/) | <p> Classe qui effectue la lecture du format XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Regroupe les méthodes d'écriture des annotations et des champs au format de fichier XFDF |
| [XForm](./xform/) | Classe représentant XForm |
| [XFormCollection](./xformcollection/) | Classe représentant la collection de XFormCollection. |
| [XImage](./ximage/) | Classe représentant l'objet image X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | Classe représentant les paramètres bruts XImage de l'image. |
| [XImageCollection](./ximagecollection/) | Classe représentant la collection XImage. |
| [XmlLoadOptions](./xmlloadoptions/) | Représente les options de chargement/importation d'un fichier XML dans un document PDF. |
| [XmlSaveOptions](./xmlsaveoptions/) | Options d'enregistrement pour l'exportation au format Xml |
| [XmpField](./xmpfield/) | Représente le champ XMP. |
| [XmpFieldType](./xmpfieldtype/) | Cette énumération représente les types d'un champ XMP. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Catégorie de propriété : interne ou externe. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Ce schéma décrit un champ dans un type structuré. Il est très similaire au schéma PDF/A Property Value Type, mais définit un champ dans une structure au lieu d'une propriété. URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/field# Préfixe d'espace de noms requis pour le schéma : pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Représente la classe de base pour les instances de champ, de propriété et de type de valeur. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Décrit une propriété unique. URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/property# Préfixe d'espace de noms requis pour le schéma : pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Décrit le schéma d'extension XMP fourni par PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Représente la description du schéma d'extension XMP fourni par PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | Le schéma PDF/A ValueType est requis pour tous les types de valeur de propriété qui ne sont pas définis dans la spécification XMP 2004, c’est‑à‑dire pour les types de valeur en dehors de la liste suivante : - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/type# Préfixe d'espace de noms requis pour le schéma : pdfaType |
| [XmpValue](./xmpvalue/) | Représente la valeur XMP |
| [XpsLoadOptions](./xpsloadoptions/) | Représente les options de chargement/importation d'un fichier XPS dans un document PDF. |
| [XpsSaveOptions](./xpssaveoptions/) | Options d'enregistrement pour l'exportation au format XPS |
| [XslFoLoadOptions](./xslfoloadoptions/) | Représente les options de chargement/importation d'un fichier XSL-FO dans un document PDF. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs de formatage. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom indique que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Description |
| --- | --- |
| [AFRelationship](./afrelationship/) | L'énumération décrit la relation des fichiers associés. |
| [AnnotationState](./annotationstate/) | L'énumération des états auxquels l'annotation originale peut être définie. |
| [AnnotationStateModel](./annotationstatemodel/) | Le modèle d'état correspondant à l'état de l'annotation. |
| [AnnotationType](./annotationtype/) | Énumération des types d'annotation. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Énumération du sous-type d'artefacts possible. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Énumération des types d'artefacts possibles. |
| [BlendMode](./blendmode/) | L'énumération des modes de fusion. |
| [BorderCornerStyle](./bordercornerstyle/) | Énumère les styles d'angle de bordure pour la bordure. |
| [BorderEffect](./bordereffect/) | Décrit l'effet qui doit être appliqué à la bordure des annotations. |
| [BorderStyle](./borderstyle/) | Décrit le style de la bordure de l'annotation. |
| [BoxStyle](./boxstyle/) | Représente les styles pour dessiner la coche dans la case à cocher. |
| [CapStyle](./capstyle/) | Style de la terminaison de ligne de l'annotation encre. |
| [CaptionPosition](./captionposition/) | Énumération du positionnement de la légende de l'annotation. |
| [CaretSymbol](./caretsymbol/) | Un symbole à associer au curseur. |
| [ColorsOfCMYK](./colorsofcmyk/) | Couleurs incluses dans le modèle de couleur CMJN. |
| [ColorSpace](./colorspace/) | L'énumération des espaces colorimétriques. |
| [ColorType](./colortype/) | Spécifie le type de couleur des éléments sur la page. |
| [ColumnAdjustment](./columnadjustment/) | Énumère les types d'ajustement de colonne. |
| [ContentDisposition](./contentdisposition/) | En-tête Content-Disposition du protocole MIME. |
| [ConvertErrorAction](./converterroraction/) | Cette classe représente l'action pour les erreurs de conversion. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Cette action représente les actions pour la conversion d'images avec masque doux. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Cette classe représente l'action pour la conversion de la transparence. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Représente le type d'algorithme cryptographique utilisé dans les routines de chiffrement/déchiffrement. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * Le {@code Aspose.Pdf.Security } namespace contient des classes utilisées pour le chiffrement et la signature numérique. / * / |
| [DefaultState](./defaultstate/) | Représente l'état par défaut d'une couche PDF. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Représente le type d'algorithme qui mappe les données vers un "hash" |
| [Direction](./direction/) | Direction du texte. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Les autorisations d'accès accordées pour ce document. Les valeurs valides sont : 1 - Aucun changement du document n'est autorisé ; toute modification du document invalide la signature. 2 - Les changements autorisés sont le remplissage des formulaires, l'instanciation de modèles de page et la signature ; d'autres modifications invalident la signature. 3 - Les changements autorisés sont les mêmes que pour 2, ainsi que la création, la suppression et la modification d'annotations ; d'autres modifications invalident la signature. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Permet de spécifier le format de fichier .doc ou .docx. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Permet de contrôler comment un document PDF est converti en document de traitement de texte. Utilisez le mode RecognitionMode.Textbox lorsque le document résultant ne sera pas fortement édité par la suite. Les zones de texte sont faciles à modifier lorsqu'il n'y a pas grand-chose à faire. Utilisez le mode RecognitionMode.Flow lorsque le document de sortie nécessite une édition supplémentaire. Les paragraphes et les lignes de texte en mode flux permettent une modification facile du texte, mais les objets de formatage non pris en charge auront un rendu pire que dans le mode RecognitionMode.Textbox. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti, le moteur de conversion tente d'effectuer un groupement et une analyse à plusieurs niveaux afin de restaurer l'intention de l'auteur du document original et de produire un résultat en mise en page fluide. Cette propriété ajuste cette conversion pour telle ou telle méthode souhaitée de reconnaissance du contenu. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Énumère les types de destinations explicites. |
| [ExtendedBoolean](./extendedboolean/) | Représente le type booléen qui prend en charge la valeur Undefined. |
| [ExtractImageMode](./extractimagemode/) | Définit différents modes pouvant être utilisés lors de l'extraction d'images à partir de documents. |
| [FileEncoding](./fileencoding/) | Encodage du fichier joint. Valeurs possibles : Zip - le fichier est compressé avec ZIP, None - le fichier n'est pas compressé. |
| [FileIcon](./fileicon/) | Une icône à utiliser lors de l'affichage de l'annotation. |
| [Fixup](./fixup/) | Cette énumération représente un type de Fixup. |
| [FormType](./formtype/) | Énumération des types possibles de formulaire Acro. |
| [FreeTextIntent](./freetextintent/) | Énumère les intentions de l'annotation de texte libre. |
| [HighlightingMode](./highlightingmode/) | Énumère le mode de surbrillance de l'annotation, l'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu dans sa zone active. |
| [HorizontalAlignment](./horizontalalignment/) | Décrit l'alignement horizontal. |
| [HtmlDocumentType](./htmldocumenttype/) | Représente l'énumération des types de documents Html. |
| [HtmlMediaType](./htmlmediatype/) | Spécifie les types de médias possibles utilisés lors du rendu. |
| [IconCaptionPosition](./iconcaptionposition/) | Décrit la position de l'icône. |
| [ImageFileType](./imagefiletype/) | Énumère les types de fichiers image. |
| [ImageFilterType](./imagefiltertype/) | Énumération représentant le type de filtre d'image. |
| [ImageFormat](./imageformat/) | Cette énumération représente les formats d'image. |
| [ImportFormat](./importformat/) | Spécifie le format d'importation. |
| [Justification](./justification/) | Énumère les formes de justification (quadding) à utiliser lors de l'affichage du texte de l'annotation. |
| [LaunchActionOperation](./launchactionoperation/) | Énumère les opérations à effectuer avec le document pendant l'exécution de l'action de lancement. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Il énumère les modes possibles de positionnement des lettres dans les mots dans le HTML résultant |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType : ensemble de types de schémas d'éclairage. |
| [LineEnding](./lineending/) | Énumère les styles de terminaison de ligne à utiliser lors du dessin de la ligne. |
| [LineIntent](./lineintent/) | Énumère les intentions de l'annotation de ligne. |
| [LoadFormat](./loadformat/) | Spécifie le format de chargement. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Valeur indiquant de quelle manière les valeurs de fraction sont affichées. |
| [NumberingStyle](./numberingstyle/) | Énumération du style de numérotation de page pris en charge pour la classe PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Spécifie la position dans un flux à utiliser pour la recherche. |
| [PageCoordinateType](./pagecoordinatetype/) | Décrit le type de coordonnées de page. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Décrit la mise en page. |
| [PageMode](./pagemode/) | La classe décrit les composants utilisés de la page du document. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Spécifie la variante pour déterminer l'emplacement de l'élément sur la page. |
| [PasswordType](./passwordtype/) | Cette énumération représente les types de mots de passe connus utilisés pour les documents PDF protégés par mot de passe. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation : ensemble des modes d'activation d'annotation 3D. |
| [PdfFormat](./pdfformat/) | Cette classe représente un format PDF. |
| [PdfVersion](./pdfversion/) | Cette énumération représente la version du fichier PDF. |
| [PolyIntent](./polyintent/) | Énumère les intentions de l'annotation de polygone ou de polyligne. |
| [PredefinedAction](./predefinedaction/) | Définit différentes actions qui peuvent être déclenchées depuis un fichier PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Représente une position d'une marque dans un coin d'une page. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Représente une position d'une marque d'enregistrement sur une page. |
| [ReplyType](./replytype/) | Énumère les types de relations (le "type de réponse") entre l'annotation et celle spécifiée par InReplyTo. |
| [ReturnAction](./returnaction/) | Enum représente une action de flux de travail du programme en cas d'appel de la méthode {@code IWarningCallback.Warning(WarningInfo)}. |
| [Rotation](./rotation/) | Énumération des valeurs de rotation possibles. |
| [SaveFormat](./saveformat/) | Spécifie le format |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Représente les types de lignes pouvant être utilisés dans le document résultant pour dessiner des bordures ou d'autres lignes |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | énumère les types possibles de ressources externes enregistrées |
| [StampIcon](./stampicon/) | Énumère les icônes à utiliser pour l'affichage de l'annotation. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | énumère les types possibles de fichiers image pouvant être enregistrés comme ressources externes lors de la conversion de PDF en SVG |
| [TextAlignment](./textalignment/) | Alignement du texte dans l'annotation. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Modes de traitement du chemin de découpe |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Comportement du remplacement de police. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Modes de transformation linguistique |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Action à effectuer si la police ne contient pas le caractère requis |
| [TextRenderingMode](./textrenderingmode/) | Le mode de rendu du texte, Tmode, détermine si l'affichage du texte doit entraîner le tracé des contours des glyphes, leur remplissage, leur utilisation comme limite de découpe, ou une combinaison de ces trois options. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Spécifie une politique concernant la façon dont la taille de police du texte doit être ajustée pour tenir dans une zone contenant. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Portée où l'opération de remplacement de texte est appliquée REPLACE_FIRST par défaut. Cette option obsolète a été conservée pour la compatibilité. Elle affecte PdfContentEditor et n'a aucun effet sur TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Énumération des valeurs d'alignement vertical possibles. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
