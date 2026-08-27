---
title: "Page"
linktitle: "Page"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant une page d'un document PDF."
type: docs
weight: 3310
url: /fr/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Classe représentant une page d'un document PDF.

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte l'objet visiteur {@code AnnotationSelector} qui fournit des fonctionnalités pour travailler avec les annotations. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepte l'objet visiteur {@code ImagePlacementAbsorber} qui fournit des fonctionnalités pour travailler avec des objets de placement d'image. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accepte l'objet visiteur {@code TextAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepte l'objet visiteur {@code TextFragmentAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Ajoute des graphiques à la page. Fonctionne plus rapidement que l'ajout d'éléments un par un avec la méthode GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Ajoute des graphiques à la page. Fonctionne plus rapidement que l'ajout d'éléments un par un avec la méthode GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Place un tampon sur la page. Le tampon peut être un numéro de page, une image ou un texte simple, par ex. un logo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Convertit la page actuelle en bitmap BMP puis renvoie un tableau d'octets. |
| [asXml](#asXml--) | Convertit la page actuelle en XML avec un encodage UTF‑8. |
| [calculateContentBBox](#calculateContentBBox--) | Calcule la valeur bbox – rectangle contenant le contenu sans marges visibles. |
| [clearContents](#clearContents--) | À usage interne uniquement |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Convertit la page en PNG pour le flux d'images DSR, OMR, OCR. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Supprime les graphiques de la page. Fonctionne plus rapidement que la suppression d'éléments un par un avec la méthode {@link GraphicElement#remove}. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Libère la mémoire. Cette méthode est obsolète, utilisez close() à la place. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Renvoie la liste des opérateurs qui utilisent la ressource avec le nom spécifié. |
| [findReferences](#findReferences-java.lang.String-) | <p> Trouver les références </p> |
| [flatten](#flatten--) | Supprime tous les champs statiques situés sur la page et place leurs valeurs à la place. |
| [freeMemory](#freeMemory--) | Efface les données en cache |
| [getActions](#getActions--) | Obtient la collection des propriétés de la page. |
| [getAnnotations](#getAnnotations--) | Obtient la collection des annotations de la page. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Obtient la boîte d'art de la page. </p> |
| [getArtifacts](#getArtifacts--) | Obtient la collection des artefacts sur la page. |
| [getBackground](#getBackground--) | Obtient la couleur d'arrière-plan de la page. |
| [getBackgroundImage](#getBackgroundImage--) | Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| [getBleedBox](#getBleedBox--) | <p> Obtient la boîte de débordement de la page. </p> |
| [getColorType](#getColorType--) | Obtient le type de couleur des pages en fonction des informations provenant des opérateurs SetColor, des images et des formulaires. |
| [getContents](#getContents--) | <p> Obtient la collection d'opérateurs dans le flux de contenu de la page. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Obtient l'appender de contenu actuel. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Obtient la boîte de recadrage de la page. </p> |
| [getDocument](#getDocument--) | Obtenir le document |
| [getDuration](#getDuration--) | <p> Obtient la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors de la présentation. Retourne -1 si la durée n'est pas définie. </p> <hr> Exemple montrant comment obtenir la durée de la page <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Pour usage interne uniquement |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Obtient la liste d'objets Field dans l'ordre de tabulation sur cette page. |
| [getFooter](#getFooter--) | Obtient le pied de page de la page. |
| [getGroup](#getGroup--) | Obtient une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparente. |
| [getHeader](#getHeader--) | Obtient l'en-tête de la page. |
| [getLayers](#getLayers--) | Obtient la collection de calques. |
| [getMediaBox](#getMediaBox--) | <p> Obtient la boîte média de la page. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Obtient le style de ligne pour les notes. (pour le générateur uniquement, non rempli lors de la lecture du document) |
| [getNotifications](#getNotifications--) | Renvoie les notifications concernant les opérations internes avec le contenu de la page. (Seules les notifications concernant les événements de paragraphe dans les scénarios d'ajout de texte sont prises en charge pour le moment.) |
| [getNumber](#getNumber--) | Obtenir le numéro de la page. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Événement pour personnaliser l'en-tête et le pied de page. |
| [getPageInfo](#getPageInfo--) | Obtient les informations de la page. (pour le générateur uniquement, non rempli lors de la lecture du document). |
| [getPageRect](#getPageRect-boolean-) | Renvoie le rectangle de la page selon son CropBox (ou MediaBox si CropBox est nul). |
| [getParagraphs](#getParagraphs--) | Obtient les paragraphes. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Renvoie le rectangle de la page selon son CropBox et MediaBox ; </p> Internal |
| [getRect](#getRect--) | <p> Renvoie le rectangle de la page selon son CropBox et MediaBox ; Pour la lecture : la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour l'écriture : la boîte média de la page est toujours définie. </p> |
| [getResources](#getResources--) | Récupère les ressources associées à la page. |
| [getResourcesField](#getResourcesField--) | <p> Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Obtient la rotation de la page. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Obtient la matrice de transformation de la page. |
| [getTabOrder](#getTabOrder--) | Obtient l'ordre des onglets de la page. Valeurs possibles : Row, Column. Par défaut, Manual |
| [getTocInfo](#getTocInfo--) | Obtient les informations de la table des matières. |
| [getTrimBox](#getTrimBox--) | <p> Obtient la boîte de rognage de la page. </p> |
| [getUserUnit](#getUserUnit--) | Obtient ou définit la valeur UserUnit. Un nombre positif indiquant la taille des unités d'espace utilisateur par défaut, en multiples de 1 / 72 pouce. La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin de supprimer cette entrée dans la page. |
| [getWatermark](#getWatermark--) | Obtient le filigrane de la page. |
| [hasVectorGraphics](#hasVectorGraphics--) | Détecte la présence de graphiques vectoriels, s'ils sont présents sur la page. |
| [intToRotation](#intToRotation-int-) | Convertit la valeur entière en le membre d'énumération de rotation correspondant. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page. Value : Value indique si les paragraphes seront ajoutés après le dernier paragraphe de la page. Les paragraphes seront ajoutés après le dernier paragraphe de la page si value est true. |
| [isBlank](#isBlank-double-) | Obtient le drapeau indiquant si la page est vide ou non. |
| [isBlank](#isBlank-double-boolean-) | Obtient le drapeau indiquant si la page est vide ou non. |
| [makeGrayscale](#makeGrayscale--) | Convertit la page en niveaux de gris. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Fusionne toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Fusionne toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié et l'Id de groupe de contenu optionnel. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Supprimer les références d'objet |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Supprime les références à XObject du contenu de la page (c.-à-d. tous les opérateurs Do qui utilisent le nom de l'objet). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Redimensionne la page. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Convertit le membre d'énumération de rotation en valeur entière. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Envoie la page au processus avec le dispositif de page fourni. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Envoie la page au processus avec le dispositif de page fourni. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page. Value : Value indique si les paragraphes seront ajoutés après le dernier paragraphe de la page. Les paragraphes seront ajoutés après le dernier paragraphe de la page si value est true. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Définit la boîte d'art de la page. |
| [setBackground](#setBackground-java.awt.Color-) | Définit la couleur d'arrière-plan de la page. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Définit la couleur d'arrière-plan de la page. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Définit la boîte de débordement de la page. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Définit la boîte de recadrage de la page. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Définit la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors de la présentation. Retourne -1 si la durée n'est pas définie. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Pour usage interne uniquement |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Définit le Footer de la page. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Définit une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparent. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Définit l'en-tête de la page. |
| [setLayers](#setLayers-java.util.ArrayList-) | Définit la collection de calques. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Définit la collection de calques. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Définit la boîte média de la page. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Définit le style de ligne pour les notes.(pour le générateur uniquement, non rempli lors de la lecture du document) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Définit les informations de la page.(pour le générateur uniquement, non rempli lors de la lecture du document). |
| [setPageSize](#setPageSize-double-double-) | Définit la taille de la page. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Définit les paragraphes. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Obtient ou définit le rectangle de la page. Pour la lecture : la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour l'écriture : la boîte média de la page est toujours définie. est renvoyée. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Définit la rotation de la page. |
| [setTabOrder](#setTabOrder-int-) | Définit l'ordre des onglets de la page. Valeurs possibles : Row, Column. Par défaut, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Définit les informations de la table des matières. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Définir la transition |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Définit la boîte de rognage de la page. |
| [setUserUnit](#setUserUnit-double-) | Obtient ou définit la valeur UserUnit. Un nombre positif indiquant la taille des unités d'espace utilisateur par défaut, en multiples de 1 / 72 pouce. La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin de supprimer cette entrée dans la page. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Définit le filigrane de la page. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Essaie d'enregistrer les graphiques vectoriels s'ils sont présents sur la page. Le format d'enregistrement est SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte l'objet visiteur {@code AnnotationSelector} qui fournit des fonctionnalités pour travailler avec les annotations.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accepte l'objet visiteur {@code ImagePlacementAbsorber} qui fournit des fonctionnalités pour travailler avec des objets de placement d'image.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accepte l'objet visiteur {@code TextAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accepte l'objet visiteur {@code TextFragmentAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Ajoute des graphiques à la page. Fonctionne plus rapidement que l'ajout d'éléments un par un avec la méthode GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Ajoute des graphiques à la page. Fonctionne plus rapidement que l'ajout d'éléments un par un avec la méthode GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Place un tampon sur la page. Le tampon peut être un numéro de page, une image ou un texte simple, par ex. un logo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Convertit la page actuelle en bitmap BMP puis renvoie un tableau d'octets.

### asXml {#asXml--}
```
public String asXml()
```

Convertit la page actuelle en XML avec un encodage UTF‑8.

**Returns:**
Chaîne XML convertie.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Calcule la valeur bbox – rectangle contenant le contenu sans marges visibles.

**Returns:**
Valeur Bbox - rectangle contenant le contenu sans marges visibles

### clearContents {#clearContents--}
```
public void clearContents()
```

À usage interne uniquement

### close {#close--}
```
public void close()
```

Ferme toutes les ressources utilisées par ce document.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Convertit la page en PNG pour le flux d'images DSR, OMR, OCR.

**Returns:**
Flux d'image dans un tableau byte[]

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Supprime les graphiques de la page. Fonctionne plus rapidement que la suppression d'éléments un par un avec la méthode {@link GraphicElement#remove}.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libère la mémoire. Cette méthode est obsolète, utilisez close() à la place.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Renvoie la liste des opérateurs qui utilisent la ressource avec le nom spécifié.

### findReferences {#findReferences-java.lang.String-}
<p> Trouver les références </p>

### flatten {#flatten--}
```
public void flatten()
```

Supprime tous les champs statiques situés sur la page et place leurs valeurs à la place.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Efface les données en cache

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Obtient la collection des propriétés de la page.

**Returns:**
Valeur PageActionCollection

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Obtient la collection des annotations de la page. {@code Annotations}

**Returns:**
Valeur AnnotationCollection

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Obtient la boîte d'art de la page. </p>

**Returns:**
Valeur Rectangle <hr> <pre> Exemple montre comment obtenir l'art box de la page : Document document = new Document(\"sample.pdf\"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Obtient la collection des artefacts sur la page.

**Returns:**
Valeur ArtifactCollection

### getBackground {#getBackground--}
```
public Color getBackground()
```

Obtient la couleur d'arrière-plan de la page.

**Returns:**
Valeur de couleur

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document).

**Returns:**
Instance d'image

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Obtient la boîte de débordement de la page. </p>

**Returns:**
Valeur Rectangle <hr> <pre> Exemple montre comment obtenir la boîte bleed de la page : Document document = new Document(\"sample.pdf\"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Obtient le type de couleur des pages en fonction des informations provenant des opérateurs SetColor, des images et des formulaires.

**Returns:**
Élément ColorType @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Obtient la collection d'opérateurs dans le flux de contenu de la page. {@code OperatorCollection} </p>

**Returns:**
Objet OperatorCollection <hr> <pre> Exemple montre comment parcourir le flux d'opérateurs de la page. Document document = new Document(\"sample.pdf\"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Obtient l'appender de contenu actuel. {@code ContentsAppender}

**Returns:**
Valeur de ContentsAppender

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Obtient la boîte de recadrage de la page. </p>

**Returns:**
Valeur de Rectangle <hr> <pre> Exemple montre comment obtenir la zone de rognage de la page : Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtenir le document

**Returns:**
Objet IDocument

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Obtient la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors de la présentation. Retourne -1 si la durée n'est pas définie. </p> <hr> Exemple montrant comment obtenir la durée de la page <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
valeur double

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Pour usage interne uniquement

**Returns:**
instance interne

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Obtient la liste d'objets Field dans l'ordre de tabulation sur cette page.

**Returns:**
Liste d'objets de champ

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Obtient le pied de page de la page.

**Returns:**
Le Footer de la page.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Obtient une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparente.

**Returns:**
Valeur du groupe

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Obtient l'en-tête de la page.

**Returns:**
Le Header de la page.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Obtient la collection de calques.

**Returns:**
Valeur : la collection des calques.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Obtient la boîte média de la page. </p>

**Returns:**
Valeur de Rectangle <hr> <pre> Exemple montre comment obtenir la boîte média de la page : Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Obtient le style de ligne pour les notes. (pour le générateur uniquement, non rempli lors de la lecture du document)

**Returns:**
Valeur de GraphInfo

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Renvoie les notifications concernant les opérations internes avec le contenu de la page. (Seules les notifications concernant les événements de paragraphe dans les scénarios d'ajout de texte sont prises en charge pour le moment.)

**Returns:**
Chaîne représentant les notifications concernant les opérations internes avec le contenu de la page.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Obtenir le numéro de la page.

**Returns:**
valeur int

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Événement pour personnaliser l'en-tête et le pied de page.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instance}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtient les informations de la page. (pour le générateur uniquement, non rempli lors de la lecture du document).

**Returns:**
Les informations de la page.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Renvoie le rectangle de la page selon son CropBox (ou MediaBox si CropBox est nul).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| considerRotation |  | Si vrai, la rotation de la page sera prise en compte dans le calcul du rectangle. |

**Returns:**
Rectangle de la page.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtient les paragraphes.

**Returns:**
Les paragraphes.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Renvoie le rectangle de la page selon son CropBox et MediaBox ; </p> Internal

**Returns:**
Valeur de Rectangle <hr> <pre> Exemple montre comment obtenir le rectangle de la page : Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Renvoie le rectangle de la page selon son CropBox et MediaBox ; Pour la lecture : la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour l'écriture : la boîte média de la page est toujours définie. </p>

**Returns:**
Valeur de Rectangle <hr> <pre> Exemple montre comment obtenir le rectangle de la page : Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Récupère les ressources associées à la page.

**Returns:**
Un objet {@code Resources}({@link #getResources()}) représentant les ressources de la page.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. {@code Resources} </p>

**Returns:**
Valeur de Resources <hr> <pre> Exemple montre comment parcourir les images de la page : Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Obtient la rotation de la page. </p>

**Returns:**
Élément Rotation <hr> <pre> Exemple montre comment déterminer la rotation de la page. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Obtient la matrice de transformation de la page.

**Returns:**
Valeur de Matrix

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Obtient l'ordre des onglets de la page. Valeurs possibles : Row, Column. Par défaut, Manual

**Returns:**
Valeur de TabOrder @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Obtient les informations de la table des matières.

**Returns:**
Les informations de la table des matières - null par défaut. Si elle est définie, cette page contiendra la table des matières.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Obtient la boîte de rognage de la page. </p>

**Returns:**
Valeur de Rectangle <hr> <pre> Exemple montre comment obtenir la boîte de rognage de la page : Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Obtient ou définit la valeur UserUnit. Un nombre positif indiquant la taille des unités d'espace utilisateur par défaut, en multiples de 1 / 72 pouce. La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin de supprimer cette entrée dans la page.

**Returns:**
valeur double

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Obtient le filigrane de la page.

**Returns:**
Valeur de Watermark

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Détecte la présence de graphiques vectoriels, s'ils sont présents sur la page.

**Returns:**
Vrai si la page contient des opérateurs de construction de chemin ; sinon, Faux.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Convertit la valeur entière en le membre d'énumération de rotation correspondant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotation |  | Valeur entière à convertir |

**Returns:**
Membre d'énumération Rotation @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page. Value : Value indique si les paragraphes seront ajoutés après le dernier paragraphe de la page. Les paragraphes seront ajoutés après le dernier paragraphe de la page si value est true.

**Returns:**
valeur booléenne

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Obtient le drapeau indiquant si la page est vide ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillThresholdFactor |  | La valeur du seuil de remplissage qui gère la sensibilité de la détection. Elle doit être dans la plage [0..1). Pour déterminer si une page est vide ou non, le rapport de l'espace rempli à l'espace total de la page est calculé. Ce rapport est comparé au paramètre fillThresholdFactor et s'il est inférieur, la page est considérée comme vide. |

**Returns:**
Valeur booléenne True - si la page est vide ; sinon, false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Obtient le drapeau indiquant si la page est vide ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillThresholdFactor |  | La valeur du seuil de remplissage qui gère la sensibilité de la détection. Elle doit être égale ou supérieure à 0,01. |
| parseWhiteContent |  | True pour une analyse complète de la page avec analyse du contenu blanc, False (par défaut) - algorithme rapide, où les graphiques blancs sont considérés comme une page non vide. |

**Returns:**
Valeur booléenne True - si la page est vide ; sinon, false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Convertit la page en niveaux de gris.

### mergeLayers {#mergeLayers-java.lang.String-}
Fusionne toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Fusionne toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié et l'Id de groupe de contenu optionnel.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Supprimer les références d'objet

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Supprime les références à XObject du contenu de la page (c.-à-d. tous les opérateurs Do qui utilisent le nom de l'objet).

### resize {#resize-com.aspose.pdf.PageSize-}
Redimensionne la page.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Convertit le membre d'énumération de rotation en valeur entière.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Envoie la page au processus avec le dispositif de page fourni.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Envoie la page au processus avec le dispositif de page fourni.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page. Value : Value indique si les paragraphes seront ajoutés après le dernier paragraphe de la page. Les paragraphes seront ajoutés après le dernier paragraphe de la page si value est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Définit la boîte d'art de la page.

### setBackground {#setBackground-java.awt.Color-}
Définit la couleur d'arrière-plan de la page.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Définit la couleur d'arrière-plan de la page.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Définit la boîte de débordement de la page.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Définit la boîte de recadrage de la page. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Définit la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors de la présentation. Retourne -1 si la durée n'est pas définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | durée d'affichage de la page. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Pour usage interne uniquement

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Définit le Footer de la page.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Définit une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparent.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Définit l'en-tête de la page.

### setLayers {#setLayers-java.util.ArrayList-}
Définit la collection de calques.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Définit la collection de calques.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Définit la boîte média de la page.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Définit le style de ligne pour les notes.(pour le générateur uniquement, non rempli lors de la lecture du document)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Définit les informations de la page.(pour le générateur uniquement, non rempli lors de la lecture du document).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Définit la taille de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de la page. |
| hauteur |  | Taille de la page. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Définit les paragraphes.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Obtient ou définit le rectangle de la page. Pour la lecture : la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour l'écriture : la boîte média de la page est toujours définie. est renvoyée. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Définit la rotation de la page.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Définit l'ordre des onglets de la page. Valeurs possibles : Row, Column. Par défaut, Manual

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Objet TabOrder @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Définit les informations de la table des matières.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Définir la transition

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Définit la boîte de rognage de la page.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Obtient ou définit la valeur UserUnit. Un nombre positif indiquant la taille des unités d'espace utilisateur par défaut, en multiples de 1 / 72 pouce. La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin de supprimer cette entrée dans la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Définit le filigrane de la page.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Essaie d'enregistrer les graphiques vectoriels s'ils sont présents sur la page. Le format d'enregistrement est SVG.
