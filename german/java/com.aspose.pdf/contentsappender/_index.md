---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Führt Inhaltsmodifikationen ausschließlich im APPEND-Modus durch. Dieser Modus ermöglicht es, unnötiges und schweres Parsen des Inhalts zu vermeiden, bevor Änderungen am Inhalt vorgenommen werden. Er fügt nur neue Inhalte hinzu."
type: docs
weight: 800
url: /de/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Führt Inhaltsänderungen ausschließlich im APPEND‑Modus durch. Dieser Modus ermöglicht es, unnötiges und umfangreiches Parsen des Inhalts zu vermeiden, bevor Änderungen vorgenommen werden. Er fügt neue Operatoren nur am Ende oder am Anfang des Inhalts hinzu.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Initialisiert eine neue Instanz des Inhalts-Appendierers mit angehängter Seite |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Initialisiert eine neue Instanz des Inhalts-Appendierers mit Form XObject. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Fügt Operatoren am Ende des Inhalts hinzu |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Fügt einen Operator am Ende des Inhalts hinzu |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Fügt Operatoren am Ende des Inhalts hinzu |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Fügt Operatoren am Anfang des Inhalts hinzu |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Fügt einen Operator am Anfang des Inhalts hinzu |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Fügt Operatoren am Anfang des Inhalts hinzu |
| [getBeginCode](#getBeginCode--) | Zeichenkette, die Operatoren enthält, die am Anfang der Seite eingefügt werden. |
| [getBeginOperators](#getBeginOperators--) | <p> Gibt Anfangsoperatoren zurück </p> |
| [getEndCode](#getEndCode--) | Zeichenkette, die Operatoren enthält, die am Ende der Seite angehängt werden. |
| [getEndOperators](#getEndOperators--) | <p> Gibt Endoperatoren zurück </p> |
| [resumeUpdate](#resumeUpdate--) | setzt die Dokumentaktualisierung fort |
| [setBeginCode](#setBeginCode-java.lang.String-) | Zeichenkette, die Operatoren enthält, die am Anfang der Seite eingefügt werden. |
| [setEndCode](#setEndCode-java.lang.String-) | Zeichenkette, die Operatoren enthält, die am Anfang der Seite eingefügt werden. |
| [suppressUpdate](#suppressUpdate--) | Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhalt wird erst aktualisiert, wenn ResumeUpdate aufgerufen wird. |
| [updateData](#updateData--) | Dies ist die neue Version von UpdateData, die das Dekodieren des bestehenden Inhalts vermeidet. |
| [updateDataOld](#updateDataOld--) | Muss aufgerufen werden, um die Änderungen anzuwenden |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Initialisiert eine neue Instanz des Inhalts-Appendierers mit angehängter Seite

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Initialisiert eine neue Instanz des Inhalts-Appendierers mit Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Fügt Operatoren am Ende des Inhalts hinzu

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Fügt einen Operator am Ende des Inhalts hinzu

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Fügt Operatoren am Ende des Inhalts hinzu

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Fügt Operatoren am Anfang des Inhalts hinzu

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Fügt einen Operator am Anfang des Inhalts hinzu

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Fügt Operatoren am Anfang des Inhalts hinzu

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

Zeichenkette, die Operatoren enthält, die am Anfang der Seite eingefügt werden.

**Returns:**
String-Objekt

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> Gibt Anfangsoperatoren zurück </p>

**Returns:**
{@code List<Operator>} Objekt

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Zeichenkette, die Operatoren enthält, die am Ende der Seite angehängt werden.

**Returns:**
String-Objekt

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> Gibt Endoperatoren zurück </p>

**Returns:**
{@code List<Operator>} Objekt

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

setzt die Dokumentaktualisierung fort

### setBeginCode {#setBeginCode-java.lang.String-}
Zeichenkette, die Operatoren enthält, die am Anfang der Seite eingefügt werden.

### setEndCode {#setEndCode-java.lang.String-}
Zeichenkette, die Operatoren enthält, die am Anfang der Seite eingefügt werden.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhalt wird erst aktualisiert, wenn ResumeUpdate aufgerufen wird.

### updateData {#updateData--}
```
public void updateData()
```

Dies ist die neue Version von UpdateData, die das Dekodieren des bestehenden Inhalts vermeidet.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Muss aufgerufen werden, um die Änderungen anzuwenden
