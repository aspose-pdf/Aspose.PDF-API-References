---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar cs-operatorn (ställer in färgrymd för icke‑strokande operationer)"
type: docs
weight: 580
url: /sv/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Klass som representerar cs-operatorn (ställer in färgrymd för icke‑strokande operationer)

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Konstruktor för operator-klassen. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Initierar operatorn. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getCommandName](#getCommandName--) | Hämtar kommandonamn. |
| [getName](#getName--) | Hämtar färgrymdens namn. |
| [setName](#setName-java.lang.String-) | Ställer in färgrymdens namn. |
| [toCommand](#toCommand--) | Endast för internt bruk! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Konstruktor för operator-klassen.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Initierar operatorn.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Hämtar kommandonamn.

**Returns:**
String värde

### getName {#getName--}
```
public String getName()
```

Hämtar färgrymdens namn.

**Returns:**
String värde

### setName {#setName-java.lang.String-}
Ställer in färgrymdens namn.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt
