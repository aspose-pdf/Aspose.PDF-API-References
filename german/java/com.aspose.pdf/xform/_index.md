---
title: "XForm"
linktitle: "XForm"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt XForm dar"
type: docs
weight: 5590
url: /de/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Klasse stellt XForm dar

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close](#close--) | Gibt Speicher frei |
| [containsOwnResources](#containsOwnResources--) | Gibt True zurück, wenn eigene Ressourcen enthalten sind. |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Erstellt ein neues XForm im Dokument. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Erstellt ein XForm, das den Inhalt der Seite dupliziert. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Gibt Speicher frei |
| [freeMemory](#freeMemory--) | Löscht zwischengespeicherte Daten |
| [getBBox](#getBBox--) | Liefert die Begrenzungsbox des Formulars. |
| [getContents](#getContents--) | Liefert die Operatoren des Formulars. |
| [getEngineObj](#getEngineObj--) | Nur intern |
| [getIT](#getIT--) | Liefert Form IT. Form IT ist ein Name, der die Absicht des XObject beschreibt. |
| [getMatrix](#getMatrix--) | Ermittelt die Matrix des Formulars. |
| [getName](#getName--) | Ermittelt den Formularnamen. Der Formularname ist der Name, der verwendet wird, um das Formular im XObejct ductionary in den Seitenressourcen zu referenzieren. |
| [getOpi](#getOpi--) | Ermittelt die Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Ermittelt das rectangel des Formulars. |
| [getResources](#getResources--) | Gibt die Ressourcen des Form X-Object zurück. Wenn das Form keine Ressourcen hat und allowCreate wahr ist, werden die Ressourcen automatisch für das Formular erstellt. |
| [getResources](#getResources-boolean-) | Gibt die Ressourcen des Form X-Object zurück. |
| [getResourcesField](#getResourcesField--) | Ermittelt die Form XObject Ressourcen. |
| [getSubtype](#getSubtype--) | Ermittelt den Subtyp des Formulars. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Setzt die Begrenzungsbox des Formulars. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Setzt die Matrix des Formulars. |
| [setName](#setName-java.lang.String-) | Setzt den Formularnamen. Der Formularname ist der Name, der verwendet wird, um das Formular im XObejct dictionary in den Seitenressourcen zu referenzieren. |

### close {#close--}
```
public final void close()
```

Gibt Speicher frei

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Gibt True zurück, wenn eigene Ressourcen enthalten sind.

**Returns:**
boolescher Wert

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Erstellt ein neues XForm im Dokument.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Erstellt ein XForm, das den Inhalt der Seite dupliziert.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Gibt Speicher frei

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Löscht zwischengespeicherte Daten

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Liefert die Begrenzungsbox des Formulars.

**Returns:**
Rechteck

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Liefert die Operatoren des Formulars.

**Returns:**
OperatorCollection-Objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Nur intern

**Returns:**
IPdfObject-Objekt

### getIT {#getIT--}
```
public final String getIT()
```

Liefert Form IT. Form IT ist ein Name, der die Absicht des XObject beschreibt.

**Returns:**
String Wert

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Ermittelt die Matrix des Formulars.

**Returns:**
Matrix

### getName {#getName--}
```
public String getName()
```

Ermittelt den Formularnamen. Der Formularname ist der Name, der verwendet wird, um das Formular im XObejct ductionary in den Seitenressourcen zu referenzieren.

**Returns:**
String

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Ermittelt die Open Prepress Interface (OPI).

**Returns:**
Opi-Instanz

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das rectangel des Formulars.

**Returns:**
Rechteck

### getResources {#getResources--}
```
public Resources getResources()
```

Gibt die Ressourcen des Form X-Object zurück. Wenn das Form keine Ressourcen hat und allowCreate wahr ist, werden die Ressourcen automatisch für das Formular erstellt.

**Returns:**
Resources-Instanz

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Gibt die Ressourcen des Form X-Object zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowCreate |  | Wenn das Form keine Ressourcen hat und allowCreate wahr ist, werden die Ressourcen automatisch für das Formular erstellt. |

**Returns:**
Resources-Instanz

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Ermittelt die Form XObject Ressourcen.

**Returns:**
Resources-Instanz. Wenn das Form keine Ressourcen hat, werden die Ressourcen automatisch für das Formular erstellt.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Ermittelt den Subtyp des Formulars.

**Returns:**
String Wert

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Setzt die Begrenzungsbox des Formulars.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Setzt die Matrix des Formulars.

### setName {#setName-java.lang.String-}
Setzt den Formularnamen. Der Formularname ist der Name, der verwendet wird, um das Formular im XObejct dictionary in den Seitenressourcen zu referenzieren.
