---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "La norme PDF/A exige que toutes les polices soient incorporées dans le document. Cette classe comprend des indicateurs pour les cas où il n'est pas possible d'incorporer une police parce que cette police est absente."
type: docs
weight: 1680
url: /fr/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

La norme PDF/A exige que toutes les polices soient incorporées dans le document. Cette classe inclut des indicateurs pour les cas où il n'est pas possible d'incorporer une police parce que cette police est absente sur le PC de destination.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Initialise une nouvelle instance de la classe {@link FontEmbeddingOptions}. Ce constructeur définit la valeur par défaut de la propriété {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) à {@code }. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Indique s'il faut substituer une police non incorporée en utilisant la stratégie de substitution de police par défaut. Par défaut false; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Indique s'il faut substituer une police non incorporée en utilisant la stratégie de substitution de police par défaut. Par défaut false; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Initialise une nouvelle instance de la classe {@link FontEmbeddingOptions}. Ce constructeur définit la valeur par défaut de la propriété {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) à {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Indique s'il faut substituer une police non incorporée en utilisant la stratégie de substitution de police par défaut. Par défaut false;

**Returns:**
valeur booléenne

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Indique s'il faut substituer une police non incorporée en utilisant la stratégie de substitution de police par défaut. Par défaut false;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
