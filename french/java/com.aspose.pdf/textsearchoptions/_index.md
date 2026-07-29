---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de recherche de texte"
type: docs
weight: 5290
url: /fr/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Représente les options de recherche de texte

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Initialise une nouvelle instance de l'objet {@code TextSearchOptions}. Spécifie le mode d'utilisation des expressions régulières. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de l'objet TextSearchOptions. Spécifie le rectangle qui délimite le texte recherché. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Initialise une nouvelle instance de l'objet TextSearchOptions. Spécifie le rectangle qui délimite le texte recherché et le mode d'utilisation des expressions régulières. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Obtient ou définit les rectangles dont les bordures excluent le texte de la recherche. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment). true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront sautés pendant le traitement. false (par défaut) - l'erreur d'absence de police terminera le traitement en lançant une exception. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Obtient l'indication que le texte est recherché à l'intérieur des limites de la page. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Obtient ou définit l'indication selon laquelle les erreurs d'extraction de texte (décodage) seront enregistrées dans l'absorbeur de texte (fragment). true - signifie que les erreurs d'extraction de texte (décodage) seront enregistrées. Cela peut réduire les performances. false (par défaut) - aucune journalisation des erreurs. |
| [getRectangle](#getRectangle--) | Obtient le rectangle qui délimite le texte recherché. La propriété peut être utilisée au cas où il serait nécessaire de délimiter l'extraction de texte ou la région de remplacement du texte. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Obtient ou définit la valeur qui autorise la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) pendant la recherche de texte. true - la recherche de graphiques liés au texte sera effectuée (valeur par défaut). false - les éléments graphiques pouvant être présents dans le document source seront ignorés. Activez ceci en cas de problèmes de performances ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le rognage. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Obtient la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page au nombre spécifié d'éléments. La valeur par défaut est 250. Réduisez la valeur en cas de problèmes de performances, essayez une valeur plus grande si certains éléments graphiques n'ont pas été trouvés. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Obtient l'indication que le texte sera recherché en utilisant le codage du moteur de police. true - signifie que le codage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue à cause d'un codage imparfait dans le document) false - signifie que le codage de la police du document sera utilisé (valeur par défaut) |
| [isDotallMode](#isDotallMode--) | <p> En mode dotall, l'expression <tt>.</tt> correspond à n'importe quel caractère, y compris un séparateur de ligne. Par défaut, cette expression ne correspond pas aux séparateurs de ligne. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Obtient ou définit l'indication que les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche. true - signifie que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches) false - signifie que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut) |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Indique si une expression régulière est utilisée ou non |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Obtient ou définit la valeur qui autorise la recherche de texte dans les annotations. true - le texte sera recherché dans les annotations. false - le texte dans les annotations ne sera pas analysé par TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Active le mode dotall. <p> En mode dotall, l'expression <tt>.</tt> correspond à n'importe quel caractère, y compris un séparateur de ligne. Par défaut, cette expression ne correspond pas aux séparateurs de ligne. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Obtient ou définit les rectangles dont les bordures excluent le texte de la recherche. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment). true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront sautés pendant le traitement. false (par défaut) - l'erreur d'absence de police terminera le traitement en lançant une exception. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Obtient ou définit l'indication que les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche. true - signifie que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches) false - signifie que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut) |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Définit l'indication que le texte est recherché à l'intérieur des limites de la page. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Obtient ou définit l'indication selon laquelle les erreurs d'extraction de texte (décodage) seront enregistrées dans l'absorbeur de texte (fragment). true - signifie que les erreurs d'extraction de texte (décodage) seront enregistrées. Cela peut réduire les performances. false (par défaut) - aucune journalisation des erreurs. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Définit le rectangle qui délimite le texte recherché. La propriété peut être utilisée au cas où il serait nécessaire de délimiter l'extraction de texte ou la région de remplacement du texte. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Indique si une expression régulière est utilisée ou non |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Obtient ou définit la valeur qui autorise la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) pendant la recherche de texte. true - la recherche de graphiques liés au texte sera effectuée (valeur par défaut). false - les éléments graphiques pouvant être présents dans le document source seront ignorés. Activez ceci en cas de problèmes de performances ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le rognage. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Obtient ou définit la valeur qui autorise la recherche de texte dans les annotations. true - le texte sera recherché dans les annotations. false - le texte dans les annotations ne sera pas analysé par TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Définit la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page au nombre spécifié d'éléments. La valeur par défaut est 250. Réduisez la valeur en cas de problèmes de performances, essayez une valeur plus grande si certains éléments graphiques n'ont pas été trouvés. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Définit l'indication que le texte sera recherché en utilisant le codage du moteur de police. true - signifie que le codage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue à cause d'un codage imparfait dans le document) false - signifie que le codage de la police du document sera utilisé (valeur par défaut) |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Initialise une nouvelle instance de l'objet {@code TextSearchOptions}. Spécifie le mode d'utilisation des expressions régulières.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isRegularExpressionUsed |  | Valeur qui indique qu'une expression régulière est utilisée. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de l'objet TextSearchOptions. Spécifie le rectangle qui délimite le texte recherché.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Initialise une nouvelle instance de l'objet TextSearchOptions. Spécifie le rectangle qui délimite le texte recherché et le mode d'utilisation des expressions régulières.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Obtient ou définit les rectangles dont les bordures excluent le texte de la recherche.

**Returns:**
tableau d'instances Rectangle

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment). true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront sautés pendant le traitement. false (par défaut) - l'erreur d'absence de police terminera le traitement en lançant une exception.

**Returns:**
valeur booléenne

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Obtient l'indication que le texte est recherché à l'intérieur des limites de la page.

**Returns:**
valeur booléenne

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Obtient ou définit l'indication selon laquelle les erreurs d'extraction de texte (décodage) seront enregistrées dans l'absorbeur de texte (fragment). true - signifie que les erreurs d'extraction de texte (décodage) seront enregistrées. Cela peut réduire les performances. false (par défaut) - aucune journalisation des erreurs.

**Returns:**
valeur booléenne

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle qui délimite le texte recherché. La propriété peut être utilisée au cas où il serait nécessaire de délimiter l'extraction de texte ou la région de remplacement du texte.

**Returns:**
Valeur du rectangle

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Obtient ou définit la valeur qui autorise la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) pendant la recherche de texte. true - la recherche de graphiques liés au texte sera effectuée (valeur par défaut). false - les éléments graphiques pouvant être présents dans le document source seront ignorés. Activez ceci en cas de problèmes de performances ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le rognage.

