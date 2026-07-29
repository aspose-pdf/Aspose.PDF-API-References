---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de modifier la page d'un fichier PDF, y compris la rotation, le zoom, le déplacement et le changement de taille de la page."
type: docs
weight: 570
url: /fr/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Représente une classe permettant de modifier la page d'un fichier PDF, y compris la rotation, le zoom, le déplacement et le changement de taille de la page.

## Champs

| Champ | Description |
| --- | --- |
| [BLINDH](#BLINDH) | Stores verticaux |
| [BLINDV](#BLINDV) | Stores verticaux |
| [BTWIPE](#BTWIPE) | Essuyage du bas vers le haut |
| [DGLITTER](#DGLITTER) | Paillettes diagonales |
| [DISSOLVE](#DISSOLVE) | L'ancienne page se dissout |
| [INBOX](#INBOX) | Boîte vers l'intérieur |
| [LRGLITTER](#LRGLITTER) | Paillettes gauche-droite |
| [LRWIPE](#LRWIPE) | Essuyage gauche-droite |
| [OUTBOX](#OUTBOX) | Boîte vers l'extérieur |
| [RLWIPE](#RLWIPE) | Essuyage droite-gauche |
| [SPLITHIN](#SPLITHIN) | Division horizontale EN |
| [SPLITHOUT](#SPLITHOUT) | Division horizontale SORTIE |
| [SPLITVIN](#SPLITVIN) | Division verticale EN |
| [SPLITVOUT](#SPLITVOUT) | Division verticale SORTIE |
| [TBGLITTER](#TBGLITTER) | Paillettes haut-bas |
| [TBWIPE](#TBWIPE) | Essuyage haut-bas |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Constructeur de la classe PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Constructeur de la classe PdfPageEditor. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [applyChanges](#applyChanges--) | Appliquer les modifications apportées aux pages du document. |
| [getAlignment](#getAlignment--) | Obtient l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. Utilisez getHorizontalAlignment à la place |
| [getDisplayDuration](#getDisplayDuration--) | Obtient la durée d'affichage des pages. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtient l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Renvoie la taille de la boîte spécifiée dans le document. </p> <hr> <pre> L'exemple suivant montre comment obtenir la boîte média de la première page : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Renvoie la taille de la page. |
| [getPageRotation](#getPageRotation-int-) | <p> Renvoie la rotation de la page spécifiée. </p> <hr> <pre> L'exemple suivant montre comment obtenir la rotation de la page : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Obtient la rotation des pages, un tableau de hachage contient le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés. </p> |
| [getPages](#getPages--) | <p> Renvoie le nombre total de pages. </p> <hr> <pre> L'exemple suivant montre l'utilisation de la méthode GetPages() : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Obtient la taille de la page du fichier de sortie. |
| [getPageSize](#getPageSize-int-) | <p> Renvoie la taille de la page spécifiée. </p> <hr> <pre> L'exemple suivant montre l'utilisation de la méthode GetPageSize : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Obtient les numéros de page à éditer. Par défaut, chaque page serait éditée. |
| [getRotation](#getRotation--) | Obtient la rotation des pages, la rotation doit être 0, 90, 180 ou 270. La valeur par défaut est 0. |
| [getTransitionDuration](#getTransitionDuration--) | Obtient la durée de l'effet de transition. |
| [getTransitionType](#getTransitionType--) | Obtient le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom. Utilisez getVerticalAlignmentType à la place |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Obtient l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Obtient le coefficient de zoom. La valeur 1.0 correspond à 100%. La valeur par défaut est 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Vérifie si la case est définie sur la page. |
| [movePosition](#movePosition-float-float-) | <p> Déplace l'origine de (0, 0) vers le point indiqué. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Enregistre le document modifié dans un flux. </p> <hr> <pre> L'exemple suivant montre comment enregistrer le document PDF modifié dans un flux. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Enregistre le document modifié dans un fichier. </p> <hr> <pre> L'exemple suivant montre comment enregistrer le document PDF modifié PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. Utilisez setHorizontalAlignment à la place |
| [setDisplayDuration](#setDisplayDuration-int-) | Définit la durée d'affichage des pages. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Définit la rotation des pages, un tableau de hachage contient le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Définit la taille de la page du fichier de sortie. |
| [setProcessPages](#setProcessPages-int:A-) | Définit les numéros de page à éditer. Par défaut, chaque page serait éditée. |
| [setRotation](#setRotation-int-) | Définit la rotation des pages, la rotation doit être 0, 90, 180 ou 270. La valeur par défaut est 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Définit la durée de l'effet de transition. |
| [setTransitionType](#setTransitionType-int-) | Définit le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Définit l'alignement vertical du contenu PDF original sur la page de résultat, la valeur par défaut est VerticalAlignmentType.Bottom. Utilisez setVerticalAlignmentType à la place |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Définit l'alignement vertical du contenu PDF original sur la page de résultat, la valeur par défaut est VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Définit le coefficient de zoom. La valeur 1.0 correspond à 100%. La valeur par défaut est 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Stores verticaux

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Stores verticaux

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Essuyage du bas vers le haut

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Paillettes diagonales

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

L'ancienne page se dissout

### INBOX {#INBOX}
```
public static final int INBOX
```

Boîte vers l'intérieur

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Paillettes gauche-droite

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Essuyage gauche-droite

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Boîte vers l'extérieur

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Essuyage droite-gauche

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

Division horizontale EN

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Division horizontale SORTIE

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

Division verticale EN

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Division verticale SORTIE

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Paillettes haut-bas

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Essuyage haut-bas

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Constructeur de la classe PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Constructeur de la classe PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Appliquer les modifications apportées aux pages du document.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Obtient l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. Utilisez getHorizontalAlignment à la place

**Returns:**
Objet AlignmentType @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Obtient la durée d'affichage des pages.

**Returns:**
valeur int

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtient l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left.

**Returns:**
Élément HorizontalAlignment @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Renvoie la taille de la boîte spécifiée dans le document. </p> <hr> <pre> L'exemple suivant montre comment obtenir la boîte média de la première page : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Renvoie la taille de la page.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Renvoie la rotation de la page spécifiée. </p> <hr> <pre> L'exemple suivant montre comment obtenir la rotation de la page : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page |  | Indice de page. Les pages du document sont numérotées à partir de 1. |

**Returns:**
Rotation de la page en degrés.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Obtient la rotation des pages, un tableau de hachage contient le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés. </p>

**Returns:**
objet {@code Map<Integer, Integer>}

### getPages {#getPages--}
```
public int getPages()
```

<p> Renvoie le nombre total de pages. </p> <hr> <pre> L'exemple suivant montre l'utilisation de la méthode GetPages() : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Nombre de pages.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Obtient la taille de la page du fichier de sortie.

**Returns:**
Objet PageSize

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Renvoie la taille de la page spécifiée. </p> <hr> <pre> L'exemple suivant montre l'utilisation de la méthode GetPageSize : PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page |  | Indice de page. Les pages du document sont numérotées à partir de 1. |

**Returns:**
Le résultat est une instance de PageSize. Utilisez les propriétés Width et Height de l'objet retourné pour obtenir la largeur et la hauteur de la page.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Obtient les numéros de page à éditer. Par défaut, chaque page serait éditée.

**Returns:**
tableau de valeurs int

### getRotation {#getRotation--}
```
public int getRotation()
```

Obtient la rotation des pages, la rotation doit être 0, 90, 180 ou 270. La valeur par défaut est 0.

**Returns:**
valeur int

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Obtient la durée de l'effet de transition.

**Returns:**
valeur int

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Obtient le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation.

**Returns:**
valeur int

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Obtient l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom. Utilisez getVerticalAlignmentType à la place

**Returns:**
Objet VerticalAlignmentType

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Obtient l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom.

**Returns:**
Élément VerticalAlignmentType @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Obtient le coefficient de zoom. La valeur 1.0 correspond à 100%. La valeur par défaut est 1.0.

**Returns:**
Valeur flottante

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Vérifie si la case est définie sur la page.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Déplace l'origine de (0, 0) vers le point indiqué. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| moveX |  | Coordonnée X. |
| moveY |  | Coordonnée Y. |

### save {#save-java.io.OutputStream-}
<p> Enregistre le document modifié dans un flux. </p> <hr> <pre> L'exemple suivant montre comment enregistrer le document PDF modifié dans un flux. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Enregistre le document modifié dans un fichier. </p> <hr> <pre> L'exemple suivant montre comment enregistrer le document PDF modifié PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. Utilisez setHorizontalAlignment à la place

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Définit la durée d'affichage des pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Définit la rotation des pages, un tableau de hachage contient le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Définit la taille de la page du fichier de sortie.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Définit les numéros de page à éditer. Par défaut, chaque page serait éditée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau de valeurs int |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Définit la rotation des pages, la rotation doit être 0, 90, 180 ou 270. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Définit la durée de l'effet de transition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Définit le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Définit l'alignement vertical du contenu PDF original sur la page de résultat, la valeur par défaut est VerticalAlignmentType.Bottom. Utilisez setVerticalAlignmentType à la place

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Définit l'alignement vertical du contenu PDF original sur la page de résultat, la valeur par défaut est VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Définit le coefficient de zoom. La valeur 1.0 correspond à 100%. La valeur par défaut est 1.0. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur float <hr> <pre> L'exemple suivant montre comment modifier le zoom des pages du document. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); </pre> |
