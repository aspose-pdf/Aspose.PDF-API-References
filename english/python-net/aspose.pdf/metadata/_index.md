---
title: Metadata
second_title: Aspose.PDF for Python via .NET API Reference
description: Provides access to XMP metadata stream.
type: docs
weight: 930
url: /python-net/aspose.pdf/metadata/
---

## Metadata class

Provides access to XMP metadata stream.

The Metadata type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_fixed_size|Checks if colleciton has fixed size.|
|keys|Gets collection of metadata keys.|
|values|Gets values in the metadata.|
|is_synchronized|Checks if collection is synchronized.|
|sync_root|Gets collection synchronization object.|
## Methods
| Name | Description |
| :- | :- |
|register_namespace_uri(prefix, namespace_uri)|Registers namespace URI.|
|register_namespace_uri(prefix, namespace_uri, schema_description)|Registers namespace URI.|
|add(key, value)|Adds value to metadata.|
|add(key, value)|Adds value to metadata.|
|add(prefix, value)|Adds pdf extension to metadata.|
|get_namespace_uri_by_prefix(prefix)|Returns  namespace URI by prefix.|
|get_prefix_by_namespace_uri(namespace_uri)|Returns prefix by namespace URI.|
|contains(key)|Checks does key is contained in metadata.|
|remove(key)|Removes entry from metadata.|
|contains_key(key)|Determines does this dictionary contasins specified key.|
|try_get_value(key, value)|Tries to find key in the dictionary and retreives value if found.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

