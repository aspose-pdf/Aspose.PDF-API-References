---
title: OutputIntent
linktitle: OutputIntent
second_title: Aspose.PDF for Java API Reference
description: Represents an output intent that matches the color characteristics of a PDF document with those of a target output device or production environment in which the document will be.
type: docs
weight: 3290
url: /java/com.aspose.pdf/outputintent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OutputIntent

```
public final class OutputIntent extends Object
```

Represents an output intent that matches the color characteristics of a PDF document with those of a target output device or production environment in which the document will be printed.

## Constructors

| Constructor | Description |
| --- | --- |
| [OutputIntent](#OutputIntent-java.lang.String-) | Initializes a new instance of the {@link OutputIntent} class with the specified output condition identifier. |

## Methods

| Method | Description |
| --- | --- |
| [getInfo](#getInfo--) | Gets a human-readable text that contains additional information or comments about the intended target device or production condition. |
| [getOutputCondition](#getOutputCondition--) | Gets a text that concisely identifies the intended output device or production condition in human-readable form. |
| [getOutputConditionIdentifier](#getOutputConditionIdentifier--) | Gets a text that identifies the intended output device or production condition in human- or machine-readable form. |
| [getRegistryName](#getRegistryName--) | Gets a text that identifies the registry in which the condition designated by {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}) is defined. |
| [getSubtype](#getSubtype--) | Gets the output intent subtype. |
| [setInfo](#setInfo-java.lang.String-) | Sets a human-readable text that contains additional information or comments about the intended target device or production condition. |
| [setOutputCondition](#setOutputCondition-java.lang.String-) | Gets or sets a text that concisely identifies the intended output device or production condition in human-readable form. |
| [setOutputConditionIdentifier](#setOutputConditionIdentifier-java.lang.String-) | Sets a text that identifies the intended output device or production condition in human- or machine-readable form. |
| [setRegistryName](#setRegistryName-java.lang.String-) | Sets a text that identifies the registry in which the condition designated by {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}) is defined. |

### OutputIntent {#OutputIntent-java.lang.String-}
Initializes a new instance of the {@link OutputIntent} class with the specified output condition identifier.

### getInfo {#getInfo--}
```
public final String getInfo()
```

Gets a human-readable text that contains additional information or comments about the intended target device or production condition.

**Returns:**
String value

### getOutputCondition {#getOutputCondition--}
```
public final String getOutputCondition()
```

Gets a text that concisely identifies the intended output device or production condition in human-readable form.

**Returns:**
String value

### getOutputConditionIdentifier {#getOutputConditionIdentifier--}
```
public final String getOutputConditionIdentifier()
```

Gets a text that identifies the intended output device or production condition in human- or machine-readable form.

**Returns:**
String value

### getRegistryName {#getRegistryName--}
```
public final String getRegistryName()
```

Gets a text that identifies the registry in which the condition designated by {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}) is defined.

**Returns:**
String value

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Gets the output intent subtype.

**Returns:**
String value

### setInfo {#setInfo-java.lang.String-}
Sets a human-readable text that contains additional information or comments about the intended target device or production condition.

### setOutputCondition {#setOutputCondition-java.lang.String-}
Gets or sets a text that concisely identifies the intended output device or production condition in human-readable form.

### setOutputConditionIdentifier {#setOutputConditionIdentifier-java.lang.String-}
Sets a text that identifies the intended output device or production condition in human- or machine-readable form.

### setRegistryName {#setRegistryName-java.lang.String-}
Sets a text that identifies the registry in which the condition designated by {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}) is defined.
