---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de chargement/importation d'un fichier html dans un document pdf."
type: docs
weight: 1960
url: /fr/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Représente les options de chargement/importation d'un fichier html dans un document pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Crée des options de chargement pour convertir du HTML en document PDF avec un chemin de base vide. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Crée des options de chargement pour convertir du HTML en document PDF avec un chemin de base vide. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBasePath](#getBasePath--) | Le chemin de base/URL du fichier HTML. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.PDF dans le cloud, l'accès direct aux fichiers référencés est impossible : dans ce cas, le code client placé dans une méthode spéciale doit être utilisé, et le délégué qui fait référence à cette méthode doit être affecté à cet attribut. |
| [getHtmlMediaType](#getHtmlMediaType--) | Obtient ou définit les types de médias possibles utilisés lors du rendu. |
| [getInputEncoding](#getInputEncoding--) | Obtient l'attribut spécifiant l'encodage utilisé pour ce document au moment de l'analyse. Si cet attribut est nul, l'encodage sera déterminé à partir de l'attribut du jeu de caractères du document. |
| [getPageInfo](#getPageInfo--) | Obtient les informations de page du document |
| [getPageLayoutOption](#getPageLayoutOption--) | Obtient ou définit l'option de mise en page. |
| [isEmbedFonts](#isEmbedFonts--) | Obtient ou définit l'incorporation des polices dans le document résultant |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Obtient ou définit le drapeau qui indique que les règles @page définies dans le CSS remplaceront les valeurs définies dans PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Obtient ou définit le rendu de tout le document sur une seule page |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Obtient ou définit l'incorporation des polices dans le document résultant |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Obtient ou définit les types de médias possibles utilisés lors du rendu. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Définit l'attribut spécifiant l'encodage utilisé pour ce document au moment de l'analyse. Si cet attribut est nul, l'encodage sera déterminé à partir de l'attribut du jeu de caractères du document. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Définit les informations de page du document |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Obtient ou définit l'option de mise en page. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Obtient ou définit le drapeau qui indique que les règles @page définies dans le CSS remplaceront les valeurs définies dans PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Obtient ou définit le rendu de tout le document sur une seule page |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Crée des options de chargement pour convertir du HTML en document PDF avec un chemin de base vide.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Crée des options de chargement pour convertir du HTML en document PDF avec un chemin de base vide.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Le chemin de base/URL du fichier HTML.

**Returns:**
valeur String

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.PDF dans le cloud, l'accès direct aux fichiers référencés est impossible : dans ce cas, le code client placé dans une méthode spéciale doit être utilisé, et le délégué qui fait référence à cette méthode doit être affecté à cet attribut.

**Returns:**
Instance de ResourceLoadingStrategy

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Obtient ou définit les types de médias possibles utilisés lors du rendu.

**Returns:**
Élément HtmlMediaType

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Obtient l'attribut spécifiant l'encodage utilisé pour ce document au moment de l'analyse. Si cet attribut est nul, l'encodage sera déterminé à partir de l'attribut du jeu de caractères du document.

**Returns:**
valeur String

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtient les informations de page du document

**Returns:**
informations de page

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Obtient ou définit l'option de mise en page.

**Returns:**
Élément HtmlPageLayoutOption @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Obtient ou définit l'incorporation des polices dans le document résultant

**Returns:**
valeur booléenne

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Obtient ou définit le drapeau qui indique que les règles @page définies dans le CSS remplaceront les valeurs définies dans PageInfo.

**Returns:**
valeur booléenne

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Obtient ou définit le rendu de tout le document sur une seule page

**Returns:**
valeur booléenne

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Obtient ou définit l'incorporation des polices dans le document résultant

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Obtient ou définit les types de médias possibles utilisés lors du rendu.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Définit l'attribut spécifiant l'encodage utilisé pour ce document au moment de l'analyse. Si cet attribut est nul, l'encodage sera déterminé à partir de l'attribut du jeu de caractères du document.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Définit les informations de page du document

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Obtient ou définit l'option de mise en page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément HtmlPageLayoutOption @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Obtient ou définit le drapeau qui indique que les règles @page définies dans le CSS remplaceront les valeurs définies dans PageInfo.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Obtient ou définit le rendu de tout le document sur une seule page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
