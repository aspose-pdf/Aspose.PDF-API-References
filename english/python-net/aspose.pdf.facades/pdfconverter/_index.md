---
title: PdfConverter
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now.<br/>            Supported content in pdfs: pictures, form, comment.
type: docs
weight: 200
url: /python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now.<br/>            Supported content in pdfs: pictures, form, comment.

The PdfConverter type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfConverter()|Initializes new [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) object.|
|PdfConverter(document)|Initializes a new instance of the PdfConverter class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|coordinate_type|Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.|
|show_hidden_areas|Gets or sets flag that controls visibility of hidden areas on the page.|
|rendering_options|Gets or sets rendering options.|
|form_presentation_mode|Gets or sets form presentation mode.|
|resolution|Gets or sets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150.|
|start_page|Gets or sets start position which you want to convert. The minimal value is 1.|
|end_page|Gets or sets end position which you want to convert.|
|password|Gets or sets document OwnerPassword.|
|user_password|Gets or sets document UserPassword.|
|page_count|Gets the page count.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(input_file)|Binds a Pdf file for converting.|
|bind_pdf(input_stream)|Binds a Pdf Stream for convert.|
|bind_pdf(src_doc)|Initializes the facade.|
|save_as_tiff(output_file)|Converts each pages of a pdf document to images and saves images to a single TIFF file.|
|save_as_tiff(output_file, compression_type)|Converts each pages of a pdf document to images and saves images to a single TIFF file.|
|save_as_tiff(output_file, image_width, image_height)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.|
|save_as_tiff(output_file, page_size)|Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.|
|save_as_tiff(output_file, page_size, settings)|Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.|
|save_as_tiff(output_file, image_width, image_height, compression_type)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.|
|save_as_tiff(output_file, image_width, image_height, settings)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.|
|save_as_tiff(output_file, image_width, image_height, settings, converter)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.|
|save_as_tiff(output_stream)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.|
|save_as_tiff(output_stream, compression_type)|Converts each pages of a pdf document to images and saves images to a single TIFF file.|
|save_as_tiff(output_stream, page_size)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.|
|save_as_tiff(output_stream, page_size, settings)|Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.|
|save_as_tiff(output_stream, image_width, image_height)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.|
|save_as_tiff(output_stream, image_width, image_height, compression_type)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.|
|save_as_tiff(output_stream, image_width, image_height, settings)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.|
|save_as_tiff(output_stream, image_width, image_height, settings, converter)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.|
|save_as_tiff(output_file, settings)|Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.|
|save_as_tiff(output_file, settings, converter)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.|
|save_as_tiff(output_stream, settings)|Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.|
|save_as_tiff(output_stream, settings, converter)|Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.|
|save_as_tiff_class_f(output_file, image_width, image_height)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.|
|save_as_tiff_class_f(output_file, page_size)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.|
|save_as_tiff_class_f(output_stream, image_width, image_height)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.|
|save_as_tiff_class_f(output_stream, page_size)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.|
|save_as_tiff_class_f(output_file)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.|
|save_as_tiff_class_f(output_stream)|Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.|
|get_next_image(output_file)|Saves image to file with default image format - jpeg.|
|get_next_image(output_file, page_size)|Saves image to file with ith given page size and default image format - jpeg.|
|get_next_image(output_file, format)|Saves image to file with the givin image format.|
|get_next_image(output_file, page_size, format)|Saves image to file with given page size and image format.|
|get_next_image(output_stream)|Saves image to stream with default image format - jpeg.|
|get_next_image(output_stream, page_size)|Saves image to stream with given page size.|
|get_next_image(output_stream, format)|Saves image to stream with given image format.|
|get_next_image(output_stream, page_size, format)|Saves image to stream with given page size.|
|get_next_image(output_file, format, image_width, image_height, quality)|Saves image to file with the given image format, dimensions and quality.|
|get_next_image(output_stream, format, image_width, image_height, quality)|Saves image to stream with the givin image format, dimensions and quality.|
|get_next_image(output_file, format, image_width, image_height, quality)|Saves image to file with the givin image format, image size,  and quality.|
|get_next_image(output_stream, format, image_width, image_height, quality)|Saves image to stream with the givin image format, size and quality.|
|get_next_image(output_file, format, image_width, image_height)|Saves image to file with the given image format, dimensions and quality.|
|get_next_image(output_stream, format, image_width, image_height)|Saves image to stream with the givin image format, dimensions and quality.|
|get_next_image(output_stream, format, quality)|Saves image to stream with the givin image format, dimensions and quality.|
|get_next_image(output_stream, page_size, format, quality)|Saves image to stream with given page size, image format and quality.|
|get_next_image(output_file, format, quality)|Saves image to file with the given image format, dimensions and quality.|
|get_next_image(output_file, page_size, format, quality)|Saves image to file with given page size, image format and quality.|
|close()|Close the instance of PdfConverter and release the resources.|
|do_convert()|Do some initial works for converting a pdf document to images.|
|has_next_image()|Indicates whether the pdf file has more images or not.|
|merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical)|None|
|merge_images_as_tiff(input_images_streams)|Merges list of tiff streams as one multiple frames tiff stream.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

