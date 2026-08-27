---
title: "Do"
linktitle: "Do"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Do-Operator (Invoke XObject) darstellt."
type: docs
weight: 180
url: /de/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Klasse, die den Do-Operator (Invoke XObject) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Do](#Do--) | Erzeugt einen neuen Do-Operator. Wird verwendet, um alle Do-Operatoren abzurufen, d. h. ohne ihre Argumentnamen zu prüfen. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Erzeugt einen neuen Do-Operator. Wird verwendet, um alle Do-Operatoren abzurufen, d. h. ohne ihre Argumentnamen zu prüfen. |
| [Do](#Do-java.lang.String-) | Erzeugt einen neuen Do-Operator. Wird verwendet, um alle Do-Operatoren abzurufen, d. h. ohne ihre Argumentnamen zu prüfen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getCommandName](#getCommandName--) | Liefert den Befehlsnamen. |
| [getName](#getName--) | Liefert den Namen des XObject-Arguments des Operators. |
| [setName](#setName-java.lang.String-) | Setzt den Namen des XObject-Arguments des Operators. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### Do {#Do--}
```
public Do()
```

Erzeugt einen neuen Do-Operator. Wird verwendet, um alle Do-Operatoren abzurufen, d. h. ohne ihre Argumentnamen zu prüfen.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Erzeugt einen neuen Do-Operator. Wird verwendet, um alle Do-Operatoren abzurufen, d. h. ohne ihre Argumentnamen zu prüfen.

### Do {#Do-java.lang.String-}
Erzeugt einen neuen Do-Operator. Wird verwendet, um alle Do-Operatoren abzurufen, d. h. ohne ihre Argumentnamen zu prüfen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Liefert den Befehlsnamen.

**Returns:**
String Wert

### getName {#getName--}
```
public String getName()
```

Liefert den Namen des XObject-Arguments des Operators.

**Returns:**
String Wert

### setName {#setName-java.lang.String-}
Setzt den Namen des XObject-Arguments des Operators.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
