---
title: "Do"
linktitle: "Do"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar Do-operatorn (Invoke XObject)."
type: docs
weight: 180
url: /sv/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Klassen representerar Do-operatorn (Invoke XObject).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Do](#Do--) | Skapar en ny Do-operator. Används för att hämta alla Do-operatorer, d.v.s. utan att kontrollera deras argumentnamn. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Skapar en ny Do-operator. Används för att hämta alla Do-operatorer, d.v.s. utan att kontrollera deras argumentnamn. |
| [Do](#Do-java.lang.String-) | Skapar en ny Do-operator. Används för att hämta alla Do-operatorer, d.v.s. utan att kontrollera deras argumentnamn. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getCommandName](#getCommandName--) | Hämtar kommandonamn |
| [getName](#getName--) | Hämta namn på XObject-argumentet för operatorn. |
| [setName](#setName-java.lang.String-) | Ställ in namn på XObject-argumentet för operatorn. |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### Do {#Do--}
```
public Do()
```

Skapar en ny Do-operator. Används för att hämta alla Do-operatorer, d.v.s. utan att kontrollera deras argumentnamn.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Skapar en ny Do-operator. Används för att hämta alla Do-operatorer, d.v.s. utan att kontrollera deras argumentnamn.

### Do {#Do-java.lang.String-}
Skapar en ny Do-operator. Används för att hämta alla Do-operatorer, d.v.s. utan att kontrollera deras argumentnamn.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Hämtar kommandonamn

**Returns:**
String värde

### getName {#getName--}
```
public String getName()
```

Hämta namn på XObject-argumentet för operatorn.

**Returns:**
String värde

### setName {#setName-java.lang.String-}
Ställ in namn på XObject-argumentet för operatorn.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.