**Returns:**
valeur booléenne

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Obtient la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page au nombre spécifié d'éléments. La valeur par défaut est 250. Réduisez la valeur en cas de problèmes de performances, essayez une valeur plus grande si certains éléments graphiques n'ont pas été trouvés.

**Returns:**
valeur int

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Obtient l'indication que le texte sera recherché en utilisant le codage du moteur de police. true - signifie que le codage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue à cause d'un codage imparfait dans le document) false - signifie que le codage de la police du document sera utilisé (valeur par défaut)

**Returns:**
valeur booléenne

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> En mode dotall, l'expression <tt>.</tt> correspond à n'importe quel caractère, y compris un séparateur de ligne. Par défaut, cette expression ne correspond pas aux séparateurs de ligne.

**Returns:**
valeur booléenne

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Obtient ou définit l'indication que les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche. true - signifie que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches) false - signifie que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut)

**Returns:**
valeur booléenne

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Indique si une expression régulière est utilisée ou non

**Returns:**
valeur booléenne

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Obtient ou définit la valeur qui autorise la recherche de texte dans les annotations. true - le texte sera recherché dans les annotations. false - le texte dans les annotations ne sera pas analysé par TextFragmentAbsorber.

**Returns:**
valeur booléenne

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Active le mode dotall. <p> En mode dotall, l'expression <tt>.</tt> correspond à n'importe quel caractère, y compris un séparateur de ligne. Par défaut, cette expression ne correspond pas aux séparateurs de ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dotallMode |  | valeur booléenne |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Obtient ou définit les rectangles dont les bordures excluent le texte de la recherche.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment). true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront sautés pendant le traitement. false (par défaut) - l'erreur d'absence de police terminera le traitement en lançant une exception.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Obtient ou définit l'indication que les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche. true - signifie que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches) false - signifie que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Définit l'indication que le texte est recherché à l'intérieur des limites de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Obtient ou définit l'indication selon laquelle les erreurs d'extraction de texte (décodage) seront enregistrées dans l'absorbeur de texte (fragment). true - signifie que les erreurs d'extraction de texte (décodage) seront enregistrées. Cela peut réduire les performances. false (par défaut) - aucune journalisation des erreurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Définit le rectangle qui délimite le texte recherché. La propriété peut être utilisée au cas où il serait nécessaire de délimiter l'extraction de texte ou la région de remplacement du texte.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Indique si une expression régulière est utilisée ou non

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Obtient ou définit la valeur qui autorise la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) pendant la recherche de texte. true - la recherche de graphiques liés au texte sera effectuée (valeur par défaut). false - les éléments graphiques pouvant être présents dans le document source seront ignorés. Activez ceci en cas de problèmes de performances ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le rognage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Obtient ou définit la valeur qui autorise la recherche de texte dans les annotations. true - le texte sera recherché dans les annotations. false - le texte dans les annotations ne sera pas analysé par TextFragmentAbsorber.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Définit la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page au nombre spécifié d'éléments. La valeur par défaut est 250. Réduisez la valeur en cas de problèmes de performances, essayez une valeur plus grande si certains éléments graphiques n'ont pas été trouvés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Définit l'indication que le texte sera recherché en utilisant le codage du moteur de police. true - signifie que le codage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue à cause d'un codage imparfait dans le document) false - signifie que le codage de la police du document sera utilisé (valeur par défaut)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
