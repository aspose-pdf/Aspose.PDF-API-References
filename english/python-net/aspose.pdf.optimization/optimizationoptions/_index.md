---
title: OptimizationOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Class which describes document optimization algorithm.<br/>            Instance of this class may be used as parameter of OptimizeResources() method.
type: docs
weight: 20
url: /python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Class which describes document optimization algorithm.<br/>            Instance of this class may be used as parameter of OptimizeResources() method.

The OptimizationOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|OptimizationOptions()|Initializes a new instance of the OptimizationOptions class|
## Properties
| Name | Description |
| :- | :- |
|link_duplcate_streams|If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. <br/>            This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times).|
|allow_reuse_page_content|If true page contents will be reused when document is optimized for equal pages.|
|remove_unused_streams|If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed.<br/>            This may decrease document size for example when pages were extracted from document.|
|remove_unused_objects|If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.|
|image_compression_options|Set of options which describe will images in the document be compressed and parameters of the compression.|
|compress_images|If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.|
|resize_images|If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.|
|image_quality|Specifies level of image compression when CompressIamges flag is used.|
|max_resoultion|Specifies maximum resolution of images. If image has higher resolition it will be scaled|
|unembed_fonts|Make fonts not embedded if set to true.|
|subset_fonts|Fonts will be converted into subsets if set to true.|
|remove_private_info|Remove private information (page piece info).|
|image_encoding|Image encodre which will be used.|
## Methods
| Name | Description |
| :- | :- |
|all()|Creates optimization strategy will all options activated.<br/>            Please note that activated only options which does not change any functionality of the document.<br/>            I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually).|

### See Also

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

