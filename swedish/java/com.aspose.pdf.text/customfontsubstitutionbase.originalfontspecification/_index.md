---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar original teckensnittsspecifikation. </p> <hr> <p> Tillhandahåller information relaterad till originalteckensnittet såsom , flagga. Tillhandahåller också en flagga som hjälper till att kontrollera om substitutionen kommer att. </p>"
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Representerar original teckensnittsspecifikation. </p> <hr> <p> Tillhandahåller information relaterad till originalteckensnittet såsom , flagga. Tillhandahåller också en flagga som hjälper till att kontrollera om bytet ändå kommer att ske med teckensnittet och användaren kan åsidosätta standardbyteslogiken. </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Initierar ett nytt OriginalFontSpecification-objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Hämtar originalteckensnittets namn. |
| [isEmbedded](#isEmbedded--) | Hämtar ett värde som indikerar om teckensnittet är inbäddat. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Hämtar ett värde som indikerar att substitutionen är oundviklig. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Initierar ett nytt OriginalFontSpecification-objekt.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Hämtar originalteckensnittets namn.

**Returns:**
String värde

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Hämtar ett värde som indikerar om teckensnittet är inbäddat.

**Returns:**
booleskt värde

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Hämtar ett värde som indikerar att substitutionen är oundviklig. </p>

**Returns:**
boolean value <hr> <p> Returnerar true om substitution begärdes på grund av avsaknad av originalteckensnittet eller om originalteckensnittet inte kan användas i samband med någon uppgift. Om användaren ignorerar flaggan och inte ersätter teckensnittet - utförs standardproceduren för teckensnittssubstitution. Men det ger möjlighet för användaren att byta standardproceduren för teckensnittssubstitution och ange ett bättre teckensnitt till systemet. Returnerar false om originalteckensnittet är närvarande, giltigt, men det är tillåtet för användaren att ersätta det. </p>
