---
title: Aspose::Pdf::Optimization::OptimizationOptions class
linktitle: OptimizationOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Optimization::OptimizationOptions class. Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class


Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.

```cpp
class OptimizationOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [All](./all/)() | Creates optimization strategy will all options activated. Please note that activated only options which does not change any functionality of the document. I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually). |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() const | If true page contents will be reused when document is optimized for equal pages. |
| [get_CompressAllContentStreams](./get_compressallcontentstreams/)() const | If set to **true**

, all uncompressed page content streams will be compressed using the FlateDecode filter during [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). Default is **false**

to preserve backward compatibility. |
| [get_CompressImages](./get_compressimages/)() | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [get_CompressObjects](./get_compressobjects/)() const | If this flag is set to **true**

, [Pdf](../../aspose.pdf/) objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [get_ImageEncoding](./get_imageencoding/)() const | [Image](../../aspose.pdf/image/) encodre which will be used. |
| [get_ImageQuality](./get_imagequality/)() | Specifies level of image compression when CompressIamges flag is used. |
| [get_LinkDuplicateStreams](./get_linkduplicatestreams/)() const | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times). |
| [get_MaxResoultion](./get_maxresoultion/)() | Specifies maximum resolution of images. If image has higher resolition it will be scaled. |
| [get_RemovePrivateInfo](./get_removeprivateinfo/)() const | Remove private information (page piece info). |
| [get_RemoveUnusedObjects](./get_removeunusedobjects/)() const | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [get_RemoveUnusedStreams](./get_removeunusedstreams/)() const | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document. |
| [get_ResizeImages](./get_resizeimages/)() | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [get_SubsetFonts](./get_subsetfonts/)() const | Fonts will be converted into subsets if set to true. |
| [get_UnembedFonts](./get_unembedfonts/)() const | Make fonts not embedded if set to true. |
| [OptimizationOptions](./optimizationoptions/)() |  |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | If true page contents will be reused when document is optimized for equal pages. |
| [set_CompressAllContentStreams](./set_compressallcontentstreams/)(bool) | If set to **true**

, all uncompressed page content streams will be compressed using the FlateDecode filter during [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). Default is **false**

to preserve backward compatibility. |
| [set_CompressImages](./set_compressimages/)(bool) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [set_CompressObjects](./set_compressobjects/)(bool) | If this flag is set to **true**

, [Pdf](../../aspose.pdf/) objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [set_ImageEncoding](./set_imageencoding/)(Aspose::Pdf::Optimization::ImageEncoding) | [Image](../../aspose.pdf/image/) encodre which will be used. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Specifies level of image compression when CompressIamges flag is used. |
| [set_LinkDuplicateStreams](./set_linkduplicatestreams/)(bool) | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times). |
| [set_MaxResoultion](./set_maxresoultion/)(int32_t) | Specifies maximum resolution of images. If image has higher resolition it will be scaled. |
| [set_RemovePrivateInfo](./set_removeprivateinfo/)(bool) | Remove private information (page piece info). |
| [set_RemoveUnusedObjects](./set_removeunusedobjects/)(bool) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [set_RemoveUnusedStreams](./set_removeunusedstreams/)(bool) | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document. |
| [set_ResizeImages](./set_resizeimages/)(bool) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Fonts will be converted into subsets if set to true. |
| [set_UnembedFonts](./set_unembedfonts/)(bool) | Make fonts not embedded if set to true. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
