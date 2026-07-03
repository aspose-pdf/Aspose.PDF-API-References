---
title: Id
second_title: Aspose.PDF for Java API Reference
description: <p> Represents file identifier structure. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified =.
type: docs
weight: 2220
url: /java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Represents file identifier structure. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Methods

| Method | Description |
| --- | --- |
| [getModified](#getModified--) | Changing identifier based on the document's contents at the time it was last updated. |
| [getOriginal](#getOriginal--) | Permanent identifier based on the contents of the document at the time it was originally created. |

### getModified {#getModified--}
```
public String getModified()
```

Changing identifier based on the document's contents at the time it was last updated.

**Returns:**
String value

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Permanent identifier based on the contents of the document at the time it was originally created.

**Returns:**
String value
