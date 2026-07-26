---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Kapselt nicht signierte Inhaltselemente, die aus einem PDF-Dokument extrahiert wurden. Diese Klasse bietet Zugriff auf Seiten, Formularfelder, XForms und Anmerkungen, die Teil des Nichtsignierten sind."
type: docs
weight: 50
url: /de/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Kapselt unsignierte Inhaltselemente, die aus einem PDF-Dokument extrahiert wurden. Diese Klasse bietet Zugriff auf Seiten, Formularfelder, XForms und Anmerkungen, die Teil des unsignierten Inhalts im Dokument sind.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Liefert ein Wörterbuch modifizierter Anmerkungen, die geändert oder hinzugefügt worden sein könnten. |
| [getForms](#getForms--) | Liefert Formularfelder, die inkrementell geändert oder hinzugefügt wurden. |
| [getPages](#getPages--) | Liefert eine Liste von Seiten, deren Inhalt nicht signiert ist oder inkrementell geändert wurde. Die Seite gilt als modifiziert und XForms werden nicht geprüft und erscheinen nicht in der XForms-Liste. |
| [getXForms](#getXForms--) | Liefert ein Wörterbuch modifizierter XForm-Objekte, die geändert worden sein könnten, obwohl die Seite selbst nicht geändert wurde (nicht in der Seitenliste). |
| [setXForms](#setXForms-java.util.HashMap-) | Ein Wörterbuch modifizierter XForm-Objekte, die geändert worden sein könnten, obwohl die Seite selbst nicht geändert wurde (nicht in der Seitenliste). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Liefert ein Wörterbuch modifizierter Anmerkungen, die geändert oder hinzugefügt worden sein könnten.

**Returns:**
ein Wörterbuch modifizierter Anmerkungen, die geändert oder hinzugefügt worden sein könnten.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Liefert Formularfelder, die inkrementell geändert oder hinzugefügt wurden.

**Returns:**
Formularfelder, die inkrementell geändert oder hinzugefügt wurden.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Liefert eine Liste von Seiten, deren Inhalt nicht signiert ist oder inkrementell geändert wurde. Die Seite gilt als modifiziert und XForms werden nicht geprüft und erscheinen nicht in der XForms-Liste.

**Returns:**
eine Liste von Seiten, deren Inhalt nicht signiert ist oder inkrementell geändert wurde.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Liefert ein Wörterbuch modifizierter XForm-Objekte, die geändert worden sein könnten, obwohl die Seite selbst nicht geändert wurde (nicht in der Seitenliste).

**Returns:**
ein Wörterbuch modifizierter XForm-Objekte, die geändert worden sein könnten, obwohl die Seite selbst nicht geändert wurde (nicht in der Seitenliste).

### setXForms {#setXForms-java.util.HashMap-}
Ein Wörterbuch modifizierter XForm-Objekte, die geändert worden sein könnten, obwohl die Seite selbst nicht geändert wurde (nicht in der Seitenliste).
