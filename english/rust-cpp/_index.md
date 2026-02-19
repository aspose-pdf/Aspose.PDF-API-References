---
title: "Aspose.PDF for Rust via C++"
description:  "Aspose.PDF for Rust via C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Structs

## Document
Document represents a PDF-document.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Function | Description |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Convert and save the previously opened PDF-document as DocX-document. |
| [save_doc](./convert/save_doc/) | Convert and save the previously opened PDF-document as Doc-document. |
| [save_xlsx](./convert/save_xlsx/) | Convert and save the previously opened PDF-document as XlsX-document. |
| [save_txt](./convert/save_txt/) | Convert and save the previously opened PDF-document as Txt-document. |
| [save_pptx](./convert/save_pptx/) | Convert and save the previously opened PDF-document as PptX-document. |
| [save_xps](./convert/save_xps/) | Convert and save the previously opened PDF-document as Xps-document. |
| [save_tex](./convert/save_tex/) | Convert and save the previously opened PDF-document as TeX-document. |
| [save_epub](./convert/save_epub/) | Convert and save the previously opened PDF-document as Epub-document. |
| [save_booklet](./convert/save_booklet/) | Convert and save the previously opened PDF-document as booklet PDF-document. |
| [save_n_up](./convert/save_n_up/) | Convert and save the previously opened PDF-document as N-Up PDF-document. |
| [save_markdown](./convert/save_markdown/) | Convert and save the previously opened PDF-document as Markdown-document. |
| [save_tiff](./convert/save_tiff/) | Convert and save the previously opened PDF-document as Tiff-document. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Convert and save the previously opened PDF-document as DocX-document with Enhanced Recognition Mode (fully editable tables and paragraphs). |
| [save_svg_zip](./convert/save_svg_zip/) | Convert and save the previously opened PDF-document as SVG-archive. |
| [export_fdf](./convert/export_fdf/) | Export from the previously opened PDF-document with AcroForm to FDF-document. |
| [export_xfdf](./convert/export_xfdf/) | Export from the previously opened PDF-document with AcroForm to XFDF-document. |
| [export_xml](./convert/export_xml/) | Export from the previously opened PDF-document with AcroForm to XML-document. |
| [page_to_jpg](./convert/page_to_jpg/) | Convert and save the specified page as Jpg-image. |
| [page_to_png](./convert/page_to_png/) | Convert and save the specified page as Png-image. |
| [page_to_bmp](./convert/page_to_bmp/) | Convert and save the specified page as Bmp-image. |
| [page_to_tiff](./convert/page_to_tiff/) | Convert and save the specified page as Tiff-image. |
| [page_to_svg](./convert/page_to_svg/) | Convert and save the specified page as Svg-image. |
| [page_to_pdf](./convert/page_to_pdf/) | Convert and save the specified page as PDF-document. |
| [page_to_dicom](./convert/page_to_dicom/) | Convert and save the specified page as DICOM-image. |


## Organize PDF functions

| Function | Description |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Optimize PDF-document content. |
| [optimize_resource](./organize/optimize_resource/) | Optimize resources of PDF-document. |
| [grayscale](./organize/grayscale/) | Convert PDF-document to black and white. |
| [rotate](./organize/rotate/) | Rotate PDF-document. |
| [set_background](./organize/set_background/) | Set PDF-document background color using RGB values. |
| [repair](./organize/repair/) | Repair PDF-document. |
| [replace_text](./organize/replace_text/) | Replace text in PDF-document |
| [add_page_num](./organize/add_page_num/) | Add page number to a PDF-document |
| [add_text_header](./organize/add_text_header/) | Add text in Header of a PDF-document |
| [add_text_footer](./organize/add_text_footer/) | Add text in Footer of a PDF-document |
| [flatten](./organize/flatten/) | Flatten PDF-document |
| [remove_annotations](./organize/remove_annotations/) | Remove annotations from PDF-document |
| [remove_attachments](./organize/remove_attachments/) | Remove attachments from PDF-document |
| [remove_blank_pages](./organize/remove_blank_pages/) | Remove blank pages from PDF-document |
| [remove_bookmarks](./organize/remove_bookmarks/) | Remove bookmarks from PDF-document |
| [remove_hidden_text](./organize/remove_hidden_text/) | Remove hidden text from PDF-document |
| [remove_images](./organize/remove_images/) | Remove images from PDF-document |
| [remove_javascripts](./organize/remove_javascripts/) | Remove java scripts from PDF-document |
| [remove_tables](./organize/remove_tables/) | Remove tables from a PDF-document. |
| [remove_watermarks](./organize/remove_watermarks/) | Remove watermarks from PDF-document. |
| [add_watermark](./organize/add_watermark/) | Add watermark to PDF-document. |
| [embed_fonts](./organize/embed_fonts/) | Embed fonts a PDF-document. |
| [unembed_fonts](./organize/unembed_fonts/) | Unembed fonts a PDF-document. |
| [optimize_file_size](./organize/optimize_file_size/) | Optimize size of PDF-document with image compression quality. |
| [remove_text_headers](./organize/remove_text_headers/) | Remove text headers from PDF-document. |
| [remove_text_footers](./organize/remove_text_footers/) | Remove text footers from PDF-document. |
| [crop](./organize/crop/) | Crop pages of a PDF-document. |
| [page_rotate](./organize/page_rotate/) | Rotate a page in the PDF-document. |
| [page_set_size](./organize/page_set_size/) | Set the size of a page in the PDF-document. |
| [page_grayscale](./organize/page_grayscale/) | Convert page to black and white. |
| [page_add_text](./organize/page_add_text/) | Add text on page. |
| [page_replace_text](./organize/page_replace_text/) | Replace text on page |
| [page_add_page_num](./organize/page_add_page_num/) | Add page number on page |
| [page_add_text_header](./organize/page_add_text_header/) | Add text in page header |
| [page_add_text_footer](./organize/page_add_text_footer/) | Add text in page footer |
| [page_remove_annotations](./organize/page_remove_annotations/) | Remove annotations in page. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Remove hidden text in page. |
| [page_remove_images](./organize/page_remove_images/) | Remove images in page. |
| [page_remove_tables](./organize/page_remove_tables/) | Remove tables in page. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Remove watermarks in page. |
| [page_add_watermark](./organize/page_add_watermark/) | Add watermark on page. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Remove text headers in page. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Remove text footers in page. |
| [page_crop](./organize/page_crop/) | Crop a page. |


