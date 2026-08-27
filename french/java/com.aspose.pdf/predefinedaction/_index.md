---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Définit différentes actions qui peuvent être déclenchées depuis un fichier PDF."
type: docs
weight: 3960
url: /fr/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Définit différentes actions qui peuvent être déclenchées depuis un fichier PDF.

## Champs

| Champ | Description |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | Une action nommée pour trouver le signet actuel. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | Une action nommée pour mettre en surbrillance le signet actuel. |
| [Document_AttachFile](#Document_AttachFile) | Une action nommée pour ajouter une pièce jointe de fichier. |
| [Document_CropPages](#Document_CropPages) | Une action nommée pour recadrer les pages du document. |
| [Document_DeletePages](#Document_DeletePages) | Une action nommée pour supprimer les pages du document. |
| [Document_ExtractPages](#Document_ExtractPages) | Une action nommée pour extraire les pages du document. |
| [Document_InsertPages](#Document_InsertPages) | Une action nommée pour insérer des pages à partir d'un document. |
| [Document_ReplacePages](#Document_ReplacePages) | Une action nommée pour remplacer les pages du document. |
| [Document_RotatePages](#Document_RotatePages) | Une action nommée pour faire pivoter les pages du document. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | Une action nommée pour vérifier l'orthographe dans les commentaires. |
| [Edit_Find](#Edit_Find) | Une action nommée pour trouver. |
| [Edit_Preferences](#Edit_Preferences) | Une action nommée pour modifier les préférences. |
| [Edit_Search](#Edit_Search) | Une action nommée pour la recherche. |
| [File_AttachToEmail](#File_AttachToEmail) | Une action nommée pour joindre le document pdf actuel à un message électronique. |
| [File_Close](#File_Close) | Une action nommée pour fermer le document. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | Une action nommée pour créer un document pdf à partir d'un scanner. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | Une action nommée pour créer un document pdf à partir d'une page web. |
| [File_Exit](#File_Exit) | Une action nommée pour quitter le lecteur pdf. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | Une action nommée pour ouvrir l'organisateur. |
| [File_Print](#File_Print) | Une action nommée pour imprimer le document. |
| [File_Properties](#File_Properties) | Une action nommée pour ouvrir les propriétés du document. |
| [File_SaveAs](#File_SaveAs) | Une action nommée pour enregistrer le document sous un autre nom. |
| [FirstPage](#FirstPage) | Une action nommée pour aller à la première page. |
| [LastPage](#LastPage) | Une action nommée pour aller à la dernière page. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | Une action nommée pour zoomer sur le document. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | Une action nommée pour dézoomer le document. |
| [NextPage](#NextPage) | Une action nommée pour aller à la page suivante. |
| [PageImages_PrintPages](#PageImages_PrintPages) | Une action nommée pour imprimer les pages du document. |
| [PrevPage](#PrevPage) | Une action nommée pour aller à la page précédente. |
| [Print](#Print) | Une action nommée pour ouvrir une boîte de dialogue d'impression. |
| [PrintDialog](#PrintDialog) | Une action nommée pour ouvrir une boîte de dialogue d'impression (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | Une action nommée pour passer à la vue suivante. |
| [View_GoTo_Page](#View_GoTo_Page) | Une action nommée pour aller à une page précise. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | Une action nommée pour aller au document précédent. |
| [View_GoTo_PreView](#View_GoTo_PreView) | Une action nommée pour revenir à la vue précédente. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | Une action nommée pour afficher/masquer le panneau des articles. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | Une action nommée pour afficher/masquer le panneau des pièces jointes. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | Une action nommée pour afficher/masquer le panneau des signets. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | Une action nommée pour afficher/masquer le panneau des commentaires. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | Une action nommée pour afficher/masquer le panneau des champs. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | Une action nommée pour afficher/masquer le panneau des calques. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | Une action nommée pour afficher/masquer le panneau de l'arbre de modèle. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | Une action nommée pour afficher/masquer le panneau des pages. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | Une action nommée pour afficher/masquer le panneau des signatures. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | Une action nommée pour afficher une page unique. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | Une action nommée pour afficher une page unique continue. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | Une action nommée pour afficher les pages en mode deux pages côte à côte. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | Une action nommée pour afficher les pages en mode deux pages côte à côte continu. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | Une action nommée pour afficher/masquer la barre d'outils d'édition avancée. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | Une action nommée pour afficher/masquer la barre d'outils de commentaires. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | Une action nommée pour afficher/masquer la barre d'outils d'édition. |
| [View_Toolbars_File](#View_Toolbars_File) | Une action nommée pour afficher/masquer la barre d'outils de fichiers. |
| [View_Toolbars_Find](#View_Toolbars_Find) | Une action nommée pour afficher/masquer la barre d'outils de recherche. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | Une action nommée pour afficher/masquer la barre d'outils de formulaires. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | Une action nommée pour afficher/masquer la barre d'outils de mesure. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | Une action nommée pour afficher/masquer la barre d'outils des données d'objet. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | Une action nommée pour afficher/masquer la barre d'outils d'affichage de page. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | Une action nommée pour afficher/masquer la barre d'outils de navigation. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | Une action nommée pour afficher/masquer la barre d'outils de production d'impression. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | Une action nommée pour afficher/masquer la barre d'outils des propriétés. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | Une action nommée pour afficher/masquer la barre d'outils de rédaction. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | Une action nommée pour afficher/masquer la barre d'outils de sélection et de zoom. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | Une action nommée pour afficher/masquer la barre d'outils des tâches. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | Une action nommée pour afficher/masquer la barre d'outils de machine à écrire. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | Une action nommée pour afficher les pages à leur taille réelle. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | Une action nommée pour ajuster la page à la hauteur. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | Une action nommée pour ajuster la page. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | Une action nommée pour ajuster la visibilité de la page. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | Une action nommée pour ajuster la page à la largeur. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | Une action nommée pour effectuer un zoom. |
| [Window_FullScreenMode](#Window_FullScreenMode) | Une action nommée pour afficher le document en mode plein écran. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

Une action nommée pour trouver le signet actuel.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

Une action nommée pour mettre en surbrillance le signet actuel.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

Une action nommée pour ajouter une pièce jointe de fichier.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

Une action nommée pour recadrer les pages du document.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

Une action nommée pour supprimer les pages du document.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

Une action nommée pour extraire les pages du document.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

Une action nommée pour insérer des pages à partir d'un document.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

Une action nommée pour remplacer les pages du document.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

Une action nommée pour faire pivoter les pages du document.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

Une action nommée pour vérifier l'orthographe dans les commentaires.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

Une action nommée pour trouver.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

Une action nommée pour modifier les préférences.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

Une action nommée pour la recherche.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

Une action nommée pour joindre le document pdf actuel à un message électronique.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

Une action nommée pour fermer le document.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

Une action nommée pour créer un document pdf à partir d'un scanner.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

Une action nommée pour créer un document pdf à partir d'une page web.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

Une action nommée pour quitter le lecteur pdf.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

Une action nommée pour ouvrir l'organisateur.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

Une action nommée pour imprimer le document.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

Une action nommée pour ouvrir les propriétés du document.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

Une action nommée pour enregistrer le document sous un autre nom.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

Une action nommée pour aller à la première page.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

Une action nommée pour aller à la dernière page.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

Une action nommée pour zoomer sur le document.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

Une action nommée pour dézoomer le document.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

Une action nommée pour aller à la page suivante.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

Une action nommée pour imprimer les pages du document.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

Une action nommée pour aller à la page précédente.

### Print {#Print}
```
public static final PredefinedAction Print
```

Une action nommée pour ouvrir une boîte de dialogue d'impression.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

Une action nommée pour ouvrir une boîte de dialogue d'impression (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

Une action nommée pour passer à la vue suivante.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

Une action nommée pour aller à une page précise.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

Une action nommée pour aller au document précédent.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

Une action nommée pour revenir à la vue précédente.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

Une action nommée pour afficher/masquer le panneau des articles.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

Une action nommée pour afficher/masquer le panneau des pièces jointes.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

Une action nommée pour afficher/masquer le panneau des signets.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

Une action nommée pour afficher/masquer le panneau des commentaires.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

Une action nommée pour afficher/masquer le panneau des champs.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

Une action nommée pour afficher/masquer le panneau des calques.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

Une action nommée pour afficher/masquer le panneau de l'arbre de modèle.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

Une action nommée pour afficher/masquer le panneau des pages.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

Une action nommée pour afficher/masquer le panneau des signatures.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

Une action nommée pour afficher une page unique.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

Une action nommée pour afficher une page unique continue.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

Une action nommée pour afficher les pages en mode deux pages côte à côte.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

Une action nommée pour afficher les pages en mode deux pages côte à côte continu.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

Une action nommée pour afficher/masquer la barre d'outils d'édition avancée.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

Une action nommée pour afficher/masquer la barre d'outils de commentaires.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

Une action nommée pour afficher/masquer la barre d'outils d'édition.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

Une action nommée pour afficher/masquer la barre d'outils de fichiers.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

Une action nommée pour afficher/masquer la barre d'outils de recherche.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

Une action nommée pour afficher/masquer la barre d'outils de formulaires.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

Une action nommée pour afficher/masquer la barre d'outils de mesure.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

Une action nommée pour afficher/masquer la barre d'outils des données d'objet.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

Une action nommée pour afficher/masquer la barre d'outils d'affichage de page.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

Une action nommée pour afficher/masquer la barre d'outils de navigation.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

Une action nommée pour afficher/masquer la barre d'outils de production d'impression.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

Une action nommée pour afficher/masquer la barre d'outils des propriétés.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

Une action nommée pour afficher/masquer la barre d'outils de rédaction.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

Une action nommée pour afficher/masquer la barre d'outils de sélection et de zoom.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

Une action nommée pour afficher/masquer la barre d'outils des tâches.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

Une action nommée pour afficher/masquer la barre d'outils de machine à écrire.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

Une action nommée pour afficher les pages à leur taille réelle.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

Une action nommée pour ajuster la page à la hauteur.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

Une action nommée pour ajuster la page.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

Une action nommée pour ajuster la visibilité de la page.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

Une action nommée pour ajuster la page à la largeur.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

Une action nommée pour effectuer un zoom.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

Une action nommée pour afficher le document en mode plein écran.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static PredefinedAction [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
