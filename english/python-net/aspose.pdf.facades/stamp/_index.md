---
title: Stamp
second_title: Aspose.PDF for Python via .NET API Reference
description: Class represeting stamp.
type: docs
weight: 410
url: /python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Class represeting stamp.

The Stamp type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Stamp()|Initializes a new instance of the Stamp class|
## Properties
| Name | Description |
| :- | :- |
|stamp_id|Gets or sets identifier of stamp.|
|quality|Gets or sets quality of image stamp in percent. Valiued values 0..100%.|
|opacity|Gets or sets opacity of the stamp.|
|page_number|Gets or sets page number.|
|pages|Gets or sets array with numbers of pages which will be affected by stamp. <br/>            If Pages = null all pages of the document are affected.|
|rotation|Gets or sets rotation of the stamp in degrees.|
|is_background|Gets or sets background status. If true stamp will be placed as background of the spamped page.<br/>            By default is set to false.|
|blending_space|Gets or sets a BlendingColorSpace value that defines a color space <br/>            that is used to perform transparency and blending operations on the page.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(pdf_file, page_number)|Sets PDF file and number of page which will be used as stamp.|
|bind_pdf(pdf_stream, page_number)|Sets PDF file and number of page which will be used as stamp.|
|bind_image(image_file)|Sets image as a stamp.|
|bind_image(image)|Sets image which will be used as stamp.|
|bind_logo(formatted_text)|Sets text as stamp.|
|bind_text_state(text_state)|Sets text state of stamp text.|
|set_origin(origin_x, origin_y)|Sets position on page where stamp will be placed.|
|set_image_size(width, height)|Sets size of image stamp. Image will be scaled according to the specified values.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

