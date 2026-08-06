---
title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Rust için C++ aracılığıyla Aspose.PDF"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /tr/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Yapılar

## Document
Document bir PDF belgesini temsil eder.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Fonksiyon | Açıklama |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Önceden açılmış PDF belgesini DocX belgesi olarak dönüştür ve kaydet. |
| [save_doc](./convert/save_doc/) | Önceden açılmış PDF belgesini Doc belgesi olarak dönüştür ve kaydet. |
| [save_xlsx](./convert/save_xlsx/) | Önceden açılmış PDF belgesini XlsX belgesi olarak dönüştür ve kaydet. |
| [save_txt](./convert/save_txt/) | Önceden açılmış PDF belgesini Txt belgesi olarak dönüştür ve kaydet. |
| [save_pptx](./convert/save_pptx/) | Önceden açılmış PDF belgesini PptX belgesi olarak dönüştür ve kaydet. |
| [save_xps](./convert/save_xps/) | Önceden açılmış PDF belgesini Xps belgesi olarak dönüştür ve kaydet. |
| [save_tex](./convert/save_tex/) | Önceden açılmış PDF belgesini TeX belgesi olarak dönüştür ve kaydet. |
| [save_epub](./convert/save_epub/) | Önceden açılmış PDF belgesini Epub belgesi olarak dönüştür ve kaydet. |
| [save_booklet](./convert/save_booklet/) | Önceden açılmış PDF belgesini kitapçık PDF belgesi olarak dönüştür ve kaydet. |
| [save_n_up](./convert/save_n_up/) | Önceden açılmış PDF belgesini N-Up PDF belgesi olarak dönüştür ve kaydet. |
| [save_markdown](./convert/save_markdown/) | Önceden açılmış PDF belgesini Markdown belgesi olarak dönüştür ve kaydet. |
| [save_tiff](./convert/save_tiff/) | Önceden açılmış PDF belgesini Tiff belgesi olarak dönüştür ve kaydet. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Önceden açılmış PDF belgesini Gelişmiş Tanıma Modu ile DocX belgesi olarak dönüştür ve kaydet (tamamen düzenlenebilir tablolar ve paragraflar). |
| [save_svg_zip](./convert/save_svg_zip/) | Önceden açılmış PDF belgesini SVG arşivi olarak dönüştür ve kaydet. |
| [export_fdf](./convert/export_fdf/) | AcroForm içeren önceden açılmış PDF belgesini FDF belgesine dışa aktar. |
| [export_xfdf](./convert/export_xfdf/) | AcroForm içeren önceden açılmış PDF belgesini XFDF belgesine dışa aktar. |
| [export_xml](./convert/export_xml/) | AcroForm içeren önceden açılmış PDF belgesini XML belgesine dışa aktar. |
| [page_to_jpg](./convert/page_to_jpg/) | Belirtilen sayfayı Jpg görüntüsü olarak dönüştür ve kaydet. |
| [page_to_png](./convert/page_to_png/) | Belirtilen sayfayı Png görüntüsü olarak dönüştür ve kaydet. |
| [page_to_bmp](./convert/page_to_bmp/) | Belirtilen sayfayı Bmp görüntüsü olarak dönüştür ve kaydet. |
| [page_to_tiff](./convert/page_to_tiff/) | Belirtilen sayfayı Tiff-görüntüsü olarak dönüştür ve kaydet. |
| [page_to_svg](./convert/page_to_svg/) | Belirtilen sayfayı Svg-görüntüsü olarak dönüştür ve kaydet. |
| [page_to_pdf](./convert/page_to_pdf/) | Belirtilen sayfayı PDF-dokümanı olarak dönüştür ve kaydet. |
| [page_to_dicom](./convert/page_to_dicom/) | Belirtilen sayfayı DICOM-görüntüsü olarak dönüştür ve kaydet. |


## Organize PDF functions

