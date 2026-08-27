---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Encapsule les éléments de contenu non signé extraits d'un document PDF. Cette classe fournit l'accès aux pages, aux champs de formulaire, aux XForms et aux annotations qui font partie du contenu non signé."
type: docs
weight: 50
url: /fr/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Encapsule les éléments de contenu non signé extraits d'un document PDF. Cette classe donne accès aux pages, aux champs de formulaire, aux XForms et aux annotations qui font partie du contenu non signé du document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Obtient un dictionnaire des annotations modifiées qui peuvent avoir été changées ou ajoutées. |
| [getForms](#getForms--) | Obtient les champs de formulaire qui ont été modifiés ou ajoutés de manière incrémentielle. |
| [getPages](#getPages--) | Obtient une liste de pages dont le contenu n'est pas signé ou a été modifié de manière incrémentielle. La page est considérée comme modifiée et les XForms ne sont pas vérifiés et n'apparaissent pas dans la liste des XForms. |
| [getXForms](#getXForms--) | Obtient un dictionnaire d'objets XForm modifiés qui peuvent avoir changé, bien que la page elle-même n'ait pas changé (pas dans la liste des Pages). |
| [setXForms](#setXForms-java.util.HashMap-) | Un dictionnaire d'objets XForm modifiés qui peuvent avoir changé, bien que la page elle-même n'ait pas changé (pas dans la liste des Pages). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Obtient un dictionnaire des annotations modifiées qui peuvent avoir été changées ou ajoutées.

**Returns:**
un dictionnaire d'annotations modifiées qui peuvent avoir changé ou été ajoutées.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Obtient les champs de formulaire qui ont été modifiés ou ajoutés de manière incrémentielle.

**Returns:**
champs de formulaire qui ont été modifiés ou ajoutés de manière incrémentielle.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Obtient une liste de pages dont le contenu n'est pas signé ou a été modifié de manière incrémentielle. La page est considérée comme modifiée et les XForms ne sont pas vérifiés et n'apparaissent pas dans la liste des XForms.

**Returns:**
une liste de pages dont le contenu n'est pas signé ou a été modifié de manière incrémentielle.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Obtient un dictionnaire d'objets XForm modifiés qui peuvent avoir changé, bien que la page elle-même n'ait pas changé (pas dans la liste des Pages).

**Returns:**
un dictionnaire d'objets XForm modifiés qui peuvent avoir changé, bien que la page elle-même n'ait pas changé (pas dans la liste des Pages).

### setXForms {#setXForms-java.util.HashMap-}
Un dictionnaire d'objets XForm modifiés qui peuvent avoir changé, bien que la page elle-même n'ait pas changé (pas dans la liste des Pages).
