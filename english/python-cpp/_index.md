---
title: "Aspose.PDF for Python via C++"
description:  "Aspose.PDF for Python via C++"
keywords:  "Python via C++, Python PDF toolkit"
tags: ['pdf-to-jpg', 'pdf-to-png']
weight: 40
url: /Python-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Python via C++ allows developers manipulate them PDF files

## Core Functions

| Function | Description |
| -------- | ----------- |
| [close_handle](./core/close_handle/) | Close handle |
| [document_create](./core/document_create/) | Initializes empty document. |
| [document_decrypt](./core/document_decrypt/) | Decrypts the document. Call then Save to obtain decrypted version of the document. |
| [document_encrypt](./core/document_encrypt/) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [document_export_annotations_to_xfdf](./core/document_export_annotations_to_xfdf/) | Exports all document annotations to XFDF file
| [document_get_pages](./core/document_get_pages/) | Gets collection of document pages.  
| [document_open](./core/document_open/) | Open PDF document. |
| [document_open_encrypted](./core/document_open_encrypted) | Initialize new Document instance from the filename stream. |
| [document_optimize](./core/document_optimize/) | Linearize document
| [document_save](./core/document_save/) | Saves document into the specified file.  
| [document_save_xml](./core/document_save_xml/) | Save document to XML. |
| [document_set_title](./core/document_set_title/) | Set Title for Pdf Document. |
| [extractor_bind_pdf](./core/extractor_bind_pdf/) | Bind input PDF file. |
| [extractor_create](./core/extractor_create/) | Construct extractor object for extracting images and text from PDF document. |
| [extractor_extract_text](./core/extractor_extract_text/) | Extracts text from a Pdf document using Unicode encoding. |
| [image_create](./core/image_create/) | Construct image representation. |
| [image_get_file](./core/image_get_file/) | Gets the image file. |
| [image_get_file_type](./core/image_get_file_type) | Gets the image file type. |
| [image_get_fix_height](./core/image_get_fix_height/) | Gets the image height. |
| [image_get_fix_width](./core/image_get_fix_width/) | Gets the image width. |
| [image_set_file](./core/image_set_file/) | Set the image file. |
| [image_set_file_type](./core/image_set_file_type/) | Set the image file type. |
| [image_set_fix_height](./core/image_set_fix_height/) | Sets the image height. |
| [image_set_fix_width](./core/image_set_fix_width/) | Sets the image width. |
| [image_stamp_create](./core/image_stamp_create/) | Creates image stamp by image in the specified file. |
| [image_stamp_get_background](./core/image_stamp_get_background) | Get a bool value that indicates the content is stamped as background. |
| [image_stamp_get_height](./core/image_stamp_get_height)  | Desired height of the stamp on the page. |
| [image_stamp_get_opacity](./core/image_stamp_get_opacity) | Get a value to indicate the stamp opacity. The value is from 0.0 to 1.0. |
| [image_stamp_get_rotate](./core/image_stamp_get_rotate/) | Get the rotation of stamp content according Rotation values. |
| [image_stamp_get_width](./core/image_stamp_get_width/) | Desired width of the stamp on the page. |
| [image_stamp_get_x_indent](./core/image_stamp_get_x_indent/) | Horizontal stamp coordinate, starting from the left. |
| [image_stamp_get_y_indent](./core/image_stamp_get_y_indent/) | Vertical stamp coordinate, starting from the bottom. |
| [image_stamp_set_background](./core/image_stamp_set_background/) | Set a bool value that indicates the content is stamped as background. |
| [image_stamp_set_height](./core/image_stamp_set_height/) | Set desired height of the stamp on the page. |
| [image_stamp_set_opacity](./core/image_stamp_set_opacity/) | Set a value to indicate the stamp opacity. The value is from 0.0 to 1.0. |
| [image_stamp_set_rotate](./core/image_stamp_set_rotate/) | Set the rotation of stamp content according Rotation values. |
| [image_stamp_set_width](./core/image_stamp_set_width/) | Set desired width of the stamp on the page. |
| [image_stamp_set_x_indent](./core/image_stamp_set_x_indent/) | Set horizontal stamp coordinate, starting from the left. |
| [image_stamp_set_y_indent](./core/image_stamp_set_y_indent/) | Vertical stamp coordinate, starting from the bottom. |
| [jpeg_device_create_from_width_height_resolution](./core/jpeg_device_create_from_width_height_resolution/) | Initializes a new instance of the with provided image dimensions, resolution and maximum quality. |
| [jpeg_device_save_page_to_file](./core/jpeg_device_save_page_to_file/) | Converts the page into jpeg and saves it in the file. |
| [license_create](./core/license_create/) | Provides methods to license the component. |
| [license_set](./core/license_set/) | Licenses the component. |
| [page_add_image_stamp](./core/page_add_image_stamp/) | Put image stamp into page. |
| [page_collection_add_page](./core/page_collection_add_page/) | Adds empty page. |
| [page_collection_add_pages](./core/age_collection_add_pages/) | Adds to collection all pages from 'pages_handle'. |
| [page_collection_copy_page](./core/page_collection_copy_page/) | Adds page to collection. |
| [page_collection_count](./core/page_collection_count/) | Gets count of pages. |
| [page_collection_get_page](./core/page_collection_get_page/) | Gets page by index. |
| [page_color_type](./core/page_color_type/) | Sets color type of the pages based on information getting from operators SetColor, images and forms. |
| [page_get_number](./core/page_get_number/) | Get number of the page. |
| [page_get_paragraphs](./core/page_get_paragraphs/) | Gets the paragraphs. |
| [page_get_rectangle](./core/page_get_rectangle/) | Gets rectangle of the page. |
| [page_get_rotate](./core/page_get_rotate/) | Get rotation of the page. |
| [page_set_paragraphs](./core/page_set_paragraphs/) | Sets the paragraphs. |
| [page_set_rectangle](./core/page_set_rectangle/) | Sets rectangle of the page. |
| [page_set_rotate](./core/page_set_rotate/) | Set rotation of the page. |
| [paragraphs_add_image](./core/paragraphs_add_image/) | Add image to collection. |
| [paragraphs_create](./core/paragraphs_create/) | Construct paragraph collection. |
| [png_device_create](./core/png_device_create/) | Initializes a new instance of the png device with default resolution. |
| [png_device_create_from_resolution](./core/png_device_create_from_resolution/) | Initializes a new instance of the png device. |
| [png_device_create_from_width_height_resolution](./core/png_device_create_from_width_height_resolution/) | Initializes a new instance of the png device with provided image dimensions and resolution. |
| [png_device_save_page_to_file](./core/png_device_save_page_to_file/) | Converts the page into png and saves it in the file. |
| [rectangle_create](./core/rectangle_create/) | Create Rectangle. |
| [resolution_create](./core/resolution_create/) | Initializes a new instance of resolution. |
| [resolution_create_xy](./core/resolution_create_xy/) | Initializes a new instance of resolution. |
| [stamp_bind_image](./core/stamp_bind_image/) | Sets image as a stamp. |
| [stamp_create](./core/stamp_creat/) | Construct Stamp object. |
| [stamp_get_rotation](./core/stamp_get_rotation/) | Gets rotation of the stamp in degrees. |
| [stamp_set_image_size](./core/stamp_set_image_size/) | Image will be scaled according to the specified values. |
| [stamp_set_rotation](./core/stamp_set_rotation/) | Sets rotation of the stamp in degrees. |
