---
title: FileSpecification
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing embedded file.
type: docs
weight: 360
url: /python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Class representing embedded file.

The FileSpecification type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FileSpecification(file)|Initializes a new instance of the FileSpecification class|
|FileSpecification(stream, name)|Initializes a new instance of the FileSpecification class|
|FileSpecification(file, description)|Initializes a new instance of the FileSpecification class|
|FileSpecification(stream, name, description)|Initializes a new instance of the FileSpecification class|
|FileSpecification(file_name, annot)|Initializes a new instance of the FileSpecification class|
|FileSpecification()|Create new empty file specification.|
## Properties
| Name | Description |
| :- | :- |
|encoding|Gets or sets encoding format.<br/>            Possible values: Zip - file is compressed with ZIP, <br/>            None - file is not compressed.|
|include_contents|If true, contents of the file will be included in the file specification.|
|encrypted_payload|Gets encrypted payload.|
|description|Gets or sets text associated with the file specification.|
|af_relationship|Associated file Relationship.|
|stream_contents|Gets contents of file as stream. <br/>            Contents is not loaded into memory which allows to decrease memory usage.<br/>            But this stream does not support positioning and Length property. If you need this features please use Contents property instead.|
|contents|Gets or sets contents file. <br/>            This property returns data loaded in memory which may cause Out of memory exception for large data.<br/>            To decrease memory usage please use StreamContents.|
|params|Gets file paramteres.|
|mime_type|Gets subtype of the embedded file|
|name|Gets or sets file specification name.|
|unicode_name|Gets or sets file specification unicode name.|
|file_system|Gets or sets name of the file system.|
## Methods
| Name | Description |
| :- | :- |
|get_value(key)|Gets application-specific parameter.|
|set_value(key, value)|Sets application-specific parameter.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

