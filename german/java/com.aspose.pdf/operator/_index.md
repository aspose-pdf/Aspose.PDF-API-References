---
title: "Operator"
linktitle: "Operator"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Abstrakte Klasse, die einen Operator darstellt."
type: docs
weight: 3180
url: /de/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Abstrakte Klasse, die einen Operator darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Nur für den internen Gebrauch! |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert den Besucher IOperatorSelector, der die Verarbeitung von Operatoren bereitstellt. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Erstellt einen Operator anhand des Namens einer com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-Instanz. |
| [equals](#equals-com.aspose.pdf.Operator-) | Vergleicht diese Instanz mit dem angegebenen Objekt. |
| [getCommand](#getCommand--) | Liest Befehl |
| [getCommandName](#getCommandName--) | Liest Operatornamen. |
| [getIndex](#getIndex--) | Lese Operatorindex in der Liste der Seitenoperatoren. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Bestimmt, ob der Operator ein Operator ist, der für die Textausgabe (Tj, TJ usw.) verantwortlich ist. |
| [setIndex](#setIndex-int-) | Setzt Operatorindex in der Liste der Seitenoperatoren. |
| [toString](#toString--) | Übersetzt Befehl und Parameter in eine Zeichenkettenrepräsentation. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Vergleicht diese Instanz mit dem angegebenen Objekt. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Nur für den internen Gebrauch!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert den Besucher IOperatorSelector, der die Verarbeitung von Operatoren bereitstellt.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Erstellt einen Operator anhand des Namens einer com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-Instanz.

### equals {#equals-com.aspose.pdf.Operator-}
Vergleicht diese Instanz mit dem angegebenen Objekt.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Liest Befehl

**Returns:**
ICommand-Objekt

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Liest Operatornamen.

**Returns:**
String Wert

### getIndex {#getIndex--}
```
public int getIndex()
```

Lese Operatorindex in der Liste der Seitenoperatoren.

**Returns:**
int-Wert

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Bestimmt, ob der Operator ein Operator ist, der für die Textausgabe (Tj, TJ usw.) verantwortlich ist.

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Setzt Operatorindex in der Liste der Seitenoperatoren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### toString {#toString--}
```
public String toString()
```

Übersetzt Befehl und Parameter in eine Zeichenkettenrepräsentation.

**Returns:**
Operator-Text

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Vergleicht diese Instanz mit dem angegebenen Objekt.
