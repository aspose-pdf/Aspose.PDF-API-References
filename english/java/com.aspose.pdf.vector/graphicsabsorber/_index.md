---
title: GraphicsAbsorber
linktitle: GraphicsAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via {@code GraphicsAbsorber.Elements}({@link.
type: docs
weight: 30
url: /java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}) collection.

## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Methods

| Method | Description |
| --- | --- |
| [dispose](#dispose--) | Releases all resources used by the {@link GraphicsAbsorber} class. |
| [getElements](#getElements--) | Gets collection of search occurrences that are presented with {@link GraphicElement} objects. |
| [resumeUpdate](#resumeUpdate--) | Resume update forPage#getContents and all @link XForm#getContents Was made for performance increase, see also. |
| [suppressUpdate](#suppressUpdate--) | Suppresses update for Page#getContents and all @link XForm#getContents Was made for performance increase, see also. |
| [visit](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Releases all resources used by the {@link GraphicsAbsorber} class.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Gets collection of search occurrences that are presented with {@link GraphicElement} objects.

**Returns:**
GraphicElementCollection instance

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Resume update forPage#getContents and all @link XForm#getContents Was made for performance increase, see also.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Suppresses update for Page#getContents and all @link XForm#getContents Was made for performance increase, see also.

### visit {#visit-com.aspose.pdf.Page-}
Performs search on the specified page.
