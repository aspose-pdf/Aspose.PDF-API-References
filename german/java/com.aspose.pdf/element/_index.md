---
title: "Element"
linktitle: "Element"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die das Basiselement der logischen Struktur darstellt."
type: docs
weight: 1180
url: /de/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Klasse, die das Basiselement der logischen Struktur darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getActualText](#getActualText--) | (Optional; PDF 1.4) Text, der eine exakte Ersetzung des Strukturelements und seiner Kinder darstellt. Dieser Ersetzungstext (der so klein wie möglich gehalten werden sollte) ist nützlich beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke. |
| [getAlt](#getAlt--) | (Optional) Eine alternative Beschreibung des Strukturelements und seiner Kinder in menschenlesbarer Form, die beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke nützlich ist. |
| [getChildren](#getChildren--) | Gibt die Sammlung der Kind-Elemente zurück. |
| [getE](#getE--) | (Optional; PDF 1.5) Die ausgeschriebene Form einer Abkürzung. |
| [getLang](#getLang--) | (Optional; PDF 1.4) Eine Sprache, die die natürliche Sprache für allen Text im Strukturelement angibt, außer dort, wo sie durch Sprachspezifikationen für verschachtelte Strukturelemente oder markierten Inhalt überschrieben wird. |
| [remove](#remove--) | Element entfernen. |
| [setActualText](#setActualText-java.lang.String-) | (Optional; PDF 1.4) Text, der eine exakte Ersetzung des Strukturelements und seiner Kinder darstellt. Dieser Ersetzungstext (der so klein wie möglich gehalten werden sollte) ist nützlich beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke. |
| [setAlt](#setAlt-java.lang.String-) | (Optional) Eine alternative Beschreibung des Strukturelements und seiner Kinder in menschenlesbarer Form, die beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke nützlich ist. |
| [setE](#setE-java.lang.String-) | (Optional; PDF 1.5) Die ausgeschriebene Form einer Abkürzung. |
| [setLang](#setLang-java.lang.String-) | (Optional; PDF 1.4) Eine Sprache, die die natürliche Sprache für allen Text im Strukturelement angibt, außer dort, wo sie durch Sprachspezifikationen für verschachtelte Strukturelemente oder markierten Inhalt überschrieben wird. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Optional; PDF 1.4) Text, der eine exakte Ersetzung des Strukturelements und seiner Kinder darstellt. Dieser Ersetzungstext (der so klein wie möglich gehalten werden sollte) ist nützlich beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke.

**Returns:**
String-Objekt

### getAlt {#getAlt--}
```
public String getAlt()
```

(Optional) Eine alternative Beschreibung des Strukturelements und seiner Kinder in menschenlesbarer Form, die beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke nützlich ist.

**Returns:**
String-Objekt

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Gibt die Sammlung der Kind-Elemente zurück.

**Returns:**
ElementCollection-Instanz

### getE {#getE--}
```
public String getE()
```

(Optional; PDF 1.5) Die ausgeschriebene Form einer Abkürzung.

**Returns:**
String-Objekt

### getLang {#getLang--}
```
public String getLang()
```

(Optional; PDF 1.4) Eine Sprache, die die natürliche Sprache für allen Text im Strukturelement angibt, außer dort, wo sie durch Sprachspezifikationen für verschachtelte Strukturelemente oder markierten Inhalt überschrieben wird.

**Returns:**
String-Objekt

### remove {#remove--}
```
public final void remove()
```

Element entfernen.

### setActualText {#setActualText-java.lang.String-}
(Optional; PDF 1.4) Text, der eine exakte Ersetzung des Strukturelements und seiner Kinder darstellt. Dieser Ersetzungstext (der so klein wie möglich gehalten werden sollte) ist nützlich beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke.

### setAlt {#setAlt-java.lang.String-}
(Optional) Eine alternative Beschreibung des Strukturelements und seiner Kinder in menschenlesbarer Form, die beim Extrahieren des Dokumentinhalts zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder für andere Zwecke nützlich ist.

### setE {#setE-java.lang.String-}
(Optional; PDF 1.5) Die ausgeschriebene Form einer Abkürzung.

### setLang {#setLang-java.lang.String-}
(Optional; PDF 1.4) Eine Sprache, die die natürliche Sprache für allen Text im Strukturelement angibt, außer dort, wo sie durch Sprachspezifikationen für verschachtelte Strukturelemente oder markierten Inhalt überschrieben wird.
