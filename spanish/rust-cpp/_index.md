---
title: "Aspose.PDF para Rust vía C++"
description: "Aspose.PDF para Rust vía C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /es/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Estructuras

## Document
Document representa un documento PDF.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Función | Descripción |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Convertir y guardar el PDF-documento previamente abierto como documento DocX-document. |
| [save_doc](./convert/save_doc/) | Convertir y guardar el PDF-documento previamente abierto como documento Doc-document. |
| [save_xlsx](./convert/save_xlsx/) | Convertir y guardar el PDF-documento previamente abierto como documento XlsX-document. |
| [save_txt](./convert/save_txt/) | Convertir y guardar el PDF-documento previamente abierto como documento Txt-document. |
| [save_pptx](./convert/save_pptx/) | Convertir y guardar el PDF-documento previamente abierto como documento PptX-document. |
| [save_xps](./convert/save_xps/) | Convertir y guardar el PDF-documento previamente abierto como documento Xps-document. |
| [save_tex](./convert/save_tex/) | Convertir y guardar el PDF-documento previamente abierto como documento TeX-document. |
| [save_epub](./convert/save_epub/) | Convertir y guardar el PDF-documento previamente abierto como documento Epub-document. |
| [save_booklet](./convert/save_booklet/) | Convertir y guardar el PDF-documento previamente abierto como documento PDF de folleto. |
| [save_n_up](./convert/save_n_up/) | Convertir y guardar el PDF-documento previamente abierto como documento PDF N-Up. |
| [save_markdown](./convert/save_markdown/) | Convertir y guardar el PDF-documento previamente abierto como documento Markdown-document. |
| [save_tiff](./convert/save_tiff/) | Convertir y guardar el PDF-documento previamente abierto como documento Tiff-document. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Convertir y guardar el PDF-documento previamente abierto como documento DocX-document con Modo de Reconocimiento Mejorado (tablas y párrafos totalmente editables). |
| [save_svg_zip](./convert/save_svg_zip/) | Convertir y guardar el PDF-documento previamente abierto como archivo SVG-archive. |
| [export_fdf](./convert/export_fdf/) | Exportar desde el PDF-documento previamente abierto con AcroForm a documento FDF-document. |
| [export_xfdf](./convert/export_xfdf/) | Exportar desde el PDF-documento previamente abierto con AcroForm a documento XFDF-document. |
| [export_xml](./convert/export_xml/) | Exportar desde el PDF-documento previamente abierto con AcroForm a documento XML-document. |
| [page_to_jpg](./convert/page_to_jpg/) | Convertir y guardar la página especificada como imagen Jpg-image. |
| [page_to_png](./convert/page_to_png/) | Convertir y guardar la página especificada como imagen Png-image. |
| [page_to_bmp](./convert/page_to_bmp/) | Convertir y guardar la página especificada como imagen Bmp-image. |
| [page_to_tiff](./convert/page_to_tiff/) | Convertir y guardar la página especificada como imagen Tiff. |
| [page_to_svg](./convert/page_to_svg/) | Convertir y guardar la página especificada como imagen Svg. |
| [page_to_pdf](./convert/page_to_pdf/) | Convertir y guardar la página especificada como documento PDF. |
| [page_to_dicom](./convert/page_to_dicom/) | Convertir y guardar la página especificada como imagen DICOM. |


## Organize PDF functions

