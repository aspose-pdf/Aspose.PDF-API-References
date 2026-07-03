---
title: GraphicState
linktitle: GraphicState
second_title: Aspose.PDF for Java API Reference
description: Represents graphic state of the current {@link GraphicElement}.
type: docs
weight: 40
url: /java/com.aspose.pdf.vector/graphicstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicState

```
public class GraphicState extends Object
```

Represents graphic state of the current {@link GraphicElement}.

## Methods

| Method | Description |
| --- | --- |
| [getClipsAndMatrices](#getClipsAndMatrices--) | Gets the operators representing clips and concatenation matrices. |
| [getColorsAndStyles](#getColorsAndStyles--) | Gets the operators representing colorspaces, colors and line styles. |
| [getMatrix](#getMatrix--) | Gets the current transformation matrix. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Gets the current transformation matrix. |

### getClipsAndMatrices {#getClipsAndMatrices--}
```
public final List < Operator > getClipsAndMatrices()
```

Gets the operators representing clips and concatenation matrices.

**Returns:**
List of Operator instances

### getColorsAndStyles {#getColorsAndStyles--}
```
public final com.aspose.ms.System.Collections.Generic.SortedDictionary< Byte , Operator > getColorsAndStyles()
```

Gets the operators representing colorspaces, colors and line styles.

**Returns:**
SortedDictionary instance

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Gets the current transformation matrix.

**Returns:**
Matrix instance

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Gets the current transformation matrix.
