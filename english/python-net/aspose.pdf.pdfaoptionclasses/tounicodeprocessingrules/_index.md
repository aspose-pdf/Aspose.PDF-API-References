---
title: ToUnicodeProcessingRules
second_title: Aspose.PDF for Python via .NET API Reference
description: This class describes rules which can be used to solve Adobe Preflight error <br/>            "Text cannot be mapped to Unicode".
type: docs
weight: 20
url: /python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

This class describes rules which can be used to solve Adobe Preflight error <br/>            "Text cannot be mapped to Unicode".

The ToUnicodeProcessingRules type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ToUnicodeProcessingRules()|Constructor|
|ToUnicodeProcessingRules(remove_spaces)|Initializes a new instance of the ToUnicodeProcessingRules class|
|ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space)|Initializes a new instance of the ToUnicodeProcessingRules class|
## Properties
| Name | Description |
| :- | :- |
|remove_spaces_from_c_map_names|Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors<br/>            with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps.<br/>            By default false.|
|map_non_linked_symbols_on_space|Some fonts doesn't provide information about unicodes for some text symbols. <br/>            This lack of information calls an error "Text cannot be mapped to Unicode".<br/>            Use this flag to map non-linked symbols on unicode "space"(code 32).|

### See Also

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

