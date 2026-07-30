---
title: "Aspose.Pdf.Annotations"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "L'espace de noms Aspose.Pdf.Annotations fournit des classes pour travailler avec différents types d'actions, de destinations et d'autres fonctionnalités du document traditionnellement appelées interactives, offrant des moyens pour l'utilisateur d'interagir avec lui."
type: docs
weight: 50
url: /fr/net/aspose.pdf.annotations/
---
L’espace de noms **Aspose.Pdf.Annotations** fournit des classes pour travailler avec différents types d’actions, de destinations et d’autres fonctionnalités du document traditionnellement appelées interactives, permettant à l’utilisateur d’interagir avec celui‑ci.

## Classes

| Classe | Description |
| --- | --- |
| [ActionCollection](./actioncollection/) | Collection d'actions |
| [Annotation](./annotation/) | Classe représentant l'objet d'annotation. |
| [AnnotationActionCollection](./annotationactioncollection/) | Représente la collection d'actions d'annotation. |
| [AnnotationCollection](./annotationcollection/) | Classe représentant la collection d'annotations. |
| [AnnotationSelector](./annotationselector/) | Cette classe est utilisée pour sélectionner des annotations en utilisant le concept de modèle Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Représente une annotation de repère de débordement. |
| [Border](./border/) | Classe représentant les caractéristiques de la bordure d'annotation. |
| [CaretAnnotation](./caretannotation/) | Classe représentant l'annotation Caret. |
| [Characteristics](./characteristics/) | Représente les caractéristiques de l'annotation |
| [CircleAnnotation](./circleannotation/) | Classe représentant l'annotation Cercle. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe représentant l'annotation ColorBarAnnotation. La propriété Color est ignorée, à la place la couleur ColorsOfCMYK est utilisée. Lors de la création, le rapport entre la largeur et la hauteur détermine l'orientation de l'annotation – horizontale ou verticale. Ensuite, il vérifie que le rectangle de l'annotation se trouve en dehors du TrimBox, et si ce n'est pas le cas, il est déplacé vers l'emplacement le plus proche à l'extérieur du TrimBox, en tenant compte de l'orientation de l'annotation. Il est possible de réduire la largeur (ou la hauteur) afin que l'annotation tienne en dehors du TrimBox. S'il n'y a pas d'espace pour la mise en page, la largeur/hauteur peut être réglée à zéro (dans ce cas, l'annotation est présente sur la page, mais n'est pas affichée). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe abstraite représentant une annotation de figure commune. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Représente les types d'annotation placés dans les coins de la page imprimée. |
| [CustomExplicitDestination](./customexplicitdestination/) | Représente une destination explicite personnalisée. |
| [Dash](./dash/) | Classe représentant le motif de tirets de ligne. |
| [DefaultAppearance](./defaultappearance/) | Décrit l'apparence par défaut du champ (police, taille du texte et couleur). |
| [DocumentActionCollection](./documentactioncollection/) | Classe décrivant les actions effectuées sur certaines actions avec le document. |
| [ExplicitDestination](./explicitdestination/) | Représente la classe de base pour les destinations explicites dans un document PDF. |
| [FdfReader](./fdfreader/) | Classe qui effectue la lecture du format FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe décrivant l'annotation de pièce jointe de fichier. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la boîte englobante dans la fenêtre dans l'autre dimension. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur totale de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur totale de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitExplicitDestination](./fitexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que la page entière tienne dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la page dans la fenêtre dans l'autre dimension. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur totale de la page tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées left, bottom, right et top tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Représente une destination explicite qui affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur totale de la page tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| [FixedPrint](./fixedprint/) | Représente les données d'impression fixes de l'annotation Watermark. |
| [FreeTextAnnotation](./freetextannotation/) | Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé ; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible. |
| [GoToAction](./gotoaction/) | Représente une action de navigation qui change la vue vers une destination spécifiée (page, emplacement et facteur d'agrandissement). |
| [GoToRemoteAction](./gotoremoteaction/) | Représente une action de navigation distante similaire à une action de navigation ordinaire mais qui saute vers une destination dans un autre fichier PDF au lieu du fichier actuel. |
| [GoToURIAction](./gotouriaction/) | Représente une action URI qui entraîne la résolution d'un URI. |
| [HideAction](./hideaction/) | Représente une action de masquage qui masque ou affiche une ou plusieurs annotations à l'écran en définissant ou en effaçant leurs indicateurs Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Représente une annotation de surlignage qui met en évidence une plage de texte dans le document. |
| [ImportDataAction](./importdataaction/) | Lors de l'invocation d'une action import-data, les données Forms Data Format (FDF) doivent être importées dans le formulaire interactif du document à partir d'un fichier spécifié. |
| [InkAnnotation](./inkannotation/) | Représente un « gribouillage » à main levée composé d'un ou plusieurs chemins disjoints. |
| [JavascriptAction](./javascriptaction/) | Classe représentant l'action javascript. |
| [LaunchAction](./launchaction/) | Représente une action de lancement qui lance une application ou ouvre ou imprime un document. |
| [LineAnnotation](./lineannotation/) | Classe représentant une annotation de ligne. |
| [LinkAnnotation](./linkannotation/) | Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à exécuter. |
| [MarkupAnnotation](./markupannotation/) | Classe abstraite représentant une annotation de balisage. |
| [Measure](./measure/) | Classe qui décrit le système de coordonnées de mesure. |
| [MediaClip](./mediaclip/) | Classe décrivant l'objet de clip média de la représentation. |
| [MediaClipData](./mediaclipdata/) | Classe décrivant les données du clip média. |
| [MediaClipSection](./mediaclipsection/) | Cette classe décrit la section du clip média. |
| [MediaRendition](./mediarendition/) | Classe décrivant la représentation média. |
| [MovieAnnotation](./movieannotation/) | Représente une annotation vidéo qui contient des graphiques animés et du son à présenter sur l'écran de l'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, la vidéo est lue. |
| [NamedAction](./namedaction/) | Représente des actions nommées que les applications de visualisation PDF sont censées prendre en charge. |
| [NamedDestination](./nameddestination/) | Au lieu d'être définie directement avec la syntaxe explicite, une destination peut être référencée indirectement au moyen d'un objet nom ou d'une chaîne d'octets. |
| [PageInformationAnnotation](./pageinformationannotation/) | Représente une annotation d'informations de page dans un document PDF. Cette annotation contient le nom du fichier, le numéro de page, ainsi que la date et l'heure de création de l'annotation. |
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
| [PdfAction](./pdfaction/) | Représente une action dans un document PDF |
| [PdfActionCollection](./pdfactioncollection/) | La classe décrit la liste des actions. |
| [PolyAnnotation](./polyannotation/) | Classe de base abstraite pour les annotations poly-. |
| [PolygonAnnotation](./polygonannotation/) | Classe représentant l'annotation polygon. |
| [PolylineAnnotation](./polylineannotation/) | Représente l'annotation polyline qui est similaire à un polygone, sauf que le premier et le dernier sommet ne sont pas implicitement connectés. |
| [PopupAnnotation](./popupannotation/) | Représente l'annotation pop-up qui affiche du texte dans une fenêtre pop-up pour la saisie et la modification. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe abstraite représentant l'annotation de marque d'imprimante. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fournit des méthodes d'extension pour l'énumération [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Représente l'annotation Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Représente une annotation de repère d'enregistrement. |
| [Rendition](./rendition/) | Classe qui décrit l'objet de rendu de RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Une action de rendu qui contrôle la lecture du contenu multimédia. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe décrivant RichMediaAnnotation qui permet d'intégrer des données vidéo/audio dans un document PDF. |
| [ScreenAnnotation](./screenannotation/) | Une annotation d'écran qui spécifie une région d'une page sur laquelle des clips multimédias peuvent être lus. |
| [SelectorRendition](./selectorrendition/) | Classe décrivant le rendu du sélecteur. |
| [SoundAnnotation](./soundannotation/) | Représente une annotation sonore qui contient un son enregistré depuis le microphone de l'ordinateur ou importé depuis un fichier. |
| [SoundData](./sounddata/) | Représente des données sonores définissant le son à lire lorsque l'annotation est activée. |
| [SoundSampleData](./soundsampledata/) | Représente des entrées supplémentaires spécifiques à un objet sonore (Section 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Classe représentant l'annotation carrée. |
| [SquigglyAnnotation](./squigglyannotation/) | Représente l'annotation ondulée qui apparaît comme un soulignement irrégulier dans le texte d'un document. |
| [StampAnnotation](./stampannotation/) | Représente l'annotation tampon en caoutchouc. Ce type d'annotation affiche du texte ou des graphiques destinés à ressembler à une impression sur la page avec un tampon en caoutchouc. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Représente une annotation de barré qui apparaît comme un texte barré dans le document. |
| [SubmitFormAction](./submitformaction/) | Classe qui décrit l'action de soumission de formulaire. |
| [TextAnnotation](./textannotation/) | Représente une annotation de texte qui est une « note autocollante » attachée à un point du document PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe de base abstraite pour les annotations de balisage de texte. |
| [TextStyle](./textstyle/) | Classe représentant le style du texte dans l'annotation |
| [TrimMarkAnnotation](./trimmarkannotation/) | Représente une annotation de repère de coupe. |
| [UnderlineAnnotation](./underlineannotation/) | Représente une annotation de soulignement qui apparaît comme un soulignement dans le texte du document. |
| [WatermarkAnnotation](./watermarkannotation/) | Classe décrivant l'objet d'annotation de filigrane. |
| [WidgetAnnotation](./widgetannotation/) | Classe représentant une annotation de widget. |
| [XfdfReader](./xfdfreader/) | Classe qui effectue la lecture du format XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom indique que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Définit le visiteur pour parcourir les différentes annotations de document. |
| [IAppointment](./iappointment/) | Représente une interface générale pour les actions et les destinations. |
## Énumération

| Énumération | Description |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation. |
| [AnnotationState](./annotationstate/) | L'énumération des états auxquels l'annotation d'origine peut être définie. |
| [AnnotationStateModel](./annotationstatemodel/) | Le modèle d'état correspondant à l'état de l'annotation. |
| [AnnotationType](./annotationtype/) | Énumération des types d'annotation. |
| [BorderEffect](./bordereffect/) | Décrit l'effet qui doit être appliqué à la bordure des annotations. |
| [BorderStyle](./borderstyle/) | Décrit le style de la bordure de l'annotation. |
| [CapStyle](./capstyle/) | Style de terminaison de ligne d'une annotation d'encre. |
| [CaptionPosition](./captionposition/) | Énumération du positionnement de la légende de l'annotation. |
| [CaretSymbol](./caretsymbol/) | Un symbole à associer au curseur. |
| [ColorsOfCMYK](./colorsofcmyk/) | Couleurs incluses dans le modèle de couleur CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Énumère les types de destinations explicites. |
| [FileIcon](./fileicon/) | Une icône à utiliser pour afficher l'annotation. |
| [FreeTextIntent](./freetextintent/) | Énumère les intentions de l'annotation de texte libre. |
| [HighlightingMode](./highlightingmode/) | Énumère le mode de mise en évidence de l'annotation, l'effet visuel à utiliser lorsque le bouton de la souris est enfoncé ou maintenu dans sa zone active. |
| [Justification](./justification/) | Énumère les formes de justification à utiliser pour l'affichage du texte de l'annotation. |
| [LaunchActionOperation](./launchactionoperation/) | Énumère les opérations à effectuer avec le document lors de l'exécution de l'action de lancement. |
| [LightingSchemeType](./lightingschemetype/) | Énumération LightingSchemeType : ensemble de types de schémas d'éclairage. |
| [LineEnding](./lineending/) | Énumère les styles de terminaison de ligne à utiliser lors du tracé de la ligne. |
| [LineIntent](./lineintent/) | Énumère les intentions de l'annotation de ligne. |
| [PDF3DActivation](./pdf3dactivation/) | Énumération PDF3DActivation : ensemble des modes d'activation d'annotation 3D. |
| [PolyIntent](./polyintent/) | Énumère les intentions de l'annotation de polygone ou de polyligne. |
| [PredefinedAction](./predefinedaction/) | Définit différentes actions pouvant être déclenchées depuis un fichier PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Représente une position d'une marque dans un coin d'une page. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Représente une position d'une marque d'enregistrement sur une page. |
| [PrinterMarksKind](./printermarkskind/) | Spécifie les types de marques d'imprimante à ajouter à un document. |
| [RenderModeType](./rendermodetype/) | Énumération RenderModeType : ensemble des types de mode de rendu |
| [RenditionOperation](./renditionoperation/) | L'opération à exécuter lorsque l'action est déclenchée. |
| [RenditionType](./renditiontype/) | L'énumération décrit les types possibles de Rendition. |
| [ReplyType](./replytype/) | Énumère les types de relations (le "type de réponse") entre l'annotation et celle spécifiée par InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Options pour le style des fragments de texte dans RichText. |
| [SoundEncoding](./soundencoding/) | Le format d'encodage des données d'exemple. |
| [SoundIcon](./soundicon/) | Énumère les icônes à utiliser pour afficher l'annotation. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Le format d'encodage des données d'échantillon sonore. |
| [StampIcon](./stampicon/) | Énumère les icônes à utiliser pour afficher l'annotation. |
| [TextIcon](./texticon/) | Énumère les icônes à utiliser pour afficher l'annotation. |