| Función | Descripción |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Optimizar el contenido del documento PDF. |
| [optimize_resource](./organize/optimize_resource/) | Optimizar los recursos del documento PDF. |
| [grayscale](./organize/grayscale/) | Convertir el documento PDF a blanco y negro. |
| [rotate](./organize/rotate/) | Rotar el documento PDF. |
| [set_background](./organize/set_background/) | Establecer el color de fondo del documento PDF usando valores RGB. |
| [repair](./organize/repair/) | Reparar el documento PDF. |
| [replace_text](./organize/replace_text/) | Reemplazar texto en el documento PDF |
| [add_page_num](./organize/add_page_num/) | Agregar número de página a un documento PDF |
| [add_text_header](./organize/add_text_header/) | Agregar texto en el encabezado de un documento PDF |
| [add_text_footer](./organize/add_text_footer/) | Agregar texto en el pie de página de un documento PDF |
| [flatten](./organize/flatten/) | Aplanar el documento PDF |
| [remove_annotations](./organize/remove_annotations/) | Eliminar anotaciones del documento PDF |
| [remove_attachments](./organize/remove_attachments/) | Eliminar adjuntos del documento PDF |
| [remove_blank_pages](./organize/remove_blank_pages/) | Eliminar páginas en blanco del documento PDF |
| [remove_bookmarks](./organize/remove_bookmarks/) | Eliminar marcadores del documento PDF |
| [remove_hidden_text](./organize/remove_hidden_text/) | Eliminar texto oculto del documento PDF |
| [remove_images](./organize/remove_images/) | Eliminar imágenes del documento PDF |
| [remove_javascripts](./organize/remove_javascripts/) | Eliminar scripts Java del documento PDF |
| [remove_tables](./organize/remove_tables/) | Eliminar tablas de un documento PDF. |
| [remove_watermarks](./organize/remove_watermarks/) | Eliminar marcas de agua del documento PDF. |
| [add_watermark](./organize/add_watermark/) | Agregar marca de agua al documento PDF. |
| [embed_fonts](./organize/embed_fonts/) | Incrustar fuentes en un documento PDF. |
| [unembed_fonts](./organize/unembed_fonts/) | Desincrustar fuentes de un documento PDF. |
| [optimize_file_size](./organize/optimize_file_size/) | Optimizar el tamaño de un documento PDF con calidad de compresión de imagen. |
| [remove_text_headers](./organize/remove_text_headers/) | Eliminar encabezados de texto de un documento PDF. |
| [remove_text_footers](./organize/remove_text_footers/) | Eliminar pies de página de texto de un documento PDF. |
| [crop](./organize/crop/) | Recortar páginas de un documento PDF. |
| [replace_font](./organize/replace_font/) | Reemplazar la fuente en un documento PDF. |
| [convert](./organize/convert/) | Convertir un documento PDF en un documento PDF con el formato PDF especificado |
| [validate](./organize/validate/) | Validar un documento PDF para el cumplimiento del formato PDF |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Eliminar el cumplimiento PDF/A de un documento PDF |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Eliminar el cumplimiento PDF/UA de un documento PDF |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Obtener si un documento PDF cumple con PDF/A |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Obtener si un documento PDF cumple con PDF/UA |
| [page_rotate](./organize/page_rotate/) | Rotar una página en el documento PDF. |
| [page_set_size](./organize/page_set_size/) | Establecer el tamaño de una página en el documento PDF. |
| [page_grayscale](./organize/page_grayscale/) | Convertir la página a blanco y negro. |
| [page_add_text](./organize/page_add_text/) | Agregar texto en la página. |
| [page_replace_text](./organize/page_replace_text/) | Reemplazar texto en la página |
| [page_add_page_num](./organize/page_add_page_num/) | Agregar número de página en la página |
| [page_add_text_header](./organize/page_add_text_header/) | Agregar texto en el encabezado de la página |
| [page_add_text_footer](./organize/page_add_text_footer/) | Agregar texto en el pie de página de la página |
| [page_remove_annotations](./organize/page_remove_annotations/) | Eliminar anotaciones en la página. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Eliminar texto oculto en la página. |
| [page_remove_images](./organize/page_remove_images/) | Eliminar imágenes en la página. |
| [page_remove_tables](./organize/page_remove_tables/) | Eliminar tablas en la página. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Eliminar marcas de agua en la página. |
| [page_add_watermark](./organize/page_add_watermark/) | Agregar marca de agua en la página. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Eliminar encabezados de texto en la página. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Eliminar pies de página de texto en la página. |
| [page_crop](./organize/page_crop/) | Recortar una página. |
| [page_replace_font](./organize/page_replace_font/) | Reemplazar la fuente en la página. |
| [page_merge_layers](./organize/page_merge_layers/) | Combinar todas las capas en la página en una sola capa con el nombre de capa nuevo especificado. |
| [page_layers](./organize/page_layers/) | Obtener los nombres de las capas en la página. |


## Core PDF functions

| Función | Descripción |
| -------- | ----------- |
| [new](./core/new/) | Crear un nuevo documento PDF. |
| [open](./core/open/) | Abrir un documento PDF con el nombre de archivo. |
| [save](./core/save/) | Guardar el documento PDF abierto previamente. |
| [save_as](./core/save_as/) | Guardar el documento PDF abierto previamente con un nuevo nombre de archivo. |
| [set_license](./core/set_license/) | Establecer la licencia con el nombre de archivo. |
| [extract_text](./core/extract_text/) | Devolver el contenido del documento PDF como texto plano. |
| [word_count](./core/word_count/) | Devolver el recuento de palabras en el documento PDF. |
| [character_count](./core/character_count/) | Devolver el recuento de caracteres en el documento PDF. |
| [append](./core/append/) | Agregar páginas de otro documento PDF. |
| [append_pages](./core/append_pages/) | Agregar páginas seleccionadas de otro documento PDF. |
| [merge_documents](./core/merge_documents/) | Crear un nuevo documento PDF combinando los documentos PDF proporcionados. |
| [split_document](./core/split_document/) | Crear varios documentos PDF nuevos extrayendo páginas del documento PDF fuente. |
| [split](./core/split/) | Crear varios documentos PDF nuevos extrayendo páginas del documento PDF actual. |
| [split_at_page](./core/split_at_page/) | Dividir el documento PDF en dos documentos PDF nuevos. |
| [split_at](./core/split_at/) | Dividir el documento PDF actual en dos documentos PDF nuevos. |
| [bytes](./core/bytes/) | Devolver el contenido del documento PDF como un vector de bytes. |
| [get_meta_info](./core/get_meta_info/) | Obtener el valor de la información meta del documento PDF. |
| [set_meta_info](./core/set_meta_info/) | Establecer el valor de la información meta del PDF-document. |
| [clear_meta_info](./core/clear_meta_info/) | Borrar todos los valores de información meta del PDF-document. |
| [is_linearized](./core/is_linearized/) | Obtener un valor que indique si el documento está linealizado. |
| [page_add](./core/page_add/) | Agregar una nueva página en el PDF-document. |
| [page_insert](./core/page_insert/) | Insertar una nueva página en la posición especificada del PDF-document. |
| [page_delete](./core/page_delete/) | Eliminar la página especificada del PDF-document. |
| [page_count](./core/page_count/) | Devolver el número de páginas del PDF-document. |
| [page_word_count](./core/page_word_count/) | Devolver el recuento de palabras en la página especificada del PDF-document. |
| [page_character_count](./core/page_character_count/) | Devolver el recuento de caracteres en la página especificada del PDF-document. |
| [page_is_blank](./core/page_is_blank/) | Devolver si la página está en blanco en el PDF-document. |


