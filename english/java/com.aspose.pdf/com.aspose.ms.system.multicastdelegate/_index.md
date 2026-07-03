---
title: com.aspose.ms.System.MulticastDelegate>
second_title: Aspose.PDF for Java API Reference
description: Class representing events
type: docs
weight: 740
url: /java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Class representing events

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-T-) | Add one more delegate. |
| [assign](#assign-T-) | Add only the current delegate, clearing other. |
| [clear](#clear--) | Clear delegate list |
| [isEmpty](#isEmpty--) | Returns true if the list of handlers is empty |
| [remove](#remove-T-) | Delete delegate from list |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Add one more delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate |  | Handlers object |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Add only the current delegate, clearing other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate |  | Handlers object |

### clear {#clear--}
```
public final void clear()
```

Clear delegate list

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Returns true if the list of handlers is empty

**Returns:**
boolean value

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Delete delegate from list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate |  | Handlers object |
