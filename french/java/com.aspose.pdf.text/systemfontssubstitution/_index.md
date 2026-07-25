---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour une stratégie de substitution de police qui remplace les polices par des polices système."
type: docs
weight: 110
url: /fr/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Représente une classe pour une stratégie de substitution de police qui remplace les polices par des polices système.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Initialise une nouvelle instance de la classe {@code SystemFontsSubstitution}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Obtient ou définit la police de substitution par défaut. La police est utilisée lorsqu'aucune autre substitution valide n'a été trouvée mais que la police initiale appartient à la catégorie de substitution cible ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Obtient ou définit les catégories de police de substitution qui doivent être remplacées par des polices système. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Obtient ou définit la police de substitution par défaut. La police est utilisée lorsqu'aucune autre substitution valide n'a été trouvée mais que la police initiale appartient à la catégorie de substitution cible ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Obtient ou définit les catégories de police de substitution qui doivent être remplacées par des polices système. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Initialise une nouvelle instance de la classe {@code SystemFontsSubstitution}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontCategories |  | Catégories de polices cibles à substituer par les polices système |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Obtient ou définit la police de substitution par défaut. La police est utilisée lorsqu'aucune autre substitution valide n'a été trouvée mais que la police initiale appartient à la catégorie de substitution cible ({@code FontCategories}).

**Returns:**
Objet Font

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Obtient ou définit les catégories de police de substitution qui doivent être remplacées par des polices système.

**Returns:**
Élément SubstitutionFontCategories @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Obtient ou définit la police de substitution par défaut. La police est utilisée lorsqu'aucune autre substitution valide n'a été trouvée mais que la police initiale appartient à la catégorie de substitution cible ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Obtient ou définit les catégories de police de substitution qui doivent être remplacées par des polices système.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément SubstitutionFontCategories @see SubstitutionFontCategories |
