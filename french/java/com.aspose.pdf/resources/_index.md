---
title: "Resources"
linktitle: "Resources"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant les ressources de page."
type: docs
weight: 4220
url: /fr/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Classe représentant les ressources de page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Efface les données en cache, libère la mémoire, etc. |
| [getExtGStates](#getExtGStates--) | Obtient tous les ExGStates à partir des ressources. |
| [getFonts](#getFonts--) | Obtient la collection de ressources {@code Fonts} |
| [getFonts](#getFonts-boolean-) | Renvoie la collection de polices. Si les ressources ne contiennent pas d'entrée de polices, elle sera créée en fonction du drapeau CreateIfAbsent. |
| [getForms](#getForms--) | Obtient la collection {@code Forms} de formulaires |
| [getImages](#getImages--) | Obtient la collection {@code Images} d'images |
| [getResourceDictionary](#getResourceDictionary--) | Champ interne |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Obtient les ressources pour |
| [isCommonResource](#isCommonResource--) | Vrai si ces ressources sont communes, c’est‑à‑dire partagées entre plusieurs pages (placées dans le dictionnaire des pages ou dans chaque page en tant que référence d’objet). La manipulation des ressources communes doit être effectuée très soigneusement, par exemple la suppression d’un objet des ressources communes dans une page peut provoquer des erreurs sur d’autres pages si l’objet supprimé était utilisé pour d’autres pages. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | À usage interne uniquement ! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Efface les données en cache, libère la mémoire, etc.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Obtient tous les ExGStates à partir des ressources.

**Returns:**
Renvoie un dictionnaire avec les clés de noms ExGStates.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Obtient la collection de ressources {@code Fonts}

**Returns:**
Objet FontCollection

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Renvoie la collection de polices. Si les ressources ne contiennent pas d'entrée de polices, elle sera créée en fonction du drapeau CreateIfAbsent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createIfAbsent |  | Si ce drapeau est vrai, les polices seront créées si cette entrée est absente. |

**Returns:**
Collection de polices.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Obtient la collection {@code Forms} de formulaires

**Returns:**
Objet XFormCollection

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Obtient la collection {@code Images} d'images

**Returns:**
Objet XImageCollection

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Champ interne

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Obtient les ressources pour

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Vrai si ces ressources sont communes, c’est‑à‑dire partagées entre plusieurs pages (placées dans le dictionnaire des pages ou dans chaque page en tant que référence d’objet). La manipulation des ressources communes doit être effectuée très soigneusement, par exemple la suppression d’un objet des ressources communes dans une page peut provoquer des erreurs sur d’autres pages si l’objet supprimé était utilisé pour d’autres pages.

**Returns:**
valeur booléenne

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
À usage interne uniquement !
