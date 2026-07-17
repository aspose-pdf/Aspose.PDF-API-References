---
title: ToUnicodeProcessingRules
linktitle: ToUnicodeProcessingRules
second_title: Aspose.PDF for Java API Reference
description: This class describes rules which can be used to solve Adobe Preflight error \"Text cannot be mapped to Unicode\".
type: docs
weight: 5380
url: /java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode".

## Constructors

| Constructor | Description |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Initializes a new instance of the {@link ToUnicodeProcessingRules} class. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Initializes a new instance of the {@link ToUnicodeProcessingRules} class with the specified option to remove spaces from CMap names. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Initializes a new instance of the {@link ToUnicodeProcessingRules} class with specified options. |

## Methods

| Method | Description |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Initializes a new instance of the {@link ToUnicodeProcessingRules} class.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Initializes a new instance of the {@link ToUnicodeProcessingRules} class with the specified option to remove spaces from CMap names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeSpaces |  | A boolean value indicating whether to remove spaces from CMap names. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Initializes a new instance of the {@link ToUnicodeProcessingRules} class with specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeSpaces |  | Indicates whether spaces should be removed from CMap names. |
| mapNonLinkedUnicodesOnSpace |  | Indicates whether non-linked Unicode symbols should be mapped to spaces. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32).

**Returns:**
boolean value

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false.

**Returns:**
boolean value

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
