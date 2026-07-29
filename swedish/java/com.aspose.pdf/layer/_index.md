---
title: "Layer"
linktitle: "Layer"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett lager inom en PDF‑sida."
type: docs
weight: 2640
url: /sv/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Representerar ett lager inom en PDF‑sida.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen {@code Layer}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [delete](#delete--) | Tar bort det aktuella lagret från PDF-dokumentet. |
| [flatten](#flatten-boolean-) | Plattar till det angivna lagret. |
| [getContents](#getContents--) | <p> Hämtar lagerinnehållet. </p> |
| [getDefaultState](#getDefaultState--) | Hämtar standardtillståndet för PDF-lagret. |
| [getId](#getId--) | Hämtar lagrets ID. |
| [getLocked](#getLocked--) | Hämtar ett värde som indikerar om lagret är låst. |
| [getName](#getName--) | Hämtar lagrets namn. |
| [lock](#lock--) | Låser lagret. |
| [save](#save-java.io.OutputStream-) | Sparar det aktuella lagret till ett PDF-dokument. |
| [save](#save-java.lang.String-) | Sparar det aktuella lagret till ett PDF-dokument. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Ställer in standardtillståndet för PDF-lagret. |
| [unlock](#unlock--) | Låser upp lagret. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Initierar en ny instans av klassen {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

Tar bort det aktuella lagret från PDF-dokumentet.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Plattar till det angivna lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cleanupContentStream |  | Anger om valfria innehållsgruppsmarkörer ska tas bort från innehållsströmmen. Att sätta parametern {@code cleanupContentStream} till false påskyndar plattningsprocessen. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Hämtar lagerinnehållet. </p>

**Returns:**
{@code List<Operator>} objekt

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Hämtar standardtillståndet för PDF-lagret.

**Returns:**
standardtillståndet för PDF-lagret.

### getId {#getId--}
```
public String getId()
```

Hämtar lagrets ID.

**Returns:**
String värde

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Hämtar ett värde som indikerar om lagret är låst.

**Returns:**
booleskt värde

### getName {#getName--}
```
public String getName()
```

Hämtar lagrets namn.

**Returns:**
String värde

### lock {#lock--}
```
public final void lock()
```

Låser lagret.

### save {#save-java.io.OutputStream-}
Sparar det aktuella lagret till ett PDF-dokument.

### save {#save-java.lang.String-}
Sparar det aktuella lagret till ett PDF-dokument.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Ställer in standardtillståndet för PDF-lagret.

### unlock {#unlock--}
```
public final void unlock()
```

Låser upp lagret.
