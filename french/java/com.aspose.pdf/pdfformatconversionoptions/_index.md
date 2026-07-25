---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "représente un ensemble d'options pour convertir un document PDF"
type: docs
weight: 3730
url: /fr/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

représente un ensemble d'options pour convertir un document PDF

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructeur |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Constructeur |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructeur |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Constructeur |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructeur |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Stratégie d'alignement du texte. Ce paramètre n'a de sens que lorsque le drapeau {@code AlignText} est activé. |
| [getAlignText](#getAlignText--) | Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion de document n'affecte pas l'alignement du texte et laisse le texte tel quel. Cependant, dans certains cas, la substitution de police entraîne un chevauchement du texte ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé, des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être activé que pour les documents présentant des problèmes de texte chevauché ou d'espaces supplémentaires, car son utilisation diminue les performances et peut, dans certains cas, corrompre le contenu du texte. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Obtient ou définit les paramètres de balisage automatique lors de la conversion de format PDF. Les paramètres de balisage automatique sont utilisés pour configurer le comportement du processus de balisage automatique, généralement employé pour améliorer l'accessibilité et la structure d'un document PDF lors de la conversion vers un format PDF spécifique. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Action pour les images avec masque doux. |
| [getDefault](#getDefault--) | Obtient l'objet PdfFormatConversionOptions avec les paramètres par défaut. |
| [getErrorAction](#getErrorAction--) | Action pour les objets qui ne peuvent pas être convertis. |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau {@code OptimizeFileSize} est activé. Par défaut, la combinaison des stratégies {@code SubsetFonts} et {@code RemoveDuplicatedFonts} est utilisée. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Options pour les cas où il n'est pas possible d'intégrer certaines polices dans le document PDF. |
| [getFormat](#getFormat--) | Format PDF. |
| [getIccProfileFileName](#getIccProfileFileName--) | Obtient le nom de fichier du profil icc. En cas de null, le profil icc par défaut est utilisé. |
| [getLogFileName](#getLogFileName--) | Chemin du fichier où les commentaires seront stockés. |
| [getLogStream](#getLogStream--) | Flux où les commentaires seront stockés. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Contient des indicateurs pour contrôler le processus de conversion PDF/A dans les cas où le document source ne correspond pas à la spécification PDF/A. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Cette propriété est une propriété de sortie. Elle contient toutes les polices (noms de polices) qui n'ont pas été trouvées sur l'ordinateur lors de la dernière conversion PDF/A. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Obtient un indicateur qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A de taille réduite. Actuellement, cet indicateur influence l'optimisation des polices utilisées dans le document PDF ; éventuellement, à l'avenir, il pourra également être utilisé pour activer l'optimisation d'autres structures de données, comme les graphiques. L'ensemble de cet indicateur et du mode peut réduire considérablement la taille du fichier, mais peut également diminuer sensiblement les performances de la conversion. |
| [getOutputIntent](#getOutputIntent--) | Obtient ou définit le {@link OutputIntent} pour la conversion du format PDF. Le {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) spécifie le dispositif de sortie ou la condition prévue pour laquelle le document PDF est préparé. Il est utilisé pour garantir que les couleurs du document sont rendues correctement sur le dispositif cible. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Stratégie pour traiter les symboles de la zone d'utilisation privée Unicode (PUA). |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Stratégie pour copier les données d'encodage des polices symboliques si la police TrueType symbolique possède plus d'une sous-table d'encodage. |
| [getTransparencyAction](#getTransparencyAction--) | Action pour les objets d'image masqués |
| [getTransparencyResolution](#getTransparencyResolution--) | Définit la résolution lors de la conversion d'images transparentes. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Règles pour résoudre les problèmes de mappage Unicode. Peut être null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Obtient/definit l'exécution des flux d'images en mode asynchrone. |
| [isLowMemoryMode](#isLowMemoryMode--) | Le mode de conversion à faible mémoire est-il activé |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Le mode d'analyse des polices page par page est-il activé Valeur par défaut = false |
| [isTransferInfo](#isTransferInfo--) | Obtient ou définit s'il faut transférer les données de Info vers Metadata lors de la conversion en PDF 2.0. Vrai par défaut. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Valeur par défaut FALSE et la couleur de transparence sera conservée pour maintenir l'apparence du document. Avec la valeur TRUE, la couleur de transparence sera convertie en opacité, certains objets pourraient être couverts. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Stratégie d'alignement du texte. Ce paramètre n'a de sens que lorsque le drapeau {@code AlignText} est activé. |
| [setAlignText](#setAlignText-boolean-) | Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion de document n'affecte pas l'alignement du texte et laisse le texte tel quel. Cependant, dans certains cas, la substitution de police entraîne un chevauchement du texte ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé, des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être activé que pour les documents présentant des problèmes de texte chevauché ou d'espaces supplémentaires, car son utilisation diminue les performances et peut, dans certains cas, corrompre le contenu du texte. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Obtient/definit l'exécution des flux d'images en mode asynchrone. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Obtient ou définit les paramètres de balisage automatique lors de la conversion de format PDF. Les paramètres de balisage automatique sont utilisés pour configurer le comportement du processus de balisage automatique, généralement employé pour améliorer l'accessibilité et la structure d'un document PDF lors de la conversion vers un format PDF spécifique. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Action pour les images avec masque doux. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Action pour les objets qui ne peuvent pas être convertis. |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau {@code OptimizeFileSize} est activé. Par défaut, la combinaison des stratégies {@code SubsetFonts} et {@code RemoveDuplicatedFonts} est utilisée. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | Format PDF. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Définit le nom de fichier du profil icc. En cas de null, le profil icc par défaut est utilisé. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Chemin du fichier où les commentaires seront stockés. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Flux où les commentaires seront stockés. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Le mode de conversion à faible mémoire est-il activé |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Définit un indicateur qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A de taille réduite. Actuellement, cet indicateur influence l'optimisation des polices utilisées dans le document PDF ; éventuellement, à l'avenir, il pourra également être utilisé pour activer l'optimisation d'autres structures de données, comme les graphiques. L'ensemble de cet indicateur et du mode peut réduire considérablement la taille du fichier, mais peut aussi diminuer sensiblement les performances de la conversion. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Obtient ou définit le {@link OutputIntent} pour la conversion du format PDF. Le {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) spécifie le dispositif de sortie ou la condition prévue pour laquelle le document PDF est préparé. Il est utilisé pour garantir que les couleurs du document sont rendues correctement sur le dispositif cible. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Définit le mode d'analyse des polices page par page activé Valeur par défaut = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Stratégie pour traiter les symboles de la zone d'utilisation privée Unicode (PUA). |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Stratégie pour copier les données d'encodage des polices symboliques si la police TrueType symbolique possède plus d'une sous-table d'encodage. |
| [setTransferInfo](#setTransferInfo-boolean-) | Obtient ou définit s'il faut transférer les données de Info vers Metadata lors de la conversion en PDF 2.0. Vrai par défaut. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Action pour les objets d'image masqués |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Valeur par défaut FALSE et la couleur de transparence sera conservée pour maintenir l'apparence du document. Avec la valeur TRUE, la couleur de transparence sera convertie en opacité, certains objets pourraient être couverts. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Définit la résolution lors de la conversion d'images transparentes. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Règles pour résoudre les problèmes de mappage Unicode. Peut être null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructeur

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Constructeur

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructeur

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Constructeur

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructeur

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Constructeur

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Stratégie d'alignement du texte. Ce paramètre n'a de sens que lorsque le drapeau {@code AlignText} est activé.

**Returns:**
Élément SegmentAlignStrategy @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion de document n'affecte pas l'alignement du texte et laisse le texte tel quel. Cependant, dans certains cas, la substitution de police entraîne un chevauchement du texte ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé, des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être activé que pour les documents présentant des problèmes de texte chevauché ou d'espaces supplémentaires, car son utilisation diminue les performances et peut, dans certains cas, corrompre le contenu du texte.

**Returns:**
valeur booléenne

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Obtient ou définit les paramètres de balisage automatique lors de la conversion de format PDF. Les paramètres de balisage automatique sont utilisés pour configurer le comportement du processus de balisage automatique, généralement employé pour améliorer l'accessibilité et la structure d'un document PDF lors de la conversion vers un format PDF spécifique.

**Returns:**
Instance AutoTaggingSettings

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Action pour les images avec masque doux.

**Returns:**
valeur int

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Obtient l'objet PdfFormatConversionOptions avec les paramètres par défaut.

**Returns:**
Objet PdfFormatConversionOptions

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Action pour les objets qui ne peuvent pas être convertis.

**Returns:**
Élément ConvertErrorAction @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau {@code OptimizeFileSize} est activé. Par défaut, la combinaison des stratégies {@code SubsetFonts} et {@code RemoveDuplicatedFonts} est utilisée.

**Returns:**
Valeur byte @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Options pour les cas où il n'est pas possible d'intégrer certaines polices dans le document PDF.

**Returns:**
Objet FontEmbeddingOptions

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

Format PDF.

**Returns:**
Élément PdfFormat @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Obtient le nom de fichier du profil icc. En cas de null, le profil icc par défaut est utilisé.

**Returns:**
Objet String

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Chemin du fichier où les commentaires seront stockés.

**Returns:**
Objet String

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Flux où les commentaires seront stockés.

**Returns:**
Objet OutputStream

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Contient des indicateurs pour contrôler le processus de conversion PDF/A dans les cas où le document source ne correspond pas à la spécification PDF/A.

**Returns:**
Objet PdfANonSpecificationFlags

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Cette propriété est une propriété de sortie. Elle contient toutes les polices (noms de polices) qui n'ont pas été trouvées sur l'ordinateur lors de la dernière conversion PDF/A.

**Returns:**
Tableau de chaînes

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Obtient un indicateur qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A de taille réduite. Actuellement, cet indicateur influence l'optimisation des polices utilisées dans le document PDF ; éventuellement, à l'avenir, il pourra également être utilisé pour activer l'optimisation d'autres structures de données, comme les graphiques. L'ensemble de cet indicateur et du mode peut réduire considérablement la taille du fichier, mais peut également diminuer sensiblement les performances de la conversion.

**Returns:**
valeur booléenne

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Obtient ou définit le {@link OutputIntent} pour la conversion du format PDF. Le {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) spécifie le dispositif de sortie ou la condition prévue pour laquelle le document PDF est préparé. Il est utilisé pour garantir que les couleurs du document sont rendues correctement sur le dispositif cible.

**Returns:**
Instance OutputIntent

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Stratégie pour traiter les symboles de la zone d'utilisation privée Unicode (PUA).

**Returns:**
Élément PuaProcessingStrategy @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Stratégie pour copier les données d'encodage des polices symboliques si la police TrueType symbolique possède plus d'une sous-table d'encodage.

**Returns:**
Objet PdfASymbolicFontEncodingStrategy

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Action pour les objets d'image masqués

**Returns:**
Élément ConvertTransparencyAction @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Définit la résolution lors de la conversion d'images transparentes. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 300.

**Returns:**
Valeur de résolution

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Règles pour résoudre les problèmes de mappage Unicode. Peut être null.

**Returns:**
Objet ToUnicodeProcessingRules

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Obtient/definit l'exécution des flux d'images en mode asynchrone.

**Returns:**
valeur booléenne

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Le mode de conversion à faible mémoire est-il activé

**Returns:**
valeur booléenne

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Le mode d'analyse des polices page par page est-il activé Valeur par défaut = false

**Returns:**
valeur booléenne

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Obtient ou définit s'il faut transférer les données de Info vers Metadata lors de la conversion en PDF 2.0. Vrai par défaut.

**Returns:**
valeur booléenne

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Valeur par défaut FALSE et la couleur de transparence sera conservée pour maintenir l'apparence du document. Avec la valeur TRUE, la couleur de transparence sera convertie en opacité, certains objets pourraient être couverts.

**Returns:**
valeur booléenne

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Stratégie d'alignement du texte. Ce paramètre n'a de sens que lorsque le drapeau {@code AlignText} est activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alignStrategy |  | Élément SegmentAlignStrategy @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion de document n'affecte pas l'alignement du texte et laisse le texte tel quel. Cependant, dans certains cas, la substitution de police entraîne un chevauchement du texte ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé, des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être activé que pour les documents présentant des problèmes de texte chevauché ou d'espaces supplémentaires, car son utilisation diminue les performances et peut, dans certains cas, corrompre le contenu du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Obtient/definit l'exécution des flux d'images en mode asynchrone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Obtient ou définit les paramètres de balisage automatique lors de la conversion de format PDF. Les paramètres de balisage automatique sont utilisés pour configurer le comportement du processus de balisage automatique, généralement employé pour améliorer l'accessibilité et la structure d'un document PDF lors de la conversion vers un format PDF spécifique.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Action pour les images avec masque doux.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Action pour les objets qui ne peuvent pas être convertis.

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau {@code OptimizeFileSize} est activé. Par défaut, la combinaison des stratégies {@code SubsetFonts} et {@code RemoveDuplicatedFonts} est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
Format PDF.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Définit le nom de fichier du profil icc. En cas de null, le profil icc par défaut est utilisé.

### setLogFileName {#setLogFileName-java.lang.String-}
Chemin du fichier où les commentaires seront stockés.

### setLogStream {#setLogStream-java.io.OutputStream-}
Flux où les commentaires seront stockés.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Le mode de conversion à faible mémoire est-il activé

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Définit un indicateur qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A de taille réduite. Actuellement, cet indicateur influence l'optimisation des polices utilisées dans le document PDF ; éventuellement, à l'avenir, il pourra également être utilisé pour activer l'optimisation d'autres structures de données, comme les graphiques. L'ensemble de cet indicateur et du mode peut réduire considérablement la taille du fichier, mais peut aussi diminuer sensiblement les performances de la conversion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Obtient ou définit le {@link OutputIntent} pour la conversion du format PDF. Le {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) spécifie le dispositif de sortie ou la condition prévue pour laquelle le document PDF est préparé. Il est utilisé pour garantir que les couleurs du document sont rendues correctement sur le dispositif cible.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Définit le mode d'analyse des polices page par page activé Valeur par défaut = false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| b |  | valeur booléenne |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Stratégie pour traiter les symboles de la zone d'utilisation privée Unicode (PUA).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément PuaProcessingStrategy @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Stratégie pour copier les données d'encodage des polices symboliques si la police TrueType symbolique possède plus d'une sous-table d'encodage.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Obtient ou définit s'il faut transférer les données de Info vers Metadata lors de la conversion en PDF 2.0. Vrai par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Action pour les objets d'image masqués

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Valeur par défaut FALSE et la couleur de transparence sera conservée pour maintenir l'apparence du document. Avec la valeur TRUE, la couleur de transparence sera convertie en opacité, certains objets pourraient être couverts.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Définit la résolution lors de la conversion d'images transparentes. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 300.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpi |  | Valeur de résolution |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Règles pour résoudre les problèmes de mappage Unicode. Peut être null.