## Core PDF functions

| Function | Description |
| -------- | ----------- |
| [new](./core/new/) | Create a new PDF-document. |
| [open](./core/open/) | Open a PDF-document with filename. |
| [save](./core/save/) | Save the previously opened PDF-document. |
| [save_as](./core/save_as/) | Save the previously opened PDF-document with new filename. |
| [set_license](./core/set_license/) | Set license with filename. |
| [extract_text](./core/extract_text/) | Return the PDF-document contents as plain text. |
| [word_count](./core/word_count/) | Return word count in PDF-document. |
| [character_count](./core/character_count/) | Return character count in PDF-document. |
| [append](./core/append/) | Append pages from another PDF-document. |
| [append_pages](./core/append_pages/) | Append selected pages from another PDF-document. |
| [merge_documents](./core/merge_documents/) | Create a new PDF-document by merging the provided PDF-documents. |
| [split_document](./core/split_document/) | Create multiple new PDF-documents by extracting pages from the source PDF-document. |
| [split](./core/split/) | Create multiple new PDF-documents by extracting pages from the current PDF-document. |
| [split_at_page](./core/split_at_page/) | Split the PDF-document into two new PDF-documents. |
| [split_at](./core/split_at/) | Split the current PDF-document into two new PDF-documents. |
| [bytes](./core/bytes/) | Return the contents of the PDF-document as a byte vector. |
| [page_add](./core/page_add/) | Add new page in PDF-document. |
| [page_insert](./core/page_insert/) | Insert new page at the specified position in PDF-document. |
| [page_delete](./core/page_delete/) | Delete specified page in PDF-document. |
| [page_count](./core/page_count/) | Return the number of pages in the PDF-document. |
| [page_word_count](./core/page_word_count/) | Return word count on specified page in PDF-document. |
| [page_character_count](./core/page_character_count/) | Return character count on specified page in PDF-document. |
| [page_is_blank](./core/page_is_blank/) | Return page is blank in PDF-document. |


## Security
| Function | Description |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Open a password-protected PDF-document. |
| [encrypt](./security/encrypt/) | Encrypt PDF-document. |
| [decrypt](./security/decrypt/) | Decrypt PDF-document. |
| [set_permissions](./security/set_permissions/) | Set permissions for PDF-document. |
| [get_permissions](./security/get_permissions/) | Get current permissions of PDF-document. |


## Miscellaneous

| Function | Description |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Return metadata information about the Aspose.PDF for Rust via C++. |



# Structs secondary

## ProductInfo contains metadata about the Aspose.PDF for Rust via C++.
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

## Bitflag set representing PDF permission capabilities.
```rust
bitflags! {
    /// Bitflag set representing PDF permission capabilities.
    #[derive(Copy, Clone, PartialEq, Eq)]
    pub struct Permissions: i32 {
        const PRINT_DOCUMENT                    = 1 << 2;  // 4
        const MODIFY_CONTENT                    = 1 << 3;  // 8
        const EXTRACT_CONTENT                   = 1 << 4;  // 16
        const MODIFY_TEXT_ANNOTATIONS           = 1 << 5;  // 32
        const FILL_FORM                         = 1 << 8;  // 256
        const EXTRACT_CONTENT_WITH_DISABILITIES = 1 << 9;  // 512
        const ASSEMBLE_DOCUMENT                 = 1 << 10; // 1024
        const PRINTING_QUALITY                  = 1 << 11; // 2048
    }
}
```

# Enums

## Enumeration of possible page size values.
```rust
pub enum PageSize {
    /// A0 size.
    A0 = 0,
    /// A1 size.
    A1 = 1,
    /// A2 size.
    A2 = 2,
    /// A3 size.
    A3 = 3,
    /// A4 size.
    A4 = 4,
    /// A5 size.
    A5 = 5,
    /// A6 size.
    A6 = 6,
    /// B5 size.
    B5 = 7,
    /// PageLetter size.
    PageLetter = 8,
    /// PageLegal size.
    PageLegal = 9,
    /// PageLedger size.
    PageLedger = 10,
    /// P11x17 size.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Non-rotated.
    None = 0,
    /// Rotated on 90 degrees clockwise.
    On90 = 1,
    /// Rotated on 180 degrees.
    On180 = 2,
    /// Rotated on 270 degrees clockwise.
    On270 = 3,
    /// Rotated on 360 degrees clockwise.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 with key length 40.
    RC4x40 = 0,
    /// RC4 with key length 128.
    RC4x128 = 1,
    /// AES with key length 128.
    AESx128 = 2,
    /// AES with key length 256.
    AESx256 = 3,
}
```
