---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente les options d'enregistrement qui utilisent une méthode de conversion unifiée (avec un modèle de document interne unifié)."
type: docs
weight: 5420
url: /fr/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Cette classe représente les options d'enregistrement qui utilisent une méthode de conversion unifiée (avec un modèle de document interne unifié).

## Champs

| Champ | Description |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Traiter les pages avec quelques threads. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Représente le processeur interne d'événements de progression qui fonctionne pendant la conversion et traduit les événements de conversion des étapes internes en événements de progression totale externes. Cette classe diffuse également des événements permettant de libérer les ressources qui ne sont plus nécessaires. Cette classe interne gère les événements de progression de PDF vers APS et d'APS vers [Other format] afin de calculer la progression totale et d'informer le code du client de cette progression totale. Cette classe utilise deux types d'événements : conversion de modèle ApsToExternal et événements de conversion de PDF vers APS pour générer des événements de progression totale. L'exportation comporte trois étapes : 1) PDF vers APS 2) reconnaissance APS 3) exportation APS vers le format cible. Le constructeur permet d'ajuster le nombre de pages converties et la partie approximative de chaque étape dans la progression totale. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Cet attribut active la fonctionnalité d'extraction d'images ou de texte pour les documents PDF avec une sous-couche OCR. Valeur : {@code true} le texte sera extrait dans le document résultat ; sinon, {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière-plan identiques en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anti‑aliasing) diffèrent de celles d'Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec une sous-couche OCR. </p>Valeur : {@code true} le texte sera extrait dans le document résultant ; sinon, {@code false}. <hr> Valeur par défaut == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Représente le processeur interne d'événements de progression qui fonctionne pendant la conversion et traduit les événements de conversion des étapes internes en événements de progression totale externes. Cette classe diffuse également des événements permettant de libérer les ressources qui ne sont plus nécessaires. Cette classe interne gère les événements de progression de PDF vers APS et d'APS vers [Other format] afin de calculer la progression totale et d'informer le code du client de cette progression totale. Cette classe utilise deux types d'événements : conversion de modèle ApsToExternal et événements de conversion de PDF vers APS pour générer des événements de progression totale. L'exportation comporte trois étapes : 1) PDF vers APS 2) reconnaissance APS 3) exportation APS vers le format cible. Le constructeur permet d'ajuster le nombre de pages converties et la partie approximative de chaque étape dans la progression totale. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière-plan identiques en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anti‑aliasing) diffèrent de celles d'Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Traiter les pages avec quelques threads.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Représente le processeur interne d'événements de progression qui fonctionne pendant la conversion et traduit les événements de conversion des étapes internes en événements de progression totale externes. Cette classe diffuse également des événements permettant de libérer les ressources qui ne sont plus nécessaires. Cette classe interne gère les événements de progression de PDF vers APS et d'APS vers [Other format] afin de calculer la progression totale et d'informer le code du client de cette progression totale. Cette classe utilise deux types d'événements : conversion de modèle ApsToExternal et événements de conversion de PDF vers APS pour générer des événements de progression totale. L'exportation comporte trois étapes : 1) PDF vers APS 2) reconnaissance APS 3) exportation APS vers le format cible. Le constructeur permet d'ajuster le nombre de pages converties et la partie approximative de chaque étape dans la progression totale.

**Returns:**
instance de ConversionProgressEventsTranslator

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Cet attribut active la fonctionnalité d'extraction d'images ou de texte pour les documents PDF avec une sous-couche OCR. Valeur : {@code true} le texte sera extrait dans le document résultat ; sinon, {@code false}.

**Returns:**
valeur booléenne

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière-plan identiques en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anti‑aliasing) diffèrent de celles d'Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire.

**Returns:**
valeur booléenne

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec une sous-couche OCR. </p>Valeur : {@code true} le texte sera extrait dans le document résultant ; sinon, {@code false}. <hr> Valeur par défaut == false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Représente le processeur interne d'événements de progression qui fonctionne pendant la conversion et traduit les événements de conversion des étapes internes en événements de progression totale externes. Cette classe diffuse également des événements permettant de libérer les ressources qui ne sont plus nécessaires. Cette classe interne gère les événements de progression de PDF vers APS et d'APS vers [Other format] afin de calculer la progression totale et d'informer le code du client de cette progression totale. Cette classe utilise deux types d'événements : conversion de modèle ApsToExternal et événements de conversion de PDF vers APS pour générer des événements de progression totale. L'exportation comporte trois étapes : 1) PDF vers APS 2) reconnaissance APS 3) exportation APS vers le format cible. Le constructeur permet d'ajuster le nombre de pages converties et la partie approximative de chaque étape dans la progression totale.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière-plan identiques en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anti‑aliasing) diffèrent de celles d'Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valeur booléenne |