| Fonksiyon | Açıklama |
| -------- | ----------- |
| [optimize](./organize/optimize/) | PDF-dokümanının içeriğini optimize et. |
| [optimize_resource](./organize/optimize_resource/) | PDF-dokümanının kaynaklarını optimize et. |
| [grayscale](./organize/grayscale/) | PDF-dokümanını siyah beyaza dönüştür. |
| [rotate](./organize/rotate/) | PDF-dokümanını döndür. |
| [set_background](./organize/set_background/) | RGB değerlerini kullanarak PDF-dokümanının arka plan rengini ayarla. |
| [repair](./organize/repair/) | PDF-dokümanını onar. |
| [replace_text](./organize/replace_text/) | PDF-dokümanındaki metni değiştir |
| [add_page_num](./organize/add_page_num/) | PDF-dokümanına sayfa numarası ekle |
| [add_text_header](./organize/add_text_header/) | PDF-dokümanının başlığına metin ekle |
| [add_text_footer](./organize/add_text_footer/) | PDF-dokümanının altbilgisine metin ekle |
| [flatten](./organize/flatten/) | PDF-dokümanını düzleştir |
| [remove_annotations](./organize/remove_annotations/) | PDF-dokümanından ek açıklamaları kaldır |
| [remove_attachments](./organize/remove_attachments/) | PDF-dokümanından ekleri kaldır |
| [remove_blank_pages](./organize/remove_blank_pages/) | PDF-dokümanından boş sayfaları kaldır |
| [remove_bookmarks](./organize/remove_bookmarks/) | PDF-dokümanından yer imlerini kaldır |
| [remove_hidden_text](./organize/remove_hidden_text/) | PDF-dokümanından gizli metni kaldır |
| [remove_images](./organize/remove_images/) | PDF-dokümanından görüntüleri kaldır |
| [remove_javascripts](./organize/remove_javascripts/) | PDF-dokümanından java script'leri kaldır |
| [remove_tables](./organize/remove_tables/) | PDF-dokümanından tabloları kaldır. |
| [remove_watermarks](./organize/remove_watermarks/) | PDF-dokümanından filigranları kaldır. |
| [add_watermark](./organize/add_watermark/) | PDF-dokümanına filigran ekle. |
| [embed_fonts](./organize/embed_fonts/) | Bir PDF-document içine yazı tiplerini göm. |
| [unembed_fonts](./organize/unembed_fonts/) | Bir PDF-document'tan yazı tiplerini çıkar. |
| [optimize_file_size](./organize/optimize_file_size/) | PDF-document'in boyutunu görüntü sıkıştırma kalitesiyle optimize et. |
| [remove_text_headers](./organize/remove_text_headers/) | PDF-document'ten metin başlıklarını kaldır. |
| [remove_text_footers](./organize/remove_text_footers/) | PDF-document'ten metin altbilgilerini kaldır. |
| [crop](./organize/crop/) | Bir PDF-document'in sayfalarını kırp. |
| [replace_font](./organize/replace_font/) | Bir PDF-document'teki yazı tipini değiştir. |
| [convert](./organize/convert/) | Bir PDF-document'i belirtilen PDF formatıyla bir PDF-document'e dönüştür |
| [validate](./organize/validate/) | Bir PDF-document'in PDF formatına uyumluluğunu doğrula |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Bir PDF-document'ten PDF/A uyumluluğunu kaldır |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Bir PDF-document'ten PDF/UA uyumluluğunu kaldır |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | PDF-document'in PDF/A uyumlu olup olmadığını al |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | PDF-document'in PDF/UA uyumlu olup olmadığını al |
| [page_rotate](./organize/page_rotate/) | PDF-document'teki bir sayfayı döndür. |
| [page_set_size](./organize/page_set_size/) | PDF-document'teki bir sayfanın boyutunu ayarla. |
| [page_grayscale](./organize/page_grayscale/) | Sayfayı siyah beyaza dönüştür. |
| [page_add_text](./organize/page_add_text/) | Sayfaya metin ekle. |
| [page_replace_text](./organize/page_replace_text/) | Sayfadaki metni değiştir |
| [page_add_page_num](./organize/page_add_page_num/) | Sayfaya sayfa numarası ekle |
| [page_add_text_header](./organize/page_add_text_header/) | Sayfa başlığına metin ekle |
| [page_add_text_footer](./organize/page_add_text_footer/) | Sayfa altbilgisine metin ekle |
| [page_remove_annotations](./organize/page_remove_annotations/) | Sayfadaki ek açıklamaları kaldır. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Sayfadaki gizli metni kaldır. |
| [page_remove_images](./organize/page_remove_images/) | Sayfadaki görüntüleri kaldır. |
| [page_remove_tables](./organize/page_remove_tables/) | Sayfadaki tabloları kaldır. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Sayfadaki filigranları kaldır. |
| [page_add_watermark](./organize/page_add_watermark/) | Sayfaya filigran ekle. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Sayfadaki metin başlıklarını kaldır. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Sayfadaki metin altbilgilerini kaldır. |
| [page_crop](./organize/page_crop/) | Bir sayfayı kırp. |
| [page_replace_font](./organize/page_replace_font/) | Sayfadaki yazı tipini değiştir. |
| [page_merge_layers](./organize/page_merge_layers/) | Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmanda birleştir. |
| [page_layers](./organize/page_layers/) | Sayfadaki katman adlarını al. |


