---
title: PdfEvent
second_title: Aspose.PDF for Java API Reference
description: Class representing events
type: docs
weight: 225
url: /java/com.aspose.pdf/pdfevent/
---
**Inheritance:**
java.lang.Object
```
public abstract class PdfEvent<T>
```

Class representing events
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfEvent()](#PdfEvent--) |  |
## Methods

| Method | Description |
| --- | --- |
| [assign(T delegate)](#assign-T-) | Add only the current delegate, clearing other. |
| [add(T delegate)](#add-T-) | Add one more delegate. |
| [remove(T delegate)](#remove-T-) | Delete delegate from list |
| [clear()](#clear--) | Clear delegate list |
| [isEmpty()](#isEmpty--) | Returns true if the list of handlers is empty |
### PdfEvent() {#PdfEvent--}
```
public PdfEvent()
```


### assign(T delegate) {#assign-T-}
```
public final void assign(T delegate)
```


Add only the current delegate, clearing other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate | T | Handlers object |

### add(T delegate) {#add-T-}
```
public final void add(T delegate)
```


Add one more delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate | T | Handlers object |

### remove(T delegate) {#remove-T-}
```
public final void remove(T delegate)
```


Delete delegate from list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate | T | Handlers object |

### clear() {#clear--}
```
public final void clear()
```


Clear delegate list

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Returns true if the list of handlers is empty

**Returns:**
boolean - boolean value
