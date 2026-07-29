---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt die ursprüngliche Schriftspezifikation dar. </p> <hr> <p> Liefert Informationen zur ursprünglichen Schrift, wie z. B. , Flag. Außerdem liefert ein Flag, das hilft zu prüfen, ob die Substitution stattfinden wird. </p>"
type: docs
weight: 20
url: /de/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Stellt die ursprüngliche Schriftartenspezifikation dar. </p> <hr> <p> Stellt Informationen zur ursprünglichen Schriftart bereit, wie z. B. ein Flag. Außerdem wird ein Flag bereitgestellt, das hilft zu prüfen, ob die Ersetzung ohnehin mit der Schriftart stattfinden wird, und der Benutzer kann die Standard‑Ersetzungslogik überschreiben. </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Initialisiert ein neues OriginalFontSpecification-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Liest den Namen der Originalschrift. |
| [isEmbedded](#isEmbedded--) | Liest einen Wert, der angibt, ob die Schrift eingebettet ist. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Liest einen Wert, der anzeigt, dass die Substitution unvermeidlich ist. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Initialisiert ein neues OriginalFontSpecification-Objekt.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Liest den Namen der Originalschrift.

**Returns:**
String Wert

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Liest einen Wert, der angibt, ob die Schrift eingebettet ist.

**Returns:**
boolescher Wert

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Liest einen Wert, der anzeigt, dass die Substitution unvermeidlich ist. </p>

**Returns:**
boolean value <hr> <p> Gibt true zurück, wenn die Substitution angefordert wurde, weil die Originalschrift fehlt oder die Originalschrift im Kontext einer Aufgabe nicht verwendet werden kann. Falls der Benutzer das Flag ignoriert und die Schrift nicht ersetzt – das Standardverfahren zur Schrift‑substitution wird durchgeführt. Es bietet jedoch die Möglichkeit, das übliche Substitutionsverfahren zu ändern und eine bessere Schrift im System festzulegen. Gibt false zurück, wenn die Originalschrift vorhanden und gültig ist, aber der Benutzer sie ersetzen darf. </p>
