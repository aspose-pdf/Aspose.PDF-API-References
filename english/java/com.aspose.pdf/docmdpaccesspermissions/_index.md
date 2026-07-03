---
title: DocMDPAccessPermissions
second_title: Aspose.PDF for Java API Reference
description: The access permissions granted for this document. Valid values are: 1 - No changes to the document are permitted; any change to the document invalidates the signature. 2 -.
type: docs
weight: 1010
url: /java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

The access permissions granted for this document. Valid values are: 1 - No changes to the document are permitted; any change to the document invalidates the signature. 2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature. 3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature.

## Fields

| Field | Description |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature. |
| [FillingInForms](#FillingInForms) | 2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature. |
| [NoChanges](#NoChanges) | 1 - No changes to the document are permitted; any change to the document invalidates the signature. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - No changes to the document are permitted; any change to the document invalidates the signature.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
