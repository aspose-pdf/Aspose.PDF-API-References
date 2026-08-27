---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Aspose.PDF för Java API-referens"
description: "Inkapslar osignerade innehållselement som extraherats från ett PDF‑dokument. Denna klass ger åtkomst till sidor, formulärfält, XForms och annotationer som är en del av det osignerade."
type: docs
weight: 50
url: /sv/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Inkapslar osignerade innehållselement som extraherats från ett PDF-dokument. Denna klass ger åtkomst till sidor, formulärfält, XForms och annotationer som är en del av det osignerade innehållet i dokumentet.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Hämtar en ordbok med modifierade annotationer som kan ha ändrats eller lagts till. |
| [getForms](#getForms--) | Hämtar formulärfält som har ändrats eller lagts till inkrementellt. |
| [getPages](#getPages--) | Hämtar en lista med sidor vars innehåll är osignerat eller har ändrats inkrementellt. Sidan anses vara modifierad och XForms kontrolleras inte och visas inte i XForms‑listan. |
| [getXForms](#getXForms--) | Hämtar en ordbok med modifierade XForm‑objekt som kan ha förändrats, även om själva sidan inte har ändrats (inte i sidlistan). |
| [setXForms](#setXForms-java.util.HashMap-) | En ordbok med modifierade XForm‑objekt som kan ha förändrats, även om själva sidan inte har ändrats (inte i sidlistan). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Hämtar en ordbok med modifierade annotationer som kan ha ändrats eller lagts till.

**Returns:**
en ordbok med modifierade annotationer som kan ha ändrats eller lagts till.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Hämtar formulärfält som har ändrats eller lagts till inkrementellt.

**Returns:**
formulärfält som har ändrats eller lagts till inkrementellt.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Hämtar en lista med sidor vars innehåll är osignerat eller har ändrats inkrementellt. Sidan anses vara modifierad och XForms kontrolleras inte och visas inte i XForms‑listan.

**Returns:**
en lista med sidor vars innehåll är osignerat eller har ändrats inkrementellt.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Hämtar en ordbok med modifierade XForm‑objekt som kan ha förändrats, även om själva sidan inte har ändrats (inte i sidlistan).

**Returns:**
en ordbok med modifierade XForm‑objekt som kan ha förändrats, även om själva sidan inte har ändrats (inte i sidlistan).

### setXForms {#setXForms-java.util.HashMap-}
En ordbok med modifierade XForm‑objekt som kan ha förändrats, även om själva sidan inte har ändrats (inte i sidlistan).
