---
title: CollectionField
linktitle: CollectionField
second_title: Aspose.PDF for Java API Reference
description: Represents a document collection schema field class.
type: docs
weight: 620
url: /java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Represents a document collection schema field class.

## Methods

| Method | Description |
| --- | --- |
| [getE](#getE--) | Gets a flag indicating whether the interactive PDF processor should provide support for editing the field value. Default value: false |
| [getFiledType](#getFiledType--) | Gets the type of a field value in a schema collection. This field describes the value type corresponding to {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Gets the textual field name that shall be presented to the user by the interactive PDF processor |
| [getO](#getO--) | Gets the relative order of the field name in the user interface. Fields shall be sorted by the interactive PDF processor in ascending order. |
| [getSubtype](#getSubtype--) | Gets the subtype of a field value in a schema collection. The subtype of collection field or file-related field that this dictionary describes. This entry identifies the type of data that shall be stored in the field. |
| [getV](#getV--) | Gets the initial visibility of the field in the user interface. Default value: true. |

### getE {#getE--}
```
public final boolean getE()
```

Gets a flag indicating whether the interactive PDF processor should provide support for editing the field value. Default value: false

**Returns:**
boolean value

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Gets the type of a field value in a schema collection. This field describes the value type corresponding to {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
FieldValueType element

### getN {#getN--}
```
public final String getN()
```

Gets the textual field name that shall be presented to the user by the interactive PDF processor

**Returns:**
String value

### getO {#getO--}
```
public final Integer [] getO()
```

Gets the relative order of the field name in the user interface. Fields shall be sorted by the interactive PDF processor in ascending order.

**Returns:**
array of Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Gets the subtype of a field value in a schema collection. The subtype of collection field or file-related field that this dictionary describes. This entry identifies the type of data that shall be stored in the field.

**Returns:**
CollectionFieldSubtype element

### getV {#getV--}
```
public final boolean getV()
```

Gets the initial visibility of the field in the user interface. Default value: true.

**Returns:**
boolean value
