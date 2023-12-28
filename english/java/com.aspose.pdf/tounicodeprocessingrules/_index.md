---
title: ToUnicodeProcessingRules
second_title: Aspose.PDF for Java API Reference
description: This class describes rules which can be used to solve Adobe Preflight error Text cannot be mapped to Unicode.
type: docs
weight: 394
url: /java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object
```
public class ToUnicodeProcessingRules
```

This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode".
## Constructors

| Constructor | Description |
| --- | --- |
| [ToUnicodeProcessingRules()](#ToUnicodeProcessingRules--) | Constructor |
| [ToUnicodeProcessingRules(boolean removeSpaces)](#ToUnicodeProcessingRules-boolean-) | Constructor |
| [ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)](#ToUnicodeProcessingRules-boolean-boolean-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getRemoveSpacesFromCMapNames()](#getRemoveSpacesFromCMapNames--) | Some fonts have ToUnicode character code maps with spaces in names. |
| [setRemoveSpacesFromCMapNames(boolean value)](#setRemoveSpacesFromCMapNames-boolean-) | Some fonts have ToUnicode character code maps with spaces in names. |
| [getMapNonLinkedSymbolsOnSpace()](#getMapNonLinkedSymbolsOnSpace--) | Some fonts doesn't provide information about unicodes for some text symbols. |
| [setMapNonLinkedSymbolsOnSpace(boolean value)](#setMapNonLinkedSymbolsOnSpace-boolean-) | Some fonts doesn't provide information about unicodes for some text symbols. |
### ToUnicodeProcessingRules() {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```


Constructor

### ToUnicodeProcessingRules(boolean removeSpaces) {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeSpaces | boolean | sets  RemoveSpacesFromCMapNames  flag |

### ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace) {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeSpaces | boolean | sets  RemoveSpacesFromCMapNames  flag |
| mapNonLinkedUnicodesOnSpace | boolean | sets  MapNonLinkedSymbolsOnSpace  flag |

### getRemoveSpacesFromCMapNames() {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```


Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false.

**Returns:**
boolean - boolean value
### setRemoveSpacesFromCMapNames(boolean value) {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```


Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMapNonLinkedSymbolsOnSpace() {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```


Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32).

**Returns:**
boolean - boolean value
### setMapNonLinkedSymbolsOnSpace(boolean value) {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```


Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

