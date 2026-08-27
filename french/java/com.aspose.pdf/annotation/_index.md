---
title: "Annotation"
linktitle: "Annotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant un objet d'annotation."
type: docs
weight: 60
url: /fr/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Classe représentant un objet d'annotation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte le visiteur pour le traitement des annotations. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Met à jour les paramètres et l'apparence, selon la transformation matricielle. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | À usage interne uniquement |
| [flatten](#flatten--) | Place le contenu de l'annotation directement sur la page, l'objet annotation sera supprimé. |
| [getActiveState](#getActiveState--) | Obtient l'état d'apparence actuel de l'annotation. |
| [getAlignment](#getAlignment--) | ff / * / * Retourne le nom de l'état "checked" selon les noms d'états existants. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getAppearance](#getAppearance--) | Obtient le dictionnaire d'apparence de l'annotation. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Obtient l'index de la page (à partir de 1) où l'annotation doit apparaître. |
| [getBorder](#getBorder--) | Obtient les caractéristiques de bordure de l'annotation. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Obtient les caractéristiques de l'annotation. |
| [getColor](#getColor--) | Obtient la couleur de l'annotation. |
| [getContents](#getContents--) | Obtient le texte de l'annotation. |
| [getEngineDict](#getEngineDict--) | Interne uniquement |
| [getEngineObj](#getEngineObj--) | Pour usage interne uniquement |
| [getFlags](#getFlags--) | Obtient les indicateurs de l'annotation. |
| [getFullName](#getFullName--) | Obtient le nom complet de l'annotation. |
| [getHeight](#getHeight--) | Obtient la hauteur de l'annotation. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Obtient ou définit l'alignement du texte pour l'annotation. |
| [getModified](#getModified--) | Obtient la date et l'heure de la dernière modification de l'annotation. |
| [getModifiedInternal](#getModifiedInternal--) | Obtient la date et l'heure de la dernière modification de l'annotation. |
| [getName](#getName--) | Obtient le nom de l'annotation sur la page. |
| [getNormalAppearance](#getNormalAppearance--) | Obtient l'apparence normale. |
| [getPage](#getPage--) | Obtient l'objet page auquel cette annotation est associée. |
| [getPageIndex](#getPageIndex--) | Obtient l'index de la page contenant l'annotation. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Obtient l'index de la page contenant l'annotation. |
| [getPdfActions](#getPdfActions--) | Obtient la liste des actions de l'annotation. |
| [getRect](#getRect--) | Obtient le rectangle de l'annotation. |
| [getRectangle](#getRectangle-boolean-) | Retourne le rectangle de l'annotation en tenant compte de la rotation de la page. |
| [getStates](#getStates--) | Obtient le dictionnaire d'apparence de l'annotation. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Obtient l'alignement du texte pour l'annotation. |
| [getWidth](#getWidth--) | Obtient la largeur de l'annotation. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Initialisation d'instance |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Si true, l'apparence de l'annotation sera mise à jour avant de convertir le document PDF en image. Cela permet de convertir les champs correctement mais nécessite probablement plus de temps. |
| [isUseFontSubset](#isUseFontSubset--) | Si cette propriété est définie sur true, les polices seront ajoutées au document sous forme de sous‑ensembles. La valeur par défaut est true. |
| [setActiveState](#setActiveState-java.lang.String-) | Définit l'état actuel de l'apparence de l'annotation. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Alignement de l'annotation. Cette propriété est obsolète. Utilisez getHorizontalAlignment_Annotation_New à la place. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Définit l'index de page (à partir de 1) où l'annotation doit apparaître. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Définit les caractéristiques de la bordure de l'annotation. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Définit la couleur de l'annotation. |
| [setContents](#setContents-java.lang.String-) | Définit le texte de l'annotation. |
| [setFlags](#setFlags-int-) | Définit les indicateurs de l'annotation. |
| [setHeight](#setHeight-double-) | Définit la hauteur de l'annotation. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Obtient ou définit l'alignement du texte pour l'annotation. |
| [setModified](#setModified-java.util.Date-) | Définit la date et l'heure de la dernière modification de l'annotation. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Définit la date et l'heure de la dernière modification de l'annotation. |
| [setName](#setName-java.lang.String-) | Définit le nom de l'annotation sur la page. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Définit le rectangle de l'annotation. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement du texte pour l'annotation. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Si true, l'apparence de l'annotation sera mise à jour avant de convertir le document PDF en image. Cela permet de convertir les champs correctement mais nécessite probablement plus de temps. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Si cette propriété est définie sur true, les polices seront ajoutées au document sous forme de sous‑ensembles. La valeur par défaut est true. |
| [setWidth](#setWidth-double-) | Définit la largeur de l'annotation. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte le visiteur pour le traitement des annotations.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Met à jour les paramètres et l'apparence, selon la transformation matricielle.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
À usage interne uniquement

### flatten {#flatten--}
```
public void flatten()
```

Place le contenu de l'annotation directement sur la page, l'objet annotation sera supprimé.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Obtient l'état d'apparence actuel de l'annotation.

**Returns:**
valeur String

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Retourne le nom de l'état "checked" selon les noms d'états existants. / * / * / *

**Returns:**
Valeur de chaîne /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Valeur int @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Obtient le dictionnaire d'apparence de l'annotation.

**Returns:**
Objet AppearanceDictionary

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Obtient l'index de la page (à partir de 1) où l'annotation doit apparaître.

**Returns:**
l'index de page (à partir de 1) où l'annotation doit apparaître.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Obtient les caractéristiques de bordure de l'annotation. {@code Border}

**Returns:**
Objet Border

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Obtient les caractéristiques de l'annotation.

**Returns:**
Objet Characteristics

### getColor {#getColor--}
```
public Color getColor()
```

Obtient la couleur de l'annotation.

**Returns:**
Objet Color

### getContents {#getContents--}
```
public String getContents()
```

Obtient le texte de l'annotation.

**Returns:**
valeur String

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Interne uniquement

**Returns:**
Objet IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Pour usage interne uniquement

**Returns:**
Objet interne

### getFlags {#getFlags--}
```
public int getFlags()
```

Obtient les indicateurs de l'annotation.

**Returns:**
Indicateurs de l'annotation @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Obtient le nom complet de l'annotation.

**Returns:**
valeur String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtient la hauteur de l'annotation.

**Returns:**
hauteur de l'annotation

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Obtient ou définit l'alignement du texte pour l'annotation.

**Returns:**
alignement du texte pour l'annotation. @see HorizontalAlignment @deprecated Utilisez la propriété TextHorizontalAlignment

### getModified {#getModified--}
```
public Date getModified()
```

Obtient la date et l'heure de la dernière modification de l'annotation.

**Returns:**
date et heure de la dernière modification de l'annotation.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Obtient la date et l'heure de la dernière modification de l'annotation.

**Returns:**
objet DateTime

### getName {#getName--}
```
public String getName()
```

Obtient le nom de l'annotation sur la page.

**Returns:**
valeur String

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Obtient l'apparence normale.

**Returns:**
objet XForm

### getPage {#getPage--}
```
public Page getPage()
```

Obtient l'objet page auquel cette annotation est associée.

**Returns:**
objet Page

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtient l'index de la page contenant l'annotation.

**Returns:**
valeur int

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Obtient l'index de la page contenant l'annotation.

**Returns:**
valeur int

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Obtient la liste des actions de l'annotation.

**Returns:**
instance PdfActionCollection

### getRect {#getRect--}
```
public Rectangle getRect()
```

Obtient le rectangle de l'annotation.

**Returns:**
objet Rectangle

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Retourne le rectangle de l'annotation en tenant compte de la rotation de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| considerRotation |  | Si vrai, la rotation de la page est prise en compte. |

**Returns:**
objet Rectangle

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Obtient le dictionnaire d'apparence de l'annotation.

**Returns:**
Objet AppearanceDictionary

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Obtient l'alignement du texte pour l'annotation.

**Returns:**
alignement du texte pour l'annotation. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur de l'annotation.

**Returns:**
valeur double, largeur de l'annotation.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Initialisation d'instance

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Si true, l'apparence de l'annotation sera mise à jour avant de convertir le document PDF en image. Cela permet de convertir les champs correctement mais nécessite probablement plus de temps.

**Returns:**
valeur booléenne

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Si cette propriété est définie sur true, les polices seront ajoutées au document sous forme de sous‑ensembles. La valeur par défaut est true.

**Returns:**
valeur booléenne

### setActiveState {#setActiveState-java.lang.String-}
Définit l'état actuel de l'apparence de l'annotation.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Alignement de l'annotation. Cette propriété est obsolète. Utilisez getHorizontalAlignment_Annotation_New à la place.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Définit l'index de page (à partir de 1) où l'annotation doit apparaître.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Définit les caractéristiques de la bordure de l'annotation. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Définit la couleur de l'annotation.

### setContents {#setContents-java.lang.String-}
Définit le texte de l'annotation.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Définit les indicateurs de l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | indicateurs de l'annotation @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Définit la hauteur de l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | hauteur de l'annotation |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Obtient ou définit l'alignement du texte pour l'annotation.

### setModified {#setModified-java.util.Date-}
Définit la date et l'heure de la dernière modification de l'annotation.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Définit la date et l'heure de la dernière modification de l'annotation.

### setName {#setName-java.lang.String-}
Définit le nom de l'annotation sur la page.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Définit le rectangle de l'annotation.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement du texte pour l'annotation.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Si true, l'apparence de l'annotation sera mise à jour avant de convertir le document PDF en image. Cela permet de convertir les champs correctement mais nécessite probablement plus de temps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Si cette propriété est définie sur true, les polices seront ajoutées au document sous forme de sous‑ensembles. La valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la largeur de l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | largeur de l'annotation. |
