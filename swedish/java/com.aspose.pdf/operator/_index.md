---
title: "Operator"
linktitle: "Operator"
second_title: "Aspose.PDF för Java API-referens"
description: "Abstrakt klass som representerar operatör."
type: docs
weight: 3180
url: /sv/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Abstrakt klass som representerar operatör.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Endast för internt bruk! |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökaren IOperatorSelector som tillhandahåller bearbetning av operatorer. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Skapar operator efter namn på instansen av com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | Jämför den här instansen med det angivna objektet. |
| [getCommand](#getCommand--) | Hämtar kommando |
| [getCommandName](#getCommandName--) | Hämtar operatornamn. |
| [getIndex](#getIndex--) | Hämta operatorns index i sidans operatorlista. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Bestämmer om operatorn är en operator som ansvarar för textutmatning (Tj, TJ, etc) |
| [setIndex](#setIndex-int-) | Ställ in operatorns index i sidans operatorlista. |
| [toString](#toString--) | Översätter kommando och parametrar till en strängrepresentation. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Jämför den här instansen med det angivna objektet. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Endast för internt bruk!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökaren IOperatorSelector som tillhandahåller bearbetning av operatorer.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Skapar operator efter namn på instansen av com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
Jämför den här instansen med det angivna objektet.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Hämtar kommando

**Returns:**
ICommand-objekt

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Hämtar operatornamn.

**Returns:**
String värde

### getIndex {#getIndex--}
```
public int getIndex()
```

Hämta operatorns index i sidans operatorlista.

**Returns:**
int‑värde

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Bestämmer om operatorn är en operator som ansvarar för textutmatning (Tj, TJ, etc)

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Ställ in operatorns index i sidans operatorlista.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### toString {#toString--}
```
public String toString()
```

Översätter kommando och parametrar till en strängrepresentation.

**Returns:**
Operatortext

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Jämför den här instansen med det angivna objektet.
