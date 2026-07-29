---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion de PDF en HTML."
type: docs
weight: 2070
url: /fr/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion de PDF en HTML.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | crée une nouvelle instance de HtmlImageSavingInfo |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Indique au code personnalisé à quelle page du jeu de fichiers HTML générés l'image enregistrée se rapporte. Si la division en pages est désactivée, cette valeur contient toujours '1' car dans ce cas une seule page HTML est générée. |
| [getImageType](#getImageType--) | Représente le type d'image enregistrée référencée dans le HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider quoi faire. |
| [getParentType](#getParentType--) | L'image enregistrée peut concerner le HTML lui‑même ou être extraite d'un SVG intégré au HTML. Cette propriété peut indiquer au code personnalisé le type de parent de l'image traitée. Elle est définie par le convertisseur et peut être utilisée dans le code personnalisé pour décider quoi faire avec cette image (par ex. le code personnalisé peut décider où enregistrer l'image ou comment elle doit être référencée dans le contenu du parent). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Indique au code personnalisé à quelle page du document PDF original l'image enregistrée se rapporte. Puisqu'il est possible que toutes les pages du document original ne soient pas enregistrées, cette valeur indique le numéro de page d'origine dans le PDF. Si, pour une raison quelconque, le numéro de page d'origine est inconnu, elle renvoie toujours '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Indique au code personnalisé à quelle page du jeu de fichiers HTML générés l'image enregistrée se rapporte. Si la division en pages est désactivée, cette valeur contient toujours '1' car dans ce cas une seule page HTML est générée. |
| [setImageType](#setImageType-int-) | Représente le type d'image enregistrée référencée dans le HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider quoi faire. |
| [setParentType](#setParentType-int-) | L'image enregistrée peut concerner le HTML lui‑même ou être extraite d'un SVG intégré au HTML. Cette propriété peut indiquer au code personnalisé le type de parent de l'image traitée. Elle est définie par le convertisseur et peut être utilisée dans le code personnalisé pour décider quoi faire avec cette image (par ex. le code personnalisé peut décider où enregistrer l'image ou comment elle doit être référencée dans le contenu du parent). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Indique au code personnalisé à quelle page du document PDF original l'image enregistrée se rapporte. Puisqu'il est possible que toutes les pages du document original ne soient pas enregistrées, cette valeur indique le numéro de page d'origine dans le PDF. Si, pour une raison quelconque, le numéro de page d'origine est inconnu, elle renvoie toujours '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

crée une nouvelle instance de HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Indique au code personnalisé à quelle page du jeu de fichiers HTML générés l'image enregistrée se rapporte. Si la division en pages est désactivée, cette valeur contient toujours '1' car dans ce cas une seule page HTML est générée.

**Returns:**
valeur int

### getImageType {#getImageType--}
```
public int getImageType()
```

Représente le type d'image enregistrée référencée dans le HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider quoi faire.

**Returns:**
Élément HtmlImageType @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

L'image enregistrée peut concerner le HTML lui‑même ou être extraite d'un SVG intégré au HTML. Cette propriété peut indiquer au code personnalisé le type de parent de l'image traitée. Elle est définie par le convertisseur et peut être utilisée dans le code personnalisé pour décider quoi faire avec cette image (par ex. le code personnalisé peut décider où enregistrer l'image ou comment elle doit être référencée dans le contenu du parent).

**Returns:**
Élément ImageParentTypes @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Indique au code personnalisé à quelle page du document PDF original l'image enregistrée se rapporte. Puisqu'il est possible que toutes les pages du document original ne soient pas enregistrées, cette valeur indique le numéro de page d'origine dans le PDF. Si, pour une raison quelconque, le numéro de page d'origine est inconnu, elle renvoie toujours '1'.

**Returns:**
valeur int

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Indique au code personnalisé à quelle page du jeu de fichiers HTML générés l'image enregistrée se rapporte. Si la division en pages est désactivée, cette valeur contient toujours '1' car dans ce cas une seule page HTML est générée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlHostPageNumber |  | valeur int |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Représente le type d'image enregistrée référencée dans le HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider quoi faire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageType |  | Élément HtmlImageType @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

L'image enregistrée peut concerner le HTML lui‑même ou être extraite d'un SVG intégré au HTML. Cette propriété peut indiquer au code personnalisé le type de parent de l'image traitée. Elle est définie par le convertisseur et peut être utilisée dans le code personnalisé pour décider quoi faire avec cette image (par ex. le code personnalisé peut décider où enregistrer l'image ou comment elle doit être référencée dans le contenu du parent).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parentType |  | Élément ImageParentTypes @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Indique au code personnalisé à quelle page du document PDF original l'image enregistrée se rapporte. Puisqu'il est possible que toutes les pages du document original ne soient pas enregistrées, cette valeur indique le numéro de page d'origine dans le PDF. Si, pour une raison quelconque, le numéro de page d'origine est inconnu, elle renvoie toujours '1'.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfHostPageNumber |  | valeur int |
