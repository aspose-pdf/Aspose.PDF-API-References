---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe d'options pour extraire les graphiques vectoriels de la page du document PDF."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Représente une classe d'options pour extraire les graphiques vectoriels de la page du document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Crée une instance de la classe SvgExtractionOptions. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Obtient et définit l'option de regrouper automatiquement les sous‑chemins en images. Cette option exclut l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Obtient et définit l'option d'extraire chaque sous‑chemin d'un document PDF en images SVG séparées. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Obtient et définit le rectangle englobant qui définit la zone d'extraction pour l'extraction SVG. |
| [getGroupStrength](#getGroupStrength--) | Obtient et définit une option : la force du regroupement des sous‑chemins en images. Permet de configurer le degré de regroupement des sous‑chemins. La plage de valeurs va de 0 à 1. Une valeur de 0 correspond à l'activation de l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Une valeur de 1 créera une image unique pour tous les chemins vectoriels de la page. L'option a un effet lorsque {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) est false. La valeur par défaut est {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Obtient ou définit la largeur de trait minimale qui sera utilisée dans le SVG résultant. Si le PDF utilise une largeur de trait plus fine, elle sera remplacée par cette largeur. La valeur par défaut est 0,5. La valeur est exprimée en unités d'espace utilisateur transformées de la page PDF convertie. Par défaut, 1 unité d'espace utilisateur correspond à 1/72 pouce (0,35 mm), mais cela peut être remplacé par le document PDF. Les transformations peuvent affecter la largeur minimale réelle dans le SVG généré. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Obtient et définit une option pour vérifier strictement si les sous‑chemins se trouvent à l'intérieur du rectangle spécifié dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si elle est définie sur false, les sous‑chemins qui ne sont pas entièrement inclus dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) seront extraits. La valeur par défaut est {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Obtient et définit un indicateur qui détermine si les XFrom trouvés sur les pages doivent être décompressés ou non. Les éléments XFrom peuvent se retrouver dans différents fichiers SVG. Seuls les XForms rendus par les instructions Do du contenu de la page sont décompressés. Les XForms imbriqués ne le sont pas. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Obtient et définit l'option de décompresser uniquement le XForm correspondant au prédicat spécifié. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Obtient et définit l'option de regrouper automatiquement les sous‑chemins en images. Cette option exclut l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Obtient et définit l'option d'extraire chaque sous‑chemin d'un document PDF en images SVG séparées. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Obtient et définit le rectangle englobant qui définit la zone d'extraction pour l'extraction SVG. |
| [setGroupStrength](#setGroupStrength-double-) | Obtient et définit une option : la force du regroupement des sous‑chemins en images. Permet de configurer le degré de regroupement des sous‑chemins. La plage de valeurs va de 0 à 1. Une valeur de 0 correspond à l'activation de l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Une valeur de 1 créera une image unique pour tous les chemins vectoriels de la page. L'option a un effet lorsque {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) est false. La valeur par défaut est {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Obtient ou définit la largeur de trait minimale qui sera utilisée dans le SVG résultant. Si le PDF utilise une largeur de trait plus fine, elle sera remplacée par cette largeur. La valeur par défaut est 0,5. La valeur est exprimée en unités d'espace utilisateur transformées de la page PDF convertie. Par défaut, 1 unité d'espace utilisateur correspond à 1/72 pouce (0,35 mm), mais cela peut être remplacé par le document PDF. Les transformations peuvent affecter la largeur minimale réelle dans le SVG généré. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Obtient et définit une option pour vérifier strictement si les sous‑chemins se trouvent à l'intérieur du rectangle spécifié dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si elle est définie sur false, les sous‑chemins qui ne sont pas entièrement inclus dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) seront extraits. La valeur par défaut est {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Obtient et définit un indicateur qui détermine si les XFrom trouvés sur les pages doivent être décompressés ou non. Les éléments XFrom peuvent se retrouver dans différents fichiers SVG. Seuls les XForms rendus par les instructions Do du contenu de la page sont décompressés. Les XForms imbriqués ne le sont pas. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Obtient et définit l'option de décompresser uniquement le XForm correspondant au prédicat spécifié. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Crée une instance de la classe SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Obtient et définit l'option de regrouper automatiquement les sous‑chemins en images. Cette option exclut l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Returns:**
valeur booléenne

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Obtient et définit l'option d'extraire chaque sous‑chemin d'un document PDF en images SVG séparées.

**Returns:**
valeur booléenne

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Obtient et définit le rectangle englobant qui définit la zone d'extraction pour l'extraction SVG.

**Returns:**
Instance de Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Obtient et définit une option : la force du regroupement des sous‑chemins en images. Permet de configurer le degré de regroupement des sous‑chemins. La plage de valeurs va de 0 à 1. Une valeur de 0 correspond à l'activation de l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Une valeur de 1 créera une image unique pour tous les chemins vectoriels de la page. L'option a un effet lorsque {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) est false. La valeur par défaut est {@code 0.8}.

**Returns:**
valeur double

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Obtient ou définit la largeur de trait minimale qui sera utilisée dans le SVG résultant. Si le PDF utilise une largeur de trait plus fine, elle sera remplacée par cette largeur. La valeur par défaut est 0,5. La valeur est exprimée en unités d'espace utilisateur transformées de la page PDF convertie. Par défaut, 1 unité d'espace utilisateur correspond à 1/72 pouce (0,35 mm), mais cela peut être remplacé par le document PDF. Les transformations peuvent affecter la largeur minimale réelle dans le SVG généré.

**Returns:**
valeur double

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Obtient et définit une option pour vérifier strictement si les sous‑chemins se trouvent à l'intérieur du rectangle spécifié dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si elle est définie sur false, les sous‑chemins qui ne sont pas entièrement inclus dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) seront extraits. La valeur par défaut est {@code True}.

**Returns:**
valeur booléenne

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Obtient et définit un indicateur qui détermine si les XFrom trouvés sur les pages doivent être décompressés ou non. Les éléments XFrom peuvent se retrouver dans différents fichiers SVG. Seuls les XForms rendus par les instructions Do du contenu de la page sont décompressés. Les XForms imbriqués ne le sont pas.

**Returns:**
valeur booléenne

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Obtient et définit l'option de décompresser uniquement le XForm correspondant au prédicat spécifié.

**Returns:**
instance interne de Predicate de l'instance XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Obtient et définit l'option de regrouper automatiquement les sous‑chemins en images. Cette option exclut l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Obtient et définit l'option d'extraire chaque sous‑chemin d'un document PDF en images SVG séparées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Obtient et définit le rectangle englobant qui définit la zone d'extraction pour l'extraction SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Obtient et définit une option : la force du regroupement des sous‑chemins en images. Permet de configurer le degré de regroupement des sous‑chemins. La plage de valeurs va de 0 à 1. Une valeur de 0 correspond à l'activation de l'option {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Une valeur de 1 créera une image unique pour tous les chemins vectoriels de la page. L'option a un effet lorsque {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) est false. La valeur par défaut est {@code 0.8}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Obtient ou définit la largeur de trait minimale qui sera utilisée dans le SVG résultant. Si le PDF utilise une largeur de trait plus fine, elle sera remplacée par cette largeur. La valeur par défaut est 0,5. La valeur est exprimée en unités d'espace utilisateur transformées de la page PDF convertie. Par défaut, 1 unité d'espace utilisateur correspond à 1/72 pouce (0,35 mm), mais cela peut être remplacé par le document PDF. Les transformations peuvent affecter la largeur minimale réelle dans le SVG généré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Obtient et définit une option pour vérifier strictement si les sous‑chemins se trouvent à l'intérieur du rectangle spécifié dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si elle est définie sur false, les sous‑chemins qui ne sont pas entièrement inclus dans {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) seront extraits. La valeur par défaut est {@code True}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Obtient et définit un indicateur qui détermine si les XFrom trouvés sur les pages doivent être décompressés ou non. Les éléments XFrom peuvent se retrouver dans différents fichiers SVG. Seuls les XForms rendus par les instructions Do du contenu de la page sont décompressés. Les XForms imbriqués ne le sont pas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Obtient et définit l'option de décompresser uniquement le XForm correspondant au prédicat spécifié.
