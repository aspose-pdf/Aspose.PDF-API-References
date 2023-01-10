---
title: PageCollection
second_title: Aspose.PDF for Python via .NET API Reference
description: Collection of PDF document pages.
type: docs
weight: 1100
url: /python-net/aspose.pdf/pagecollection/
---

## PageCollection class

Collection of PDF document pages.

The PageCollection type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_synchronized|Returns true of object is synchorinzed.|
|sync_root|Gets synchronization object of the collection.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets page by index.|
## Methods
| Name | Description |
| :- | :- |
|add(entity)|Adds page to collection.|
|add()|Adds page to collection.|
|add(pages)|Adds to collection all pages from list. |
|add(pages)|Adds to collection all pages from array.|
|delete(index)|Delete specified page.|
|delete()|Delete specified page.|
|delete(pages)|Delete pages specified which numbers are specified in array.|
|accept(visitor)|Accepts [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) visitor object that provides functionality to work with annotations.|
|accept(visitor)|Accepts [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) visitor object that provides functionality to work with image placement objects.|
|accept(visitor)|Accepts [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) visitor object that provides functionality to work with text objects.|
|accept(visitor)|Accepts [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) visitor object that provides functionality to work with text objects.|
|insert(page_number)|Insert empty apge into collection at the specified position.|
|insert(page_number, entity)|Insert empty apge into collection at the specified position.|
|insert(page_number, pages)|Inserts pages from the collection into document.|
|insert(page_number, pages)|Inserts pages of the array into document.|
|index_of(entity)|Returns index of the specified page.|
|flatten()|Removes all fields located on the pages and place their values instead.|
|free_memory()|Clears cached data|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

