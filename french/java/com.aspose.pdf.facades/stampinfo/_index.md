---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant les informations du tampon."
type: docs
weight: 710
url: /fr/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Classe représentant les informations du tampon.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getForm](#getForm--) | Obtient le XForm du tampon. |
| [getImage](#getImage--) | Obtient l'image du tampon. Peut être nul si le tampon ne contient pas d'images (par exemple pour un tampon texte). |
| [getImageInternal](#getImageInternal--) | Obtient l'image du tampon. Peut être nul si le tampon ne contient pas d'images (par exemple pour un tampon texte). |
| [getIndexOnPage](#getIndexOnPage--) | Obtient l'indice du tampon sur la page. |
| [getRectangle](#getRectangle--) | Obtient le rectangle où le tampon est placé. |
| [getStampId](#getStampId--) | Obtient l'identifiant du tampon. |
| [getStampType](#getStampType--) | Obtient le type du tampon (image / formulaire). |
| [getText](#getText--) | Obtient le texte du tampon. |
| [getVisible](#getVisible--) | Obtient la visibilité du tampon. Si false alors le tampon est masqué (avec HideStampById). Le tampon masqué peut être restauré par ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Obtient le XForm du tampon.

**Returns:**
objet XForm

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Obtient l'image du tampon. Peut être nul si le tampon ne contient pas d'images (par exemple pour un tampon texte).

**Returns:**
Objet BufferedImage

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Obtient l'image du tampon. Peut être nul si le tampon ne contient pas d'images (par exemple pour un tampon texte).

**Returns:**
Objet image

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Obtient l'indice du tampon sur la page.

**Returns:**
valeur int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle où le tampon est placé.

**Returns:**
Élément rectangle

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtient l'identifiant du tampon.

**Returns:**
valeur int

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Obtient le type du tampon (image / formulaire).

**Returns:**
Élément StampType @see StampType

### getText {#getText--}
```
public String getText()
```

Obtient le texte du tampon.

**Returns:**
valeur String

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Obtient la visibilité du tampon. Si false alors le tampon est masqué (avec HideStampById). Le tampon masqué peut être restauré par ShowStampById.

**Returns:**
valeur booléenne