## Core PDF functions

| Fonksiyon | Açıklama |
| -------- | ----------- |
| [new](./core/new/) | Yeni bir PDF belgesi oluştur. |
| [open](./core/open/) | Dosya adıyla bir PDF belgesi aç. |
| [save](./core/save/) | Daha önce açılan PDF belgesini kaydet. |
| [save_as](./core/save_as/) | Daha önce açılan PDF belgesini yeni dosya adıyla kaydet. |
| [set_license](./core/set_license/) | Dosya adıyla lisansı ayarla. |
| [extract_text](./core/extract_text/) | PDF belgesinin içeriğini düz metin olarak döndür. |
| [word_count](./core/word_count/) | PDF belgesindeki kelime sayısını döndür. |
| [character_count](./core/character_count/) | PDF belgesindeki karakter sayısını döndür. |
| [append](./core/append/) | Başka bir PDF belgesinden sayfaları ekle. |
| [append_pages](./core/append_pages/) | Başka bir PDF belgesinden seçilen sayfaları ekle. |
| [merge_documents](./core/merge_documents/) | Sağlanan PDF belgelerini birleştirerek yeni bir PDF belgesi oluştur. |
| [split_document](./core/split_document/) | Kaynak PDF belgesinden sayfaları çıkararak birden fazla yeni PDF belgesi oluştur. |
| [split](./core/split/) | Mevcut PDF belgesinden sayfaları çıkararak birden fazla yeni PDF belgesi oluştur. |
| [split_at_page](./core/split_at_page/) | PDF belgesini iki yeni PDF belgesine böl. |
| [split_at](./core/split_at/) | Mevcut PDF belgesini iki yeni PDF belgesine böl. |
| [bytes](./core/bytes/) | PDF belgesinin içeriğini bayt vektörü olarak döndür. |
| [get_meta_info](./core/get_meta_info/) | PDF belgesinin meta bilgi değerini al. |
| [set_meta_info](./core/set_meta_info/) | PDF-dökümanının meta bilgi değerini ayarla. |
| [clear_meta_info](./core/clear_meta_info/) | PDF-dökümanının tüm meta bilgi değerlerini temizle. |
| [is_linearized](./core/is_linearized/) | Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer al. |
| [page_add](./core/page_add/) | PDF-dökümanına yeni bir sayfa ekle. |
| [page_insert](./core/page_insert/) | PDF-dökümanında belirtilen konuma yeni bir sayfa ekle. |
| [page_delete](./core/page_delete/) | PDF-dökümanında belirtilen sayfayı sil. |
| [page_count](./core/page_count/) | PDF-dökümanındaki sayfa sayısını döndür. |
| [page_word_count](./core/page_word_count/) | PDF-dökümanındaki belirtilen sayfadaki kelime sayısını döndür. |
| [page_character_count](./core/page_character_count/) | PDF-dökümanındaki belirtilen sayfadaki karakter sayısını döndür. |
| [page_is_blank](./core/page_is_blank/) | PDF-dökümanındaki sayfanın boş olup olmadığını döndür. |


