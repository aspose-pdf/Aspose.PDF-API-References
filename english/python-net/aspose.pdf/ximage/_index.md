---
title: XImage
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing image X-Object.
type: docs
weight: 1680
url: /python-net/aspose.pdf/ximage/
---

## XImage class

Class representing image X-Object.

The XImage type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|contains_transparency|If the image contains transparancy than return true; otherwise, false.|
|grayscaled|Gets grayscaled version of image.|
|filter_type|Gets image filter type.|
|width|Gets width of the image.|
|height|Gets height of the image.|
|name|Gets or sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case.|
|metadata|Metadata of the image.|
## Methods
| Name | Description |
| :- | :- |
|save(stream)|Saves image data into stream as JPEG image.|
|save(stream, format)|Saves image into stream with requested format.|
|save(stream, resolution)|Saves image data into stream as JPEG image with specified resolution.|
|save(stream, format, resolution)|Saves image into stream with requested format with specified resolution.|
|rename(name)|Renames image and replaces all references to the image with the new name|
|get_color_type()|Returns color type of image.|
|detect_color_type(bmp)|Returns color type of image.|
|is_the_same_object(image)|Returns true if both images references to the same object.|
|get_name_in_collection()|Returns name of the image in ints collection.|
|to_stream()|Returns the original image stream.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