## Security
| Función | Descripción |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Abrir un PDF-document protegido con contraseña. |
| [encrypt](./security/encrypt/) | Cifrar el PDF-document. |
| [decrypt](./security/decrypt/) | Descifrar el PDF-document. |
| [set_permissions](./security/set_permissions/) | Establecer permisos para el PDF-document. |
| [get_permissions](./security/get_permissions/) | Obtener los permisos actuales del PDF-document. |
| [is_encrypted](./security/is_encrypted/) | Obtener el estado cifrado del PDF-document. |
| [sign_pkcs7](./security/sign_pkcs7/) | Firmar un PDF-document usando firmas digitales PKCS#7. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Firmar un PDF-document usando firmas digitales PKCS#7 desacopladas. |
| [is_signed](./security/is_signed/) | Obtener el estado de firma del PDF-document. |
| [remove_signs](./security/remove_signs/) | Eliminar firmas del PDF-document. |


## Miscellaneous

| Función | Descripción |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Devolver información de metadatos sobre Aspose.PDF para Rust vía C++. |



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
    /// Conjunto de banderas que representa las capacidades de permisos PDF.
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
    /// Tamaño A0.
    A0 = 0,
    /// Tamaño A1.
    A1 = 1,
    /// Tamaño A2.
    A2 = 2,
    /// tamaño A3.
    A3 = 3,
    /// tamaño A4.
    A4 = 4,
    /// tamaño A5.
    A5 = 5,
    /// tamaño A6.
    A6 = 6,
    /// tamaño B5.
    B5 = 7,
    /// tamaño PageLetter.
    PageLetter = 8,
    /// tamaño PageLegal.
    PageLegal = 9,
    /// tamaño PageLedger.
    PageLedger = 10,
    /// tamaño P11x17.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// No rotado.
    None = 0,
    /// Rotado 90 grados en sentido horario.
    On90 = 1,
    /// Rotado 180 grados.
    On180 = 2,
    /// Rotado 270 grados en sentido horario.
    On270 = 3,
    /// Rotado 360 grados en sentido horario.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 con longitud de clave 40.
    RC4x40 = 0,
    /// RC4 con longitud de clave 128.
    RC4x128 = 1,
    /// AES con longitud de clave 128.
    AESx128 = 2,
    /// AES con longitud de clave 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// formato PDF/A-1a.
    PDF_A_1A = 0,
    /// formato PDF/A-1b.
    PDF_A_1B = 1,
    /// formato PDF/A-2a.
    PDF_A_2A = 2,
    /// formato PDF/A-3a.
    PDF_A_3A = 3,
    /// formato PDF/A-2b.
    PDF_A_2B = 4,
    /// formato PDF/A-2u.
    PDF_A_2U = 5,
    /// formato PDF/A-3b.
    PDF_A_3B = 6,
    /// formato PDF/A-3u.
    PDF_A_3U = 7,
    /// versión Adobe 1.0.
    V_1_0 = 8,
    /// versión Adobe 1.1.
    V_1_1 = 9,
    /// versión Adobe 1.2.
    V_1_2 = 10,
    /// versión Adobe 1.3.
    V_1_3 = 11,
    /// versión Adobe 1.4.
    V_1_4 = 12,
    /// versión Adobe 1.5.
    V_1_5 = 13,
    /// versión Adobe 1.6.
    V_1_6 = 14,
    /// versión Adobe 1.7.
    V_1_7 = 15,
    /// Estándar ISO PDF 2.0.
    V_2_0 = 16,
    /// formato PDF/UA-1.
    PDF_UA_1 = 17,
    /// formato PDF/X-1a:2001.
    PDF_X_1A_2001 = 18,
    /// formato PDF/X-1a.
    PDF_X_1A = 19,
    /// formato PDF/X-3.
    PDF_X_3 = 20,
    /// formato ZUGFeRD.
    ZUGFeRD = 21,
    /// formato PDF/A-4.
    PDF_A_4 = 22,
    /// formato PDF/A-4e.
    PDF_A_4E = 23,
    /// formato PDF/A-4f.
    PDF_A_4F = 24,
    /// formato PDF/X-4.
    PDF_X_4 = 25,
    /// formato PDF/E-1 (PDF 1.6).
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Eliminar elementos no conformes.
    Delete = 0,
    /// No hacer nada, mantener elementos no conformes.
    None = 1,
}
```

