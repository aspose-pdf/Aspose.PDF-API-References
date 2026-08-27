---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta la specifica del carattere originale. </p> <hr> <p> Fornisce informazioni relative al carattere originale, come , flag. Fornisce anche un flag che aiuta a verificare se la sostituzione avverrà. </p>"
type: docs
weight: 20
url: /it/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Rappresenta la specifica del carattere originale. </p> <hr> <p> Fornisce informazioni relative al carattere originale come , flag. Fornisce anche un flag che aiuta a verificare se la sostituzione avverrà comunque con il carattere e l'utente può sovrascrivere la logica di sostituzione predefinita. </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Inizializza un nuovo oggetto OriginalFontSpecification. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Ottiene il nome del carattere originale. |
| [isEmbedded](#isEmbedded--) | Ottiene un valore che indica se il carattere è incorporato. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Ottiene un valore che indica che la sostituzione è inevitabile. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Inizializza un nuovo oggetto OriginalFontSpecification.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Ottiene il nome del carattere originale.

**Returns:**
valore String

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Ottiene un valore che indica se il carattere è incorporato.

**Returns:**
valore booleano

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Ottiene un valore che indica che la sostituzione è inevitabile. </p>

**Returns:**
boolean value <hr> <p> Restituisce true nel caso in cui la sostituzione sia stata richiesta a causa dell'assenza del carattere originale o nel caso in cui il carattere originale non possa essere utilizzato nel contesto di qualche attività. Se l'utente ignora il flag e non sostituisce il carattere, viene eseguita la procedura di sostituzione del carattere predefinita. Tuttavia, offre all'utente l'opportunità di modificare la procedura di sostituzione standard e impostare un carattere migliore nel sistema. Restituisce false nel caso in cui il carattere originale sia presente, valido, ma sia consentito all'utente sostituirlo. </p>
