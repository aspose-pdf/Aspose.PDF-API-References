---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per una strategia di sostituzione dei caratteri che sostituisce i caratteri con quelli di sistema."
type: docs
weight: 110
url: /it/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Rappresenta una classe per una strategia di sostituzione dei caratteri che sostituisce i caratteri con quelli di sistema.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Inizializza una nuova istanza della classe {@code SystemFontsSubstitution}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Ottiene o imposta il font di sostituzione predefinito. Il font viene utilizzato quando non viene trovata alcuna altra sostituzione valida, ma il font iniziale appartiene alla categoria di sostituzione target ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Ottiene o imposta le categorie di font di sostituzione che dovrebbero essere sostituite con i font di sistema. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Ottiene o imposta il font di sostituzione predefinito. Il font viene utilizzato quando non viene trovata alcuna altra sostituzione valida, ma il font iniziale appartiene alla categoria di sostituzione target ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Ottiene o imposta le categorie di font di sostituzione che dovrebbero essere sostituite con i font di sistema. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Inizializza una nuova istanza della classe {@code SystemFontsSubstitution}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontCategories |  | Categorie di carattere di destinazione da sostituire con i caratteri di sistema |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Ottiene o imposta il font di sostituzione predefinito. Il font viene utilizzato quando non viene trovata alcuna altra sostituzione valida, ma il font iniziale appartiene alla categoria di sostituzione target ({@code FontCategories}).

**Returns:**
oggetto Font

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Ottiene o imposta le categorie di font di sostituzione che dovrebbero essere sostituite con i font di sistema.

**Returns:**
Elemento SubstitutionFontCategories @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Ottiene o imposta il font di sostituzione predefinito. Il font viene utilizzato quando non viene trovata alcuna altra sostituzione valida, ma il font iniziale appartiene alla categoria di sostituzione target ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Ottiene o imposta le categorie di font di sostituzione che dovrebbero essere sostituite con i font di sistema.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento SubstitutionFontCategories @see SubstitutionFontCategories |
