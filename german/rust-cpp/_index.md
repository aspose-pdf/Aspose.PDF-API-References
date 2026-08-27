---
title: "Aspose.PDF für Rust über C++"
description: "Aspose.PDF für Rust über C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /de/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Strukturen

## Document
Dokument stellt ein PDF-document dar.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Funktion | Beschreibung |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als DocX-document. |
| [save_doc](./convert/save_doc/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als Doc-document. |
| [save_xlsx](./convert/save_xlsx/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als XlsX-document. |
| [save_txt](./convert/save_txt/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als Txt-document. |
| [save_pptx](./convert/save_pptx/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als PptX-document. |
| [save_xps](./convert/save_xps/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als Xps-document. |
| [save_tex](./convert/save_tex/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als TeX-document. |
| [save_epub](./convert/save_epub/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als Epub-document. |
| [save_booklet](./convert/save_booklet/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als booklet PDF-document. |
| [save_n_up](./convert/save_n_up/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als N-Up PDF-document. |
| [save_markdown](./convert/save_markdown/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als Markdown-document. |
| [save_tiff](./convert/save_tiff/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als Tiff-document. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als DocX-document mit erweitertem Erkennungsmodus (vollständig editierbare Tabellen und Absätze). |
| [save_svg_zip](./convert/save_svg_zip/) | Konvertieren und speichern Sie das zuvor geöffnete PDF-document als SVG-Archiv. |
| [export_fdf](./convert/export_fdf/) | Exportieren Sie aus dem zuvor geöffneten PDF-document mit AcroForm zu FDF-document. |
| [export_xfdf](./convert/export_xfdf/) | Exportieren Sie aus dem zuvor geöffneten PDF-document mit AcroForm zu XFDF-document. |
| [export_xml](./convert/export_xml/) | Exportieren Sie aus dem zuvor geöffneten PDF-document mit AcroForm zu XML-document. |
| [page_to_jpg](./convert/page_to_jpg/) | Konvertieren und speichern Sie die angegebene Seite als Jpg-Bild. |
| [page_to_png](./convert/page_to_png/) | Konvertieren und speichern Sie die angegebene Seite als Png-Bild. |
| [page_to_bmp](./convert/page_to_bmp/) | Konvertieren und speichern Sie die angegebene Seite als Bmp-Bild. |
| [page_to_tiff](./convert/page_to_tiff/) | Konvertieren und speichern Sie die angegebene Seite als Tiff-Bild. |
| [page_to_svg](./convert/page_to_svg/) | Konvertieren und speichern Sie die angegebene Seite als Svg-Bild. |
| [page_to_pdf](./convert/page_to_pdf/) | Konvertieren und speichern Sie die angegebene Seite als PDF-Dokument. |
| [page_to_dicom](./convert/page_to_dicom/) | Konvertieren und speichern Sie die angegebene Seite als DICOM-Bild. |


## Organize PDF functions

| Funktion | Beschreibung |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Optimieren Sie den Inhalt des PDF-Dokuments. |
| [optimize_resource](./organize/optimize_resource/) | Optimieren Sie die Ressourcen des PDF-Dokuments. |
| [grayscale](./organize/grayscale/) | Konvertieren Sie das PDF-Dokument in Schwarzweiß. |
| [rotate](./organize/rotate/) | Drehen Sie das PDF-Dokument. |
| [set_background](./organize/set_background/) | Legen Sie die Hintergrundfarbe des PDF-Dokuments mit RGB-Werten fest. |
| [repair](./organize/repair/) | Reparieren Sie das PDF-Dokument. |
| [replace_text](./organize/replace_text/) | Ersetzen Sie Text im PDF-Dokument |
| [add_page_num](./organize/add_page_num/) | Fügen Sie einem PDF-Dokument eine Seitenzahl hinzu |
| [add_text_header](./organize/add_text_header/) | Fügen Sie Text in die Kopfzeile eines PDF-Dokuments ein |
| [add_text_footer](./organize/add_text_footer/) | Fügen Sie Text in die Fußzeile eines PDF-Dokuments ein |
| [flatten](./organize/flatten/) | PDF-Dokument flachlegen |
| [remove_annotations](./organize/remove_annotations/) | Entfernen Sie Anmerkungen aus dem PDF-Dokument |
| [remove_attachments](./organize/remove_attachments/) | Entfernen Sie Anhänge aus dem PDF-Dokument |
| [remove_blank_pages](./organize/remove_blank_pages/) | Entfernen Sie leere Seiten aus dem PDF-Dokument |
| [remove_bookmarks](./organize/remove_bookmarks/) | Entfernen Sie Lesezeichen aus dem PDF-Dokument |
| [remove_hidden_text](./organize/remove_hidden_text/) | Entfernen Sie versteckten Text aus dem PDF-Dokument |
| [remove_images](./organize/remove_images/) | Entfernen Sie Bilder aus dem PDF-Dokument |
| [remove_javascripts](./organize/remove_javascripts/) | Entfernen Sie JavaScript aus dem PDF-Dokument |
| [remove_tables](./organize/remove_tables/) | Entfernen Sie Tabellen aus einem PDF-Dokument. |
| [remove_watermarks](./organize/remove_watermarks/) | Entfernen Sie Wasserzeichen aus dem PDF-Dokument. |
| [add_watermark](./organize/add_watermark/) | Fügen Sie ein Wasserzeichen zum PDF-Dokument hinzu. |
| [embed_fonts](./organize/embed_fonts/) | Schriftarten in ein PDF-Dokument einbetten. |
| [unembed_fonts](./organize/unembed_fonts/) | Schriftarten aus einem PDF-Dokument entfernen. |
| [optimize_file_size](./organize/optimize_file_size/) | Größe des PDF-Dokuments mit Bildkomprimierungsqualität optimieren. |
| [remove_text_headers](./organize/remove_text_headers/) | Textkopfzeilen aus dem PDF-Dokument entfernen. |
| [remove_text_footers](./organize/remove_text_footers/) | Textfußzeilen aus dem PDF-Dokument entfernen. |
| [crop](./organize/crop/) | Seiten eines PDF-Dokuments zuschneiden. |
| [replace_font](./organize/replace_font/) | Schriftart in einem PDF-Dokument ersetzen. |
| [convert](./organize/convert/) | Ein PDF-Dokument in ein PDF-Dokument mit dem angegebenen PDF-Format konvertieren |
| [validate](./organize/validate/) | Ein PDF-Dokument auf Konformität mit dem PDF-Format prüfen |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | PDF/A-Konformität aus einem PDF-Dokument entfernen |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | PDF/UA-Konformität aus einem PDF-Dokument entfernen |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Ermitteln, ob ein PDF-Dokument PDF/A-konform ist |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Ermitteln, ob ein PDF-Dokument PDF/UA-konform ist |
| [page_rotate](./organize/page_rotate/) | Eine Seite im PDF-Dokument drehen. |
| [page_set_size](./organize/page_set_size/) | Die Größe einer Seite im PDF-Dokument festlegen. |
| [page_grayscale](./organize/page_grayscale/) | Seite in Schwarzweiß konvertieren. |
| [page_add_text](./organize/page_add_text/) | Text auf der Seite hinzufügen. |
| [page_replace_text](./organize/page_replace_text/) | Text auf der Seite ersetzen |
| [page_add_page_num](./organize/page_add_page_num/) | Seitennummer auf der Seite hinzufügen |
| [page_add_text_header](./organize/page_add_text_header/) | Text in der Seitenkopfzeile hinzufügen |
| [page_add_text_footer](./organize/page_add_text_footer/) | Text in der Seitenfußzeile hinzufügen |
| [page_remove_annotations](./organize/page_remove_annotations/) | Anmerkungen auf der Seite entfernen. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Versteckten Text auf der Seite entfernen. |
| [page_remove_images](./organize/page_remove_images/) | Bilder auf der Seite entfernen. |
| [page_remove_tables](./organize/page_remove_tables/) | Tabellen auf der Seite entfernen. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Wasserzeichen auf der Seite entfernen. |
| [page_add_watermark](./organize/page_add_watermark/) | Wasserzeichen auf der Seite hinzufügen. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Textkopfzeilen auf der Seite entfernen. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Textfußzeilen auf der Seite entfernen. |
| [page_crop](./organize/page_crop/) | Eine Seite zuschneiden. |
| [page_replace_font](./organize/page_replace_font/) | Schriftart auf der Seite ersetzen. |
| [page_merge_layers](./organize/page_merge_layers/) | Alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammenführen. |
| [page_layers](./organize/page_layers/) | Namen der Ebenen auf der Seite abrufen. |


## Core PDF functions

| Funktion | Beschreibung |
| -------- | ----------- |
| [new](./core/new/) | Ein neues PDF-Dokument erstellen. |
| [open](./core/open/) | Ein PDF-Dokument mit Dateinamen öffnen. |
| [save](./core/save/) | Das zuvor geöffnete PDF-Dokument speichern. |
| [save_as](./core/save_as/) | Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern. |
| [set_license](./core/set_license/) | Lizenz mit Dateinamen festlegen. |
| [extract_text](./core/extract_text/) | Den Inhalt des PDF-Dokuments als Klartext zurückgeben. |
| [word_count](./core/word_count/) | Wortanzahl im PDF-Dokument zurückgeben. |
| [character_count](./core/character_count/) | Zeichenanzahl im PDF-Dokument zurückgeben. |
| [append](./core/append/) | Seiten aus einem anderen PDF-Dokument anhängen. |
| [append_pages](./core/append_pages/) | Ausgewählte Seiten aus einem anderen PDF-Dokument anhängen. |
| [merge_documents](./core/merge_documents/) | Ein neues PDF-Dokument erstellen, indem die bereitgestellten PDF-Dokumente zusammengeführt werden. |
| [split_document](./core/split_document/) | Mehrere neue PDF-Dokumente erstellen, indem Seiten aus dem Quell-PDF-Dokument extrahiert werden. |
| [split](./core/split/) | Mehrere neue PDF-Dokumente erstellen, indem Seiten aus dem aktuellen PDF-Dokument extrahiert werden. |
| [split_at_page](./core/split_at_page/) | Das PDF-Dokument in zwei neue PDF-Dokumente aufteilen. |
| [split_at](./core/split_at/) | Das aktuelle PDF-Dokument in zwei neue PDF-Dokumente aufteilen. |
| [bytes](./core/bytes/) | Den Inhalt des PDF-Dokuments als Byte-Vektor zurückgeben. |
| [get_meta_info](./core/get_meta_info/) | Metainformationswert des PDF-Dokuments abrufen. |
| [set_meta_info](./core/set_meta_info/) | Setze den Meta-Informationswert des PDF-Dokuments. |
| [clear_meta_info](./core/clear_meta_info/) | Lösche alle Meta-Informationswerte des PDF-Dokuments. |
| [is_linearized](./core/is_linearized/) | Erhalte einen Wert, der angibt, ob das Dokument linearisiert ist. |
| [page_add](./core/page_add/) | Füge eine neue Seite im PDF-Dokument hinzu. |
| [page_insert](./core/page_insert/) | Füge eine neue Seite an der angegebenen Position im PDF-Dokument ein. |
| [page_delete](./core/page_delete/) | Lösche die angegebene Seite im PDF-Dokument. |
| [page_count](./core/page_count/) | Gib die Anzahl der Seiten im PDF-Dokument zurück. |
| [page_word_count](./core/page_word_count/) | Gib die Wortanzahl auf der angegebenen Seite im PDF-Dokument zurück. |
| [page_character_count](./core/page_character_count/) | Gib die Zeichenanzahl auf der angegebenen Seite im PDF-Dokument zurück. |
| [page_is_blank](./core/page_is_blank/) | Gib zurück, ob die Seite im PDF-Dokument leer ist. |


## Security
| Funktion | Beschreibung |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Öffne ein passwortgeschütztes PDF-Dokument. |
| [encrypt](./security/encrypt/) | Verschlüssele das PDF-Dokument. |
| [decrypt](./security/decrypt/) | Entschlüssele das PDF-Dokument. |
| [set_permissions](./security/set_permissions/) | Setze Berechtigungen für das PDF-Dokument. |
| [get_permissions](./security/get_permissions/) | Erhalte die aktuellen Berechtigungen des PDF-Dokuments. |
| [is_encrypted](./security/is_encrypted/) | Erhalte den verschlüsselten Status des PDF-Dokuments. |
| [sign_pkcs7](./security/sign_pkcs7/) | Signiere ein PDF-Dokument mit PKCS#7-Digitalsignaturen. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Signiere ein PDF-Dokument mit PKCS#7-Detached-Digitalsignaturen. |
| [is_signed](./security/is_signed/) | Erhalte den signierten Status des PDF-Dokuments. |
| [remove_signs](./security/remove_signs/) | Entferne Signaturen vom PDF-Dokument. |


## Miscellaneous

| Funktion | Beschreibung |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Gib Metadateninformationen über Aspose.PDF für Rust via C++ zurück. |



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
    /// Bitflag-Set, das PDF-Berechtigungsfähigkeiten darstellt.
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
    /// A0-Größe.
    A0 = 0,
    /// A1-Größe.
    A1 = 1,
    /// A2-Größe.
    A2 = 2,
    /// A3 Größe.
    A3 = 3,
    /// A4 Größe.
    A4 = 4,
    /// A5 Größe.
    A5 = 5,
    /// A6 Größe.
    A6 = 6,
    /// B5 Größe.
    B5 = 7,
    /// PageLetter Größe.
    PageLetter = 8,
    /// PageLegal Größe.
    PageLegal = 9,
    /// PageLedger Größe.
    PageLedger = 10,
    /// P11x17 Größe.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Nicht rotiert.
    None = 0,
    /// Um 90 Grad im Uhrzeigersinn rotiert.
    On90 = 1,
    /// Um 180 Grad rotiert.
    On180 = 2,
    /// Um 270 Grad im Uhrzeigersinn rotiert.
    On270 = 3,
    /// Um 360 Grad im Uhrzeigersinn rotiert.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 mit Schlüssellänge 40.
    RC4x40 = 0,
    /// RC4 mit Schlüssellänge 128.
    RC4x128 = 1,
    /// AES mit Schlüssellänge 128.
    AESx128 = 2,
    /// AES mit Schlüssellänge 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// PDF/A-1a Format.
    PDF_A_1A = 0,
    /// PDF/A-1b Format.
    PDF_A_1B = 1,
    /// PDF/A-2a Format.
    PDF_A_2A = 2,
    /// PDF/A-3a Format.
    PDF_A_3A = 3,
    /// PDF/A-2b Format.
    PDF_A_2B = 4,
    /// PDF/A-2u Format.
    PDF_A_2U = 5,
    /// PDF/A-3b Format.
    PDF_A_3B = 6,
    /// PDF/A-3u-Format.
    PDF_A_3U = 7,
    /// Adobe-Version 1.0.
    V_1_0 = 8,
    /// Adobe-Version 1.1.
    V_1_1 = 9,
    /// Adobe-Version 1.2.
    V_1_2 = 10,
    /// Adobe-Version 1.3.
    V_1_3 = 11,
    /// Adobe-Version 1.4.
    V_1_4 = 12,
    /// Adobe-Version 1.5.
    V_1_5 = 13,
    /// Adobe-Version 1.6.
    V_1_6 = 14,
    /// Adobe-Version 1.7.
    V_1_7 = 15,
    /// ISO-Standard PDF 2.0.
    V_2_0 = 16,
    /// PDF/UA-1-Format.
    PDF_UA_1 = 17,
    /// PDF/X-1a:2001-Format.
    PDF_X_1A_2001 = 18,
    /// PDF/X-1a-Format.
    PDF_X_1A = 19,
    /// PDF/X-3-Format.
    PDF_X_3 = 20,
    /// ZUGFeRD-Format.
    ZUGFeRD = 21,
    /// PDF/A-4-Format.
    PDF_A_4 = 22,
    /// PDF/A-4e-Format.
    PDF_A_4E = 23,
    /// PDF/A-4f-Format.
    PDF_A_4F = 24,
    /// PDF/X-4-Format.
    PDF_X_4 = 25,
    /// PDF/E-1 (PDF 1.6)-Format.
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Nicht konforme Elemente löschen.
    Delete = 0,
    /// Nichts tun, nicht konforme Elemente behalten.
    None = 1,
}
```

