---
title: FontEmbeddingOptions
second_title: Aspose.PDF for Java API Reference
description: PDF/A standard requires that all fonts must be embedded into document.
type: docs
weight: 113
url: /java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public class FontEmbeddingOptions
```

PDF/A standard requires, that all fonts must be embedded into document. This class includes flags for cases when it's not possible to embed some font cause this font is absent on destination PC.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontEmbeddingOptions()](#FontEmbeddingOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getUseDefaultSubstitution()](#getUseDefaultSubstitution--) | Declares to substitute non-embedded font using default font substitution strategy. |
| [setUseDefaultSubstitution(boolean value)](#setUseDefaultSubstitution-boolean-) | Declares to substitute non-embedded font using default font substitution strategy. |
### FontEmbeddingOptions() {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```


Constructor

### getUseDefaultSubstitution() {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```


Declares to substitute non-embedded font using default font substitution strategy. By default false;

**Returns:**
boolean - boolean value
### setUseDefaultSubstitution(boolean value) {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```


Declares to substitute non-embedded font using default font substitution strategy. By default false;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

