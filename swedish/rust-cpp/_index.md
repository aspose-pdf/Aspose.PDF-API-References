---
title: "Aspose.PDF för Rust via C++"
description: "Aspose.PDF för Rust via C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /sv/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Strukturer

## Document
Dokumentet representerar ett PDF-dokument.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Funktion | Beskrivning |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett DocX-dokument. |
| [save_doc](./convert/save_doc/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett Doc-dokument. |
| [save_xlsx](./convert/save_xlsx/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett XlsX-dokument. |
| [save_txt](./convert/save_txt/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett Txt-dokument. |
| [save_pptx](./convert/save_pptx/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett PptX-dokument. |
| [save_xps](./convert/save_xps/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett Xps-dokument. |
| [save_tex](./convert/save_tex/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett TeX-dokument. |
| [save_epub](./convert/save_epub/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett Epub-dokument. |
| [save_booklet](./convert/save_booklet/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett häfte PDF-dokument. |
| [save_n_up](./convert/save_n_up/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett N-Up PDF-dokument. |
| [save_markdown](./convert/save_markdown/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett Markdown-dokument. |
| [save_tiff](./convert/save_tiff/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett Tiff-dokument. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett DocX-dokument med förbättrat igenkänningsläge (fullt redigerbara tabeller och stycken). |
| [save_svg_zip](./convert/save_svg_zip/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som ett SVG-arkiv. |
| [export_fdf](./convert/export_fdf/) | Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till ett FDF-dokument. |
| [export_xfdf](./convert/export_xfdf/) | Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till ett XFDF-dokument. |
| [export_xml](./convert/export_xml/) | Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till ett XML-dokument. |
| [page_to_jpg](./convert/page_to_jpg/) | Konvertera och spara den angivna sidan som en Jpg-bild. |
| [page_to_png](./convert/page_to_png/) | Konvertera och spara den angivna sidan som en Png-bild. |
| [page_to_bmp](./convert/page_to_bmp/) | Konvertera och spara den angivna sidan som en Bmp-bild. |
| [page_to_tiff](./convert/page_to_tiff/) | Konvertera och spara den angivna sidan som Tiff-bild. |
| [page_to_svg](./convert/page_to_svg/) | Konvertera och spara den angivna sidan som Svg-bild. |
| [page_to_pdf](./convert/page_to_pdf/) | Konvertera och spara den angivna sidan som PDF-dokument. |
| [page_to_dicom](./convert/page_to_dicom/) | Konvertera och spara den angivna sidan som DICOM-bild. |


## Organize PDF functions

| Funktion | Beskrivning |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Optimera PDF-dokumentets innehåll. |
| [optimize_resource](./organize/optimize_resource/) | Optimera resurserna i PDF-dokumentet. |
| [grayscale](./organize/grayscale/) | Konvertera PDF-dokument till svartvitt. |
| [rotate](./organize/rotate/) | Rotera PDF-dokument. |
| [set_background](./organize/set_background/) | Ställ in PDF-dokumentets bakgrundsfärg med RGB-värden. |
| [repair](./organize/repair/) | Reparera PDF-dokument. |
| [replace_text](./organize/replace_text/) | Ersätt text i PDF-dokument |
| [add_page_num](./organize/add_page_num/) | Lägg till sidnummer i ett PDF-dokument |
| [add_text_header](./organize/add_text_header/) | Lägg till text i rubriken på ett PDF-dokument |
| [add_text_footer](./organize/add_text_footer/) | Lägg till text i sidfoten på ett PDF-dokument |
| [flatten](./organize/flatten/) | Platta till PDF-dokument |
| [remove_annotations](./organize/remove_annotations/) | Ta bort annotationer från PDF-dokument |
| [remove_attachments](./organize/remove_attachments/) | Ta bort bilagor från PDF-dokument |
| [remove_blank_pages](./organize/remove_blank_pages/) | Ta bort tomma sidor från PDF-dokument |
| [remove_bookmarks](./organize/remove_bookmarks/) | Ta bort bokmärken från PDF-dokument |
| [remove_hidden_text](./organize/remove_hidden_text/) | Ta bort dold text från PDF-dokument |
| [remove_images](./organize/remove_images/) | Ta bort bilder från PDF-dokument |
| [remove_javascripts](./organize/remove_javascripts/) | Ta bort JavaScript från PDF-dokument |
| [remove_tables](./organize/remove_tables/) | Ta bort tabeller från ett PDF-dokument. |
| [remove_watermarks](./organize/remove_watermarks/) | Ta bort vattenstämplar från PDF-dokument. |
| [add_watermark](./organize/add_watermark/) | Lägg till vattenstämpel i PDF-dokument. |
| [embed_fonts](./organize/embed_fonts/) | Bädda in typsnitt i ett PDF-dokument. |
| [unembed_fonts](./organize/unembed_fonts/) | Ta bort inbäddade typsnitt i ett PDF-dokument. |
| [optimize_file_size](./organize/optimize_file_size/) | Optimera storleken på PDF-dokumentet med bildkomprimeringskvalitet. |
| [remove_text_headers](./organize/remove_text_headers/) | Ta bort textrubriker från PDF-dokumentet. |
| [remove_text_footers](./organize/remove_text_footers/) | Ta bort textsidfötter från PDF-dokumentet. |
| [crop](./organize/crop/) | Beskär sidor i ett PDF-dokument. |
| [replace_font](./organize/replace_font/) | Byt ut typsnitt i ett PDF-dokument. |
| [convert](./organize/convert/) | Konvertera ett PDF-dokument till ett PDF-dokument med det angivna PDF-formatet |
| [validate](./organize/validate/) | Validera ett PDF-dokument för efterlevnad av PDF-formatet |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Ta bort PDF/A-efterlevnad från ett PDF-dokument |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Ta bort PDF/UA-efterlevnad från ett PDF-dokument |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Kontrollera om ett PDF-dokument är PDF/A-kompatibelt |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Kontrollera om ett PDF-dokument är PDF/UA-kompatibelt |
| [page_rotate](./organize/page_rotate/) | Rotera en sida i PDF-dokumentet. |
| [page_set_size](./organize/page_set_size/) | Ställ in storleken på en sida i PDF-dokumentet. |
| [page_grayscale](./organize/page_grayscale/) | Konvertera sidan till svartvitt. |
| [page_add_text](./organize/page_add_text/) | Lägg till text på sidan. |
| [page_replace_text](./organize/page_replace_text/) | Byt ut text på sidan |
| [page_add_page_num](./organize/page_add_page_num/) | Lägg till sidnummer på sidan |
| [page_add_text_header](./organize/page_add_text_header/) | Lägg till text i sidhuvud |
| [page_add_text_footer](./organize/page_add_text_footer/) | Lägg till text i sidfot |
| [page_remove_annotations](./organize/page_remove_annotations/) | Ta bort annotationer på sidan. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Ta bort dold text på sidan. |
| [page_remove_images](./organize/page_remove_images/) | Ta bort bilder på sidan. |
| [page_remove_tables](./organize/page_remove_tables/) | Ta bort tabeller på sidan. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Ta bort vattenstämplar på sidan. |
| [page_add_watermark](./organize/page_add_watermark/) | Lägg till vattenstämpel på sidan. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Ta bort textrubriker på sidan. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Ta bort textfotnoter på sidan. |
| [page_crop](./organize/page_crop/) | Beskär en sida. |
| [page_replace_font](./organize/page_replace_font/) | Byt teckensnitt på sidan. |
| [page_merge_layers](./organize/page_merge_layers/) | Slå samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet. |
| [page_layers](./organize/page_layers/) | Hämta lagernamnen på sidan. |


## Core PDF functions

| Funktion | Beskrivning |
| -------- | ----------- |
| [new](./core/new/) | Skapa ett nytt PDF-dokument. |
| [open](./core/open/) | Öppna ett PDF-dokument med filnamn. |
| [save](./core/save/) | Spara det tidigare öppnade PDF-dokumentet. |
| [save_as](./core/save_as/) | Spara det tidigare öppnade PDF-dokumentet med nytt filnamn. |
| [set_license](./core/set_license/) | Ange licens med filnamn. |
| [extract_text](./core/extract_text/) | Returnera PDF-dokumentets innehåll som vanlig text. |
| [word_count](./core/word_count/) | Returnera antalet ord i PDF-dokumentet. |
| [character_count](./core/character_count/) | Returnera antalet tecken i PDF-dokumentet. |
| [append](./core/append/) | Lägg till sidor från ett annat PDF-dokument. |
| [append_pages](./core/append_pages/) | Lägg till valda sidor från ett annat PDF-dokument. |
| [merge_documents](./core/merge_documents/) | Skapa ett nytt PDF-dokument genom att slå samman de angivna PDF-dokumenten. |
| [split_document](./core/split_document/) | Skapa flera nya PDF-dokument genom att extrahera sidor från käll-PDF-dokumentet. |
| [split](./core/split/) | Skapa flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet. |
| [split_at_page](./core/split_at_page/) | Dela PDF-dokumentet i två nya PDF-dokument. |
| [split_at](./core/split_at/) | Dela det aktuella PDF-dokumentet i två nya PDF-dokument. |
| [bytes](./core/bytes/) | Returnera innehållet i PDF-dokumentet som en bytevektor. |
| [get_meta_info](./core/get_meta_info/) | Hämta metainformationsvärdet för PDF-dokumentet. |
| [set_meta_info](./core/set_meta_info/) | Ange metainformationsvärde för PDF-dokument. |
| [clear_meta_info](./core/clear_meta_info/) | Rensa alla metainformationsvärden för PDF-dokument. |
| [is_linearized](./core/is_linearized/) | Hämta ett värde som indikerar om dokumentet är lineariserat. |
| [page_add](./core/page_add/) | Lägg till en ny sida i PDF-dokument. |
| [page_insert](./core/page_insert/) | Infoga en ny sida på den angivna positionen i PDF-dokument. |
| [page_delete](./core/page_delete/) | Ta bort angiven sida i PDF-dokument. |
| [page_count](./core/page_count/) | Returnera antalet sidor i PDF-dokument. |
| [page_word_count](./core/page_word_count/) | Returnera ordantal på angiven sida i PDF-dokument. |
| [page_character_count](./core/page_character_count/) | Returnera teckenantal på angiven sida i PDF-dokument. |
| [page_is_blank](./core/page_is_blank/) | Returnera om sidan är tom i PDF-dokument. |


## Security
| Funktion | Beskrivning |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Öppna ett lösenordsskyddat PDF-dokument. |
| [encrypt](./security/encrypt/) | Kryptera PDF-dokument. |
| [decrypt](./security/decrypt/) | Dekryptera PDF-dokument. |
| [set_permissions](./security/set_permissions/) | Ange behörigheter för PDF-dokument. |
| [get_permissions](./security/get_permissions/) | Hämta aktuella behörigheter för PDF-dokument. |
| [is_encrypted](./security/is_encrypted/) | Hämta krypteringsstatus för PDF-dokument. |
| [sign_pkcs7](./security/sign_pkcs7/) | Signera ett PDF-dokument med PKCS#7 digitala signaturer. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Signera ett PDF-dokument med PKCS#7 fristående digitala signaturer. |
| [is_signed](./security/is_signed/) | Hämta signeringsstatus för PDF-dokument. |
| [remove_signs](./security/remove_signs/) | Ta bort signaturer från PDF-dokument. |


## Miscellaneous

| Funktion | Beskrivning |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Returnera metadatainformation om Aspose.PDF för Rust via C++. |



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
    /// Bitflag-uppsättning som representerar PDF-behörighetsfunktioner.
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
    /// A0-storlek.
    A0 = 0,
    /// A1-storlek.
    A1 = 1,
    /// A2-storlek.
    A2 = 2,
    /// A3 storlek.
    A3 = 3,
    /// A4 storlek.
    A4 = 4,
    /// A5 storlek.
    A5 = 5,
    /// A6 storlek.
    A6 = 6,
    /// B5 storlek.
    B5 = 7,
    /// PageLetter storlek.
    PageLetter = 8,
    /// PageLegal storlek.
    PageLegal = 9,
    /// PageLedger storlek.
    PageLedger = 10,
    /// P11x17 storlek.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Ej roterad.
    None = 0,
    /// Roterad 90 grader medurs.
    On90 = 1,
    /// Roterad 180 grader.
    On180 = 2,
    /// Roterad 270 grader medurs.
    On270 = 3,
    /// Roterad 360 grader medurs.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 med nyckellängd 40.
    RC4x40 = 0,
    /// RC4 med nyckellängd 128.
    RC4x128 = 1,
    /// AES med nyckellängd 128.
    AESx128 = 2,
    /// AES med nyckellängd 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// PDF/A-1a format.
    PDF_A_1A = 0,
    /// PDF/A-1b format.
    PDF_A_1B = 1,
    /// PDF/A-2a format.
    PDF_A_2A = 2,
    /// PDF/A-3a format.
    PDF_A_3A = 3,
    /// PDF/A-2b format.
    PDF_A_2B = 4,
    /// PDF/A-2u format.
    PDF_A_2U = 5,
    /// PDF/A-3b format.
    PDF_A_3B = 6,
    /// PDF/A-3u-format.
    PDF_A_3U = 7,
    /// Adobe version 1.0.
    V_1_0 = 8,
    /// Adobe version 1.1.
    V_1_1 = 9,
    /// Adobe version 1.2.
    V_1_2 = 10,
    /// Adobe version 1.3.
    V_1_3 = 11,
    /// Adobe version 1.4.
    V_1_4 = 12,
    /// Adobe version 1.5.
    V_1_5 = 13,
    /// Adobe version 1.6.
    V_1_6 = 14,
    /// Adobe version 1.7.
    V_1_7 = 15,
    /// ISO-standard PDF 2.0.
    V_2_0 = 16,
    /// PDF/UA-1-format.
    PDF_UA_1 = 17,
    /// PDF/X-1a:2001-format.
    PDF_X_1A_2001 = 18,
    /// PDF/X-1a-format.
    PDF_X_1A = 19,
    /// PDF/X-3-format.
    PDF_X_3 = 20,
    /// ZUGFeRD-format.
    ZUGFeRD = 21,
    /// PDF/A-4-format.
    PDF_A_4 = 22,
    /// PDF/A-4e-format.
    PDF_A_4E = 23,
    /// PDF/A-4f-format.
    PDF_A_4F = 24,
    /// PDF/X-4-format.
    PDF_X_4 = 25,
    /// PDF/E-1 (PDF 1.6)-format.
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Ta bort icke‑konformerande element.
    Delete = 0,
    /// Gör ingenting, behåll icke‑konformerande element.
    None = 1,
}
```

