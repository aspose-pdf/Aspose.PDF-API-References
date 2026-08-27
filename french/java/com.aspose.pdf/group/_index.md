---
title: "Group"
linktitle: "Group"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparent."
type: docs
weight: 1850
url: /fr/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

Une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparent.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | Le constructeur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Obtient ColorSpace <p> |
| [isKnockout](#isKnockout--) | pour usage interne uniquement Si ce drapeau est faux, les objets ultérieurs du groupe sont composés avec les précédents avec lesquels ils se chevauchent ; si vrai, ils sont composés avec l’arrière-plan initial du groupe et écrasent (\"knock out\") tout objet antérieur qui se chevauche. |
| [isTransparency](#isTransparency--) | pour un usage interne uniquement renvoie le drapeau de transparence du groupe. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | L'espace couleur du groupe. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | Si ce drapeau est faux, les objets ultérieurs du groupe sont composés avec les objets antérieurs avec lesquels ils se chevauchent ; si vrai, ils sont composés avec le fond initial du groupe et écrasent (\"knock out\") tout objet antérieur qui se chevauche. |

### Group {#Group-com.aspose.pdf.Page-}
Le constructeur.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Obtient ColorSpace <p>

**Returns:**
Valeur ColorSpace. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

pour usage interne uniquement Si ce drapeau est faux, les objets ultérieurs du groupe sont composés avec les précédents avec lesquels ils se chevauchent ; si vrai, ils sont composés avec l’arrière-plan initial du groupe et écrasent (\"knock out\") tout objet antérieur qui se chevauche.

**Returns:**
Élément ExtendedBoolean @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

pour un usage interne uniquement renvoie le drapeau de transparence du groupe.

**Returns:**
valeur booléenne

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
L'espace couleur du groupe.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
Si ce drapeau est faux, les objets ultérieurs du groupe sont composés avec les objets antérieurs avec lesquels ils se chevauchent ; si vrai, ils sont composés avec le fond initial du groupe et écrasent (\"knock out\") tout objet antérieur qui se chevauche.
