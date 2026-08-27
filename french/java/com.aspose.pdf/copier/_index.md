---
title: "Copier"
linktitle: "Copier"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour la copie d'objet."
type: docs
weight: 850
url: /fr/java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

Classe pour la copie d'objet.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Crée une instance de la classe Copier. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Duplique IPdfPrimitive |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Crée une copie de l'objet avec tous les objets dépendants. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | obtenir Allow Reuse Page Content |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | obtenir Ignore Corrupted Objects |
| [getRestrictedKeys](#getRestrictedKeys--) | obtenir Restricted Keys |
| [getReuseStreams](#getReuseStreams--) | obtenir Reuse Streams |
| [getUseStubs](#getUseStubs--) | Indique si les stubs doivent être utilisés pendant le processus de duplication. Si l'option est activée, les flux seront copiés, sinon un lien vers le flux source sera utilisé. Cela ne vous permettra pas de fermer le document copié, mais économise le processus de copie et la mémoire. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | définir Allow Reuse Page Content |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Définir Ignore Corrupted Objects |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | définir Restricted Keys |
| [setReuseStreams](#setReuseStreams-boolean-) | définir Reuse Streams |
| [setUseStubs](#setUseStubs-boolean-) | Indique si les stubs doivent être utilisés pendant le processus de duplication. Si l'option est activée, les flux seront copiés, sinon un lien vers le flux source sera utilisé. Cela ne vous permettra pas de fermer le document copié, mais économise le processus de copie et la mémoire. |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
Crée une instance de la classe Copier.

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
Duplique IPdfPrimitive

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
Crée une copie de l'objet avec tous les objets dépendants.

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

obtenir Allow Reuse Page Content

**Returns:**
valeur booléenne

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

obtenir Ignore Corrupted Objects

**Returns:**
valeur booléenne

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

obtenir Restricted Keys

**Returns:**
String[] array

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

obtenir Reuse Streams

**Returns:**
valeur booléenne

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

Indique si les stubs doivent être utilisés pendant le processus de duplication. Si l'option est activée, les flux seront copiés, sinon un lien vers le flux source sera utilisé. Cela ne vous permettra pas de fermer le document copié, mais économise le processus de copie et la mémoire.

**Returns:**
valeur booléenne

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

définir Allow Reuse Page Content

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Définir Ignore Corrupted Objects

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
définir Restricted Keys

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

définir Reuse Streams

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

Indique si les stubs doivent être utilisés pendant le processus de duplication. Si l'option est activée, les flux seront copiés, sinon un lien vers le flux source sera utilisé. Cela ne vous permettra pas de fermer le document copié, mais économise le processus de copie et la mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
