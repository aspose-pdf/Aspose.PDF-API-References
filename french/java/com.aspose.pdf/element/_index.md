---
title: "Élément"
linktitle: "Élément"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'élément de base de la structure logique."
type: docs
weight: 1180
url: /fr/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Classe représentant l'élément de base de la structure logique.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getActualText](#getActualText--) | (Facultatif ; PDF 1.4) Texte qui constitue un remplacement exact de l’élément de structure et de ses enfants. Ce texte de remplacement (qui doit s’appliquer à la plus petite portion de contenu possible) est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins. |
| [getAlt](#getAlt--) | (Facultatif) Une description alternative de l’élément de structure et de ses enfants sous forme lisible par l’homme, qui est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins. |
| [getChildren](#getChildren--) | Obtient la collection des éléments enfants. |
| [getE](#getE--) | (Facultatif ; PDF 1.5) La forme développée d’une abréviation. |
| [getLang](#getLang--) | (Facultatif ; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte de l’élément de structure, sauf lorsqu’elle est remplacée par des spécifications de langue pour les éléments de structure imbriqués ou le contenu balisé. |
| [remove](#remove--) | Supprimer l’élément. |
| [setActualText](#setActualText-java.lang.String-) | (Facultatif ; PDF 1.4) Texte qui constitue un remplacement exact de l’élément de structure et de ses enfants. Ce texte de remplacement (qui doit s’appliquer à la plus petite portion de contenu possible) est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins. |
| [setAlt](#setAlt-java.lang.String-) | (Facultatif) Une description alternative de l’élément de structure et de ses enfants sous forme lisible par l’homme, qui est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins. |
| [setE](#setE-java.lang.String-) | (Facultatif ; PDF 1.5) La forme développée d’une abréviation. |
| [setLang](#setLang-java.lang.String-) | (Facultatif ; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte de l’élément de structure, sauf lorsqu’elle est remplacée par des spécifications de langue pour les éléments de structure imbriqués ou le contenu balisé. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Facultatif ; PDF 1.4) Texte qui constitue un remplacement exact de l’élément de structure et de ses enfants. Ce texte de remplacement (qui doit s’appliquer à la plus petite portion de contenu possible) est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins.

**Returns:**
Objet String

### getAlt {#getAlt--}
```
public String getAlt()
```

(Facultatif) Une description alternative de l’élément de structure et de ses enfants sous forme lisible par l’homme, qui est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins.

**Returns:**
Objet String

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Obtient la collection des éléments enfants.

**Returns:**
Instance d’ElementCollection

### getE {#getE--}
```
public String getE()
```

(Facultatif ; PDF 1.5) La forme développée d’une abréviation.

**Returns:**
Objet String

### getLang {#getLang--}
```
public String getLang()
```

(Facultatif ; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte de l’élément de structure, sauf lorsqu’elle est remplacée par des spécifications de langue pour les éléments de structure imbriqués ou le contenu balisé.

**Returns:**
Objet String

### remove {#remove--}
```
public final void remove()
```

Supprimer l’élément.

### setActualText {#setActualText-java.lang.String-}
(Facultatif ; PDF 1.4) Texte qui constitue un remplacement exact de l’élément de structure et de ses enfants. Ce texte de remplacement (qui doit s’appliquer à la plus petite portion de contenu possible) est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins.

### setAlt {#setAlt-java.lang.String-}
(Facultatif) Une description alternative de l’élément de structure et de ses enfants sous forme lisible par l’homme, qui est utile lors de l’extraction du contenu du document afin de soutenir l’accessibilité pour les utilisateurs en situation de handicap ou à d’autres fins.

### setE {#setE-java.lang.String-}
(Facultatif ; PDF 1.5) La forme développée d’une abréviation.

### setLang {#setLang-java.lang.String-}
(Facultatif ; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte de l’élément de structure, sauf lorsqu’elle est remplacée par des spécifications de langue pour les éléments de structure imbriqués ou le contenu balisé.
