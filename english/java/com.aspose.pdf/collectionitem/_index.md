---
title: CollectionItem
linktitle: CollectionItem
second_title: Aspose.PDF for Java API Reference
description: Represents a collection item class. The collection item contains the data described by the collection schema.
type: docs
weight: 640
url: /java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Represents a collection item class. The collection item contains the data described by the collection schema.

## Methods

| Method | Description |
| --- | --- |
| [getAllNames](#getAllNames--) | Gets a collection of all the names of collection item values. |
| [hasName](#hasName-java.lang.String-) | Checks if the given name exists in the collection item. |
| [isEmpty](#isEmpty--) | Gets a value indicating whether the collection item is empty. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tries to get the value of type DateTime from the collection item by the specified name. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tries to get the double value for the specified name from the collection item. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tries to get the integer value for a specified name from the collection item. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tries to get the text value with the specified name from the collection item. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Gets a collection of all the names of collection item values.

**Returns:**
list of String

### hasName {#hasName-java.lang.String-}
Checks if the given name exists in the collection item.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Gets a value indicating whether the collection item is empty.

**Returns:**
true if the collection item is empty; otherwise, false. This property returns true if the collection item does not contain any values, including string values, double values, integer values, and date values. If any of these value types are present in the collection item, this property returns false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tries to get the value of type DateTime from the collection item by the specified name.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tries to get the double value for the specified name from the collection item.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tries to get the integer value for a specified name from the collection item.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tries to get the text value with the specified name from the collection item.