## Security
| Fonksiyon | Açıklama |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Şifre korumalı bir PDF-dökümanını aç. |
| [encrypt](./security/encrypt/) | PDF-dökümanını şifrele. |
| [decrypt](./security/decrypt/) | PDF-dökümanının şifresini çöz. |
| [set_permissions](./security/set_permissions/) | PDF-dökümanı için izinleri ayarla. |
| [get_permissions](./security/get_permissions/) | PDF-dökümanının mevcut izinlerini al. |
| [is_encrypted](./security/is_encrypted/) | PDF-dökümanının şifrelenme durumunu al. |
| [sign_pkcs7](./security/sign_pkcs7/) | PDF-dökümanını PKCS#7 dijital imzalarıyla imzala. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | PDF-dökümanını PKCS#7 Ayrık dijital imzalarıyla imzala. |
| [is_signed](./security/is_signed/) | PDF-dökümanının imzalı durumunu al. |
| [remove_signs](./security/remove_signs/) | PDF-dökümanından imzaları kaldır. |


## Miscellaneous

| Fonksiyon | Açıklama |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Aspose.PDF for Rust via C++ hakkında meta veri bilgilerini döndür. |



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
    /// PDF izin yeteneklerini temsil eden bitbayrak kümesi.
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
    /// A0 boyutu.
    A0 = 0,
    /// A1 boyutu.
    A1 = 1,
    /// A2 boyutu.
    A2 = 2,
    /// A3 boyutu.
    A3 = 3,
    /// A4 boyutu.
    A4 = 4,
    /// A5 boyutu.
    A5 = 5,
    /// A6 boyutu.
    A6 = 6,
    /// B5 boyutu.
    B5 = 7,
    /// PageLetter boyutu.
    PageLetter = 8,
    /// PageLegal boyutu.
    PageLegal = 9,
    /// PageLedger boyutu.
    PageLedger = 10,
    /// P11x17 boyutu.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Döndürülmemiş.
    None = 0,
    /// 90 derece saat yönünde döndürülmüş.
    On90 = 1,
    /// 180 derece döndürülmüş.
    On180 = 2,
    /// 270 derece saat yönünde döndürülmüş.
    On270 = 3,
    /// 360 derece saat yönünde döndürülmüş.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4, anahtar uzunluğu 40.
    RC4x40 = 0,
    /// RC4, anahtar uzunluğu 128.
    RC4x128 = 1,
    /// AES, anahtar uzunluğu 128.
    AESx128 = 2,
    /// AES, anahtar uzunluğu 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// PDF/A-1a formatı.
    PDF_A_1A = 0,
    /// PDF/A-1b formatı.
    PDF_A_1B = 1,
    /// PDF/A-2a formatı.
    PDF_A_2A = 2,
    /// PDF/A-3a formatı.
    PDF_A_3A = 3,
    /// PDF/A-2b formatı.
    PDF_A_2B = 4,
    /// PDF/A-2u formatı.
    PDF_A_2U = 5,
    /// PDF/A-3b formatı.
    PDF_A_3B = 6,
    /// PDF/A-3u formatı.
    PDF_A_3U = 7,
    /// Adobe sürüm 1.0.
    V_1_0 = 8,
    /// Adobe sürüm 1.1.
    V_1_1 = 9,
    /// Adobe sürüm 1.2.
    V_1_2 = 10,
    /// Adobe sürüm 1.3.
    V_1_3 = 11,
    /// Adobe sürüm 1.4.
    V_1_4 = 12,
    /// Adobe sürüm 1.5.
    V_1_5 = 13,
    /// Adobe sürüm 1.6.
    V_1_6 = 14,
    /// Adobe sürüm 1.7.
    V_1_7 = 15,
    /// ISO Standardı PDF 2.0.
    V_2_0 = 16,
    /// PDF/UA-1 formatı.
    PDF_UA_1 = 17,
    /// PDF/X-1a:2001 formatı.
    PDF_X_1A_2001 = 18,
    /// PDF/X-1a formatı.
    PDF_X_1A = 19,
    /// PDF/X-3 formatı.
    PDF_X_3 = 20,
    /// ZUGFeRD formatı.
    ZUGFeRD = 21,
    /// PDF/A-4 formatı.
    PDF_A_4 = 22,
    /// PDF/A-4e formatı.
    PDF_A_4E = 23,
    /// PDF/A-4f formatı.
    PDF_A_4F = 24,
    /// PDF/X-4 formatı.
    PDF_X_4 = 25,
    /// PDF/E-1 (PDF 1.6) formatı.
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Uygun olmayan öğeleri sil.
    Delete = 0,
    /// Hiçbir şey yapma, uygun olmayan öğeleri tut.
    None = 1,
}
```

