---
title: FieldSerializationResult
second_title: Aspose.PDF for Java API Reference
description: Represents the result of a form field serialization process.
type: docs
weight: 1390
url: /java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Represents the result of a form field serialization process.

## Constructors

| Constructor | Description |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Initializes a new instance of the {@link FieldSerializationResult} class. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Initializes a new instance of the {@link FieldSerializationResult} class. |

## Methods

| Method | Description |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Gets the error messages associated with the serialization process. Value: A set of error messages. |
| [getFieldFullName](#getFieldFullName--) | Gets the full name of the field. Value: The full name of the field. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Gets the status of the form field serialization. Value: The serialization status of the form field. |
| [getWarningMessages](#getWarningMessages--) | Gets the warning messages associated with the serialization process. Value: A set of warning messages. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Updates the serialization status and adds a message to the appropriate set. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Initializes a new instance of the {@link FieldSerializationResult} class.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Initializes a new instance of the {@link FieldSerializationResult} class.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Gets the error messages associated with the serialization process. Value: A set of error messages.

**Returns:**
HashSet of String instance

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Gets the full name of the field. Value: The full name of the field.

**Returns:**
String value

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Gets the status of the form field serialization. Value: The serialization status of the form field.

**Returns:**
FieldSerializationStatus element

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Gets the warning messages associated with the serialization process. Value: A set of warning messages.

**Returns:**
HashSet of String instance

### updateStatus {#updateStatus-int-java.lang.String-}
Updates the serialization status and adds a message to the appropriate set.
