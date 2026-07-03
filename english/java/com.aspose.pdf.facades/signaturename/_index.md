---
title: SignatureName
second_title: Aspose.PDF for Java API Reference
description: Represents a class for a signature name. Represents a more precise signature name. Used instead of string names. Allows you to present signatures with the same string names.
type: docs
weight: 690
url: /java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Represents a class for a signature name. Represents a more precise signature name. Used instead of string names. Allows you to present signatures with the same string names.

## Fields

| Field | Description |
| --- | --- |
| [FullName](#FullName) | Gets the full name of the signature, providing a unique and precise identifier for the signature field. |
| [Name](#Name) | Gets the name of a signature. |

## Methods

| Method | Description |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determines whether this instance and a specified object are equal. |
| [getSignatureDictionary](#getSignatureDictionary--) | Gets the signature dictionary. |
| [hashCode](#hashCode--) | Returns a hash code for this instance based on the FullName property. |
| [hasSignature](#hasSignature--) | Indicates whether the signature is present or not. |
| [toString](#toString--) | Returns a string representation of the {@link SignatureName} instance, primarily using its name. |

### FullName {#FullName}
```
public final String FullName
```

Gets the full name of the signature, providing a unique and precise identifier for the signature field.

### Name {#Name}
```
public final String Name
```

Gets the name of a signature.

### equals {#equals-java.lang.Object-}
Determines whether this instance and a specified object are equal.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Gets the signature dictionary.

**Returns:**
The signature dictionary or null if it not found.

### hashCode {#hashCode--}
```
public int hashCode()
```

Returns a hash code for this instance based on the FullName property.

**Returns:**
An integer representing the hash code of the FullName property.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Indicates whether the signature is present or not.

**Returns:**
boolean value

### toString {#toString--}
```
public String toString()
```

Returns a string representation of the {@link SignatureName} instance, primarily using its name.

**Returns:**
A string representing the name of the signature.
