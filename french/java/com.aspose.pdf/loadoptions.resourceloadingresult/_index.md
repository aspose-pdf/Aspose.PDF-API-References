---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Résultat du chargement personnalisé de la ressource"
type: docs
weight: 2820
url: /fr/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Résultat du chargement personnalisé de la ressource

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Crée une instance du résultat de chargement |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getData](#getData--) | Données binaires chargées avec un chargeur personnalisé - elles doivent être définies après le chargement |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Parfois, l'encodage de la ressource est connu après ou pendant le chargement. Dans ce cas, le code personnalisé peut fournir au convertisseur cette connaissance via ce paramètre. Vous pouvez laisser null dans ce paramètre si l'encodage est inconnu ou n'a pas d'importance. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Parfois, il est impossible de charger la ressource demandée pour une raison quelconque. L'indisponibilité de la ressource ne conduit souvent pas à un plantage des conversions et le document résultant peut être créé quand même (mais peut-être avec une qualité légèrement inférieure, sans images, etc.). Si une exception s'est produite pendant le chargement, il suffit de l'attraper et de la placer dans ce paramètre - parfois cette information est utile au convertisseur pour le rendu du résultat. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Parfois, la connaissance du type MIME de la ressource chargée est utile pour le convertisseur. Vous pouvez fournir le type MIME (s'il est connu après le chargement) dans ce paramètre. Veuillez laisser le paramètre à null lorsque le type MIME est inconnu ou qu'il n'est pas nécessaire de le fournir. |
| [isLoadingCancelled](#isLoadingCancelled--) | Parfois, pour certaines raisons, le chargement ne doit pas être effectué par du code personnalisé. Dans ce cas, veuillez définir ce drapeau sur True. Ainsi, le convertisseur essaiera d'utiliser le chargeur de ressources interne par défaut pour obtenir ce résultat (comme il se comporte lorsqu'aucune stratégie personnalisée n'est fournie). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Parfois, l'encodage de la ressource est connu après ou pendant le chargement. Dans ce cas, le code personnalisé peut fournir au convertisseur cette connaissance via ce paramètre. Vous pouvez laisser null dans ce paramètre si l'encodage est inconnu ou n'a pas d'importance. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Parfois, il est impossible de charger la ressource demandée pour une raison quelconque. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Parfois, pour certaines raisons, le chargement ne doit pas être effectué par du code personnalisé. Dans ce cas, veuillez définir ce drapeau sur True. Ainsi, le convertisseur essaiera d'utiliser le chargeur de ressources interne par défaut pour obtenir ce résultat (comme il se comporte lorsqu'aucune stratégie personnalisée n'est fournie). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Parfois, la connaissance du type MIME de la ressource chargée est utile pour le convertisseur. Vous pouvez fournir le type MIME (s'il est connu après le chargement) dans ce paramètre. Veuillez laisser le paramètre à null lorsque le type MIME est inconnu ou qu'il n'est pas nécessaire de le fournir. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Crée une instance du résultat de chargement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données |  | Le résultat du chargement personnalisé doit toujours être fourni, il peut s'agir d'un tableau de longueur zéro s'il est impossible d'obtenir un résultat. |

### getData {#getData--}
```
public byte[] getData()
```

Données binaires chargées avec un chargeur personnalisé - elles doivent être définies après le chargement

**Returns:**
tableau de valeurs d'octets

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Parfois, l'encodage de la ressource est connu après ou pendant le chargement. Dans ce cas, le code personnalisé peut fournir au convertisseur cette connaissance via ce paramètre. Vous pouvez laisser null dans ce paramètre si l'encodage est inconnu ou n'a pas d'importance.

**Returns:**
Instance de Charset

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Parfois, il est impossible de charger la ressource demandée pour une raison quelconque. L'indisponibilité de la ressource ne conduit souvent pas à un plantage des conversions et le document résultant peut être créé quand même (mais peut-être avec une qualité légèrement inférieure, sans images, etc.). Si une exception s'est produite pendant le chargement, il suffit de l'attraper et de la placer dans ce paramètre - parfois cette information est utile au convertisseur pour le rendu du résultat.

**Returns:**
Exception

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Parfois, la connaissance du type MIME de la ressource chargée est utile pour le convertisseur. Vous pouvez fournir le type MIME (s'il est connu après le chargement) dans ce paramètre. Veuillez laisser le paramètre à null lorsque le type MIME est inconnu ou qu'il n'est pas nécessaire de le fournir.

**Returns:**
valeur String

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Parfois, pour certaines raisons, le chargement ne doit pas être effectué par du code personnalisé. Dans ce cas, veuillez définir ce drapeau sur True. Ainsi, le convertisseur essaiera d'utiliser le chargeur de ressources interne par défaut pour obtenir ce résultat (comme il se comporte lorsqu'aucune stratégie personnalisée n'est fournie).

**Returns:**
valeur booléenne

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Parfois, l'encodage de la ressource est connu après ou pendant le chargement. Dans ce cas, le code personnalisé peut fournir au convertisseur cette connaissance via ce paramètre. Vous pouvez laisser null dans ce paramètre si l'encodage est inconnu ou n'a pas d'importance.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Parfois, il est impossible de charger la ressource demandée pour une raison quelconque.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Parfois, pour certaines raisons, le chargement ne doit pas être effectué par du code personnalisé. Dans ce cas, veuillez définir ce drapeau sur True. Ainsi, le convertisseur essaiera d'utiliser le chargeur de ressources interne par défaut pour obtenir ce résultat (comme il se comporte lorsqu'aucune stratégie personnalisée n'est fournie).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| loadingCancelled |  | valeur booléenne |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Parfois, la connaissance du type MIME de la ressource chargée est utile pour le convertisseur. Vous pouvez fournir le type MIME (s'il est connu après le chargement) dans ce paramètre. Veuillez laisser le paramètre à null lorsque le type MIME est inconnu ou qu'il n'est pas nécessaire de le fournir.
