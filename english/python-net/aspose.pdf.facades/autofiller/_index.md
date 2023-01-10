---
title: AutoFiller
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream.<br/>             It has two template file input modes:input as a stream or a pdf file.<br/>             It has four types of output modes:one merged stream, one merged file, many small streams, many small files.<br/>             It can recieve literal data contained in a System.Data.DataTable.
type: docs
weight: 20
url: /python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream.<br/>             It has two template file input modes:input as a stream or a pdf file.<br/>             It has four types of output modes:one merged stream, one merged file, many small streams, many small files.<br/>             It can recieve literal data contained in a System.Data.DataTable.

The AutoFiller type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|AutoFiller()|Initializes a new instance of the AutoFiller class|
## Properties
| Name | Description |
| :- | :- |
|output_stream|Gets or sets the OutputStream. One of four output modes. Its classical use case is Response.OutputStream.<br/>            Please refer to the online demo.|
|output_streams|Gets or sets the many Output Streams. One of four output modes.|
|input_stream|Gets or sets the input template stream. One of two input modes.|
|input_file_name|Gets or sets the input template file. One of two input modes.|
|output_file_name|Gets or sets the one big merged output file. One of the four output modes.|
|generating_path|Gets or sets the Generating Path of the small pdf files if many small pdf files to be generated. It works with another property [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            One of the four output modes.|
|basic_file_name|Gets or sets the basic file name if many small files will be generated. The generated file will be like "BasicFileName0","BasicFileName1",...<br/>            It works with another property [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath.|
## Methods
| Name | Description |
| :- | :- |
|save()|Saves all the pdfs.|
|save(dest_file)|Saves all the pdfs.|
|save(dest_stream)|Saves all the pdfs.|
|bind_pdf(src_file)|Binds a Pdf file.|
|bind_pdf(src_stream)|Binds a Pdf file.|
|bind_pdf(src_doc)|Binds a Pdf document.|
|close()|Closes the object and output streams.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

