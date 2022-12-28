---
title: TableAbsorber
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents an absorber object of table elements.<br/>            Performs search and provides access to search results via [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/) collection.
type: docs
weight: 310
url: /python-net/aspose.pdf.text/tableabsorber/
---

## TableAbsorber class

Represents an absorber object of table elements.<br/>            Performs search and provides access to search results via [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/) collection.

The TableAbsorber type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TableAbsorber(text_search_options)|Initializes a new instance of the TableAbsorber class|
|TableAbsorber()|Initializes a new instance of the [TableAbsorber](/pdf/python-net/aspose.pdf.text/tableabsorber/).|
## Properties
| Name | Description |
| :- | :- |
|text_search_options|Gets or sets text search options.|
|table_list|Returns readonly IList containing tables that were found|
|use_flow_engine|* Activate an early alfa version of alternative table recognition engine that could be used for conversion tables <br/>            without borders.<br/>            Doesn't support editing tables and getting text styles yet. Default value is false;|
## Methods
| Name | Description |
| :- | :- |
|visit(page)|Extracts tables on the specified page|
|remove(table)|Removes an [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) from the page.|
|replace(page, old_table, new_table)|Replaces an [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) with [Table](/pdf/python-net/aspose.pdf/table/) on the page.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

