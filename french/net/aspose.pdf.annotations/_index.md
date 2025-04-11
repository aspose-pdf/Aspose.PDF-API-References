---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: L'espace de noms Aspose.Pdf.Annotations fournit des classes pour travailler avec divers types d'actions, de destinations et d'autres fonctionnalités du document qui sont traditionnellement appelées interactives, fournissant des moyens pour que l'utilisateur puisse intercommuniquer avec lui.
type: docs
weight: 50
url: /fr/net/aspose.pdf.annotations/
---
L'espace de noms **Aspose.Pdf.Annotations** fournit des classes pour travailler avec divers types d'actions, de destinations et d'autres fonctionnalités du document qui sont traditionnellement appelées interactives, fournissant des moyens pour que l'utilisateur puisse intercommuniquer avec lui.

## Classes

| Classe | Description |
| --- | --- |
| [ActionCollection](./actioncollection/) | Collection d'actions |
| [Annotation](./annotation/) | Classe représentant un objet d'annotation. |
| [AnnotationActionCollection](./annotationactioncollection/) | Représente la collection d'actions d'annotation. |
| [AnnotationCollection](./annotationcollection/) | Classe représentant une collection d'annotations. |
| [AnnotationSelector](./annotationselector/) | Cette classe est utilisée pour sélectionner des annotations en utilisant l'idée du modèle Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Représente une annotation de marque de débordement. |
| [Border](./border/) | Classe représentant les caractéristiques de la bordure d'annotation. |
| [CaretAnnotation](./caretannotation/) | Classe représentant une annotation de caret. |
| [Characteristics](./characteristics/) | Représente les caractéristiques de l'annotation |
| [CircleAnnotation](./circleannotation/) | Classe représentant une annotation de cercle. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe représentant une annotation de barre de couleur. La propriété Color est ignorée, à la place, on utilise ColorsOfCMYK. Lors de la création, le rapport de largeur et de hauteur détermine l'orientation de l'annotation - horizontale ou verticale. Ensuite, il vérifie que le rectangle d'annotation est en dehors du TrimBox, et si ce n'est pas le cas, il est déplacé vers l'emplacement le plus proche en dehors du TrimBox, en tenant compte de l'orientation de l'annotation. Il est possible de réduire la largeur (hauteur) afin que l'annotation s'adapte en dehors du TrimBox. S'il n'y a pas d'espace pour la mise en page, la largeur/hauteur peut être définie sur zéro (dans ce cas, l'annotation est présente sur la page, mais n'est pas affichée). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe abstraite représentant une annotation de figure commune. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Représente les types d'annotations qui sont placées dans les coins de la page imprimée. |
| [CustomExplicitDestination](./customexplicitdestination/) | Représente une destination explicite personnalisée. |
| [Dash](./dash/) | Classe représentant le motif de tiret de ligne. |
| [DefaultAppearance](./defaultappearance/) | Décrit l'apparence par défaut du champ (police, taille et couleur du texte). |
| [DocumentActionCollection](./documentactioncollection/) | Classe décrivant les actions effectuées sur certaines actions avec le document |
| [ExplicitDestination](./explicitdestination/) | Représente la classe de base pour les destinations explicites dans le document PDF. |
| [FdfReader](./fdfreader/) | Classe qui effectue la lecture du format FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe décrivant l'annotation de pièce jointe de fichier. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante s'adapte entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la boîte englobante dans la fenêtre dans l'autre dimension. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que toute la largeur de sa boîte englobante s'adapte dans la fenêtre. Une valeur nulle pour le haut spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que toute la hauteur de sa boîte englobante s'adapte dans la fenêtre. Une valeur nulle pour la gauche spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitExplicitDestination](./fitexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que l'ensemble de la page s'adapte dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la page dans la fenêtre dans l'autre dimension. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que toute la largeur de la page s'adapte dans la fenêtre. Une valeur nulle pour le haut spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées gauche, bas, droite et haut s'adapte entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que toute la hauteur de la page s'adapte dans la fenêtre. Une valeur nulle pour la gauche spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FixedPrint](./fixedprint/) | Représente les données d'impression fixe de l'annotation de filigrane. |
| [FreeTextAnnotation](./freetextannotation/) | Représente une annotation de texte libre qui affiche du texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a pas d'état ouvert ou fermé ; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible. |
| [GoToAction](./gotoaction/) | Représente une action de saut qui change la vue vers une destination spécifiée (page, emplacement et facteur de grossissement). |
| [GoToRemoteAction](./gotoremoteaction/) | Représente une action de saut à distance qui est similaire à une action de saut ordinaire mais qui saute vers une destination dans un autre fichier PDF au lieu du fichier actuel. |
| [GoToURIAction](./gotouriaction/) | Représente une action URI qui provoque la résolution d'une URI. |
| [HideAction](./hideaction/) | Représente une action de masquage qui masque ou affiche une ou plusieurs annotations à l'écran en définissant ou en effaçant leurs indicateurs cachés. |
| [HighlightAnnotation](./highlightannotation/) | Représente une annotation de surlignage qui surligne une plage de texte dans le document. |
| [ImportDataAction](./importdataaction/) | Lors de l'invocation d'une action d'importation de données, les données du format de données de formulaire (FDF) doivent être importées dans le formulaire interactif du document à partir d'un fichier spécifié. |
| [InkAnnotation](./inkannotation/) | Représente un "gribouillage" à main levée composé d'un ou plusieurs chemins disjoints. |
| [JavascriptAction](./javascriptaction/) | Classe représentant une action javascript. |
| [LaunchAction](./launchaction/) | Représente une action de lancement qui lance une application ou ouvre ou imprime un document. |
| [LineAnnotation](./lineannotation/) | Classe représentant une annotation de ligne. |
| [LinkAnnotation](./linkannotation/) | Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à effectuer. |
| [MarkupAnnotation](./markupannotation/) | Classe abstraite représentant une annotation de balisage. |
| [Measure](./measure/) | Classe qui décrit le système de coordonnées de mesure. |
| [MediaClip](./mediaclip/) | Classe décrivant l'objet de clip multimédia de la représentation. |
| [MediaClipData](./mediaclipdata/) | Classe décrivant les données de clip multimédia. |
| [MediaClipSection](./mediaclipsection/) | Cette classe décrit la section de clip multimédia. |
| [MediaRendition](./mediarendition/) | Classe décrivant la représentation multimédia. |
| [MovieAnnotation](./movieannotation/) | Représente une annotation de film qui contient des graphiques animés et du son à présenter sur l'écran de l'ordinateur et à travers les haut-parleurs. Lorsque l'annotation est activée, le film est joué. |
| [NamedAction](./namedaction/) | Représente des actions nommées que les applications de visualisation PDF sont censées prendre en charge. |
| [NamedDestination](./nameddestination/) | Au lieu d'être défini directement avec la syntaxe explicite, une destination peut être référencée indirectement par le biais d'un objet de nom ou d'une chaîne d'octets. |
| [PageInformationAnnotation](./pageinformationannotation/) | Représente une annotation d'information de page dans un document PDF. Cette annotation contient le nom de fichier, le numéro de page et la date et l'heure de création de l'annotation. |
| [PDF3DAnnotation](./pdf3dannotation/) | Classe PDF3DAnnotation. Cette classe ne peut pas être héritée. |
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
| [PdfAction](./pdfaction/) | Représente une action dans le document PDF |
| [PdfActionCollection](./pdfactioncollection/) | Classe décrivant la liste des actions. |
| [PolyAnnotation](./polyannotation/) | Classe de base abstraite pour les annotations poly-. |
| [PolygonAnnotation](./polygonannotation/) | Classe représentant une annotation de polygone. |
| [PolylineAnnotation](./polylineannotation/) | Représente une annotation de polyligne qui est similaire à un polygone, sauf que le premier et le dernier sommet ne sont pas implicitement connectés. |
| [PopupAnnotation](./popupannotation/) | Représente l'annotation contextuelle qui affiche du texte dans une fenêtre contextuelle pour saisie et édition. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe abstraite représentant une annotation de marque d'imprimante. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fournit des méthodes d'extension pour l'énumération [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Représente une annotation de censure. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Représente une annotation de marque d'enregistrement. |
| [Rendition](./rendition/) | Classe qui décrit l'objet de représentation de l'annotation de représentation. |
| [RenditionAction](./renditionaction/) | Une action de représentation qui contrôle la lecture de contenu multimédia. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe décrivant RichMediaAnnotation qui permet d'incorporer des données vidéo/audio dans un document PDF. |
| [ScreenAnnotation](./screenannotation/) | Une annotation d'écran qui spécifie une région d'une page sur laquelle des clips multimédias peuvent être lus. |
| [SelectorRendition](./selectorrendition/) | Classe décrivant la représentation du sélecteur. |
| [SoundAnnotation](./soundannotation/) | Représente une annotation sonore qui contient un son enregistré à partir du microphone de l'ordinateur ou importé d'un fichier. |
| [SoundData](./sounddata/) | Représente des données sonores définissant le son à jouer lorsque l'annotation est activée. |
| [SoundSampleData](./soundsampledata/) | Représente des entrées supplémentaires spécifiques à un objet sonore (Section 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Classe représentant une annotation carrée. |
| [SquigglyAnnotation](./squigglyannotation/) | Représente l'annotation ondulée qui apparaît comme un soulignement en dents de scie dans le texte d'un document. |
| [StampAnnotation](./stampannotation/) | Représente une annotation de tampon en caoutchouc. Ce type d'annotation affiche du texte ou des graphiques destinés à ressembler à s'ils avaient été estampillés sur la page avec un tampon en caoutchouc. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Représente une annotation de barré qui apparaît comme un barré dans le texte du document. |
| [SubmitFormAction](./submitformaction/) | Classe qui décrit l'action de soumission de formulaire. |
| [TextAnnotation](./textannotation/) | Représente une annotation de texte qui est une 'note autocollante' attachée à un point dans le document PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe de base abstraite pour les annotations de balisage de texte. |
| [TextStyle](./textstyle/) | Classe représentant le style de texte dans l'annotation |
| [TrimMarkAnnotation](./trimmarkannotation/) | Représente une annotation de marque de coupe. |
| [UnderlineAnnotation](./underlineannotation/) | Représente une annotation de soulignement qui apparaît comme un soulignement dans le texte du document. |
| [WatermarkAnnotation](./watermarkannotation/) | Classe décrivant l'objet d'annotation de filigrane. |
| [WidgetAnnotation](./widgetannotation/) | Classe représentant une annotation de widget. |
| [XfdfReader](./xfdfreader/) | Classe qui effectue la lecture du format XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Définit le visiteur pour visiter différentes annotations de document. |
| [IAppointment](./iappointment/) | Représente l'interface générale pour les actions et les destinations. |
## Énumération

| Énumération | Description |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation. |
| [AnnotationState](./annotationstate/) | L'énumération des états auxquels l'annotation originale peut être définie. |
| [AnnotationStateModel](./annotationstatemodel/) | Le modèle d'état correspondant à l'état de l'annotation. |
| [AnnotationType](./annotationtype/) | Énumération des types d'annotations. |
| [BorderEffect](./bordereffect/) | Décrit l'effet qui doit être appliqué à la bordure des annotations. |
| [BorderStyle](./borderstyle/) | Décrit le style de la bordure de l'annotation. |
| [CapStyle](./capstyle/) | Style de terminaison de ligne de l'annotation d'encre. |
| [CaptionPosition](./captionposition/) | Énumération des positions de légende de l'annotation. |
| [CaretSymbol](./caretsymbol/) | Un symbole à associer au caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Couleurs incluses dans le modèle de couleur CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Énumère les types de destinations explicites. |
| [FileIcon](./fileicon/) | Une icône à utiliser pour afficher l'annotation. |
| [FreeTextIntent](./freetextintent/) | Énumère les intentions de l'annotation de texte libre. |
| [HighlightingMode](./highlightingmode/) | Énumère le mode de surlignage de l'annotation, l'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu enfoncé à l'intérieur de sa zone active. |
| [Justification](./justification/) | Énumère les formes de justification à utiliser pour afficher le texte de l'annotation. |
| [LaunchActionOperation](./launchactionoperation/) | Énumère les opérations à effectuer avec le document lors de l'exécution de l'action de lancement. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType : ensemble de types de schémas d'éclairage. |
| [LineEnding](./lineending/) | Énumère les styles de terminaison de ligne à utiliser pour dessiner la ligne. |
| [LineIntent](./lineintent/) | Énumère les intentions de l'annotation de ligne. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation : ensemble de modes d'activation d'annotation 3D. |
| [PolyIntent](./polyintent/) | Énumère les intentions de l'annotation de polygone ou de polyligne. |
| [PredefinedAction](./predefinedaction/) | Définit différentes actions qui peuvent être déclenchées à partir d'un fichier PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Représente une position d'une marque dans un coin d'une page. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Représente une position d'une marque d'enregistrement sur une page. |
| [PrinterMarksKind](./printermarkskind/) | Spécifie les types de marques d'imprimante à ajouter à un document. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType : ensemble de types de modes de rendu |
| [RenditionOperation](./renditionoperation/) | L'opération à effectuer lorsque l'action est déclenchée. |
| [RenditionType](./renditiontype/) | Énumération décrivant les types possibles de représentation. |
| [ReplyType](./replytype/) | Énumère les types de relations (le "type de réponse") entre l'annotation et une spécifiée par InReplyTo. |
| [SoundEncoding](./soundencoding/) | Le format d'encodage pour les données d'échantillon. |
| [SoundIcon](./soundicon/) | Énumère les icônes à utiliser pour afficher l'annotation. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Le format d'encodage pour les données d'échantillon sonore. |
| [StampIcon](./stampicon/) | Énumère les icônes à utiliser pour afficher l'annotation. |
| [TextIcon](./texticon/) | Énumère les icônes à utiliser pour afficher l'annotation. |