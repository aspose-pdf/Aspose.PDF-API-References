---
title: Layer
second_title: Aspose.PDF for Java API Reference
description: Represents a layer within a PDF page.
type: docs
weight: 2640
url: /java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Represents a layer within a PDF page.

## Constructors

| Constructor | Description |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Initializes a new instance of the {@code Layer} class. |

## Methods

| Method | Description |
| --- | --- |
| [delete](#delete--) | Deletes the current layer from the PDF document. |
| [flatten](#flatten-boolean-) | Flattens the specified layer. |
| [getContents](#getContents--) | <p> Gets the layer content. </p> |
| [getDefaultState](#getDefaultState--) | Gets the default state of the PDF layer. |
| [getId](#getId--) | Gets the layer id. |
| [getLocked](#getLocked--) | Gets a value indicating whether the layer is locked. |
| [getName](#getName--) | Gets the layer name. |
| [lock](#lock--) | Locks the layer. |
| [save](#save-java.io.OutputStream-) | Saves the current layer to a PDF document. |
| [save](#save-java.lang.String-) | Saves the current layer to a PDF document. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Sets the default state of the PDF layer. |
| [unlock](#unlock--) | Unlocks the layer. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Initializes a new instance of the {@code Layer} class.

### delete {#delete--}
```
public final void delete()
```

Deletes the current layer from the PDF document.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Flattens the specified layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cleanupContentStream |  | Specifies whether to remove optional content group markers from the content stream. Setting the {@code cleanupContentStream} parameter to false speeds up the process of flattening. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Gets the layer content. </p>

**Returns:**
{@code List<Operator>} object

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Gets the default state of the PDF layer.

**Returns:**
the default state of the PDF layer.

### getId {#getId--}
```
public String getId()
```

Gets the layer id.

**Returns:**
String value

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Gets a value indicating whether the layer is locked.

**Returns:**
boolean value

### getName {#getName--}
```
public String getName()
```

Gets the layer name.

**Returns:**
String value

### lock {#lock--}
```
public final void lock()
```

Locks the layer.

### save {#save-java.io.OutputStream-}
Saves the current layer to a PDF document.

### save {#save-java.lang.String-}
Saves the current layer to a PDF document.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Sets the default state of the PDF layer.

### unlock {#unlock--}
```
public final void unlock()
```

Unlocks the layer.
