---
title: Aspose::Pdf::ToUnicodeProcessingRules class
linktitle: ToUnicodeProcessingRules
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ToUnicodeProcessingRules class. This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode" in C++.'
type: docs
weight: 18500
url: /cpp/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class


This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode".

```cpp
class ToUnicodeProcessingRules : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_MapNonLinkedSymbolsOnSpace](./get_mapnonlinkedsymbolsonspace/)() const | Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32). |
| [get_RemoveSpacesFromCMapNames](./get_removespacesfromcmapnames/)() const | Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false. |
| [set_MapNonLinkedSymbolsOnSpace](./set_mapnonlinkedsymbolsonspace/)(bool) | Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32). |
| [set_RemoveSpacesFromCMapNames](./set_removespacesfromcmapnames/)(bool) | Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)() | Initializes a new instance of the [ToUnicodeProcessingRules](./) class. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool) | Initializes a new instance of the [ToUnicodeProcessingRules](./) class with the specified option to remove spaces from CMap names. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool, bool) | Initializes a new instance of the [ToUnicodeProcessingRules](./) class with specified options. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
