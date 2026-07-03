---
title: Copier
second_title: Aspose.PDF for Java API Reference
description: Class for coping object
type: docs
weight: 850
url: /java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

Class for coping object

## Constructors

| Constructor | Description |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Creates an instance of Copier class. |

## Methods

| Method | Description |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Duplicates IPdfPrimitive |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Creates copy of object with all dependent object. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | get Allow Reuse Page Content |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | get Ignore Corrupted Objects |
| [getRestrictedKeys](#getRestrictedKeys--) | get Restricted Keys |
| [getReuseStreams](#getReuseStreams--) | get Reuse Streams |
| [getUseStubs](#getUseStubs--) | Indicates whether stubs should be used during the duplication process. If the option is turned on, then the streams will be copied, otherwise a link to the source stream will be used. Which will not allow you to close the copied document, but saves on the process of copying and memory. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | set Allow Reuse Page Content |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Set Ignore Corrupted Objects |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | set Restricted Keys |
| [setReuseStreams](#setReuseStreams-boolean-) | set Reuse Streams |
| [setUseStubs](#setUseStubs-boolean-) | Indicates whether stubs should be used during the duplication process. If the option is turned on, then the streams will be copied, otherwise a link to the source stream will be used. Which will not allow you to close the copied document, but saves on the process of copying and memory. |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
Creates an instance of Copier class.

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
Duplicates IPdfPrimitive

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
Creates copy of object with all dependent object.

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

get Allow Reuse Page Content

**Returns:**
boolean value

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

get Ignore Corrupted Objects

**Returns:**
boolean value

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

get Restricted Keys

**Returns:**
String[] array

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

get Reuse Streams

**Returns:**
boolean value

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

Indicates whether stubs should be used during the duplication process. If the option is turned on, then the streams will be copied, otherwise a link to the source stream will be used. Which will not allow you to close the copied document, but saves on the process of copying and memory.

**Returns:**
boolean value

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

set Allow Reuse Page Content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Set Ignore Corrupted Objects

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
set Restricted Keys

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

set Reuse Streams

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

Indicates whether stubs should be used during the duplication process. If the option is turned on, then the streams will be copied, otherwise a link to the source stream will be used. Which will not allow you to close the copied document, but saves on the process of copying and memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
