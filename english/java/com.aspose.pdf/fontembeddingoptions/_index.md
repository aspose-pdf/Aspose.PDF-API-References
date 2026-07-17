---
title: FontEmbeddingOptions
linktitle: FontEmbeddingOptions
second_title: Aspose.PDF for Java API Reference
description: PDF/A standard requires, that all fonts must be embedded into document. This class includes flags for cases when it's not possible to embed some font cause this font is absent on.
type: docs
weight: 1680
url: /java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

PDF/A standard requires, that all fonts must be embedded into document. This class includes flags for cases when it's not possible to embed some font cause this font is absent on destination PC.

## Constructors

| Constructor | Description |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Initializes a new instance of the {@link FontEmbeddingOptions} class. This constructor sets the default value for the {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) property to {@code }. |

## Methods

| Method | Description |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Indicates whether to substitute non-embedded font using default font substitution strategy. By default false; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Indicates whether to substitute non-embedded font using default font substitution strategy. By default false; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Initializes a new instance of the {@link FontEmbeddingOptions} class. This constructor sets the default value for the {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) property to {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Indicates whether to substitute non-embedded font using default font substitution strategy. By default false;

**Returns:**
boolean value

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Indicates whether to substitute non-embedded font using default font substitution strategy. By default false;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
