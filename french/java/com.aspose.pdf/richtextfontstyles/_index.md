---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options pour le style des fragments de texte dans RichText."
type: docs
weight: 4300
url: /fr/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Options pour le style des fragments de texte dans RichText.

## Champs

| Champ | Description |
| --- | --- |
| [Bold](#Bold) | Option qui spécifie le gras. |
| [ClearExisting](#ClearExisting) | Si définie, supprime tous les styles existants avant d'appliquer des styles supplémentaires. Lorsqu'elle est combinée avec d'autres indicateurs de style (par exemple {@code RichTextFontStyles#Bold}), elle réinitialise d'abord les styles, puis applique ceux spécifiés. Sans cet indicateur, les nouveaux styles sont ajoutés aux styles existants. |
| [Italic](#Italic) | Option qui spécifie l'italique. |
| [Underline](#Underline) | Option qui spécifie le soulignement. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Vérifie si le drapeau spécifié est défini. |

### Bold {#Bold}
```
public static final int Bold
```

Option qui spécifie le gras.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Si définie, supprime tous les styles existants avant d'appliquer des styles supplémentaires. Lorsqu'elle est combinée avec d'autres indicateurs de style (par exemple {@code RichTextFontStyles#Bold}), elle réinitialise d'abord les styles, puis applique ceux spécifiés. Sans cet indicateur, les nouveaux styles sont ajoutés aux styles existants.

### Italic {#Italic}
```
public static final int Italic
```

Option qui spécifie l'italique.

### Underline {#Underline}
```
public static final int Underline
```

Option qui spécifie le soulignement.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Vérifie si le drapeau spécifié est défini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeau |  | la valeur d'énumération représentant le drapeau à vérifier |
| flagToCheck |  | la valeur d'énumération représentant le drapeau à vérifier |

**Returns:**
{@code true} si le drapeau est défini ; {@code false} sinon
