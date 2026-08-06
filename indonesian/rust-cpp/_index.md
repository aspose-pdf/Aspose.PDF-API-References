---
title: "Aspose.PDF untuk Rust via C++"
description: "Aspose.PDF untuk Rust via C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /id/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Struktur

## Document
Dokumen mewakili PDF-document.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Fungsi | Deskripsi |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai DocX-document. |
| [save_doc](./convert/save_doc/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Doc-document. |
| [save_xlsx](./convert/save_xlsx/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai XlsX-document. |
| [save_txt](./convert/save_txt/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Txt-document. |
| [save_pptx](./convert/save_pptx/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai PptX-document. |
| [save_xps](./convert/save_xps/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Xps-document. |
| [save_tex](./convert/save_tex/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai TeX-document. |
| [save_epub](./convert/save_epub/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Epub-document. |
| [save_booklet](./convert/save_booklet/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai booklet PDF-document. |
| [save_n_up](./convert/save_n_up/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai N-Up PDF-document. |
| [save_markdown](./convert/save_markdown/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Markdown-document. |
| [save_tiff](./convert/save_tiff/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Tiff-document. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai DocX-document dengan Mode Pengakuan Tingkat Lanjut (tabel dan paragraf dapat diedit sepenuhnya). |
| [save_svg_zip](./convert/save_svg_zip/) | Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai SVG-archive. |
| [export_fdf](./convert/export_fdf/) | Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke FDF-document. |
| [export_xfdf](./convert/export_xfdf/) | Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document. |
| [export_xml](./convert/export_xml/) | Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XML-document. |
| [page_to_jpg](./convert/page_to_jpg/) | Konversi dan simpan halaman yang ditentukan sebagai Jpg-image. |
| [page_to_png](./convert/page_to_png/) | Konversi dan simpan halaman yang ditentukan sebagai Png-image. |
| [page_to_bmp](./convert/page_to_bmp/) | Konversi dan simpan halaman yang ditentukan sebagai Bmp-image. |
| [page_to_tiff](./convert/page_to_tiff/) | Konversi dan simpan halaman yang ditentukan sebagai Tiff-image. |
| [page_to_svg](./convert/page_to_svg/) | Konversi dan simpan halaman yang ditentukan sebagai Svg-image. |
| [page_to_pdf](./convert/page_to_pdf/) | Konversi dan simpan halaman yang ditentukan sebagai PDF-document. |
| [page_to_dicom](./convert/page_to_dicom/) | Konversi dan simpan halaman yang ditentukan sebagai DICOM-image. |


## Organize PDF functions

| Fungsi | Deskripsi |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Optimalkan konten PDF-document. |
| [optimize_resource](./organize/optimize_resource/) | Optimalkan sumber daya PDF-document. |
| [grayscale](./organize/grayscale/) | Konversi PDF-document menjadi hitam putih. |
| [rotate](./organize/rotate/) | Putar PDF-document. |
| [set_background](./organize/set_background/) | Atur warna latar belakang PDF-document menggunakan nilai RGB. |
| [repair](./organize/repair/) | Perbaiki PDF-document. |
| [replace_text](./organize/replace_text/) | Ganti teks dalam PDF-document |
| [add_page_num](./organize/add_page_num/) | Tambahkan nomor halaman ke PDF-document |
| [add_text_header](./organize/add_text_header/) | Tambahkan teks di Header PDF-document |
| [add_text_footer](./organize/add_text_footer/) | Tambahkan teks di Footer PDF-document |
| [flatten](./organize/flatten/) | Ratakan PDF-document |
| [remove_annotations](./organize/remove_annotations/) | Hapus anotasi dari PDF-document |
| [remove_attachments](./organize/remove_attachments/) | Hapus lampiran dari PDF-document |
| [remove_blank_pages](./organize/remove_blank_pages/) | Hapus halaman kosong dari PDF-document |
| [remove_bookmarks](./organize/remove_bookmarks/) | Hapus bookmark dari PDF-document |
| [remove_hidden_text](./organize/remove_hidden_text/) | Hapus teks tersembunyi dari PDF-document |
| [remove_images](./organize/remove_images/) | Hapus gambar dari PDF-document |
| [remove_javascripts](./organize/remove_javascripts/) | Hapus skrip java dari PDF-document |
| [remove_tables](./organize/remove_tables/) | Hapus tabel dari PDF-document. |
| [remove_watermarks](./organize/remove_watermarks/) | Hapus watermark dari PDF-document. |
| [add_watermark](./organize/add_watermark/) | Tambahkan watermark ke PDF-document. |
| [embed_fonts](./organize/embed_fonts/) | Sematkan font pada PDF-document. |
| [unembed_fonts](./organize/unembed_fonts/) | Hapus penyematan font pada PDF-document. |
| [optimize_file_size](./organize/optimize_file_size/) | Optimalkan ukuran PDF-document dengan kualitas kompresi gambar. |
| [remove_text_headers](./organize/remove_text_headers/) | Hapus header teks dari PDF-document. |
| [remove_text_footers](./organize/remove_text_footers/) | Hapus footer teks dari PDF-document. |
| [crop](./organize/crop/) | Potong halaman PDF-document. |
| [replace_font](./organize/replace_font/) | Ganti font dalam PDF-document. |
| [convert](./organize/convert/) | Konversi PDF-document menjadi PDF-document dengan format PDF yang ditentukan |
| [validate](./organize/validate/) | Validasi PDF-document untuk kepatuhan terhadap format PDF |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Hapus kepatuhan PDF/A dari PDF-document |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Hapus kepatuhan PDF/UA dari PDF-document |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Dapatkan apakah PDF-document mematuhi PDF/A |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Dapatkan apakah PDF-document mematuhi PDF/UA |
| [page_rotate](./organize/page_rotate/) | Putar halaman dalam PDF-document. |
| [page_set_size](./organize/page_set_size/) | Atur ukuran halaman dalam PDF-document. |
| [page_grayscale](./organize/page_grayscale/) | Konversi halaman menjadi hitam putih. |
| [page_add_text](./organize/page_add_text/) | Tambahkan teks pada halaman. |
| [page_replace_text](./organize/page_replace_text/) | Ganti teks pada halaman |
| [page_add_page_num](./organize/page_add_page_num/) | Tambahkan nomor halaman pada halaman |
| [page_add_text_header](./organize/page_add_text_header/) | Tambahkan teks di header halaman |
| [page_add_text_footer](./organize/page_add_text_footer/) | Tambahkan teks di footer halaman |
| [page_remove_annotations](./organize/page_remove_annotations/) | Hapus anotasi di halaman. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Hapus teks tersembunyi di halaman. |
| [page_remove_images](./organize/page_remove_images/) | Hapus gambar di halaman. |
| [page_remove_tables](./organize/page_remove_tables/) | Hapus tabel di halaman. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Hapus watermark pada halaman. |
| [page_add_watermark](./organize/page_add_watermark/) | Tambahkan watermark pada halaman. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Hapus header teks pada halaman. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Hapus footer teks pada halaman. |
| [page_crop](./organize/page_crop/) | Potong sebuah halaman. |
| [page_replace_font](./organize/page_replace_font/) | Ganti font pada halaman. |
| [page_merge_layers](./organize/page_merge_layers/) | Gabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan. |
| [page_layers](./organize/page_layers/) | Dapatkan nama-nama lapisan pada halaman. |


## Core PDF functions

| Fungsi | Deskripsi |
| -------- | ----------- |
| [new](./core/new/) | Buat dokumen PDF baru. |
| [open](./core/open/) | Buka dokumen PDF dengan nama file. |
| [save](./core/save/) | Simpan dokumen PDF yang sebelumnya dibuka. |
| [save_as](./core/save_as/) | Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru. |
| [set_license](./core/set_license/) | Atur lisensi dengan nama file. |
| [extract_text](./core/extract_text/) | Kembalikan isi dokumen PDF sebagai teks biasa. |
| [word_count](./core/word_count/) | Kembalikan jumlah kata dalam dokumen PDF. |
| [character_count](./core/character_count/) | Kembalikan jumlah karakter dalam dokumen PDF. |
| [append](./core/append/) | Tambahkan halaman dari dokumen PDF lain. |
| [append_pages](./core/append_pages/) | Tambahkan halaman terpilih dari dokumen PDF lain. |
| [merge_documents](./core/merge_documents/) | Buat dokumen PDF baru dengan menggabungkan dokumen PDF yang disediakan. |
| [split_document](./core/split_document/) | Buat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF sumber. |
| [split](./core/split/) | Buat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF saat ini. |
| [split_at_page](./core/split_at_page/) | Pisahkan dokumen PDF menjadi dua dokumen PDF baru. |
| [split_at](./core/split_at/) | Pisahkan dokumen PDF saat ini menjadi dua dokumen PDF baru. |
| [bytes](./core/bytes/) | Kembalikan isi dokumen PDF sebagai vektor byte. |
| [get_meta_info](./core/get_meta_info/) | Dapatkan nilai informasi meta dokumen PDF. |
| [set_meta_info](./core/set_meta_info/) | Atur nilai informasi meta dari dokumen PDF. |
| [clear_meta_info](./core/clear_meta_info/) | Kosongkan semua nilai informasi meta dari dokumen PDF. |
| [is_linearized](./core/is_linearized/) | Dapatkan nilai yang menunjukkan apakah dokumen terlinier. |
| [page_add](./core/page_add/) | Tambahkan halaman baru dalam dokumen PDF. |
| [page_insert](./core/page_insert/) | Sisipkan halaman baru pada posisi yang ditentukan dalam dokumen PDF. |
| [page_delete](./core/page_delete/) | Hapus halaman yang ditentukan dalam dokumen PDF. |
| [page_count](./core/page_count/) | Kembalikan jumlah halaman dalam dokumen PDF. |
| [page_word_count](./core/page_word_count/) | Kembalikan jumlah kata pada halaman yang ditentukan dalam dokumen PDF. |
| [page_character_count](./core/page_character_count/) | Kembalikan jumlah karakter pada halaman yang ditentukan dalam dokumen PDF. |
| [page_is_blank](./core/page_is_blank/) | Kembalikan apakah halaman kosong dalam dokumen PDF. |


## Security
| Fungsi | Deskripsi |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Buka dokumen PDF yang dilindungi kata sandi. |
| [encrypt](./security/encrypt/) | Enkripsi dokumen PDF. |
| [decrypt](./security/decrypt/) | Dekripsi dokumen PDF. |
| [set_permissions](./security/set_permissions/) | Atur izin untuk dokumen PDF. |
| [get_permissions](./security/get_permissions/) | Dapatkan izin saat ini dari dokumen PDF. |
| [is_encrypted](./security/is_encrypted/) | Dapatkan status terenkripsi dari dokumen PDF. |
| [sign_pkcs7](./security/sign_pkcs7/) | Tandatangani dokumen PDF menggunakan tanda tangan digital PKCS#7. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Tandatangani dokumen PDF menggunakan tanda tangan digital PKCS#7 Terpisah. |
| [is_signed](./security/is_signed/) | Dapatkan status tertanda pada dokumen PDF. |
| [remove_signs](./security/remove_signs/) | Hapus tanda dari dokumen PDF. |


## Miscellaneous

| Fungsi | Deskripsi |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Kembalikan informasi metadata tentang Aspose.PDF untuk Rust melalui C++. |



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
    /// Set bitflag yang mewakili kemampuan izin PDF.
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
    /// Ukuran A0.
    A0 = 0,
    /// Ukuran A1.
    A1 = 1,
    /// Ukuran A2.
    A2 = 2,
    /// ukuran A3.
    A3 = 3,
    /// ukuran A4.
    A4 = 4,
    /// ukuran A5.
    A5 = 5,
    /// ukuran A6.
    A6 = 6,
    /// ukuran B5.
    B5 = 7,
    /// ukuran PageLetter.
    PageLetter = 8,
    /// ukuran PageLegal.
    PageLegal = 9,
    /// ukuran PageLedger.
    PageLedger = 10,
    /// ukuran P11x17.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Tidak diputar.
    None = 0,
    /// Diputar 90 derajat searah jarum jam.
    On90 = 1,
    /// Diputar 180 derajat.
    On180 = 2,
    /// Diputar 270 derajat searah jarum jam.
    On270 = 3,
    /// Diputar 360 derajat searah jarum jam.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 dengan panjang kunci 40.
    RC4x40 = 0,
    /// RC4 dengan panjang kunci 128.
    RC4x128 = 1,
    /// AES dengan panjang kunci 128.
    AESx128 = 2,
    /// AES dengan panjang kunci 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// format PDF/A-1a.
    PDF_A_1A = 0,
    /// format PDF/A-1b.
    PDF_A_1B = 1,
    /// format PDF/A-2a.
    PDF_A_2A = 2,
    /// format PDF/A-3a.
    PDF_A_3A = 3,
    /// format PDF/A-2b.
    PDF_A_2B = 4,
    /// format PDF/A-2u.
    PDF_A_2U = 5,
    /// format PDF/A-3b.
    PDF_A_3B = 6,
    /// format PDF/A-3u.
    PDF_A_3U = 7,
    /// Versi Adobe 1.0.
    V_1_0 = 8,
    /// Versi Adobe 1.1.
    V_1_1 = 9,
    /// Versi Adobe 1.2.
    V_1_2 = 10,
    /// Versi Adobe 1.3.
    V_1_3 = 11,
    /// Versi Adobe 1.4.
    V_1_4 = 12,
    /// Versi Adobe 1.5.
    V_1_5 = 13,
    /// Versi Adobe 1.6.
    V_1_6 = 14,
    /// Versi Adobe 1.7.
    V_1_7 = 15,
    /// Standar ISO PDF 2.0.
    V_2_0 = 16,
    /// format PDF/UA-1.
    PDF_UA_1 = 17,
    /// format PDF/X-1a:2001.
    PDF_X_1A_2001 = 18,
    /// format PDF/X-1a.
    PDF_X_1A = 19,
    /// format PDF/X-3.
    PDF_X_3 = 20,
    /// format ZUGFeRD.
    ZUGFeRD = 21,
    /// format PDF/A-4.
    PDF_A_4 = 22,
    /// format PDF/A-4e.
    PDF_A_4E = 23,
    /// format PDF/A-4f.
    PDF_A_4F = 24,
    /// format PDF/X-4.
    PDF_X_4 = 25,
    /// format PDF/E-1 (PDF 1.6).
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Hapus elemen yang tidak sesuai.
    Delete = 0,
    /// Tidak melakukan apa pun, pertahankan elemen yang tidak sesuai.
    None = 1,
}
```

